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
COMMAND AND OUTPUT
<img width="757" height="275" alt="Screenshot 2025-11-17 231654" src="https://github.com/user-attachments/assets/16a3a711-4522-49c1-bd5f-b176080c5a00" />
Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="1040" height="458" alt="Screenshot 2025-11-17 231810" src="https://github.com/user-attachments/assets/1b1689e4-1cd5-4b97-a1dc-12b6a597111c" />
Create the file Rose.txt

## COMMAND AND OUTPUT
Create the file Rose.txt
<img width="1033" height="441" alt="Screenshot 2025-11-17 231938" src="https://github.com/user-attachments/assets/dfe3089f-8f12-4a75-9b2b-d6774538469c" />

## COMMAND AND OUTPUT
Create the file hello.txt using echo and redirection
<img width="1035" height="445" alt="Screenshot 2025-11-17 232439" src="https://github.com/user-attachments/assets/ed07d12c-7d7e-46d8-a2fa-6d0f645e90de" />

## COMMAND AND OUTPUT
Copy the file hello.txt into the file hello1.txt
<img width="1035" height="445" alt="Screenshot 2025-11-17 232439" src="https://github.com/user-attachments/assets/0af25bb3-7f48-4721-9f2e-03de2d1485e2" />

## COMMAND AND OUTPUT
Remove the file hello1.txt
<img width="1038" height="170" alt="Screenshot 2025-11-17 232709" src="https://github.com/user-attachments/assets/0429cd94-2edf-496f-a2a3-fee337a588c5" />

## COMMAND AND OUTPUT
List out the file hello1.txt in the current directory
<img width="976" height="274" alt="Screenshot 2025-11-17 232801" src="https://github.com/user-attachments/assets/851823bd-7c90-4608-8cf4-5af242a751e7" />

## COMMAND AND OUTPUT
List out all the associated file extensions 
<img width="976" height="274" alt="Screenshot 2025-11-17 232801" src="https://github.com/user-attachments/assets/eb8f36ed-e50b-4c65-b4d6-69579a5b394d" />

## COMMAND AND OUTPUT
Compare the file hello.txt and rose.txt
<img width="1032" height="934" alt="Screenshot 2025-11-17 232939" src="https://github.com/user-attachments/assets/9c16e67c-78f3-4d94-ae5d-3cd9485acda8" />


## COMMAND AND OUTPUT
<img width="1034" height="238" alt="Screenshot 2025-11-17 233021" src="https://github.com/user-attachments/assets/bec177c5-7a25-42ea-b1af-4f404dc6a78f" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".
## OUTPUT
<img width="875" height="116" alt="Screenshot 2025-11-17 233207" src="https://github.com/user-attachments/assets/6c028e6c-b655-4ae7-94f1-45506afdb219" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="863" height="326" alt="Screenshot 2025-11-17 233314" src="https://github.com/user-attachments/assets/a5a6952d-506c-47d3-9849-0d8db28bdde7" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
<img width="895" height="260" alt="Screenshot 2025-11-17 233359" src="https://github.com/user-attachments/assets/7ee12245-4692-4cd5-8ec9-1dfb94a53161" />




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="872" height="140" alt="Screenshot 2025-11-17 233449" src="https://github.com/user-attachments/assets/e482f1d1-cfd3-4370-953e-66e4b5d48acd" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="1005" height="554" alt="Screenshot 2025-11-17 233552" src="https://github.com/user-attachments/assets/526ecf58-7a31-417a-abb8-e42106af38e1" />



# RESULT:
The commands/batch files are executed successfully.

