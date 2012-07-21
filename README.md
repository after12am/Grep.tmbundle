Grep Textmate Bundle
====================

## Prologue

I incorporate sakura editor's grep into textmate for mates.

## Usage

To grep, execute `Filter Through Command...` which is in Text menu, and then set `Selection` in the input radio box, `Create New Document` in the output radio box and following command in the command input field.

    grep -r "search word" ~/path/to/the/project/dir

## Note

* When you set the grep command, you has to use absolute path. If you use relational path, this bundle will not work. If you get the following result, this bundle works good.

    /Users/name/Desktop/Grep.tmbundle/info.plist:the appropriate line

    grep -r "search word" ~/path/to/the/project/dir

    /Users/name/Desktop/Grep.tmbundle/info.plist the appropriate line

    /Users/name/Desktop/Grep.tmbundle/info.plist:the appropriate line
