---
layout: page
title: Getting Setup!
permalink: /module3/exercise1
---

#### Setting up and getting to know the tools in your toolkit
---
#### Exercise 1: Pipes and Redirects

**Vertical Bar**

You can use pipes to pass data from one command to another, such as in this example:

    cat hello.txt | wc -l

In this case, this command will read the contents of hello.txt and give the word count in lines. 
This allows you to easily find the number of lines in a file.

**Redirects**

You can also use a redirect to change where a command writes it's output to. Usually, output is written to 
standard out (the terminal), but you can change it to a file using the right arrow symbol.

    echo "Hello" > hello.txt

You can also use 2 right arrows to append:

    seq 10 20 > numbers_1.txt
    seq 10 20 > numbers_1.txt

    seq 10 20 >> numbers_2.txt
    seq 10 20 >> numbers_2.txt

Try these out and see the difference!

<br>

##### [> Next Exercise](/module3/exercise2)

<br>
<br>
<br>
