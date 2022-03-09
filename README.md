# Desktop-Assistant🤓
A Python Voice commanded program to work as your desktop assistant which will help you to open your required software, wishes you, sends your emails, opens your frequently visited websites etc. Used pandas, pydub, gtts for adding features and functionalities.

## How To Use This Project

1. Download the Zip Folder (https://github.com/adarshkesarwani006/Desktop-Assistant) on your machine.
2. Open it on any IDE most preferably Visual Code and Pycharm.
3. Load the Extensions asked by your IDE if needed.
4. Run the code and give order to your assistant.

## How To Add This Assistant in "auto-start" applications of your Machine.
1. Convert the python code into exe file by following below steps:
2. Install a pip (python package) named pyinstaller using shell or any IDE.
3. Change directory (cd) to the directory where you will store this program.
4. Use shift + right click to open shell directly into that directory.
5. Run pyinstaller yourfilename.txt (assistant.py) on shell and after some warnings and loading your program will be converted into exe file.
   ```bash
    pyinstaller assistant.py 👈
    ``` 
6. Zip your main file and share it with others they will be able to run your program without installing python.
7. If you need only exe file not other dependencies files then use pyinstaller "--onefile yourfilename.extension"
   ```bash
    --onefile assistant.py 👈
   ```
 8. Open Run window on your machine and type "shell:startup" to open the Startup window.
 9. Add your assistant.exe or main.exe (Application file not programming file) there.
 10. That's it now whenever you will start your machine, you wil find someone there to greet you and asks for your order.  
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
Please make sure to update tests as appropriate. 🎃
