---
layout: page
title: Getting Setup!
permalink: /module3/exercise2
---

#### Setting up and getting to know the tools in your toolkit
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

<br>

##### [> Next Exercise](/module3/exercise3)

<br>
<br>
<br>
