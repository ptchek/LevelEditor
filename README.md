LevelEditor 
===========

The LevelEditor is a software tool used to design levels (maps, campaigns, and virtual worlds) for a video game. A level editor is used by a game designer.

The standalone LevelEditor is a fully functional modern level editor. Using the LevelEditor, you can design a game world for any video game engine. You can create and lay out terrain, place static game objects in the world (such as rocks, plants, street lights, or buildings), place light sources for game objects, and place Linears for dynamic game objects.

The LevelEditor leverages the Authoring Tools Framework and C# for user interface and data management, and leverages the power of C++ and Microsoft� DirectX� 11 for 3D rendering.

Originally built from the Authoring Tools Framework, the LevelEditor offers a WYSIWYG interface and a variety of features that support asset management, game object creation, scene layout, and cross-team development. The LevelEditor can also be customized and extended by creating plug-ins. For more about the Level Editor's capabilities, see LevelEditor Features & Benefits.

The following LevelEditor features help you construct game levels efficiently and collaboratively:

* Work with a variety of file formats
* Associate assets with game objects
* Position, rotate, scale, and snap game objects precisely
* Edit game object properties
* Show or hide groups of game objects to unclutter the view as you work
* Construct Linears (lines and curves)

Prerequisites
-------------
* Operating System: Microsoft Windows 7, 32-bit or 64-bit (SP1 or later)
* Development Environment:
    * Microsoft .Net 4.0 (or later) installed
    * DirectX SDK June 2010.
Download the SDK from http://www.microsoft.com/en-us/download/details.aspx?id=6812.
    * If you have the Platform Update for Windows 7 installed, perform the actions for Windows 7 DirectX developers, as described in the following Microsoft Knowledgebase article: http://support.microsoft.com/kb/2670838.
(That is, you need to use the Windows 8 SDK, use Visual studio 2012 (or later), or the Remote Tools for Visual Studio 2012 (x86 and X64).
See the following Dev Center article for more information about the Platform Update for Windows 7: http://msdn.microsoft.com/en-us/library/windows/desktop/jj863687%28v=vs.85%29.aspx.
  
   
Getting Started 
--------------- 
To build/run LevelEditor:

1. Open the solution Leveleditor\build\LevelEditor.vs2010.sln in Visual Studio 2010 or later.
1. Change the configuration to Release and then build LevelEditor.
1. Navigate to the directory in which LevelEditor is built and double-click the file LevelEditor.exe to start LevelEditor.
1. After LevelEditor starts, select Edit->Preferences and use the Preferences dialog to set the resource root to a location that contains a few ATGI or Collada files and then restart LevelEditor. (Restart LevelEditor just in case).
1. Drag/drop a few 3D assets from the Resources windows to either the DesignView or the Project lister.


Important note about performance:
The release build of LvEdRenderingEngine.dll is much faster than the debug build
when loading levels and rendering.


More Info
---------
LevelEditor wiki pages: https://github.com/SonyWWS/LevelEditor/wiki

