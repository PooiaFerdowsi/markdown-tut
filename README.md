# markdown-tut
My markdown (.md) practices

# Header 1
for substitutes you can use ============ and/or `<h1>`
  
## Header 2
for alternatives you can use ------------ and/or `<h2>`

### Header 3
as an alternative you can use `<h3>`

#### Header 4
`<h4>` is a good alternative!

##### Header 5
and header 5 has five # (sharp) behind header name

###### Header 6
now can you remember what's subtitute? it's `<h6>`

Header 1 like RestructuredText(.rst)
====================================
it's header 1 style used in .rst

Header 2 .rst style
--------------------
.rst header 2 style

Text formatting
================

you can use *astriskes like * to mark a text as italic* or you can use _underscores _ as alternative for *_
when you want mark text as strong and/or bold you can use double * or _ like
__Hello World used double underscores(_)___
**Hello World used double astriskes(*)***

# Lists
1. item 1
2. item 2
3. item 3
4. item 4
..* unordered sub item
  + another sub item
  1. order sub items
  2. second ordeer sub item
5. item 5

...an indented paraghraph is here

...another indented paraghraph

+ using plus to insert an unorder list
+ and continue it
- can you continue an unorder list started by + by -
- No! it's make new list

* and a splited list!
* is here

# Links
now is turn of _links_ 
*R8|R10|R11 are scratch registers! there not preserved*
[link](https://google.com)

[link with title html attributes](https://google.com "google.com popularest search engine in the earth")

[link with reference][an-example-link]

[an-example-link]: https://google.com

[link with reference and title][linkref]

[linkref]: https://youtube.com "YouTube"
[you can insert reference links by numberical references][1]

[1]: https://github.com "Source code hosting"

[it is name of a reference in brackets that showed as link]

[it is name of a reference in brackets that showed as link]: https://dictionary.cambridge.org "Cambridge dictionary"

you can insert links between <> like <https://gnu.org> or you can insert link like https://ftp.gnu.org wothout any special character


NASA
=====

NASA is short for _National Aronastics and Space Adminstrator_

This organization is dependent on United States <https://usa.gov> and handle most of space projects 

![alt text](https://www.nasa.gov/sites/default/files/images/nasaLogo-570x450.png)

My favorite softare NASA developed:

...is [Astrobee][na]


# Tables
Now I want to experiment tables.
I've re[a]d that most simple shape of a markdown table looks like below:

```
Header 1 | Header 2 | Header 3
---------|----------|----------
Column 1 | Column 2 | Column 3
Row 2 | still | row 2
```

Header 1 | Header 2 | Header 3
---------|----------|----------
Column 1 | Column 2 | Column 3
Row 2 | still | row 2

You can insert `|` before and after heads, like following:
```

| Header 1 | Header 2 | Header 3 |
---------|----------|----------
| Column 1 | Column 2 | Column 3 |
| Row 2 | still | row 2 |
```
| Header 1 | Header 2 | Header 3 |
---------|----------|----------
| Column 1 | Column 2 | Column 3 |
| Row 2 | still | row 2 |

__It's _not_ everything about markdown tables! but it's that you need to know!__

# Blocquotes
> after a long time, I am still unable to pronunciate `quote` :)
> But you can properly see that i add a new `>` in the next line
> and you guess i am writing in a same line!
> Your guess is not true but that is'nt false!
> I am writing in different lines but in *same* blockquote!

> and it is a new one

# substitutes of `hr` tag!
You can use three

___

underscores or

---
hyphens or

***
stars

to make an `hr` tag...


[na]: https://github.com/nasa/astrobee "NASA Astrobee"
