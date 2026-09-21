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

## COMMAND AND OUTPUT
<img width="501" height="165" alt="image" src="https://github.com/user-attachments/assets/770b4b5d-2c21-4d6c-bc5f-0c940931402d" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="393" height="137" alt="image" src="https://github.com/user-attachments/assets/09197bb2-f90b-43bb-8ef9-3d5f669419eb" />


Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="621" height="386" alt="image" src="https://github.com/user-attachments/assets/6a83a9bd-1dc9-403d-9224-b59b590671d8" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="577" height="132" alt="image" src="https://github.com/user-attachments/assets/de87eba8-a4a1-4759-9b69-b27a8dcb9abb" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="492" height="152" alt="image" src="https://github.com/user-attachments/assets/7e2cda2a-9c9f-4e70-a4aa-be3583ef0d07" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="522" height="226" alt="image" src="https://github.com/user-attachments/assets/4af7bc95-5413-433c-bf55-c64898cfcc36" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="522" height="226" alt="image" src="https://github.com/user-attachments/assets/530532ef-a703-4dd5-a421-e54001d5b5f6" />

List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="450" height="602" alt="image" src="https://github.com/user-attachments/assets/45c8e4f0-7b43-445f-a9fe-b53f6a6e51c9" />

Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="468" height="243" alt="image" src="https://github.com/user-attachments/assets/775358b1-1ac0-4537-a6b6-0675f996acca" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
<img width="497" height="227" alt="image" src="https://github.com/user-attachments/assets/6e9276f9-eda1-4b2f-9926-d3080603b1b6" />
<img width="421" height="127" alt="image" src="https://github.com/user-attachments/assets/54cd82d2-d8ce-42f0-833c-255bba7a5007" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="621" height="446" alt="image" src="https://github.com/user-attachments/assets/a04ce6a0-c257-40e8-9bf7-a8ba958bbda1" />

<img width="878" height="398" alt="image" src="https://github.com/user-attachments/assets/bdc53e57-6b47-4aa4-b211-205b853bcb78" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
<img width="486" height="282" alt="image" src="https://github.com/user-attachments/assets/4a0098d3-a308-48aa-8ba2-976d2a8e20f6" />

<img width="502" height="217" alt="image" src="https://github.com/user-attachments/assets/a696104b-6a13-4be0-bc77-8695df7a0332" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="482" height="276" alt="image" src="https://github.com/user-attachments/assets/1a0346e5-6de4-416d-8644-113f1044d517" />
<img width="432" height="145" alt="image" src="https://github.com/user-attachments/assets/bfa9d696-3ebf-471f-ac3c-7273075dba92" />

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="577" height="492" alt="image" src="https://github.com/user-attachments/assets/ce853633-83e3-4830-99e5-bc1f69862c2f" />
<img width="675" height="483" alt="image" src="https://github.com/user-attachments/assets/3375cddd-25fa-4d0a-8d3b-ff5182eca84a" />



# RESULT:
The commands/batch files are executed successfully.
