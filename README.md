# Serious Engine / Tools
========================

This is the source code for Serious Engine v.1.10, including the following projects:

* `EngineGUI` Common GUI things for game tools
* `GameGUI` Common GUI things for game tools
* `LWSkaExporter` Exporter for use in LightWave
* `MakeFONT` Used for generating *.fnt files
* `DecodeReport` Used to decode crash *.rpt files
* `Depend` Used to build a list of dependency files based on a list of root files
* `Modeler` Serious Modeler
* `SeriousSkaStudio` Serious Ska Studio
* `WorldEditor` Serious Editor

Common problems
---------------

Before starting the build process, make sure you have a "Temp" folder in your development directory. If it doesn't exist, create it.
SeriousSkaStudio has some issues with MFC windows that can prevent the main window from being displayed properly.

License
-------

Serious Engine is licensed under the GNU GPL v2 (see LICENSE file).

Some of the code included with the engine sources is not licensed under the GNU GPL v2:

* LightWave SDK (located in `Sources/LWSkaExporter/SDK`) by NewTek Inc.
