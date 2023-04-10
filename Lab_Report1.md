# Lab Report - Week1
I will be demonstrating how to log into course-specific ieng6 account in this tutorial. Since I am using a mac, all the instructions are in accordance with macOS
## VScode
1. First, we have to install VScode on your laptop. For this go to <https://code.visualstudio.com/docs/setup/mac> and click on **Download Visual Studio Code**.
![Image](S1.png)
2. In VScode, open the terminal.


## Remotely Connecting
Every student has a cse15l account which is linked to a remote server. Your username would be cs15lsp23zz
1. Reset the password for this account through <https://sdacs.ucsd.edu/~icc/index.php>. Use this tutorial for help - [[TUTORIAL] How to Reset your CSE 15L Password](https://drive.google.com/file/d/17IDZn8Qq7Q0RkYMxdiIR0o6HJ3B5YqSW/view?usp=share_link)
2. After you have changed your password, go to your VScode terminal and enter the following code to login to the remote server\
    ```ssh cs15lsp23zz@ieng6.ucsd.edu```
3. Then you should enter the cs15l course-specific password and enter yes.
    ![Loging in to the remote server](S4.png)
    
    Note that you won't be able to see your password on the screen though you are typing for security reasons.
    
    
    ![Login message](S3.png)

## Trying some commands
1. Lets try some cd and pwd commands.
> 1. cd command stands for "change directory". You can use this command prompt followed by different arguments to change directories.
> 2. You can use two dots as an argument to change the directory to parent directory. ```cd ..``` 
> 3. You can use a relative path to a subdirectory(red in this example) to change the directory to a subdirectory. ```cd red```
> 4. You can give no arguments to change the directory to home directory. ```cd```
