# MirrorBLAWG Post: Exciting New Features in Mirror Three!\

Greetings, MirrorDAWg community!\

We are thrilled to unveil the latest build of Mirror Three, packed with exciting new features and significant improvements over Mirror Two. This update focuses on enhancing the user experience, adding new visual elements, and optimizing performance. Let's dive into the most notable changes:\

## Enhanced Scrolling and Display Mechanics\

### 1. Automatic and Manual Scrolling\
One of the standout features in this build is the revamped scrolling mechanism. Mirror Three introduces automatic scrolling, which advances the display by one line every second (or as configured by the user). This ensures a smooth and continuous flow of information, perfect for those long coding sessions. Additionally, manual scrolling via the mouse wheel is now fully supported, giving users more control over their viewing experience.

### 2. Center-Justified Text Stream\
To create a more immersive and visually appealing interface, we've implemented center-justified text for all directory trees and log streams. This change makes the display cleaner and easier to read, providing a better overall user experience.\

### 3. Thicker and More Dynamic Streams\
We've enhanced the visual representation of our text streams by duplicating each line with random horizontal offsets. This creates a thicker, more dynamic stream that simulates a flowing effect, much like a river. This aesthetic improvement not only looks great but also makes it easier to follow the stream of information.\

## Visual Enhancements\

### 4. Customizable Colors\
Mirror Three allows for greater customization of the interface. Users can now set their desired background color, text color, and grass color using hex codes. This flexibility lets you personalize your environment to suit your preferences and improve visual comfort during extended use.\

### 5. Animated Grass Patterns\
We've added animated ASCII grass patterns to the side panels (riverbanks) of the interface. These animations enhance the overall look and feel, making the user interface more engaging. The grass animation shifts dynamically, providing a subtle yet pleasing visual effect.\

### 6. Full-Screen Mode with Side Panels\
Mirror Three maintains a full-screen mode that immerses you in your work. The side panels, now three times wider, create a more balanced and visually appealing layout. These panels are perfect for displaying additional information or animations without cluttering the main workspace.\

## Performance and Usability Improvements\

### 7. Interval Control (Krate)\
A new feature in this build is the Krate (interval control), which lets you adjust the scrolling speed. The default is set to one second, but users can customize it to suit their needs. This makes the interface adaptable to different workflows and preferences.\

### 8. Resetting Scroll Position\
To ensure continuous information flow, we've implemented a feature that resets the scroll position to the top once the bottom is reached. This looping mechanism keeps the display fresh and prevents any interruptions in the visual stream.\

## Conclusion\

The improvements in Mirror Three mark a significant step forward from Mirror Two. With enhanced scrolling, dynamic visual elements, and greater customization options, this build is designed to elevate your experience and make your time in MirrorDAWg more productive and enjoyable. We can't wait for you to try out these new features and hear your feedback.\

Stay tuned for more updates and happy coding!\

Best,\
The MirrorDAWg Team\

---

Feel free to share your thoughts and experiences with Mirror Three in the comments below or on our community forums. Your feedback is invaluable to us as we continue to refine and enhance our platform.\alright now that that guys is done... ... ... ...
you dont need to install anything before starting. open up a .py to see its requirements. they're all modular.
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
check out the "fun" folder for standalone apps that can go alongside your environment processes threads.
