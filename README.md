# Efficient-File-Management-System-OS-Project
Developing an efficient file management system that improves data organization and access within an operating system

➢ Algorithm: 
  
1. Start  

2. Initialize i to 0  

3. While i is less than 100:  
   - Compile project.c into proj  
   - Execute proj  
   - Prompt user for choice (opt1)  
➢ Running the Project: 

Prerequisites: 
Ubuntu Server (or any Linux distribution). 

Installed GCC compiler. 

Basic knowledge of command-line operations. 

Steps to Execute: 

---Compile the C Program: 
gcc project.c -o proj 
---Run the Main Script: 
bash main.sh 
---Interact with the Menu: 
---Follow the on-screen instructions to perform desired operations. 
---Troubleshooting 
---If the script fails to execute, ensure it has executable permissions: 
chmod +x main.sh 
---Verify that required dependencies (e.g., nano, find) are installed. 
 
 
   - Decision based on opt1:  

     - Option 1 (List files and directories):  
       - List files and directories  

     - Option 2 (Create new file):  
       - Prompt for file type  
       - Create file based on chosen type  

     - Option 3 (Delete file):  
       - Prompt for file to delete  
       - Delete file if it exists  

     - Option 4 (Rename file):  
       - Prompt for old and new filenames  
       - Rename file if it exists  

     - Option 5 (Edit file):  
       - Prompt for file to edit  
       - Open file in nano editor if it exists  

     - Option 6 (Search file):  
       - Prompt for file to search  
       - Search for file using "find" command  

     - Option 7 (File details):  
       - Prompt for file to view details  
       - Display file properties using "stat" command  

     - Option 8 (View file content):  
       - Prompt for file to view  
       - Display file content using "cat" command  

     - Option 9 (Sort file content):  
       - Prompt for file to sort  
       - Sort file content using "sort" command  

     - Option 10 (List directories):  
       - List directories  

     - Option 11 (List files with specific extension):  
       - Prompt for file extension  
       - List files with chosen extension  

     - Option 12 (Count directories):  
       - Count and display the number of directories  

     - Option 13 (Count files):  
       - Count and display the number of files  

     - Option 14 (Sort files):  
       - Sort files using "ls | sort"  

     - Option 0 (Exit):  
       - Display "Good Bye" message  
       - Exit loop  
   - Increment i  

4. End
