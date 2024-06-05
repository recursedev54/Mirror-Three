Make A folder called Mirror Three Host_1 and put all these in it. n\
1 n\
Then Clone Mirror Three by downloading the zip named Mirror Three Hostz.zip. 
2
Next, decompress the files and start using them. you can use the corpus' as external HHD's for each plug depth.
3
This will sound less esoteric later...
5
After you have this setup, locate the file you created 
'''YourComputerPathFrom~C:To~end:'''/Mirror Three Host_1\Found New Depths! Mirror Four!\Daemon
6
Once you found the Daemon Folder you should see 6 layers of python files 
4
Layer 0 32x32 black box Host Shell Script (build .py in ide to Plug Depth)
Layer 1 32x32 black box Host Shell (build .py in ide to Plug Depth)
Layer 2 32x32 black box Host (build .py in ide to Plug Depth)
Layer 3 32x32 black box (build .py in ide to Plug Depth)
Layer 4 32x32 Daemon Server Matrix (build .py in ide to Plug Depth)
Layer 5 32x32 DemonHead Domain Matrix (build in .py to Plug Depth)
Layer 6 16x28 AngelHead
5
Open Up VS Code and open up Daemon as the workspace folder. 
6
If you don't know what this means you can search engine it. 
7
Once you have all the files opened, you need to make a new tasks.json for your vs code cmd palette
8
Ask ChatGPT how to use this code to let you open up all 6 layers at once or figure it out if you know how~~ 
19
if you know what you're doing you probably already opened up Cmd+Shift+P.
{
    "version": "2.0.0",
    "tasks": [
        {
            "label": "Run All Python Files",
            "type": "shell",
            "command": "powershell",
            "args": [
                "-NoProfile",
                "-Command",
                "Get-ChildItem -Filter *.py | ForEach-Object {python $_.FullName}"
            ],
            "group": {
                "kind": "build",
                "isDefault": true
            },
            "presentation": {
                "echo": true,
                "reveal": "always",
                "focus": true,
                "panel": "dedicated"
            },
            "problemMatcher": []
        }
    ]
}
now you should see this when you hit Cmd+Shift+P in vs code 
> Tasks: Run Task                                    recently used
Tasks: Run Build Task                                Ctrl + Shift + B
Tasks: Open User Tasks
Tasks: Manage Automatic Tasks
Debug: Select and Start Debugging

Accounts: Manage Trusted Extensions For Account      other commands
Add Cursor Above                                     Ctrl + Alt + UpArrow
Add Cursor Below                                     Ctrl + Alt + DownArrow
Add Cursors To Bottom                                Ctrl + Shift + Alt + DownArrow
Add Cursors to Line Ends                             Shift + Alt + I
Add Cursors To Top                                   Ctrl + Shift + Alt + UpArrow
Add Data Breakpoint at Address
Add Function Breakpoint
Add Line Comment                                     Ctrl + K Ctrl + C
Add Selection To Next Find Match                     Ctrl + D
Add Selection To Previous Find Match
Add XHR/fetch Breakpoint
C/C++ Runner: Build Folder                           Ctrl + K Ctrl + B
You want to hit the very top, "Tasks: Run Task" and it should open up 6 windows. If it suceeds, you've completed the tutoiral. hope over to Frog Height and try experimenting with building each .py by itself as a standalone terminal like this
Run Chuck Throw Shell Save.py

Run Python File > (>=Build Button In VS Code)
Run Python File in Dedicated Terminal
Python Debugger: Debug Python File
Python Debugger: Debug using launch.json
Happy Diving
