# Html Training Course

**What is HTML ?**

+ **Hyper Text Markup Language**
+ **Not** a programming language 
+ Markup Language for creating webpages/documents
+ Building blocks of the web 

**What We Need To Start  ?**

+ A Web Browser (Pick One)
  - Google Chrome
  - Mozilla Firefox
  - Microsoft Edge
  - Opera 

+ A Test Editor (Pink One)
  + Visual Studio Code
  + Sublime Text 
  + Atom.io
  + Notepad++ (Windows)
  + TextMate (Mac)

**Getting Started with Downland Visual Studio Code**

+ Firstly, visit the [Visual Studio Code website](https://code.visualstudio.com/) to download the Visual Studio Code installer for Windows. Once it is downloaded, run the installer (*VSCodeUserSetup-{version}.exe*). It will only take a minute.

![1Step ](https://user-images.githubusercontent.com/69158314/111070843-dc110180-84d3-11eb-9e5e-50e61ae6a203.png)

![2Step](https://user-images.githubusercontent.com/69158314/111070817-b7b52500-84d3-11eb-8320-dc0a2de1f6e4.png)

  ![3Step](https://user-images.githubusercontent.com/69158314/111070854-ec28e100-84d3-11eb-90a8-2123dec785b0.png)


+ Secondly, accept the agreement and click on next.

![4Step](https://user-images.githubusercontent.com/69158314/111070867-f519b280-84d3-11eb-92fc-aae7ee565004.png)

+ Thirdly, click on “***create a desktop icon***” so that it can be accessed from desktop, click on the list of the “***other***“ and click on Next.

![5Setp](https://user-images.githubusercontent.com/69158314/111070878-ff3bb100-84d3-11eb-9e45-3db962c4a160.png)

+ After that, click on the install button.

![6Step](https://user-images.githubusercontent.com/69158314/111070887-06fb5580-84d4-11eb-99c7-c2d4ca248379.png)

+ Finally, after installation completes, click on the finish button, and the visual studio code will get open.

![7Step](https://user-images.githubusercontent.com/69158314/111070894-0cf13680-84d4-11eb-9a8b-b0ac5ee8d945.png)

***Creating an HTML file*** 

 + Does Not need a server

 + Files must end with the ***.html*** extension

 + Runs in a web browser (Chrome, Firefox, etc)

 + ***index.html***  is the root / home page of a website

   + for example : 

     http://www.something.com

     Loads the ***index.html*** file

     http://www.something.com/about.html

     Loads the ***about.html*** file 

<p style="color:red;"> let's started </p>

+ Firstly, create New folder  ***"HTML Training "***

+ Secondly, in this folder Create New Document  ***"New Text Document.txt"***  And rename this document to ***index.html***

+ Thirdly, right click on the file ***index.html***  and select ***"Open with Code"***  the visual studio code will get open.

+ After that, Type ***hello world*** in visual studio code and save this with ***Ctrl+S***

+ Finally, double click on the ***index.html***, now we can see ***hello world*** in the browser 

***Tag Syntax***

<***tagname***>content</***tagname***>       Element names surrounded by angle brackets

<***h1***>About us </***h1***>                           Normally come in pairs (start tag and end tag)

<***p***>This is a paragraph<***/p***>              End tag in usually the same but with a forward slash 

<***br***> (self closing)                                Some tags close themselves 



***HTML Page  Structure***

![structure html](https://user-images.githubusercontent.com/69158314/111072762-4d54b280-84dc-11eb-9ce5-f56b3f17d205.png)




***Example of HTML Page  Structure***

<!***DOCTYPE html***>

<***html lang="en"***>

<***head***>

  <***title***>HTML Training Course</***title***>

</***head***>

<***body***>

  <***h1***>My First Heading</***h1***>

  <***p***>My First paragraph.</***p***>

</***body***>

</***html***>



### Heading
```
  <h1>Heading One</h1>

  <h2>Heading Two</h2>

  <h3>Heading Three</h3>

  <h4>Heading Four</h4>

  <h5>Heading Five</h5>

  <h6>Heading Six</h6> 
```



### Paragraph 
``` 
  <p>

 - Lorem ipsum dolor sit amet consectetur, adipisicing elit. Obcaecati 

  non magni similique ipsam. Ipsa at molestias ipsam eos pariatur saepe

  illum officiis atque blanditiis velit minima aperiam delectus, eaque beatae?

  </p>
  
```
***Inline VS Block Level Elements***

**Inline Elemnts:**
- Do not start on a new line 
- Take only the necessary with

**Block Elements:**
- Start on a new line
- Take full width available

**Block Level:**
```<div>,<h1>-<h6>,<p>,<form>```

**Inline Level:** 
```<span>,<img>,<a>```

### Paragraph with Strong, em

``` 
   <p>
    Lorem ipsum dolor sit<strong> amet consectetur</strong>, adipisicing elit. Obcaecati 
    non magni <em>similique ipsam</em>. Ipsa at molestias ipsam eos pariatur saepe
    illum officiis atque blanditiis velit minima aperiam delectus, eaque beatae?
   </p>
  
```
### Paragraph with href
``` 
   <p>
    Lorem ipsum dolor <a href="https://www.google.fr/" target="_blank">sit amet consectetur</a>,adipisicing elit. Obcaecati 
    non magni similique ipsam. Ipsa at molestias ipsam eos pariatur saepe
    illum officiis atque blanditiis velit minima aperiam delectus, eaque beatae?
   </p>
  
```
### List
``` 
  <ul>
    <li>List Item 1</li>
    <li>List Item 2</li>
    <li>List Item 3</li>
    <li>List Item 4</li>
  </ul> 
   
   <ol>
    <li>List Item 1</li>
    <li>List Item 2</li>
    <li>List Item 3</li>
    <li>List Item 4</li>
   </ol>  
```
### Table
```
 <table>
    <tr>
      <th>Firstname</th>
      <th>Lastname</th>
      <th>Email</th>
      <th>Age</th>
    </tr>
    <tr>
      <td>Jill</td>
      <td>Smith</td>
      <td>Smith@something.com</td>
      <td>50</td>
    </tr>
    <tr>
      <td>Eve</td>
      <td>Jackson</td>
      <td>Jackson@something.com</td>
      <td>94</td>
    </tr>
  </table>
```
### form
```
 <form action="action_page.php" method="POST">
   <div>
        <label>First Name:</label>
        <input type="text" name="firstName" placeholder="enter your first name">
   </div> 
   <br>
   <div>
        <label>Last Name:</label>
        <input type="text" name="lastName">
   </div> 
   <br>
   <div>
        <label>Email:</label>
        <input type="text" name="email"> 
   </div> 
   <br>
   <div>
       <label>Message:</label>
       <textarea name="message"></textarea>
   </div>
   <br>
   <div>
       <label>Gender:</label>
       <select name="gender">
           <option value="male">Male</option>
           <option value="female">Female</option>
           <option value="other">Other</option>
       </select>
   </div>
   <br>
   <div>
       <label>Age:</label>
       <input type="text" name="age" value="30">
   </div>
   <br>
   <div>
       <label>Birthday:</label>
       <input type="date" name="birthday">
   </div>
   <br>
   <input type="submit" name="submit" value="Submit">
  </form>
```
### button
```
 <button>Click Me</button>
```
### Image
```
 <img src="images/sample.jpg" alt="My sample Image">
```
### Image with css
```
 <img src="images/sample.jpg" alt="My sample Image" with="200">
```
### Image with href
```
<a href="images/sample.jpg">
  <img src="images/sample.jpg" alt="My sample Image" with="200" height="200"> 
</a>
```
### other
```
 <p><cite>HTML crash course</cite>by Mohamed</p>
```

### HTML5 Semantic Tags

![semantic](https://user-images.githubusercontent.com/69158314/111840628-06602600-88fd-11eb-8bbc-db68b0b6f9e9.png)

```
<article></article>
<aside></aside>
<details></details>
<footer></footer>
<header></header>
<main></main>
<nav></nav>
<section></section>
```
### Header

```
<header>
    <h1>My Website</h1>
</header>
```
### Section

```
<section>
    <article class="post">
        <h3>Blog Post</h3>
        <small>Poste by Mohamed on January 20</small>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias esse vero ab consequatur, rem sint dolorem eius dolorum exercitationem, necessitatibus modi iure rerum            facere obcaecati nam! Quos enim reprehenderit a.</p>
        <a href="post.html">Read More</a>
    </article>
</section>
```
### 3 Section

```
<section>
    <article class="post">
        <h3>Blog Post One</h3>
        <small>Poste by Mohamed on January 20</small>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias esse vero ab consequatur, rem sint dolorem eius dolorum exercitationem, necessitatibus modi iure                  rerum facere obcaecati nam! Quos enim reprehenderit a.</p>
        <a href="post.html">Read More</a>
    </article>
</section>

<section>
    <article class="post">
        <h3>Blog Post Two</h3>
        <small>Poste by Mohamed on January 20</small>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias esse vero ab consequatur, rem sint dolorem eius dolorum exercitationem, necessitatibus modi iure                  rerum facere obcaecati nam! Quos enim reprehenderit a.</p>
        <a href="post.html">Read More</a>
    </article>
</section>

<section>
    <article class="post">
        <h3>Blog Post Three</h3>
        <small>Poste by Mohamed on January 20</small>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias esse vero ab consequatur, rem sint dolorem eius dolorum exercitationem, necessitatibus modi iure                  rerum facere obcaecati nam! Quos enim reprehenderit a.</p>
        <a href="post.html">Read More</a>
    </article>
</section>
```





