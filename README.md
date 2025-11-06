# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

<img width="507" height="101" alt="image" src="https://github.com/user-attachments/assets/5d2214ec-d4b7-4679-ad11-167c0cc51d67" />

## COMMAND AND OUTPUT

Remove the directory "my-folder"

<img width="427" height="107" alt="image" src="https://github.com/user-attachments/assets/35545dd6-7841-495d-830b-daa90d29b754" />

## COMMAND AND OUTPUT

Create the file Rose.txt

<img width="650" height="368" alt="image" src="https://github.com/user-attachments/assets/cf4a3c36-63f4-4d7b-9bce-a92f0329833d" />


## COMMAND AND OUTPUT

Create the file hello.txt using echo and redirection

<img width="573" height="187" alt="image" src="https://github.com/user-attachments/assets/f722926a-7fb3-40e4-b185-3e5cb1ec9f63" />

## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt

<img width="532" height="117" alt="image" src="https://github.com/user-attachments/assets/241678ad-836f-46fd-ae36-22467b859a54" />


## COMMAND AND OUTPUT

Remove the file hello1.txt

<img width="372" height="107" alt="image" src="https://github.com/user-attachments/assets/4f545cf3-a6ca-4008-b63c-29734bd43101" />


## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

<img width="477" height="226" alt="image" src="https://github.com/user-attachments/assets/369b002e-18e0-45c4-a04e-bd473a992d9d" />


## COMMAND AND OUTPUT

List out all the associated file extensions 

<img width="587" height="837" alt="image" src="https://github.com/user-attachments/assets/854510f7-e9e4-461b-9fb6-0791b9a5a55b" />


## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt



## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT



# RESULT:
The commands/batch files are executed successfully.

