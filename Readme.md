## Space Engineers Toolbox
###### A toolbox utility for modifying and importing content in the Space Engineers Game.
Created by Mid-Space productions. Est. 1993

Space Engineers is Copyright Keen Software House.
* http://www.spaceengineersgame.com
* http://www.keenswh.com/about.html

This application contains code expressly licenced to it, and should not be used in any other application without the permission of Keen Software House.

---

Installation/Runtime requirements:
*	Space Engineers Game
	* http://www.spaceengineersgame.com/
	* http://store.steampowered.com/app/244850/

* [MS .NET Framework 4](http://www.microsoft.com/en-au/download/details.aspx?id=17851)

Developer/Build Requirements:
* [7Zip](http://www.7-zip.org/) (used in Build script on Setup project, to generate a .Zip of all release files without an .MSI)
    
*	[Windows Installer XML (WiX) toolset](http://wixtoolset.org/releases/)

*	Shaders:
	*	[Shader Effects BuildTask and Templates.zip](https://wpf.codeplex.com/downloads/get/40167)
	*	[Documentation](https://wpffx.codeplex.com/)
	*	[Issues](http://blogs.msdn.com/b/chuckw/archive/2011/12/09/known-issue-directx-sdk-june-2010-setup-and-the-s1023-error.aspx)
	
Resources:
*	[HelixToolkit](https://helixtoolkit.codeplex.com/) (for opening 3D mesh files, and displaying).
*	[SharpZipLib](http://www.icsharpcode.net/OpenSource/SharpZipLib)

Local references:
	Copy global.targets to user.targets, and modify the MainPath to indicate the path to SpaceEngineers in the Steam directory on your computer.
