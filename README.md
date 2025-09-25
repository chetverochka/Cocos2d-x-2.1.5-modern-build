# Cocos2d-x-2.1.5-modern-build

The original version of cocos2d-x 2.1.5 compiles successfully in Visual Studio 16 2019.

## Toolkit
> `Visual Studio 16 2019`
> `Python 3.x`

I rewrote outdated sections of code and recompiled static libraries for Windows. 
I also rewrote the project creation utility in Python.

In the future, I intend to update the project to the latest version of Visual Studio and successfully compile it on Android (and possibly iOS, if possible).

To create a project, navigate to <cocos2d>/tools/project-creator/ and run the create_project.py script.
Use the following arguments to create a project:
```
-project <ProjectName> -package com.package.name -language [cpp]
```
Then go to <cocos2d>/projects/<ProjectName>/proj.win32 and run the .sln file in Visual Studio 2019, then compile it successfully


![Cocos2d-x 2.1.5 Hello World](https://github.com/chetverochka/Cocos2d-x-2.1.5-modern-build/blob/main/HelloWorld.png)
Have fun!
