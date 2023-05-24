# Lab Report - Week5
## Researching Commands
In this lab report I will be focussing on the `-less` command and its options. 
> `less` command helps us navigate through the contents of a file without loading it to the memory completely. We view the contents page by page. Additional benefit of `less` command is that it doesn't print the contents of the file in the terminal.
> We can exit navigating through the contents of the file by entering `q`.
> Pressing space bar takes us to the next page in the contents.
> It's syntax is `less [file path]`.

There is a variety of options available for `-less` command which can be really helpful tools.

### Command option 1: `less -N`
> `less -N` displays the line numbers on the left
> This option can be helpful for keeping track of lines.

* **Example1:** 
Lets try running this command.
```
less -N biomed/1471-2121-2-1.txt
```
![](S3.1.png)

* **Example2:** 
Now we will try the same command on a smaller file.
```
less -N plos/pmed.0020258.txt
```
![](S3.2.png)
### Command option 2: `less -f`
> `less -f` option forces the file to open anyways. Sometimes the contents of the file(maybe including binary data) may not be displayed properly. In such cases, this option is highly useful in opening the file.

+ **Example1:** 
Lets try running this command on a binary file without using the option and then using the option
```
[cs15lsp23nc@ieng6-202]:technical:436$ less  plos/pmed.0020281.txt
``` 
The outputs is:
```
"plos/pmed.0020281.txt" may be a binary file.  See it anyway?
```

When running the command with option, we can open the file directly.
![](S3.3.png)

+ **Example2:**
  
### Command option 3: 
> explain the option
```
```
### Command option 4:
> explain the option
```
```

