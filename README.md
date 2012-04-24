Codea Runtime Library (BETA)
============================

This is the Codea Runtime Library. It provides all the Lua bindings and graphics, sound and runtime engine for Codea on iPad. Using this library you can create standalone apps from a [Codea](http://twolivesleft.com/Codea/) project.

This version is a BETA. Please report any issues to us on the issue tracker on github. The underlying library is release-worthy, but the related scripts could have issues.

Versions
-------
The topmost is the current version.

**1.3.6** Release BETA Version

License
-------

The Codea Runtime Library is copyright 2012 [Two Lives Left](http://www.twolivesleft.com) and is licensed under the Apache License v2.0.

Requirements
------------

The Codea Runtime Library requires OSX and the iOS 5.0 Developer Tools. An iOS Developer License is required to build the app for devices and distribute on the Apple App Store.

Setup
-----

Extracting your project's codea folder from the iPad can be done using [iExplorer](http://www.macroplant.com/iexplorer/)

1. Run the make_project.sh script from a Terminal session. It takes a parameter which is the name of the app.
   + eg, `./make_project.sh Test` will create a folder called **Test** with a CodeaTemplate.xcodeproj file inside it and targets of the same name set up 
2. Open the CodeaTemplate.xcodeproj project in XCode.
3. Delete the existing the Project.codea file from the Classes group and select Move To Trash
4. Rename your codea project Project.codea
5. Drag and drop your project into the XCode project
6. Check the "Copy items into destination folder's group (if needed)"
7. Select "Create folder references for any added folders" and make sure your app's  target is selected. Click Finish
8. Setup the bundle id and Icon for your project as per usual

Issues
------

Please report any issue on the github issue tracker, and/or on the [Codea forums](http://www.twolivesleft.com/Codea/Talk).

Open Source Libraries
---------------------

The Codea Runtime Library uses the following open source libraries with gratitude to the developers:

+ [Lua 5.1](http://www.lua.org/)
+ [Box2D](http://box2d.org/)
+ [ASIHttpRequest](http://allseeing-i.com/ASIHTTPRequest/)
+ [libb64](http://libb64.sourceforge.net/)
+ [CCTexture2D](http://www.cocos2d-iphone.org/) (from Cocos2D)
+ [GLM](http://glm.g-truc.net/)
+ [ObjectAL](http://kstenerud.github.com/ObjectAL-for-iPhone/)
+ [SFXR](http://code.google.com/p/sfxr/)

In addition, the Lua API was heavily inspired by [Processing](http://processing.org/).

Sprite Pack Attribution
-----------------------
+ "Planet Cute" art by Daniel Cook (Lostgarden.com)
+ "Small World" art by Daniel Cook (Lostgarden.com)
+ "SpaceCute" art by Daniel Cook (Lostgarden.com)
+ "Tyrian Remastered" art by Daniel Cook (Lostgarden.com)