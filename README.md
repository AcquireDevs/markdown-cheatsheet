![md](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/1200px-Markdown-mark.svg.png)

---
**what is markdown :**
> Markdown is a superset of html and used very often in github as making profile and readme of the reposatories.Markdown is used to make readme in spite of html because markdown is far more easier and also svae much time. 

**how to make a markdown file:**
`save a markdown file as .md`

---

### Cheatsheet of Markdown   
---
#### 1. **headings in markdown**



|markdown|html|output|
|:---|:---:|---:|
|`### head1`|`<h3>head</h3>`|<h3>head</h3> |  
**all headings input:**
```markdown
######head6
#####head5
####head4
###head3
##head2
#head1

```
**output**

---

######head6
#####head5
####head4
###head3
##head2
#head1

---
### 2. bold and italic in markdown
|markdown|html|output|
|---|---|---|
|`**bold**`|`<b>bold</b>`|**bold**|

>it can also be written as `__bold__`

|markdown|html|output|
|---|---|---|
|`*italic*`|`<i>itlaic</i>`|*italic*|
>it can also be written as `_italic_`

markdown|html|output|
|---|---|---|
|`**italic+bold**`|`<i><b>itlali+bold</b><i>`|***italic+bold***|

**input:**
in markdown
```markdown
*this is itlaic para*
_this is itlaic para_
**this is bold**
__this is bold__
***this is itlaic and bold***
___this is itlaic and bold___
```
in html
```html
<i>this is itlaic para</i>
<b>this is bold para<b>
<i><b>this is itlaic and bold para</b></i>


```


**output:**
  
markdown:
:  *this is itlaic para*
  _this is itlaic para_
**this is bold**
__this is bold__
***this is itlaic and bold***
___this is itlaic and bold___  

html:
 : <i>this is itlaic para</i>
<b>this is bold para<b>
<i><b>this is itlaic and bold para</b></i>




---
### Blockquote
input:
```markdown
>this is a markdown blockquote
 note:html blockquote do not have any default design 
```
output
>this is a markdown blockquote
 note:html blockquote do not have any default design 

---

### LISTS
#### __orderd list__
```markdown

in markdown

1. javascript
56. json
28845. nodejs
```
```html
in html

<ol>
<li>javascript</li>
<li>json</li>
<li>nodejs</li>
</ol>
```
output:
: 1. javascript
  56. json
  28845. nodejs

      
#### unorderd list:
```markdown
in markdown

- js
- html
- electron
```
```html
in html

<ul>
<li>js</li>
<li>html</li>
<li>electron</li>
</ul>
```
output:
: - js
  - html
  - electron 
---

### Code

input:
```markdown

javscript:
`console.log('hello world')`
python:
`print('hello world')`

```
output: 

`console.log('hello world')`
 
`print('hello world')`

---
### line
|markdown|html|
|:---|:---:|
|---|`<hr>`|
input:
```markdown
--- 

```
output: 
  
 ---

>__note:__ don't put it below any world as it will works as heading 

---
### Image
```markdown
![img](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR7_gHGIwsuuJXHTWqKMRMwAqJLuFqTxbNDw8Su84vhglOFKUHT1WAEH98G2uRaYn8EXuM&usqp=CAU)
```
output:
![img](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR7_gHGIwsuuJXHTWqKMRMwAqJLuFqTxbNDw8Su84vhglOFKUHT1WAEH98G2uRaYn8EXuM&usqp=CAU)
### Link
```markdown
[github](https://github.com/AcquireDevs/AcquireDevs.git)
```
output:
: [github](https://github.com/AcquireDevs/AcquireDevs.git)

### Table
```markdown
|languages|tools|
|---|---|
|javascript|nodejs|
|html|markdown|
|css|scss|


```
output:
|languages|tools|
|---|---|
|javascript|nodejs|
|html|markdown|
|css|scss|
### fenced code block

input:
```markdown
`` 
const express=require('express')
const app=express
``


```
>use ``` instead of ``

output:
```
const express=require('express')
const app=express
```

> for hightlighing of text you can write programming language you are writing after first ```

example:

```markdown
``javascript 
const express=require('express')
const app=express
``


```

output:
```javascript 
const express=require('express')
const app=express
```
---

### footnote in markdown

input:
```
socket.io [^1] 
[^1]: socket.io is used to make a connection between server   
and clients with  other clients
```
output:
socket.io [^1]   
  
>**note:** it will not work in github
    
     

       
        

         
[^1]: socket.io is used to make a connection between server   
and clients with  other clients

---
### Defination list
input
```markdown
title
: content
```
output:

title
: content

---
### strikeline
input
```markdown
~~this is removed~~
```
output:
: ~~this is removed~~

---
### task list 
input
```markdown
- [x] js
- [ ] css
- [x] html
```
output:
- [x] js
- [ ] css
- [x] html














