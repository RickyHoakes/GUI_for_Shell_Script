# GUI_for_Shell_Script

Usually shell interpreter looks like normal command prompt and we cant clearly segregate the useful command with the errors, so we want to built a graphical user interface through which the user enters commands, and result is shown and error shown in red color separately, like usual ide's.
This will be helpful for using simple shell commands ,basic arithmetical operations and listing out the directories, this can also compile and run various programs of all programming languages.
Introduction

we used python 3.8 IDE for python(VISUAL STUDIO, PyCharm, ATOM, Sublime, etc..
for implementing this shell interpreter

# modules we used in the source code
▷ OS ▷ Subprocess ▷ shelex ▷ sys ▷ tkinter ▷ PIL ▷ PyAutoGui module ▷ PySimpleGUI 4.39.1 module.

# Various features of GUI shell interpreter.

->buttons are eazy than to type commands 

->comfartable access of files

->output will be displayed in popup box

->easier learning for beginners 

->errors are specfied in red and “success” is printed when the command in the input is running without errors.

# Function of various buttons we used in our shell interpreter are run, calculate and list Directory.

* RUN This button is used for running general subprocess scripts and other shell commands.

* Calculate This button is used for evaluation for simple arithmetical operations.

* List Directory This button is used for listing out any kind of directory and sub directories.

# Results / Snapshots

![image](https://user-images.githubusercontent.com/89961380/188273489-25b0da61-a07d-40f1-933a-fdd13c88221a.png)

We can do all arithmetic operations, the result is shown in output textbox once the calculate button is clicked.

![image](https://user-images.githubusercontent.com/89961380/188273512-f8a73c3d-2c23-4abf-984a-3254da85f9f0.png)

In case if an invalid operation are entered, then error is shown is red color.

![image](https://user-images.githubusercontent.com/89961380/188273542-531f98aa-5291-49bb-b578-5faa56b279b1.png)

In case if we enter invalid keyword for built-in commands for run module then we might encounter an error.

![image](https://user-images.githubusercontent.com/89961380/188273560-9921ab7e-bfa0-4608-b76f-40f4d9a6ef32.png)

We can run and compile any programming file by navigating to it using our browse files option.

![image](https://user-images.githubusercontent.com/89961380/188273572-ba05506e-1a10-4f8e-a5dc-0307b1d78552.png)

After importing we can simply click on run button, then it will display the result in the output textbox

![image](https://user-images.githubusercontent.com/89961380/188273601-b5dff376-0b87-4ef4-beed-8e6bf8f55ccc.png)

We can list the directory by entering the path to the directory.

![image](https://user-images.githubusercontent.com/89961380/188273616-4f2b1a8f-5638-4934-b6c0-c549f5f9f983.png)

Incase if I want to list the directory with path “C:\\MASM611\\”, then following output is displayed.

![image](https://user-images.githubusercontent.com/89961380/188273625-a16bb65e-9467-464b-bd85-9bc4c1745033.png)







