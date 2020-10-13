# VMkiller
Brief Description: Transmitting Codes from your PC to a VM that cannot share your PC Clipboard.
## Main Idea of the Project
However isolated the VM is, at least the authority to type will be granted. This project reads code from your PC, switch to the interface of the VM automatically, and then output the code letter-by-letter into the VM.
## Users' Guide
- Check your Python Environment whether you have installed "pynput" package. If no, open cmd and run command ```pip3 install pynput```;
- Use your favorite Python IDLE to open VMkiller.py;
- Copy your source code to the same directory of VMkiller.py and change the file name in VMkiller.py to the name of your source file;
- Open your Virtual Machine via Microsoft Desktop, and log in your VM account;
- Open shell in your VM; open an empty txt file (Note: can't be cpp or other kinds of file) with vim (Another option is to use nano instead of vim; in this case you can make a new cpp or hpp file). Switch to insert mode by pressing i on the keyboard;
- Minimize your VM Desktop window (IMPORTANT!) and run the Python code (This may fail; retry this step until it works);
- Then your computer automatically shifts to the window of the Virtual Machine and start outputting your source code;
- After the whole process completed, press Esc to switch to the vim normal mode, and input ```:wq``` to save and quit. Done.
## Reminder
- This code is simply for fun; any commercial usages need to be granted by the project owner. 
- (IMPORTANT) Please don't use it for any Honor Code violation or illegal purposes.
