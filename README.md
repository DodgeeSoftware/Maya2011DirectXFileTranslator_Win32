# Maya2011DirectXFileTranslator_Win32
Maya 2011 DirectX File Exporter

Binary only! To use this plugin copy the MEL file into your Maya 2011 scripts folder. Should be something like the following "C:\Program Files (x86)\Autodesk\Maya2011\scripts\AETemplates\". Scripts in these folders are automatically loaded my maya. And copy the *.mll file into the bin\plugins folder which should be something like the following "C:\Program Files (x86)\Autodesk\Maya2011\bin\Plugins".


The *.mll file is a DLL file which I compiled with Visual Studio 2011 and this is the binary file where most of the plugin logic occurs. The MEL file here is a callback script which is called from our MLL file. The MEL script will be automatically loaded by Maya when it is copied into the correct maya folder. The MEL script here builds a GUI and prepares a parameter string to be sent into the plugin to alter how the plugin will import and export geometry.
