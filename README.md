# MacroCreeper

Welcome to the MacroCreeper! It's a macro system which can be used to run keystrokes automatically using a simple syntax :)

## Installation
Download the latest fix version of the `.exe` file from the [Releases](https://github.com/creepersaur/MacroCreeper/releases) tab.

## Usage
1. Create a new folder (or use a previous one).
2. Add a file named `action.macro`.
3. Write the macro file using proper syntax.
4. Add the `.exe` file into the same folder/directory.
5. The exe should automatically pickup the `action.macro` file and run the macro.

### SourceCode
I haven't released the Source Code at the time of writing this. But if I do, it might be in the directory or the Releases tab. Feel free to check if out and give your opinions in Issues and Discussions.

### Limitations

* Uses Python's PyAutoGui library for most of the controlling of the macros. This isn't such a liability, but there are a few things which are harder to implement.
* Loop limit of 1999/2000. Python limits recursion to a 1500 count, which I changed to 2000 for the primary release. Changing this to a higher number could cause crashing, which I do not intend for.
* Speed limits are a thing, many keys aren't going to be instant. Most things are, but with the speed of the compiled python executable and your operating system, it might slow down a tad. (Not an issue for 99% of people).
* Operating systems aren't fully supported. Windows (11) is the one I use and it's the one PyAutoGui recommends, and some features may not work for others.

### By creepersaur
> * [Github](https://github.com/creepersaur)
> * [Youtube](https://youtube.com/creepersaur)