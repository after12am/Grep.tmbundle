Grep Textmate Bundle
====================

## Prologue

At first I used sakura editor as editor in windows. And then, I uses textmate in mac now. After I often got to use textmate, I have been dissatisfied with textmate in use of grep. So I incorporated usability of sakura editor into textmate as bundle.

## Usage

To grep, execute `Filter Through Command...` which is in Text menu, and then set `Selection` in the input radio box, `Create New Document` in the output radio box and following command in the command input field.

    grep -rn "search word" ~/path/to/the/project/dir

If you would get result like following, this bundle works good.

    /Users/{#name}/Desktop/Grep.tmbundle/info.plist:<plist version="1.0">

## Note

* When you set the grep command, you has to use absolute path. If you use relational path, this bundle will not work.
* If you would save result, please save with no extension.