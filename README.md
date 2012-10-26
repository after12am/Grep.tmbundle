Grep Textmate Bundle
====================

How have you done grep in mac? I had executed grep command in terminal. This way made me so frustrated. Every time I executed command, I was disappointed that textmate don't provide good way to grep specific keywords. So I decided to make up how to grep using bundle that provided by textmate. I surely think that this bundle would help you.

## Usage

To grep, execute `Filter Through Command...` which is in Text menu, and then set `Selection` in the input radio box, `Create New Document` in the output radio box and following command in the command input field.

    grep -rn "search word" ~/path/to/the/project/dir

If you would get result like following, this bundle works good.

    /Users/{#name}/Desktop/Grep.tmbundle/info.plist:<plist version="1.0">

Focus on the line, and run `command + enter`. Since the File would be opened, you could check the line.

## Note

* When you set the grep command, you has to use absolute path. If you use relational path, this bundle will not work.
* If you would save result, please save with no extension.