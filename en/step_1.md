## Creating Directories on a Raspberry Pi

There are two ways to create directories on the Raspberry Pi. The first uses the GUI, and the second uses the Terminal.

### Method 1 - Using the GUI

![GUI-make-directory](images/GUI-make-directory.gif)

1. Open a File Manager window by clicking on the icon in the top left corner of the screen

   ![file-manager](images/file-manager.png)

1. In the window, right-click and select *Create New...* and then *Folder* from the context menu
1. In the dialogue box, type the name of your new directory and then click *OK*

### Method 2 - Using the Terminal

![Terminal-make-directory](images/Terminal-make-directory.gif)

1. Open a new Terminal window by clicking on the icon in the top left corner of the screen.

   ![terminal](images/terminal.png)

1. You can create a new directory using the `mkdir` command

	~~~bash
	mkdir my-new-directory
	~~~

1. You can list the contents of the current directory using `ls`
1. To enter your new directory use the `cd` command

	~~~bash
	cd my-new-directory
	~~~


