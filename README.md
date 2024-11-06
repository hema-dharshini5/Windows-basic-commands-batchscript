# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT

![os8 1](https://github.com/user-attachments/assets/7c9189f3-dd70-4f0c-b214-2d9ffd0e1f00)


Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.


## COMMAND AND OUTPUT

![os8 2](https://github.com/user-attachments/assets/7bd8a4bb-cc76-45ed-b6e8-5a805c7cb5fe)


List the contents of the "MyLab" directory.


## COMMAND AND OUTPUT

![os8 3](https://github.com/user-attachments/assets/a5d39cd1-d27f-4cd9-a841-b53a859ca292)


Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

## COMMAND AND OUTPUT

![os 8 4](https://github.com/user-attachments/assets/2f9402fc-1523-4ffb-824f-a40c7c595653)


Move the "MyLab" directory to the "Documents" folder.


## COMMAND AND OUTPUT

![os8 5](https://github.com/user-attachments/assets/37c7cbe5-d008-4755-9504-ab771bce5c17)


## Exercise 2: Advanced Batch Scripting
```
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.


@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!
```
Modify the script to delete files with the ".docx" extension from the "Documents" folder after creating the backup.
```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\*.docx
echo Backup and deletion completed successfully!


```
## OUTPUT


![os8 6](https://github.com/user-attachments/assets/4cfa1ac0-f5fe-407e-99b7-d0341ebaafb1)



# RESULT:
The commands/batch files are executed successfully.

