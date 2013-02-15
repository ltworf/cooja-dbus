cooja-dbus
==========

Cooja plugin to control the simulation using dbus.

Install
=======

- copy content to cooja/apps/dbus
- Install dbus.jar (on Debian libdbus-java)
- If you don't use Debian/Ubuntu, edit build.xml to look for the jar file
  in the right place.
- run ```ant jar```
- Cooja: add project path under Settings -> Cooja Projects
- Have fun!

Usage
=====

- Open/Create a simulation
- from cooja: Tools->DBus...
- From a terminal, run the following:
```qdbus org.cooja.dbus.simulation /org/cooja/dbus/simulation/SimControl```
to see the available functions.
