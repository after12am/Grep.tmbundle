Grep Textmate Bundle
====================

I met sakura editor whose 'grep' is very useful. I wanted to incorporate it into textmate that is my default editor, I have made textmate grep bundle.

## Usage

At first, execute `Filter Through Command...` in Text menu, and then set `Selection` in the Input radio box and `Create New Document` in the Output radio box. To grep, run the following commands.

    grep -r "search word" ~/path/to/the/project/dir

## Note

* When you run grep command, you has to use absolute path. If you use relational path, this bundle will not work. You get the result like below, this bundle works good.

    /Users/{#name}/Desktop/Grep.tmbundle/info.plist:<?xml version="1.0" encoding="UTF-8"?>

inspired by sakura editor