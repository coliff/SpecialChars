SpecialChars
======

An extension for [Brackets](https://github.com/adobe/brackets/) for better handling with some chars for HTML.

### How to Install

1. Select Brackets > File > Extension Manager
2. Search for this extension.
3. Click on the Install button.

### How to use SpecialChars
The extension checks after writing a word and then pressing right arrow or space, if there is a special char in it. 

**Chars supported:**

Ö,Ä,Ü,ö,ä,ü,§,ß,à,â,á,é,è,ê,î,ï,í,ô,ó,œ,ü,û,«,»,’,¿,¡,°

**For Example:**

    + `österreich` turns into `&ouml;sterreich`.
    + `§5` turn into `&sect;5`.
    
But if there is a file with such chars in it, which you didn't wrote, you can just select an specific area, which you want to change, and then just press `Ctrl-Alt-H`.

***
Tested on Brackets Sprint 39, Windows 8.1 and Ubuntu.
    
