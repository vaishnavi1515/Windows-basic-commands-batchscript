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
<img width="577" height="100" alt="image" src="https://github.com/user-attachments/assets/a7540aec-c9e6-438e-98b1-78b0e81c9d0d" />

## COMMAND AND OUTPUT
<img width="582" height="99" alt="image" src="https://github.com/user-attachments/assets/2b1e82b2-d143-4c57-8038-94d10efb73bf" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="882" height="467" alt="image" src="https://github.com/user-attachments/assets/7a8cda42-ab40-462a-a61a-35facf40ca2f" />


Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="775" height="137" alt="image" src="https://github.com/user-attachments/assets/6768fca0-021b-4c89-a9c2-96ad604726b8" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="718" height="75" alt="image" src="https://github.com/user-attachments/assets/887e3730-633d-4e10-a588-392ad95f7751" />


Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="573" height="62" alt="image" src="https://github.com/user-attachments/assets/e1f6a42b-fea1-4297-913c-eb82d8c4e7b4" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="642" height="227" alt="image" src="https://github.com/user-attachments/assets/73e6b502-b911-4379-883e-daaf34b93e1e" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="513" height="956" alt="image" src="https://github.com/user-attachments/assets/30278dc2-0c98-4e17-967a-fb96475d2029" />

List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="803" height="263" alt="image" src="https://github.com/user-attachments/assets/0e1fcc42-9c1e-4166-858e-983901d00b71" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".
<img width="720" height="172" alt="image" src="https://github.com/user-attachments/assets/5bc8238d-55c2-44ae-86a6-920c4ef1e25b" />





## OUTPUT

<img width="919" height="564" alt="image" src="https://github.com/user-attachments/assets/0b840eb8-403a-45f9-9f3c-c2df743cb99c" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT


<img width="616" height="298" alt="image" src="https://github.com/user-attachments/assets/13b74b0d-855c-463f-a7e3-a2b006482ea9" />


Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT


<img width="899" height="411" alt="image" src="https://github.com/user-attachments/assets/d6ee95dc-67d4-4311-96a9-07d1c549723b" />


Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="891" height="396" alt="image" src="https://github.com/user-attachments/assets/1a5b7437-d06c-47b9-806b-ecb6f80ba1b1" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="891" height="396" alt="image" src="https://github.com/user-attachments/assets/c41392aa-57c9-4b80-be2f-a3e595e068d9" />




# RESULT:
The commands/batch files are executed successfully.
