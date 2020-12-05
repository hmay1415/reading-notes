###### Notes from [Choosing a Text Editor](https://codefellows.github.io/code-102-guide/curriculum/class-02/Choosing-A-Text-Editor--The-Older-Coder.pdf)
- A text editor is a piece of software that you download and install on your computer, or access online through your web browser, that allows you to write and manage text, especially the text that you write to build a website. It's one of the most important tools as an aspiring developer.

Features to look for:
1. code completion: offers suggestions for text, closes brackets, availability of Emmet (shorthand language)
2. syntax highlighting: colorizes text you write. Attributes, elements, and copy are all different colors.
3. variety of themes: changes background/text color for ease on eyes
4. choice of extensions: plugins for text editor

Built in text editors (bare bones):
- Mac: Text Edit
- Windows: Notepad

If using built in text editor:
1. create code in plain text editor
2. create folder on computer to store entire website
3. use correct extensions in file names (.html or .css)

Third party options:
- Notepad ++ - Windows only. Has syntax highlighting, code completion, zoom in and out, online community, wiki
- Textwrangler / BB Edit - Mac only. Fee, but can use free version.
- Visual Studio Code - by Microsoft. For Mac, Windows, Linux. Has Emmet and all features.
- Atom - by GitHub. For Mac, Windows, Linux. Has all features.
- Brackets - by Adombe. For Mac, Windos, Linux. Only supports HTML, CSS, and JavaScript. Has "Live Preview"
- Sublime Text - has premium or free version.

Text Editors vs. IDEs:
 - IDE is suite of softwares. Includes text editor, file manager, compiler, debugger.
 
 ###### Notes from [The Command Line](https://ryanstutorials.net/linuxtutorial/commandline.php)
 - GUI: Graphical User Interface
 - Command line/terminal: text based interface to the system
 - Must be spaces between command and command line argument
 - Option - comes after command and modifies behavior of command. Starts with a dash -
 - Prompt displayed command is done running
 - Within terminal is shell. Shell defines how terminal will behave and runs commands. Bash is a type of shell (Bourne Again SHell)
 - echo $Shell tells you what shell you're using
 - Shortcut: traverse history using up and down arrows and edit with side arrows
 
 ###### Notes from [Basic Navigaton](https://ryanstutorials.net/linuxtutorial/navigation.php)
  - pwd - print working directory - where you are
  - ls - list - what is in current directory
  - ls <[options][location]> - to do more with list command
  - ls -l - long list 
  - ls -l /etc - lists contents of directories
  - two types of paths - relative and absolute
  - file system is hierarchical - at top is root, denoted by /
  - absolute paths specify location in relation to root - identified by /
  - relative paths specify location in relation to where we currently are - don't have a /
  - ~ (tilde) - shortcut for home directory (can truncate home/hilary/Documents with ~/Documents)
  - .(dot) - reference to current directory
  - ..(dotdot) - reference to parent directory - can go back up the hierarchy with ../ ../ 
  - cd - change directory. format is cd location. If run cd without location, takes you back to directory
  - Tab - autocompletes. Hit twice for options
  
  ###### Notes from [About Files](https://ryanstutorials.net/linuxtutorial/aboutfiles.php)
  - Everything is a file (directory, keyboard, etc.)
  - Linux is extensionless system - to find out what type of file use file [path]
  - Linux is case sensitive
  - On command line BE CAREFUL WITH SPACES. Individual words seen as unique commands. Use quotes or 'escape characters' ie a backslash / - skips next character ie space
  - Tab complete can automatically escape spaces in name
  - If the file or directory's name begins with a . (full stop) then it is hidden. To hide file, start name with full stop. 
  - ls will not show hidden files. ls ~a will bring up hidden files
  
  Return to [Main Page](README.md)
  
  
  
 
 

