https://osad-munich.org/

# Continuous Delivery rund um GitHub

Das Modules Team bei Puppet trägt die Verantwortung für ungefähr 30 kommerziell betreute Puppet Module die auf GitHub entwickelt und gepflegt werden. Die Module enthalten Unterstützung für "alle" Linux und Windows Varianten, und müssen mit allen aktuell genutzten Puppetversionen kompatibel sein.

In seinem Vortrag führt David die CI/CD Prozesse des Modules Teams: wie eine Quellkodeänderung von seinem Laptop zur Forge kommt, dem öffentlichen Verzeichnis aller Puppet Open Source Module. Vor drei Jahren war das ein mehr-wöchiger Prozess. Mit den aktuellen Verbesserungen können wir einen Hotfix innerhalb von Minuten veröffentlichen, reguläre Änderungen innerhalb eines Tages.

Unterwegs werden wir alle Integration und Sicherheitskontrollen sehen, die das ermöglichen:

* JIRA Integration
* CI mit Travis-CI und Appveyor
* CI/CD mit jenkins und VMWare
* ChatOps Integration für Benachrichtigungen und Release Management
* automatische Changelogs

Bio: David Schmitt, Principal Software Engineer bei Puppet, programmiert seit seiner Schulzeit. In den letzten Jahren schrieb er Ruby und Puppet für das Modules Team und den Puppet Development Kit. Aktuell verantwortlich für die neue Resource API und Netzwerkautomatisierung.
