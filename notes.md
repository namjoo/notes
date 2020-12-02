# Namjoo notes

* ## HTML, HTML5 and XHTML
* ## Emmet
* ## Bootstrap 4
* ## XML
* ## CSS
&nbsp;

* ## Jupyter
* ## Visual studio code
* ## [Markdown](#markdown)
&nbsp;

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
&nbsp;

* ## Flutter
* ## Dart
&nbsp;

* ## PWA
* ## Python
* ## Django
* ## Django Rest Framework
* ## Flask
&nbsp;

* ## Linux
* ## Git and GitHub
* ## Docker
&nbsp;

* ## SQL
* ## Mysql
* ## Mariadb
* ## Redis
&nbsp;

* ## AGILE
* ## ?Scrumm
* ## ?Jira
&nbsp;

* ## ?RabiitMQ
* ## ?travis
* ## ?Mpi
* ## ?Openmp
* ## ?Webgl

&nbsp;
&nbsp;

## HTML, HTML5 and XHTML


```
<head>
```
دیتای در مورد وب سایت در آن قرار میگیرد
برای کاربران قابل مشاهده نیست

&nbsp;
<p dir='rtl' align='right'>
HTML5


<div dir='rtl' align='right'>

* از INDEXDB پشتیبانی میکند که با جاوا اسکریپت میتواند به آن دسترسی داشت  
* پشتیبانی از فایل های صوتی و تصویری  
*  و تگ های معنایی
 HEADER
 FOOTER
 SECTION
</div>

SEO
<div dir='rtl' align='right'>
در هر صفحه یک تگ h1 وجود داشته باشد
در صفحات داخلی میتوان عنوان سایت را تگ h3 گذاشت.
در عناوین داخل سایت مثل اخبار و ... از تگ های h3 h4 استفاده نمایید
برای عناوین مهمتر از h2 استفاده نمایید
</div>
<div dir='rtl' align='right'>

* em برای ایتالیک کردن به کار میرود

* strong برای bold کردن بکار میرود
پیشنهاد میشود از تگ strong به جای b hsjthni klhddn
</div>
<div dir='rtl' align='right'>
تگ DOCTYPE html را در ابتدا قرار دهید
</div>
<div dir='rtl' align='right'>
از تگ title  در body استفاده نکنید
</div>
&nbsp;

<div dir='rtl' align='right'>
img تگ بسته نداره

alt attribute مورد استفاده موتور های جستجو قرار میگیرد

</div>

```html
<a href="mailto:namjoosadr@yahoo.com">Mail</a>
```

```html
<video controls width="720" height="350">
  <source src="sample.mp4">
    Your browser doesnot support video tag
</video>
<video controls width="720" height="350" src="sample.mp4">
  
    Your browser doesnot support video tag
</video>
<video controls width="720" height="350" poster="a___.jpg">
  <source src="sample.mp4">
    Your browser doesnot support video tag
</video>

```
<div dir='rtl' align='right'>
در تگ ویدیوی اول میتوانیم چندیدن ویدیو با پسوندهای متفاوت و کیفیت های متفاوت قرار دهیم که با توجه به براوزر لود شوند

در video دوم فقط یک ویدیو می توان آپلود کرد
</div>
```html
<audio src="" controls preload="auto">
  
</audio>
<audio src="" controls preload="auto">
  <source src="sample.mp3">
      Your browser doesnot support audio tag

</audio>

```

<div dir='rtl' align='right'>
source 
تگ بسته ندارد

تگ audio , video در html5 اضافه گردیدند
</div>

```html
<form method="get|post">
```

* get	Default. Appends the form-data to the URL in name/value pairs: URL?name=value&name=value
* post	Sends the form-data as an HTTP post transaction
* get is defult.

Notes on GET:

* Appends form-data into the URL in name/value pairs
* The length of a URL is limited (about 3000 characters)
* Never use GET to send sensitive data! (will be visible in the URL)
* Useful for form submissions where a user wants to bookmark the result
* GET is better for non-secure data, like query strings in Google

Notes on POST:
* Appends form-data inside the body of the HTTP request (data is not shown in URL)
* Has no size limitations
* Form submissions with POST cannot be bookmarked
&nbsp;

```html
<input type="submit" value="send">
<Button type="submit">send</Button>
```
<input type="submit" value="send">
<Button type="submit">send</Button>
<div dir='rtl' align='right'>
حالت اول قدیمیتر است و در حال حاضر از دومی بیشتر استفاده می شود
</div>

info about HTML tags:
https://developer.mozilla.org/en-US/docs/Web/HTML


### meta tags
```html
<meta charset="utf-8">
<meta name="author" content="namjoo">
<meta name="description" content="This is description">
<!-- will shows in result of search engines-->

<meta property="og:image" content="sample.jpg">
<meta property="og:description" content="This is description">
<meta property="og:title" content="title">
<!-- will shows in social networks similar telegram-->
```
```html
<link rel="stylesheet">
<script></script>
```

## Emmet
!!!
Output:
```html
<!DOCTYPE html>
```

!
Output:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

span#one
```html
<span id="one"></span>
```

span.two
```html
<span class="two"></span>
```

h3#title.post
```html
<h3> id="title" class="post"></h3>
```

div#block.post
```html
<div id="block" class="post"></div>
```

 #block.post
```html
<div id="block" class="post"></div>
```

h1+h2+div
```html
<h1></h1>
<h2></h2>
<div></div>
```


article>div>img+h2+span
```html
<article>
    <div>
        <img src="" alt="">
        <h2></h2>
        <span></span>
    </div>
</article>
```

ul>li*3
```html
<ul>
    <li>dd</li>
    <li>kpo</li>
    <li>kpo</li>
</ul>
```

h1+span*4
```html
<h1></h1>
<span></span>
<span></span>
<span></span>
<span></span>
```
section>h1>b+h2>li*3
```html

<section>
    <h1>
        <b></b>
        <h2>
            <li></li>
            <li></li>
            <li></li>
        </h2>
    </h1>
</section>
```

section>(h1>b)+h2>li*3

```html
<section>
    <h1><b></b></h1>
    <h2>
        <li></li>
        <li></li>
        <li></li>
    </h2>
</section>
```

lorem
```html
Lorem ipsum dolor sit amet consectetur adipisicing elit. Unde error iusto vitae aut doloribus culpa laboriosam sunt fuga esse alias dolores nulla aliquam 
delectus eos facilis, quaerat quisquam. Veniam, placeat.
```
lorem30

```html
Lorem, ipsum dolor sit amet consectetur adipisicing elit. Illo corporis facere eligendi fugiat! Quisquam maiores odio sit, nemo veniam illo consequatur harum id optio atque incidunt accusantium natus suscipit provident.
```

lorem3

```html
Lorem, ipsum dolor.
```

lorem6

```html
Lorem ipsum dolor sit amet consectetur.
```
ul>li.item*3>lorem3

```html
<ul>
    <li class="item">Lorem, ipsum dolor.</li>
    <li class="item">Quae, culpa eveniet.</li>
    <li class="item">Sed, ipsa cupiditate!</li>
</ul>
```

section>li>a.link{click me}

```html
<section>
    <li><a href="" class="link">click</a></li>
    <li><a href="" class="link">click</a></li>
    <li><a href="" class="link">click</a></li>
</section>
```

ul>li*2^div
```html
<ul>
    <li></li>
    <li></li>
</ul>
<div></div>
```
section>h1>span*2^^div
```html
<section>
    <h1><span></span><span></span></h1>
</section>
<div></div>
```
&nbsp;
img[title]
```html
<img src="" alt="" title="">
```

img[title="my title"]
```html
<img src="" alt="" title="my title">
```

[title="div tag"]

```html
<div title="div tag"></div>
```


img[title][source="ddd"]
<img src="" alt="" title="" source="ddd">

change default

input[type="checkbox"]
```html
<input type="checkbox">
```

ul>li.item-$*3
```html
    <ul>
        <li class="item-1"></li>
        <li class="item-2"></li>
        <li class="item-3"></li>
    </ul>
```

```
ul>li.item-$*3{the number of item $}
```

```html
    <ul>
        <li class="item-1">the number of item 1</li>
        <li class="item-2">the number of item 2</li>
        <li class="item-3">the number of item 3</li>
    </ul>
```
div{this is  parameters}*3
```html
    
    <div> this is  parameters</div>
    <div> this is  parameters</div>
    <div> this is  parameters</div>
```
div*3{ this is  parameters}
```HTML
    <div> this is  parameters</div>
    <div> this is  parameters</div>
    <div> this is  parameters</div>
```
div{this is the paragraph $$}*3
```HTML
    <div>this is the paragraph 01</div>
    <div>this is the paragraph 02</div>
    <div>this is the paragraph 03</div>
```
div{this is the paragraph $$$}*4
```html 
    <div>this is the paragraph 001</div>
    <div>this is the paragraph 002</div>
    <div>this is the paragraph 003</div>
    <div>this is the paragraph 004</div>
```

.item-$@4*5
```html
    <div class="item-4"></div>
    <div class="item-5"></div>
    <div class="item-6"></div>
    <div class="item-7"></div>
    <div class="item-8"></div>
```
E:\IT\Emmet





## Visual studio code
View > pallete   |   ctrl + shift + p
Delete current line
Ctrl + Shift + k
&nbsp;

Ctrl + B
show/hide left sidebar


## Markdown

### Source for Markdown:
https://dotcms.com/docs/latest/markdown-syntax
```
&nbsp;
```
برای اضافه کردن خط خالی
&nbsp;



### Ul list
```
* + -
```
For use ul tag
&nbsp;




### Add link
```Markdown
[Namjoo](http://namjoosadr.ir)
```
[Namjoo](http://namjoosadr.ir)



or add it directly
``` namjoosadr.ir ```
        namjoosadr.ir

&nbsp;

### Anchor link
 ```Markdown
[Link to anchor](#anchor)
## anchor
```

[Link to anchor](#Anchor)
## Anchor


&nbsp;



```Markdown
## head1
```
&nbsp;
For add empty line.
```&nbsp;```



&nbsp;

## Git and GitHub

Git Documention: https://docs.github.com/en

### Install git
Download from git-scm.com

 ```git
git --version
```

<div dir='rtl' align='right'>
فایل تنظیمات عمومی (global) مربوط به git
</div>


C:\Users\Namjoo\.bash_history
C:\Users\Namjoo\.gitconfig
<div dir='rtl' align='right'>
یک فایل تنظیمات سیستمی نیز وجو دارد که زمانی که در یک سیستم چندین کاربر کار می کنند مورد استفاده قرار میگیرد

یک فایل تنظمیات دیگر نیر به صورت local در سیستم وجود دارد. این فایل زمانی که با دستور git init دایرکتوری جاری را با git،  track میکنیم  در مسیر جاری به آدرس
.git/config ایجاد میگردد
</div>

```git
git config
git config --global user.name = namjoo
git config --global user.email = namjoosadr@yahoo.com
```
<div dir='rtl' align='right'>
با دو دوستور بالا نام و ایمیل خود را درفایل global تنظیم میکنیم
</div>

```git
git config --list
```
<div dir='rtl' align='right'>
با دستور بالا تنظمیات اعمال شدهدر فایل global قابل مشاهده است.
</div>

```git
git config --global --edit
```
&nbsp;
<div dir='rtl' align='right'>
فایل config را در editor پیش  فرض برای ویرایش باز میکند
</div>
<div dir='rtl' align='right'>
اگر --global نوشته نشود سیستم local را در نظر میگیرد
از دستورات لینوکس در git bash میتوان استفاده کرد.
</div>

```git
cd project_directory
git init
code .
```
<div dir='rtl' align='right'>اگر visual stdio code روی سیستم نصب است
دستور اخر پوشه جاری را در VSC باز میکند
</div>


```git
git config
git config user.name = namjoo
git config user.email = namjoosadr@yahoo.com
```
<div dir='rtl' align='right'>
با فرض اینکه در پوشه پروژه هستیم
تنظیمات را روی فایل config محلی انجام میدهد
</div>

```git
git help
git help config
git help add
git help <command>
git config -h
```

<div dir='rtl' align='right'>
به directory که آن را توسط git ترک میکنیم، Working directory میگوییم.
</div>

```git
git add note.txt
```
add note.txt to stages and tracked files
 
```git
git status
```
<div dir='rtl' align='right'>
وضعیت کل دایرکتوری رو میبینیم
</div>


```git
git commit -m "add note"
```
Add files to repository and history

```git
git log
```
<div dir='rtl' align='right'>تاریخچه commit ها را میتوانیم ببینیم</div>

```git
git add .
```
Add all current files to repository and history

```git
start index.html
```
Open index.html in your browser.
4 toplearn












&nbsp;






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


&nbsp;

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

&nbsp;
```javascript
<button type="button" onclick="this.style.display='none'" id="button1">Title of button</button>
<button type="button" onclick="disp()">Title of button 2</button>
  
  <script>
  function disp(){
      x = document.getElementById("button1");
      
      x.style.display='block';
   }
```

&nbsp;

```javascript
let i = 5;
for(let i = 0; i<10;i++)
{
 
}
alert(i);
```
Output:

5

&nbsp;
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
&nbsp;

```javascript
const person = ['John',20];
console.log(person);
person.push('12345')
console.log(person);
document.write(person)
person.pop();
console.log(person);
```

&nbsp;
### Use debugger

```javascript
debugger;
```

Press F9 for trace it step by step
Press F8 for rusume remain code
&nbsp;


### validate
```javascript
<form action="namjoo.ir/calc.html" name="formname" method="POST" onsubmit="return validate()">
      <input type="text" name="fname"/>
      <input type="submit" value="submit" />
    </form>
  <script>
  function validate(){
    return true;
  }
  </script>
```

### Objects
```javascript
var person ={name:'john',
            fam:"namjoo",
            age:30
          }
console.log(person)
console.log(person.name)
```
Output:
{name: "john", fam: "namjoo", age: 30}
john
&nbsp;
Serialaizer
{name: "john", fam: "namjoo", age: 30}

```javascript
function calc(){
  var a,b;
  a= 10;
  b=13;
  return a +b;
}
alert(calc());


function cal(){
  var a,b;
  a= 10;
  b=13;
  alert(a+b);
}
cal()
```
&nbsp;
### Constructor
```javascript

function person(name,tel,age){
  this.name=name;
  this.tel= tel;
  this.age;
  this.status =function(){
    return 'maried.'
  }
}

var people = []
var john = new person("John","34323",25)
alert(john.status())
people.push(new person('Sara','565',25))
people.push(new person('Tomas','565',32))
people.push(new person('George','5g65',20))
```
&nbsp;
```javascript
var x = function(a,b){return a +b;}
var y = x(3,7);
console.log(y)
```
Output:
10
```javascript
var x = new Function("a","b","return a +b")
var y = x(4,7);
console.log(y);
```
Output:
11

```javascript
(function(){alert('ok')})()
```
Self Invoke
&nbsp;

  Arrow Function
```javascript
var sum = (a,b)=> a+b;
alert(sum(5,11));
``` 
&nbsp;

```javascript
function  sum(){
          for (i in arguments){
            console.log(i,arguments[i])
          }
      
      }
      sum(4,"john",true,653)
```
 E:\IT\skills\js\js\21_JavaScript




## CSS

https://developer.mozilla.org/en-US/docs/Web/CSS/Reference
https://caniuse.com/

```css
a[href]{
    background:yellow;
}

a[href="yahoo.com"]{
    font-size: 1.5em;
}

a[href*="google"]{
   font-size: 3em;
}


a[href$="net"]{
    color:blue;
    font-size: xx-large;
 }

li[class="item"] a{
    color:black;
}


div li[class~="item"] a{
    background-color:black;
    font-size: 5em;
}

li > span{
}

li + span{
style to span that come directly after li
/* <li>/<li>
<span></span> */
}

li.item + span{
    style to span that come directly after <li class="item">
    /* <li>/<li>
    <span></span> */
  }

li ~ span{

  }


li:hover{

}
li:hover a{
  color:#fff;
}
```
https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes

```css
li::before{
  content:" before "
  color:blue;
}

li:after{
  content:" before "
  color:red;
}
p::first-letter{
  color:green;
}
p::first-line{
  color:green;
}

*{

}
.header *{

}
```
search for css reset.
E:\IT\html-css\css-ro\23-inheritance

## Notes
https://roadmap.sh