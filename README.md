Make A folder called Mirror Three Host_1 and put all these in it. n\
1 n\
~ n\
~ n\
~ n\
Then Clone Mirror Three by downloading the zip named Mirror Three Hostz.zip. n\
2
~ n\
~ n\
~ n\
~ n\
Next, decompress the files and start using them. you can use the corpus' as external HHD's for each plug depth. n\
3
~ n\
~ n\
~ n\
~ n\
This will sound less esoteric later... n\
5
~ n\
~ n\
~ n\
~ n\
After you have this setup, locate the file you created n\
'''YourComputerPathFrom~C:To~end:'''/Mirror Three Host_1\Found New Depths! Mirror Four!\Daemon n\
6 n\
~ n\
~ n\
~ n\
~ n\
Once you found the Daemon Folder you should see 6 layers of python files n\
4 n\
~ n\
~ n\
~ n\
~ n\
~ n\
~ n\
~ n\
~ n\
Layer 0 32x32 black box Host Shell Script (build .py in ide to Plug Depth) n\
Layer 1 32x32 black box Host Shell (build .py in ide to Plug Depth) n\
Layer 2 32x32 black box Host (build .py in ide to Plug Depth) n\
Layer 3 32x32 black box (build .py in ide to Plug Depth) n\
Layer 4 32x32 Daemon Server Matrix (build .py in ide to Plug Depth) n\
Layer 5 32x32 DemonHead Domain Matrix (build in .py to Plug Depth) n\
Layer 6 16x28 AngelHead n\
5 n\
~ n\
Open Up VS Code and open up Daemon as the workspace folder. n\ 
6 n\
~ n\
If you don't know what this means you can search engine it. 
7
~ n\
~ n\
~ n\
Once you have all the files opened, you need to make a new tasks.json for your vs code cmd palette
8
~ n\
~ n\
~ n\
~ n\
Ask ChatGPT how to use this code to let you open up all 6 layers at once or figure it out if you know how~~ 
19
~ n\
~ n\
~ n\
~ n\
~ n\
~ n\
~ n\
~ n\
~ n\
~ n\
~ n\
~ n\
~ n\
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
now you should see this when you hit Cmd+Shift+P in vs code ~ n\
> Tasks: Run Task                                    recently used~ n\
Tasks: Run Build Task                                Ctrl + Shift + B~ n\
Tasks: Open User Tasks~ n\
Tasks: Manage Automatic Tasks~ n\
Debug: Select and Start Debugging~ n\

Accounts: Manage Trusted Extensions For Account      other commands~ n\
Add Cursor Above                                     Ctrl + Alt + UpArrow~ n\
Add Cursor Below                                     Ctrl + Alt + DownArrow~ n\
Add Cursors To Bottom                                Ctrl + Shift + Alt + DownArrow~ n\
Add Cursors to Line Ends                             Shift + Alt + I~ n\
Add Cursors To Top                                   Ctrl + Shift + Alt + UpArrow~ n\
Add Data Breakpoint at Address~ n\
Add Function Breakpoint~ n\
Add Line Comment                                     Ctrl + K Ctrl + C~ n\
Add Selection To Next Find Match                     Ctrl + D~ n\
Add Selection To Previous Find Match~ n\
Add XHR/fetch Breakpoint~ n\
C/C++ Runner: Build Folder                           Ctrl + K Ctrl + B~ n\
You want to hit the very top, 
~ n\
"Tasks: Run Task" and it should open up 6 windows. If it suceeds, 
~ n\you've completed the tutoiral.
~ n\hope over to Frog Height and try experimenting with building each 
~ n\.py by itself as a standalone terminal like this
~ n\
~ n\
~ n\
Run Chuck Throw Shell Save.py ~ n\

Run Python File > (>=Build Button In VS Code) ~ n\
Run Python File in Dedicated Terminal ~ n\
Python Debugger: Debug Python File ~ n\
Python Debugger: Debug using launch.json ~ n\
~ n\
~ n\
~ n\
Happy Diving ~ n\
