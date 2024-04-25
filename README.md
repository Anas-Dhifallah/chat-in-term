# chat-in-term
Chatting Application in C, used on the terminal.
---
I will explain how each file functions and what are the commands usable on the application here!

user.txt - Contains a list of users that you registered that you can access any time without having to create new users everytime.
The user and password are separated by a "," and different users are separated by a "\n".

text.txt - contains all the chat you've had before, it's like a history tracker for you to see your previous discussions.
The layout is as such -
username: message
otheruser: message

main.c - contains all the code.

a.out - is the executable file *FOR LINUX*!

If you are on windows a.out will not be executable.
You will have to compile it again using gcc.
Do it this way:

1) Download MinGW and Install it. Open it and download GCC Compiler.
2) Open the Command Prompt or CMD for short, and run the following command: gcc main.c
3) Check repository using the following command: dir
4) You will be able to see a new file named: a.exe
5) To run it either open the directory on the Windows File Explorer and click on it or type the following command: ./a.exe

If you have any other questions, complaints or changes you want to see, let me know via the following email address: godsguestgroup@gmail.com

Note: Keep in mind that this app version is not final. An interface will be added and several more functionalities will be implemented.
With that said, enjoy!
