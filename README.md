Windows Folder Name Error
=========================
BUILD STATUS
____________

| Linux  | Windows |
| ------------- | ------------- |
| [![Build Status](https://travis-ci.org/mercuriete/windows-folder-error.svg?branch=master)](https://travis-ci.org/mercuriete/windows-folder-error)  | [![Build status](https://ci.appveyor.com/api/projects/status/y27b2f3idgc8qm2j?svg=true)](https://ci.appveyor.com/project/mercuriete/windows-folder-error)
  |

Explanation
___________

The full explanation is in this url:
https://superuser.com/questions/613313/why-cant-we-make-con-prn-null-folder-in-windows
TLDR; historically, windows can't handle folder names with the following form "aux", "prn", "con", etc...

This leads to some problems like:
Java project with package name "com.mydomain.aux.packagename" then your are screwed.

LICENSE
_______

_WTFPL_: Just do what the f**k you want public license.

