# Roblox Scripting - Intro

When starting out, I recommend the following applications

- Roblox Studio
- An Executor with a decompiler 
- A Code Editor (VS Code)


[Roblox Studio](RobloxStudio.md)

**The Basics**

Variables

![Example](https://i.imgur.com/XiddUQP.png)

Above, you can see we are using a **Keyword** local.  Keywords cannot be the variable name.  To assign a value to the variable, use the `=` sign.  After that, you can set it to a number, string, list, table, etc.

![Example Error](https://i.imgur.com/HPq1QwW.png)

Most of the time, we will be referencing an object through its path.  For example, let's say we want to reference a part in the workspace.

![](https://i.imgur.com/f7XCbEH.png)

Above, we are using the ```local``` keyword to create a local variable, only accessible within the script.  Then I set the name of the variable to 'part'.  I'm using the `=` sign to assign a value to it.  
The path is the location of the object.  The object is in the workspace, so we do `game.Workspace` to reference the workspace.  Then to reference the part, we do `game.Workspace.(PART NAME)`.  In this case, the name is Part.

Functions

A function is a group of code you can call later in the script.  Lets learn how to make one.

![](https://i.imgur.com/m3PAq90.png)
