---
layout: page
title: Searching with Regex
permalink: /module2/exercise2
---

#### Learning Regular Expressions (Regex)
---
#### Exercise 2: Parliment

In this exercise you will analyze a file named parliament.txt containing a list of the members of the Australian House of Representatives (MPs).

[download](/static/parliament.txt) (right click and save page to download)

<br>

![](https://hotelkurrajong.com.au/wp-content/uploads/2020/02/canberra-accomodation-attractions-parliament-house.jpg)

<br>

**Write a grep -E command that will print all the lines in the file where the electorate begins with 'W'.**

It should print:

    Hon Scott Buchholz: Member for Wright, Queensland
    Hon Tony Burke: Member for Watson, New South Wales
    Mr Stephen Jones: Member for Whitlam, New South Wales
    Mr Peter Khalil: Member for Wills, Victoria
    Mr Llew O'Brien: Member for Wide Bay, Queensland
    Mr Dave Sharma: Member for Wentworth, New South Wales
    Ms Anne Stanley: Member for Werriwa, New South Wales
    Ms Zali Steggall OAM: Member for Warringah, New South Wales
    Hon Dan Tehan: Member for Wannon, Victoria

<br>

---

<br>

**Write a grep -E command that will print all the lines in the file where the MP's given name (first name) is "Andrew".**

It should print:

    Hon Andrew Gee: Member for Calare, New South Wales
    Mr Andrew Giles: Member for Scullin, Victoria
    Hon Andrew Hastie: Member for Canning, Western Australia
    Hon Dr Andrew Leigh: Member for Fenner, Australian Capital Territory
    Hon Andrew Wallace: Member for Fisher, Queensland
    Mr Andrew Wilkie: Member for Clark, Tasmania

<br>

---

<br>

**Write a grep -E command that will print all the lines in the file where the MP's surname (last name) ends in the letters 'll'.**

It should print:

    Ms Angie Bell: Member for Moncrieff, Queensland
    Mr Julian Hill: Member for Bruce, Victoria
    Mr Brian Mitchell: Member for Lyons, Tasmania
    Mr Rob Mitchell: Member for McEwen, Victoria
    Ms Zali Steggall OAM: Member for Warringah, New South Wales

<br>

---

<br>

**Write a grep -E command that will print all the lines in the file where the MP's surname (last name) and the electorate name ends in the letter 'y'.**

It should print:

    Ms Peta Murphy: Member for Dunkley, Victoria
    Mr Rowan Ramsey: Member for Grey, South Australia

<br>

---

<br>

**Write a grep -E command that will print all the lines in the file where the MP's surname (last name) or the electorate name ends in the letter 'y'.**

It should print:

    Dr Anne Aly: Member for Cowan, Western Australia
    Hon Linda Burney: Member for Barton, New South Wales
    Mr Pat Conroy: Member for Shortland, New South Wales
    Mr Milton Dick: Member for Oxley, Queensland
    Hon Ed Husic: Member for Chifley, New South Wales
    Hon Bob Katter: Member for Kennedy, Queensland
    Ms Ged Kearney: Member for Cooper, Victoria
    Mr Craig Kelly: Member for Hughes, New South Wales
    Hon Michelle Landry: Member for Capricornia, Queensland
    Hon Sussan Ley: Member for Farrer, New South Wales
    Mrs Melissa McIntosh: Member for Lindsay, New South Wales
    Hon Ben Morton: Member for Tangney, Western Australia
    Ms Peta Murphy: Member for Dunkley, Victoria
    Mr Llew O'Brien: Member for Wide Bay, Queensland
    Hon Tanya Plibersek: Member for Sydney, New South Wales
    Mr Rowan Ramsey: Member for Grey, South Australia
    Ms Michelle Rowland: Member for Greenway, New South Wales
    Ms Anne Stanley: Member for Werriwa, New South Wales
    Ms Anika Wells: Member for Lilley, Queensland
    Mr Trent Zimmerman: Member for North Sydney, New South Wales
            
<br>

---

<br>

**Write a grep -E command that will print all the lines in the file where there is any word in the MP's name or the electorate name that ends in "ng".**

It should print:

    Hon Josh Frydenberg: Member for Kooyong, Victoria
    Mr Luke Gosling OAM: Member for Solomon, Northern Territory
    Hon Andrew Hastie: Member for Canning, Western Australia
    Hon Catherine King: Member for Ballarat, Victoria
    Ms Madeleine King: Member for Brand, Western Australia
    Hon Bill Shorten: Member for Maribyrnong, Victoria
    Mr Terry Young: Member for Longman, Queensland

<br>

---

<br>

**Write a grep -E command that will print all the lines in the file where the MP's surname (last name) both begins and ends with a vowel.**

It should print:

    Hon Anthony Albanese: Member for Grayndler, New South Wales
            
<br>

---

<br>

**Write a grep -E command that will print all the lines in the file where the electorate name contains multiple words (separated by spaces or hyphens).**

It should print:

    Hon Barnaby Joyce: Member for New England, New South Wales
    Ms Kristy McBain: Member for Eden-Monaro, New South Wales
    Mr Llew O'Brien: Member for Wide Bay, Queensland
    Hon Matt Thistlethwaite: Member for Kingsford Smith, New South Wales
    Hon Jason Wood: Member for La Trobe, Victoria
    Mr Trent Zimmerman: Member for North Sydney, New South Wales

<br>

##### [> Next Exercise](/module2/exercise3)

<br>
<br>
<br>
