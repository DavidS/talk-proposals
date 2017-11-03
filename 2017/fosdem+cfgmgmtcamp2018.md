# Working with the Puppet Development Kit

Abstract: Writing good modules requires one or more local ruby installs, a tool to manage those, a number of testing and quality tools, and tools to manage those, and one of the templates to get started. If this sounds tedious to you, there are good news: the Puppet Development Kit is a new open source tool that bundles all the useful tools around writing and testing puppet modules:

* puppet agent's ruby
* metadata-json-lint
* puppet-syntax
* puppet-lint
* rspec-puppet
* rspec-puppet-facts
* rubocop

David will take you through each of the tools, how they help you write better modules, and how they are used. A great introduction for newcomers, and a good refresher for old hands.

# Painless Puppet Providers

Abstract: Puppet's most powerful extension point is providing "native" types and providers. Ruby fragments that describe how puppet can interact with resources in our systems. This has been part of puppet's core code since the very first days, but adoption has been hampered by the API being tied up deeply into puppet's internals.

The new Resource API project provides a coherent, and decoupled way to define new resource types. It is based on Puppet4+ data types, making validation a breeze. The backend provider is a simple ruby class with well-defined API requirements. Together, this makes the new providers easier to read, and write, as well as easier testable.

In this talk I'll give an overview of the new API, and how to write providers using it. Basic Ruby and Puppet knowledge recommended.

# Getting to 100% Coverage with Ruby

Abstract: Many talk about TDD, but few practice it.  In Ruby, the testing library rspec provides a great base to get going. David will show the techniques to build and stay with 100% code coverage on a real-life project, and talk about the advantages of reaching 100%, and pitfalls learned. There will be code examples.

Some basic Ruby knowledge helpful.

(submit this to Testing dev room)

# Small Team, Big Success with Cloud CI

Abstract: Or, "How we move fast, and don't break things". How the Puppet Developer Experience and the Modules team at Puppet provide quick feedback across platforms on code changes using the cloud services Travis-CI and Appveyor. Examples will be mostly based on ruby and puppet, but show general patterns to improve cycle times, and provide better feedback.

(submit this to Testing dev room)

# Introduction to Testing Puppet Modules

Abstract: Are you a puppet module author? Do other people use your puppet code? Do you want to know what your change broke? Would future-you still know what you expected here? Using automated tests can help you with this. There are tools to help you answer all this for puppet modules, but only few use them. Join this talk to get an introduction to the rspec-puppet and beaker-rspec test frameworks, learn how to run automated tests on your puppet modules, and learn how to write good tests.

(this is a repeat of my OSDC'16 talk https://www.netways.de/index.php?id=3445#c44135 )

# Under the Hood of Puppet Module Testing

Abstract: Working with rspec, rspec-puppet, or beaker-rspec, but want to get a deeper understanding of the tech behind the curtain? Needed that one matcher that was not available? Format the output just right? Just want to know how the sausage is made? David will take you through the basics of

* rspec's internal data structures
* how the test suite is built and executed
* output formatting and reporting
* custom matchers

At the end, the learned content will be used for a quick highlights tour of rspec-puppet and beaker-rspec internals.

(this is a advanced follow-up to the Introduction to Testing Puppet Modules)
