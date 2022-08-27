---
layout: page
title: Getting Setup!
permalink: /module3/exercise
---

#### Setting up and getting to know the tools in your toolkit
---
<br>

#### Exercise 4: Flags and Arguments

**Flags**

Flags are additional arguments you can pass into calls to change the default behaviour and access more advanced functions.

Here are a few, try them out!

| Command 					| Description 				|
| ----------- 				| ----------- 				|
| `ls -a`					| Displays hidden files	 	|
| `rm -d <folder>`			| Removes a directory		|
| `rm -r <folder>`			| Removes files recursively (will remove all files in a folder including files in subfolders) - **CAUTION**		 |

You can also combine arguments - do not try this one out unless you are very sure

| Command 					| Description 				|
| ----------- 				| ----------- 				|
| `rm -rf <folder>`			| Removes files recursively and forcefully (without user confirmation) - <span style="color:red">**DANGER**</span>		 |


Exercises
- Remove a folder
- Find a hidden folder within your computer (hint: try `cd ~`)

---


#### Exercise 5: Programs and Pipes


**Pipes and Redirects**

Pipes and redirects allow you to redirect output into files and other programs, which is great for manipulating data. It's a powerful tool, but can get quite messy and chaotic as you can see in the image below.

![](https://images.nintendolife.com/ae4e322a531ad/1280x720.jpg)

Try out the following code snippets:

<br>

**Snippet 1: Copy Files without `cp`**
```
    echo "text" > file1.txt
    cat greet.txt > file1_copy.txt
    cat hello.txt
```

**Snippet 2: Append two files together**
```shell
    echo "Hello there" > greet.txt
    echo "General kenobi" > name.txt
    cat greet.txt name.txt > hello.txt
    cat hello.txt
```

**Snippet 3: Find number of lines in file**
```
    cat file1.txt | wc -l
```

**Snippet 4: Create many files**
```
    touch bspl{0001..0003}.c
```

**Snippet 4: Delete select files**
```
    rm .nfs000000000*
```

---

<br>
<br>
<br>