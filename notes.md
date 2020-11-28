# Namjoo notes

* ## HTML, HTML5 and XHTML
* ## Bootstrap 4
* ## XML
* ## CSS
<p>&nbsp;</p>

* ## Jupyter
* ## Visual studio code
* ## [Markdown](#markdown)
<p>&nbsp;</p>

* ## Javascript
* ## ES6
* ## AJAX
* ## JSON
* ## Typescript
* ## Expressjs
* ## Vuejs
* ## Reactjs
* ## node.js
* ## ?Backbone.js
* ## ?React native
<p>&nbsp;</p>

* ## Flutter
* ## Dart
<p>&nbsp;</p>

* ## PWA
* ## Python
* ## Django
* ## Django Rest Framework
* ## Flask
<p>&nbsp;</p>

* ## Linux
* ## Git and GitHub
* ## Docker
<p>&nbsp;</p>

* ## SQL
* ## Mysql
* ## Mariadb
* ## Redis
<p>&nbsp;</p>

* ## AGILE
* ## ?Scrumm
* ## ?Jira
<p>&nbsp;</p>

* ## ?RabiitMQ
* ## ?travis
* ## ?Mpi
* ## ?Openmp
* ## ?Webgl
<hr/>
<p>&nbsp;</p>

## Markdown

### Source for Markdown:
https://dotcms.com/docs/latest/markdown-syntax
```
<p>&nbsp;</p>
```
برای اضافه کردن خط خالی
<p>&nbsp;</p>



### Ul list
```
* + -
```
For use ul tag
<p>&nbsp;</p>




### Add link
```Markdown
[Namjoo](http://namjoosadr.ir)
```
[Namjoo](http://namjoosadr.ir)



or add it directly
``` namjoosadr.ir ```
        namjoosadr.ir

<p>&nbsp;</p>

### Anchor link
 ```Markdown
[Link to anchor](#anchor)
## anchor
```

[Link to anchor](#Anchor)
## Anchor


<p>&nbsp;</p>



```Markdown
## head1
```
<p>&nbsp;</p>
For add empty line.
```<p>&nbsp;</p>```


Delete current line
Ctrl + Shift + k
<p>&nbsp;</p>

## Git and GitHub

Git Documention: https://docs.github.com/en

### Install git
Download from git-scm.com

```git --version```











<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>


















create a new repository on the command line

```git
git init
git add README.md
touch .gitignore
git add .gitignore
git add README.md
git add .   # add all file to tracked
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/namjoo/Visual-studio-code-notes.git
git push -u origin maste

```





## Javascript

```javascript
throw 10;
throw "I am in Uncaught section";

try {
  throw "tryyyyyyyyyyyyyy";
} catch (error) {
  
  document.write(error);
  document.write(error.message);
  document.write("<br>catchhhhhhhhhhhh");
}
```

```
 x = document.getElementById("age").value;
 alert(isNaN(x));
 y = Number(x);
```

### Definition and Usage
* The isNaN() function determines whether a value is an illegal number (Not-a-Number).

* This function returns true if the value equates to NaN. Otherwise it returns false.

* This function is different from the Number specific Number.isNaN() method.

* The global isNaN() function, converts the tested value to a Number, then tests it.

* Number.isNaN() does not convert the values to a Number, and will not return true for any value that is not of the type Number.

```javascript
    x = '123';
    document.write(isNaN(x));
    document.write('<br/>');
    if (Number(x) == x)
      document.write('Number(x) == x  <br/>');
    
    if (Number(x) === x){
      document.write('Number(x) === x <br/>');
      } else {
      document.write('Number(x) !=== x <br/>');}
```
Output:

false
Number(x) == x
Number(x) !=== x


<p>&nbsp;</p>
```javascript
var age = 5;
var person = {
    age : 10,
    fistname:'john',
    family:'Muler',
    agefunc : function(){
      return 'In ' +  age + ' <br/>';
    },
    agefunc2 : function(){
      return 'In ' +  this.age + ' <br/>';
    }
  }

  alert('Person obj one : ' + person.age);
  alert("Main: "+ age);
  alert('Person obj two : ' + person.agefunc());
  alert('Person obj two : ' + person.agefunc2());
```

Output:

Person obj one : 10
Main: 5
Person obj two : In 5
Person obj two : In 10

<p>&nbsp;</p>
```javascript
<button type="button" onclick="this.style.display='none'" id="button1">Title of button</button>
<button type="button" onclick="disp()">Title of button 2</button>
  
  <script>
  function disp(){
      x = document.getElementById("button1");
      
      x.style.display='block';
   }
```

<p>&nbsp;</p>
```javascript
let i = 5;
for(let i = 0; i<10;i++)
{
 
}
alert(i);
```
Output:

5

<p>&nbsp;</p>
```javascript
const name = "John"
```


You can add/delete items to dics or arrays but you can not change them.
```javascript
const person = {name:'John',age:20};
console.log(person);
person.email =  'namjoosadr@yahoo.com';
console.log(person);

document.write(person)
document.write(person.age)
```
<p>&nbsp;</p>

```javascript
const person = ['John',20];
console.log(person);
person.push('12345')
console.log(person);
document.write(person)
person.pop();
console.log(person);
```


E:\IT\skills\js\js\16_JavaScript