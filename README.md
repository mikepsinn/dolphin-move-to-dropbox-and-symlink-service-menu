# Dolphin Move To Dropbox And Symlink ServiceMenu
A service menu plugin for Dolphin that allows you to move files to Dropbox and replace them with a symlink

![](dropbox.png)

# Installation
Servicemenus are defined using .desktop files, which are the same kind of files that are used to create entries in the Plasma launcher. These servicemenu files are found in the ServiceMenus subfolder of one of the folders that can be determined with

`kf5-config --path services`

In the case of my home machine that means that servicemenu files can be found in the following places:

```
~/.local/share/kservices5/ServiceMenus/      
/usr/share/kservices5/ServiceMenus/
```

Just copy the desktop files in this repo to the appropriate locations.

### Root Option

The root option is for copying files you don't own.  However, it sets permissions to 777 so you might want change that if necessary or use at your own risk.
