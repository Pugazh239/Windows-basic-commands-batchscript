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
~~~
Name:Pugazh sozhan.A
Reg.No:212224240121
~~~




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

## COMMAND AND OUTPUT
Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.

```c
mkdir %userprofile%\Desktop\MyLab
```
<img width="721" height="47" alt="image" src="https://github.com/user-attachments/assets/ad366342-1f88-48f8-bc57-3a473f4702e8" />

## COMMAND AND OUTPUT
List the contents of the "MyLab" directory.

```c
cd %userprofile%\Desktop\MyLab
```
<img width="752" height="52" alt="image" src="https://github.com/user-attachments/assets/deb461b7-4cb9-418b-b6f9-d28dd5ddb87d" />

<img width="829" height="46" alt="image" src="https://github.com/user-attachments/assets/d07ef762-ce24-4798-9056-df472a29e5a9" />

## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
```c
dir %userprofile%\Desktop\MyLab
```
<img width="702" height="71" alt="image" src="https://github.com/user-attachments/assets/bc475946-e393-47d9-92d8-37f90a20fc89" />

## COMMAND AND OUTPUT
Move the "MyLab" directory to the "Documents" folder.
```c
mkdir %userprofile%\Desktop\Backup

copy MyFile.txt %userprofile%\Desktop\Backup
```
<img width="734" height="46" alt="image" src="https://github.com/user-attachments/assets/18da5755-0465-4399-8ac0-64fdaf866f4b" />
<img width="966" height="49" alt="image" src="https://github.com/user-attachments/assets/c087e72e-19e0-404a-85f2-e7a739d6497f" />

## COMMAND AND OUTPUT
```c
mv Myfile.txt %userprofile%\Documents
```
<img width="954" height="47" alt="image" src="https://github.com/user-attachments/assets/d4199c77-94f7-49ff-b467-5b43a55d1924" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".
```c
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!
```
Modify the script to delete files with the ".docx" extension from the "Documents" folder after creating the backup.

```c
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\*.docx
echo Backup and deletion completed successfully!
```




## OUTPUT
<img width="754" height="80" alt="image" src="https://github.com/user-attachments/assets/5a0613ad-a94e-460c-85eb-d7eea593c30a" />




# RESULT:
The commands/batch files are executed successfully.

