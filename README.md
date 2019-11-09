# EfficientWorkWindows

## Introduction

​	EfficientWorkWindows is a repo trying to improve the prodoctivity of windows, I will add all productivity tools or useful tricks to here. 



## Note

   All tools and tricks only tested on Windows 10 64bit.

## Productivity Tools

### 	VirualDesktop works like OS X

​	        It is a very convenient tool for you to arrange your windows in mutiple virutal desktop, which helps a lot for people who have many windows when working.

​			Press Ctrl + [1,2,3,4] to switch among virtual desktop 1,2,3,4.

​			Press Alt + [1,2,3,4] to move current window to virtual desktop 1,2 

#### 		1. AutoHotKey

​				 https://www.autohotkey.com/ 

#### 		2.VirtualDesktopAccessor

​				  repo: https://github.com/Ciantic/VirtualDesktopAccessor 

​				  **Note:** If you don't want to recompile the project, you should only get the release dll.

​				  https://github.com/Ciantic/VirtualDesktopAccessor/blob/master/x64/Release/VirtualDesktopAccessor.dll

#### 		3.AutoHotKey Script

​			     https://github.com/cvidkal/EffcientWorkWindows/blob/master/VirualDesktopScript.ahk

#### 		4. How to use

   1. Download AutoHotKey and VirtualDesktopAccessor dll

   2. Download AutoHotkey Script

   3. Open Script using a text editor, and edit the 5th line to your path.

      ```
      dllPath :="C:\Program Files\AutoHotkey\VirtualDesktopAccessor.dll"
      ```

4. Open Script



### VisualSubst - Mount Folders as Virtual Drives

------

SUBST is a command used for substituting paths on physical and logical drives as virtual drives.

If you have to access a path frequently, you can use this command to map this path to a virtual drive such as 'Z:'.Then you are able to access this path very  conveniently.

VisualSubst is a GUI program helping you to use SUBST command easily.

Visual Subst allows you to create virtual drives for local folders and network shares. It solves 3 main issues with the built-in 'SUBST' and ‘NET USE’ commands: it creates drives for elevated applications without any UAC prompts, adds editable drive labels and restores drives after reboots. 



![](https://github.com/cvidkal/EffcientWorkWindows/blob/master/img/vsubst.png)