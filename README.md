![image](https://github.com/RIDWANE-EL-FILALI/MARKDOWN/blob/master/1_zv16_HpmtjBQ3QfObwGkiA.jpeg)
---


# -> MARKDOWN 
Markdown is a lightweight markup language that you can use to add formatting elements to plaintext text documents. Created by John Gruber in 2004, Markdown is now one of the world’s most popular markup languages.


## HOW IT WORKS
  when you write in markdown, the text is stored in a plaintext file that has .md or .markdown extension.
  a lot of applications convert markdown-formatted text to html so it can be displayed in web browsers
  markdown applications use something called a markdown processor
  you can check the visual overview of the process below.
  
  ![image](https://github.com/RIDWANE-EL-FILALI/MARKDOWN/blob/master/markdown.jpeg)
  
## BASIC SYNTAX
Nearly all Markdown applications support the basic syntax outlined in John Gruber’s original design document. There are minor variations and discrepancies between Markdown processors, those are noted inline wherever possible.

### Headings
just like html it has 6 levels of headings.
since the markdown processor suports html i will add html tags just to get u going 
```
MARKDOWN                         HTML
----------------------------------------------------------
# Heading level 1           | <h1>Heading level 1</h1>
## Heading level 2          | <h2>Heading level 2</h2>
### Heading level 3         | <h3>Heading level 3</h3>
#### Heading level 4        | <h4>Heading level 4</h4>
##### Heading level 5       | <h5>Heading level 5</h5>
###### Heading level 6      | <h6>Heading level 6</h6>
```

### Pragraphs
- To create paragraphs, use a blank line to separate one or more lines of text, you should not indent paragraphs with spaces or tabs
``` 
            MARKDOWN                                            HTML
-----------------------------------         |       ---------------------------------
HELLO WORLD !                               |       <p>HELLO WORLD!</p>
                                            |       
BYE WORLD                                   |       <p>BYE WORLD</p>
-----------------------------------         |       ---------------------------------
```
- To create a line break,end a line with two or more spaces, and then type return
``` 
            MARKDOWN                                            HTML
-----------------------------------         |       ---------------------------------
HELLO WORLD !                               |       <p>HELLO WORLD!<br />                         
BYE WORLD                                   |       BYE WORLD</p>
-----------------------------------         |       ---------------------------------
```

### Emphasis
You can add emphasis by making text bold or italic
- to bold text add two asteriks or underscores before and after a word or phrase
```
                        MARKDOWN
---------------------------------------------------------------------
hello **world** my name is ridwane but you can call me **B.R.O.L.Y**
hello __world__ my name is ridwane but you can call me __B.R.O.L.Y__

---------------------------------------------------------------------
                          HTML
---------------------------------------------------------------------
hello <strong>world</strong>
---------------------------------------------------------------------
```
- to italicize text, add one asterisk or underscore before and after a word or phrase.
```
                        MARKDOWN
---------------------------------------------------------------------
hello *world* my name is ridwane but you can call me *B.R.O.L.Y*
hello _world_ my name is ridwane but you can call me _B.R.O.L.Y_

---------------------------------------------------------------------
                          HTML
---------------------------------------------------------------------
hello <em>world</em>
---------------------------------------------------------------------
```
- to emphasize text with bold and italics at the same time, add three asterisks or underscores before and after a word or phrase
```
                        MARKDOWN
---------------------------------------------------------------------
hello ***world*** my name is ridwane but you can call me ***B.R.O.L.Y***
hello ___world___ my name is ridwane but you can call me ___B.R.O.L.Y___

---------------------------------------------------------------------
                          HTML
---------------------------------------------------------------------
hello <strong><em>world</em></strong>
---------------------------------------------------------------------
```
### Blockquotes
- To create a blockquote add a > in front of a paragraph
```
                        MARKDOWN
---------------------------------------------------------------------
> hello world
---------------------------------------------------------------------
                          HTML
---------------------------------------------------------------------
<blockquote>
    <p>hello world</p>
</blockquote>

---------------------------------------------------------------------
```
- To create a blockquote with multiple paragraphs add a > on the blank lines between the paragraphs.
```
                        MARKDOWN
---------------------------------------------------------------------
> hello world
>
>my name is ridwane
---------------------------------------------------------------------
                          HTML
---------------------------------------------------------------------
<blockquote>
    <p>hello world</p>
    <p>my name is ridwane</p>
</blockquote>
---------------------------------------------------------------------
```

### Lists
ordered and unordered lists
- To create an ordered list, add line items with numbers followed by periods. The numbers don’t have to be in numerical order, but the list should start with the number one.
``` 
            MARKDOWN                                            HTML
-----------------------------------         |       ---------------------------------
1.Firstitem                                 |       <ol>
2.Seconditem                                |           <li>First item</li>
3.Thirditem                                 |           <li>Second item</li>
4.Fourthitem                                |       <ol/>
                                            |
1.Firstitem                                 |
1.Seconditem                                |
1.Thirditem                                 |
1.Fourthitem                                |
                                            |
1.Firstitem                                 |
8.Seconditem                                |
3.Thirditem                                 |
5.Fourthitem                                |
---------------------------------------------------------------------------------------
```
- To create an unordered list, add dashes (-), asterisks (*), or plus signs (+) in front of line items.
``` 
            MARKDOWN                                            HTML
-----------------------------------         |       ---------------------------------
- Firstitem                                 |       <ul>
- Seconditem                                |           <li>First item</li>
- Thirditem                                 |           <li>Second item</li>
- Fourthitem                                |       <ul/>
                                            |
* Firstitem                                 |
* Seconditem                                |
* Thirditem                                 |
* Fourthitem                                |
                                            |
+ Firstitem                                 |
- Seconditem                                |
* Thirditem                                 |
+ Fourthitem                                |
---------------------------------------------------------------------------------------
```
### Images
```
            Markdown                                          Html
---------------------------------------------------------------------------------------
![image](link)                            |   <img src="link"/></p>
```

### Horizontal Rules
- To create a horizontal rule, use three or more asterisks (***), dashes (---), or underscores (___) on a line by themselves.
```
            Markdown                                          Html
---------------------------------------------------------------------------------------
***                                       |       <hr />
---                                       |       <hr />
---------------------------------------------------------------------------------------
```
### Links
- To create a link, enclose the link text in brackets (e.g., [Duck Duck Go]) and then follow it immediately with the URL in parentheses (e.g., (https://duckduckgo.com)).
```
            Markdown                                          Html
-------------------------------------------------------------------------------------------------------
[Duck Duck go](https://duckduckgo.com)    |   <p>Use<ahref="https://duckduckgo.com">DuckDuckGo</a>.</p>
-------------------------------------------------------------------------------------------------------
```
- You can optionally add a title for a link. This will appear as a tooltip when the user hovers over the link. To add a title, enclose it in parentheses after the URL.
```
            Markdown                                                           Html
------------------------------------------------------------------------------------------------------------------------------------------------
[DuckDuckGo](https://duckduckgo.com"Mysearchengine!")    |         <p><a href="https://duckduckgo.com"title="Mysearchengine!">DuckDuckGo</a>.</p>
------------------------------------------------------------------------------------------------------------------------------------------------
```
- To quickly turn a URL or email address into a link, enclose it in angle brackets.
```
            Markdown                                                           Html
------------------------------------------------------------------------------------------------------------------------------------------------
  1 <https://eff.org>                               |            <a href="https://eff.org">https://eff.org</a>
2 <helloworl@gmail.com>                             |            <a href="mailto:helloworld@gmail.com">helloworld@gmail.com</a>
------------------------------------------------------------------------------------------------------------------------------------------------
```

### Tables

- To add a table, use three or more hyphens (---) to create each column’s header, and use pipes (|) to separate each column. You can optionally add pipes on either end of the table.
```
        Markdown                                      
-------------------------
|Syntax     |Description| 
|-----------|-----------| 
|Header     |Title      | 
| Paragraph | Text      |
-------------------------
```
the output will be like this :                                     
-------------------------
|Syntax     |Description| 
|-----------|-----------| 
|Header     |Title      | 
| Paragraph | Text      |
-------------------------

- You can align text in the columns to the left, right, or center by adding a colon (:) to the left, right, or on both side of the hyphens within the header row.
```
-----------------------------------------------------
| Syntax          | Description        |   Test text|
| :---            |        :---:       |       ---: | 
| header          | Title              | Hero's this|
| Paragraph       | Text               | And more   |
-----------------------------------------------------
```
the output will be like :
| Syntax          | Description        |   Test text|
| :---            |        :---:       |       ---: | 
| header          | Title              | Hero's this|
| Paragraph       | Text               | And more   |

### Heading IDs
- Many Markdown processors support custom IDs for headings — some Markdown processors automatically add them. Adding custom IDs allows you to link directly to headings and modify them with CSS. To add a custom heading ID, enclose the custom ID in curly braces on the same line as the heading.

```
### Myheading {#custom-id}
```
- You can link to headings with custom IDs in the file by creating a standard link with a number sign (#) followed by the custom heading ID.
```
[HeadingIDs] (#heading-ids)
```

### Strikethrough
- You can “strikethrough” words by putting a horizontal line through the center of them. This feature allows you to indicate that certain words are a mistake not meant for inclusion in the document. To strikethrough words, use two tilde symbols (∼∼) before and after the words.
```
The world is ~~flat~~ round
```
the output will be:
The world is ~~flat~~ round

### Task Lists
- Task lists allow you to create a list of items with checkboxes. In Markdown applications that support task lists, checkboxes will be displayed next to the content. To create a task list, add dashes (-) and brackets with a space ([ ]) in front of task list items. To select a checkbox, add an x in between the brackets ([x]).
```
- [X] Writethepressrelease
- [ ] Updatethewebsite
- [ ] Contactthemedia
```
the output will be: 
- [X] Writethepressrelease
- [ ] Updatethewebsite
- [ ] Contactthemedia

<p align="center">
<h1 align="center"><strong>If you like this repo star it</strong></h1>
</p>
<p align="center"><a href="https://www.buymeacoffee.com/B.R.O.L.Y"> <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50" width="210" alt="ridwane-el-filali" /></a></p><br><br>
