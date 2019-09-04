# MITH 735 Introduction to the Command Line

Macs users will be working in the terminal, which you can pull up with pull up either by clicking the magnifying glass at the top right of your screen or with *command space* and typing 'terminal'.

Windows users will be using Command Prompt, which can be found by searching under the Search programs and files box.

Why command line, especially if you are accustomed to working in an environment with icons, folders, buttons etc - elements of a *Graphical User Interface* or GUI? While the graphical elements are useful and facilitate wide use of computers, they are an additional layer over the functionality that can be achieved with more flexibility and speed by typing commands directly to the terminal or Command Prompt.

## Getting Oriented

Open terminal or Command Prompt. Where are you?

### `pwd` (Macs) or `cd` (Windows)

`pwd` stands for “print working directory.” Similarly `cd` will print the directory you're in. This command just tells you where you are in the file path. When you hit enter, you should see something like “/Users/yourusername” (Macs) or “C:\Users\username” (Windows). This means you’re in the home directory for your user account. Think of this command as a way to get your bearings.
*Note - cd on Macs will take you to your home directory.*

### `cd` (for both Macs and Windows)

You can use the command line to move around your computer. `cd` stands for "change directory" (Do you sense a pattern?) This command can move you throughout your computer, much like you would use Windows Explorer or Macs Finder to move to different folders/directories on your computer. To change from your home directory to your Desktop, you can type `cd Desktop`

*Super Hint:* Use tab to autocomplete commands. You can start by typing `cd D` and then tab to autocomplete. If you have more than one directory that start with D, you can double tab to print all those directories, using the second letter often will be enough to complete the autocomplete (Example: De *tab* --> Desktop).

If you know the path, you can use cd to change to a subdirectory of Desktop (a folder on your Desktop). For example, if you have a class folder named 'MITH735' on your Desktop, you can navigate from your home directory with `cd Desktop/MITH735`

To move back up one directory, you can use `cd ..`

* Hint: Check the label behind your cursor to double check you've navigated successfully to the intended directory. It is good practice to use `ls` or `dir` to confirm available files.

### `ls` (Macs) or `dir` (Windows)

It is often useful to identify what else is located in your working directory. ls or dir will show files and folders (also called directories) that are accessible in this location on the system path (ie where you are in the computer).

To see, Macs users type `ls`, which stands for *list* and Windows users type `dir`, which stands for directory. This prints the accessible contents of the current directory to your terminal/Command Prompt screen.

Much like orienting yourself the working directory, determining which files are available is an important command. You'll use this one a lot.

### Practice
1. Open terminal
2. Navigate to Desktop
3. list files
4. Navigate to Lakeland thumbdrive
  * Accessing files on a thumbdrive or other external drives, is also pretty simple. Macs users can drag the thumbdrive from finder to the terminal. On Windows Machines, each drive is assigned a letter. Usually, the letter for external drives is D (but you can check the letter in your file explorer).
5. list files
6. Move to different sub-directories
7. List the contents for each
8. Move back to the Lakeland directory (and repeat.)
9. celebrate your skills!

## Boss commands
### `mkdir`

Can you guess what `mkdir` stands for? Recall `dir` is the abbreviation for directory (or folder). Also recall, developers like to shorthand as much as possible. `mkdir` means 'make directory' and creates a new folder with nothing inside of it.

*Hint:* Remember you can use `ls` (Macs) or `dir` to check your new directory has been created. `cd newDirectoryName` will move you into it.

*Super Hint:* Remember how useful the tab autocomplete feature is? Another useful (ie typing less) hint is to use the up and down arrows to cycle through past commands.

### `cp FileName Destination` (Macs) or `copy FileName Destination` (Windows)

You can move files around quite easily via the command line. `cp` means copy. You have to tell the computer to make a copy of a specific file and move it to a specific location. Take care to avoid spaces in your file names, use - or CamelCase. Underscores are ok in FileNames, but are sometimes hard to see, especially if the name is underlined for some reason.

If you do have spaces in your file names, you will have to tell the computer. For both Macs and Windows you can wrap the name in quotes: `long spaced out file name which no one should use.doc`. On Macs only, you can also escape spaces individually: so `no spaces.doc` would be typed `no\ spaces.doc`.

*Hint:* For Macs, Command K or `clear` will clear your terminal screen. Windows, `cls` will clear your working screen.

### `mv FileName Destination` (Macs) or `move FileName Destination` (Windows)

Often you don't want to make a copy of a file, but would rather move it from one directory to another. Move is a powerful command as you risk losing data if you are not careful.

For example if you already have a file2.doc on your Machine, but you move file1.doc to file2.doc it will override file2.doc with the information contained in file1.doc and deletes file1.doc. In this scenario, you will lose the original file2.doc info. So! Take care you are fully aware of which files you are moving and where they will go.

## Commanding Directories, like a Boss

Copying and/or moving directories is very similar to moving individual files around.

### `cp -r DirectoryName Destination` (Macs) or `robocopy DirectoryName Destination` (Windows)

This will make a copy of your directory in the new destination.

### `mv DirectoryName Destination` (Macs) or `move DirectoryName Destination` (Windows)

This will move the directory to a new location on your Machine.

### `rm -r DirectoryName` (Macs) or `rmdir DirectoryName` (Windows)

Often you need to delete directories or individual files. However, unlike moving a file to the trash bin via the GUI (Graphical User Interface), delete means delete. You will not be able to recover the file or directory later. Like `mv or move` just be sure to be fully aware of what you are doing and that your command is formed correctly.

### Practice
1. Navigate to Lakeland directory from your home directory
2. Make a new sub-directory in the Lakeland folder (aka make a folder in the Lakeland folder)
3. Copy one file from the Lakeland materials into your new subdirectory
4. Move a different file into your new sub-directory
5. Move it back where it came from
5. Copy an existing sub-directory of Lakeland
6. Remove the copied file
7. Remove the sub-directory you created
