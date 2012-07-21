Grep Textmate Bundle
====================

## Prologue

I met sakura editor whose 'grep' is very useful. I wanted to incorporate it into textmate that is my default editor and have made grep bundle for mates.

## Usage

To grep, execute `Filter Through Command...` which is in Text menu, and then set `Selection` in the input radio box, `Create New Document` in the output radio box and following command in the command input field.

    grep -r "search word" ~/path/to/the/project/dir

## Note

* When you set the grep command, you has to use absolute path. If you use relational path, this bundle will not work. If you get the following result, this bundle works good.

    /Users/{#name}/Desktop/Grep.tmbundle/info.plist:<?xml version="1.0" encoding="UTF-8"?>
