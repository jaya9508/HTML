# HTML
## Table Of Contents

 - [Introduction](#Introduction)
   
 - [First HTML File](#first-html-file)

  
 - [Basic HTML Page](#basic-html-page)
     
 - [Comments in HTML](#comment-in-html)


 - [HTML is not case sensitive](#html-is-not-case-sensitive)


 - [HTML Tags](#html-tags)


- [Page Layout Techniques](#page-layout-techniques)


- [Inside Main Tag](#inside-main-tag)


- [List in HTML](#list-in-html)

  
- [Tables in HTML](#tables-in-html)


- [Colspan Attribute](#colspan-attribute)

- [Form in HTML](#form-in-html)


- [References](#References)


## Introduction


HTML 

***Hyper Text Markup Language*** 

HTML is the code that is used to structure a web page and its content.

The component used to design the structure of websites are called HTML tags.

What do you mean by Markup Language?

It means that a markup language is a computer language that is used to apply layout and formatting conventions to a text document. Markup language makes text more interactive and dynamic. It can turn text into images, tables, links, etc.

## First HTML File

Index.html

- It is a default name for a website's homepage.

## Basic HTML Page

      <!DOCTYPE html>  `tells the browser you are using HTML5
       <html>           `root of an html document
         <head>        `container for metadata
           <title>my first page</title>  `page title
         </head>
     <body>         ` contains all data renderd by the browser
        <p>hello world</p>   ` paragraph tag
     </body>
     </html>

## Comments in HTML

- It help to make code easier to understand.

              <!-- this is an HTML comment-->

## HTML is not case sensitive

    <html>=<HTML>
    <p>=<P>
    <body>=<BODY>
    <head>=<HEAD>

## HTML Tags
### HTML Attributes

- Attributes are used to add more information.

  
      <html lang="en">
  ### Heading Tag

  - Used to display heading in HTML.

        <h1>This is heading1</h1>  most important
        <h1>This is heading2</h1>
        <h3>This is heading2</h3>
        <h4>This is heading4</h4>

  ### Paragraph Tag

 - Used to add paragraph in HTML.

         <p>My name is Jaya</p>
   ### Anchor Tag

  - Used to add links to your page.

         <a href=https://github.com/jaya9508/HTML/edit/main/README.md</a>
   
   ### Image Tag

  - Used to add image to your Page.

         <img src="/image.png" alt="Random image">

   ### Br Tag

   - Used to add next line(line break) to your page.

         <p>I am June Intern</p>
         <br>
         <p>I am foxian</p>

   ### Bold,Italic & Underline Tags

   
  - Used to highlight text in your page.

         <b>Bold</b>

         <i>Italic</i>

         <u>Underline</u>

   ### Big & Small Tags

   - Used to display big and small text on your page.

         <big>Bag</big>

         <Small>Bag</Small>

 ###  Subscript & Superscript Tag

- Used to display a horizontal rular,used to separate content.

      O<sub>2</sub><br>
      a<sup>2<sup/>

### Pre Tag
- Used to display text as it is(without ignoring spaces and next line).


      <pre>It is sample text</pre>
  
  ## Page Layout Techniques

- Using Semantic tags for layout.

   Using the Right Tags.

      <header></header>
      <main></main>
      <footer></footer>

## Inside Main Tag

#### Section Tag  
- For a section on your page.

      <section></section>
#### Article Tag
- For an article on your page.

      <article></article>

#### Aside Tag
- For content aside main content(ads).

      <aside></aside>

 ##  List in HTML

 - Lists are used to represent real life list date.
 
Unordered

    <ul>
    <li>RAM</li>
    <li>SHYAM</li>
    </ul>

Ordered

    <ol>
    <li>Ram</li>
    <li>Shyam</li>
    </ol>

 ## Tables in HTML

 
 - Tables are used to represent real life table data.
 
        <tr></tr>  ~ used to display table row
        <td></td>    ~ used to display table data
        <th></th>  ~ used to display table header
#### Example
     <Caption>student Detail</Caption>
        <table>
            <tr>
               <th>Name</th>
               <th>Roll No.</th>
            </tr>
      <tr>
         <th>Jaya</th>
         <th>102</th>
      </tr>
       </table>
 ## Colspan attribute 

     Colspan="n"
- Used to create cells which spans over multiple columns.
                <td colspan="number">content</td>
## Form in HTML

- Forms are used to collect data from the user.
- Eg-sign up/login/help requests/contact me etc.

    <Form>
     form content
     </Form>
 ### Action in Form
 - Action attribute is used to define what action needs to be performed when a form is submitted.

        <form action="/action.php">
### Form Element : Input

    <input type="text" placeholder="Enter Name">
  
  ### Label

    
     <input type="radio"value="class X" name="class" id="id1">
        <label for="id1"> class X </label>

    
    <input type="radio" value="class XI" name="class" id="id2">
       <label for="id2"> class Xi </label>

### Checkbox
    
      <input type="checkbox" value="class X" name="class" id="id1">
        <label for="id1">class X</label>
 

    
    <input type="checkbox" value="class X" name="class" id="id2">
       <label for="id2">class X</label>

### Select

    <select name="city" id="city">
    <option value="Delhi">Delhi</option>
    <option value="Mumbai">Mumbai</option>
    <option value="Varanasi">Varanasi</option>

  ## References

  
 [Link1](https://www.geeksforgeeks.org/html-tutorial/)

 [Link2](https://www.w3schools.com/tags/tryit.asp?filename=tryhtml_label)

 [Link3](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)

  

  

       

 
       
       

      
    
 

      
      
      

   

   

  
     




















  
