# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

#### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

#### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
#### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
### Exercise 1: Basic Directory and File Operations

Create a directory named "my-folder"
### COMMAND AND OUTPUT

<img width="606" height="223" alt="image" src="https://github.com/user-attachments/assets/c9879cf2-1eb2-4d00-bceb-819b2b044b16" />


Remove the directory "my-folder"
### COMMAND AND OUTPUT

<img width="842" height="371" alt="image" src="https://github.com/user-attachments/assets/59f7fbec-ad69-4a09-bff4-93d2ffbf52f4" />

Create the file Rose.txt
### COMMAND AND OUTPUT

<img width="828" height="352" alt="image" src="https://github.com/user-attachments/assets/2ba8e52b-00db-407e-b3e9-833e73d87b91" />

Create the file hello.txt using echo and redirection
### COMMAND AND OUTPUT

<img width="960" height="121" alt="image" src="https://github.com/user-attachments/assets/7f5c3f41-900e-4fd4-8f4c-ce55cbc10490" />


Copy the file hello.txt into the file hello1.txt
### COMMAND AND OUTPUT

<img width="892" height="143" alt="image" src="https://github.com/user-attachments/assets/4ad35123-708b-4131-82d5-0c0a278c51d4" />


Remove the file hello1.txt
### COMMAND AND OUTPUT

<img width="782" height="221" alt="image" src="https://github.com/user-attachments/assets/20a52dda-88ec-43b4-88f7-b327e5315975" />


List out the file hello1.txt in the current directory
### COMMAND AND OUTPUT

<img width="757" height="1059" alt="image" src="https://github.com/user-attachments/assets/94644d16-a4cc-46ce-9377-579fa2e5712d" />

List out all the associated file extensions 
### COMMAND AND OUTPUT

<img width="863" height="1106" alt="image" src="https://github.com/user-attachments/assets/04d95578-f1ef-4f3d-9a4b-1ac1c82fa9fd" />


Compare the file hello.txt and rose.txt
### COMMAND AND OUTPUT

<img width="826" height="188" alt="image" src="https://github.com/user-attachments/assets/8018e9e1-dc9e-4f91-bf42-aee136ccb19f" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

### OUTPUT

<img width="697" height="89" alt="image" src="https://github.com/user-attachments/assets/5b76fefe-6707-432d-90d7-34a3632c009b" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.

### OUTPUT

<img width="693" height="260" alt="image" src="https://github.com/user-attachments/assets/ef97c809-8859-4f02-a9d4-c546ded03854" />


Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.

### OUTPUT

<img width="715" height="209" alt="image" src="https://github.com/user-attachments/assets/bf2600d7-5711-4b24-87ec-1df49f033914" />


Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

### OUTPUT

<img width="696" height="111" alt="image" src="https://github.com/user-attachments/assets/3e5d6c70-ee1f-420d-8df5-be8022332622" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


### OUTPUT

<img width="753" height="442" alt="image" src="https://github.com/user-attachments/assets/ca24acf9-a30d-4dad-a720-d37aeb9a7591" />


# RESULT:
The commands/batch files are executed successfully.
