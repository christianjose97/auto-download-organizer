# 🤖 Auto Download Script

This code is a Python script that organizes files in a specified directory (in this case, the Downloads folder) based on their file extensions

## 📦 Tech Stack

- `Python`

## 🕹️ Features

Here's what you can do with Auto downloader organizer:
 
- `With the click of a an executable your download section in windows will be organized by extension`

## 🖥️ The Process

I began with the idea of how I could easily have my files organized in half the time. I went ahead and decided to
use python as it is the easiest to script and the most compatible with interacting with OS's. 

## 📚 What I Learned

- I learned a tremendous amount about the `os` module. I had no idea that there existed such a thing that communicate python with any OS.

-gave me the chance to referesh on Python syntax.



## 🧠 How can it be improved?

- Support other OS such as mac os, linux, etc..
- Make it more customizable with how you setup folders.
- Make it in a way that if 

## 👟 Running the Project

To run the project in your local environment, follow these steps:

To create an executable that you can click on to run the script in Windows, you can use a tool like pyinstaller to package your Python script into a standalone executable file. Here's how you can do it:

**Install PyInstaller:**
   If you haven't already installed pyinstaller, you can install it via pip by running the following command in your command prompt or terminal:
   
       pip install pyinstaller`

Navigate to Your Script Directory:
Open your command prompt or terminal and navigate to the directory where your Python script is located.

**Create Executable**:
Run the following command to create an executable for your script:

    pyinstaller --onefile your_script_name.py

   Replace your_script_name.py with the name of your Python script file.

   **Locate Executable:**
   Once pyinstaller finishes building the executable, you can find it in the dist directory within your script's directory.

   **Run the Executable:**
   You can now double-click on the executable file to run your Python script without needing to open a command prompt or terminal.

That's it! You now have an executable that you can click on to run your Python script on Windows. The pyinstaller tool packages your script and its dependencies into a single standalone executable file, making it convenient to distribute and run on Windows systems.

1. Clone the repository to your local machine.
2. in your terminal `cd` into the location of your project and run the following command... 
   this command will create the executable that will allow you to auto organize your donload folder 
   (currently windows only)

## 📺 Video

Details to be added soon.

