## HTML Notes
<p> HTML (Hypertext Markup Language) is a fundamental technology for web development.  </p>


### Table  of Content :



#

## Basic Structure of the HTML page:-

<br>


1. The document begin with doctype html tag, This tag tell the browser that the markup of the language in which page is written is HTML. <br>
``` <!DOCTYPE html> ```

<br>

2. Open html tag, html tag is the building block of the page. most other tag nested within open html tag and closing html tag, html tag must be closed to define the ending of the page. <br>
``` <html> </html> ```

<br>

3. similar to html tag, head tag also having corresponding closing tag. Note that anything contain within open tag and closing tag will not visible within content area of your browser. the headtag contains important instruction for your browser. <br>
``` <head> </head> ```

       (a). <title> :-
       First it identify the <title> of the page, actual title of the page must contain within title tag.

       (b). <meta> :-
       Second it contain the meta tag, meta tag communicate with both web browser and search engine to provide valuable information of your page.
                    goal of the meta tag is to pursue the searcher the click through to your website. 

       (c). <style> :-
        Third it contain style tag, the code that is included within style tag are refer to as style rules and it define what is known as pages CSS (Cascading style sheets):{A set of rules that define the presentation of visual elements on an HTML page}.

       (d). <script> :-
       And next comes block of code is Javascript function, remember the javascript allows us to create interactive effects within web browser, the head tag contain the javascript  functions that will be called upon in the <body> of our HTML documents.


<br>

4. the body tag contain content, which is visible content area of your web-browser, here we also call our javascript function. <br>
  ``` <body>```

#

HTML Paragraph Spacing:-
* We just to add ``` <p>   </p> ```  at the opening and closing of the paragraph.


HTML Line breaks:-
* whenever we use ``` html paragraph spacing <p> tag ```, the space is too more between tow lines to avoid this we use ``` <br> ``` tag between ``` <p> ``` tag.


HTML Non-Breaking Space:-
* spacing between two characters, A commonly used entity in HTML is the nonbreaking space: ``` &nbsp; ```. A non-breaking space is a space that will not break into a new line. <br>
  ``` &nbsp; ```  :- Non-Breaking Space.


HTML Header Tags:-
* The ```<header>``` element represents a container for introductory content or a set of navigational links. <br>
  Open Header- ```<h1>``` , close header- ```</h1>```, The 1 value represent the size of the header, smaller the value larger the header. <br>
  A ```<header>``` element typically contains: (a). one or more heading elements ``` (<h1> - <h6>)``` , (b). logo or icon, (c). authorship information
  Note: You can have several ```<header>``` elements in one HTML document. However, ```<header>``` cannot be placed within a ```<footer>```, 
        <address> or another <header> element.

#

HTML Text Formatting and Decoration:-
* Formatting elements were designed to display special types of text: <br>
  ```<b>``` - Bold text :- The HTML ```<b>``` element defines bold text, without any extra importance. <br>
  ```<strong>``` - Important text:- The HTML ```<strong>``` element defines text with strong importance. The content inside is typically displayed in bold. <br>
 ```<i>``` - Italic text:- The HTML ```<i>``` element defines a part of text in an alternate voice or mood. The content inside is typically displayed in italic. <br>
  ```<em>``` - Emphasized text:- The HTML ```<em>``` element defines emphasized text. The content inside is typically displayed in italic. <br>
  ```<mark>``` - Marked text:- The HTML ```<small>``` element defines smaller text: <br>
  ```<small>``` - Smaller text:- The HTML ```<mark>``` element defines text that should be marked or highlighted: <br>
  ```<del>``` - Deleted text:- The HTML ```<del>``` element defines text that has been deleted from a document. Browsers will usually strike a line through deleted text: <br>
  ```<ins>``` - Inserted text:- The HTML ```<ins>``` element defines a text that has been inserted into a document. Browsers will usually underline inserted text: <br>
  ```<sub>``` - Subscript text:- The HTML ```<sub>``` element defines subscript text. Subscript text appears half a character below the normal line, and is sometimes rendered 
                           in a smaller font. Subscript text can be used for chemical formulas, like H2O: <br>
  ```<sup>``` - Superscript text:- The HTML ```<sup>``` element defines superscript text. Superscript text appears half a character above the normal line, and is sometimes 
                             rendered in a smaller font. Superscript text can be used for footnotes, like WWW[1]: <br>

HTML Inline Text Formatting:-
* inline elements—that is, elements that are used inside other elements. <br>
  Paragraphs, headings, and lists are “block-level” elements. They are self-contained sections that start on a new line and take up 
  the entire width of the container. But inline elements do not start on a new line and are only as wide as the content. 
  An example is the ```<strong>``` tag.


HTML Unordered Lists:-
* An unordered list starts with the ```<ul>``` tag. Each list item starts with the ```<li>``` tag. The list items will be marked with bullets (small black circles) by default.
   
HTML Ordered Lists :-
* An ordered list starts with the ```<ol>``` tag. Each list item starts with the ```<li>``` tag. The list items will be marked with numbers by default.

#

HTML Image Insertion:-
* The HTML ```<img>``` tag is used to embed an image in a web page. Images are not technically inserted into a web page, images are linked to web pages.  <br>
  The ```<img>``` tag creates a holding space for the referenced image. The ```<img>``` tag is empty, it contains attributes only, and does not have a closing tag. <br>
  The ```<img>``` tag has two required attributes: <br>

  ```src``` - Specifies the path to the image <br>
  ```alt``` - Specifies an alternate text for the image <br>
  Syntax -  <br>
  ```<img src="url" alt="alternatetext">```  

HTML Embedding Videos:-
* To show a video in HTML, use the ```<video></video>``` element.   <br>

HTML Absolute vs. Relative File Referencing:-
* The main difference between an absolute and relative pathway is that an absolute path specifies the location from the root directory and 
  carries detailed information whereas relative path is related to the current directory and carries only a part of the absolute pathway.

HTML Link Creation:-
* To make a hyperlink in an HTML page, use the anchor ```<a>``` and ```</a>``` tags, which are the tags used to define the links. The ```<a>``` tag indicates where 
  the hyperlink starts and the ```</a>``` tag indicates where it ends. Whatever text gets added inside these tags, will work as a hyperlink.  <br>
  Add the URL for the link in the ```<a href=” ”>```.

#

HTML Anchor Tags:-
* The HTML anchor tag defines a hyperlink that links one page to another page. It can create hyperlink to other web page as well as files, 
  location, or any URL. The ```href``` attribute is the most important attribute of the HTML a tag. and which links to destination page or URL.

HTML Tables:-
* HTML tables allow web developers to arrange data into rows and columns. Define an HTML Table:-  <br>
  The ```<table>``` tag defines an HTML table. Each table row is defined with a ```<tr>``` tag. Each table header is defined with a ```<th>``` tag.   <br>
  Each table data/cell is defined with a ```<td>``` tag. By default, the text in ```<th>``` elements are bold and centered.  <br>
  By default, the text in ```<td>``` elements are regular and left-aligned.  <br>

HTML Nested Tables:-
* The nested table in HTML means creating a table on a webpage inside another table on the same web page.

HTML Merging Cells:-
* To merge cells in HTML, use the colspan and rowspan attribute. The rowspan attribute is for the number of rows a cell should span,
  whereas the colspan attribute is for a number of columns a cell should span. Both the attribute will be inside the ```<td>``` tag.   <br>
  The number will be a numeric value, for example, 2 for 2 rows if rowspan, 2 for 2 columns if column span.

#

HTML Text Wrapping:-
* The word-wrap property allows long words to be able to be broken and wrap onto the next line.

HTML Table Background Image:-
* The background attribute can also be used to control the background of an HTML elmement, specifically page body and table backgrounds.   <br>
  You can specify an image to set background of your HMTL page or table. Following is the syntax to use background attribute with any HTML tag.  <br>
  The background is deprecated and it is recommended to use Style Sheet for background setting.        ```<tagname background="Image URL">```  <br>

HTML Table Cell Alignment:-
* The ```<td>``` tag defines a standard data cell in an HTML table. An HTML table has two kinds of cells:  <br>
  Header cells - contains header information (created with the ```<th>``` element)  Data cells - contains data (created with the ```<td>``` element)  <br>
  The text in ```<td>``` elements are regular and left-aligned by default.  The text in ```<th>``` elements are bold and centered by default. 

HTML - Introduction to Forms:-
* An HTML form is a section of a document containing normal content, markup, special elements called controls (checkboxes, radio buttons, menus, etc.),
  and labels on those controls. Users generally "complete" a form by modifying its controls (entering text, selecting menu items, etc.),
  before submitting the form to an agent for processing (e.g., to a Web server, to a mail server, etc.)  <br>
  " Used to gather input from your User. "  <br>
  " Form Data can be inputted into a Database, or sent to an Email Address."  <br>
  " Input Forms are created in HTML. "  <br> 
  " Data is submitted to a PHP Script for processing. "  <br>

#

HTML  Form Tags and Attributes:-  <br>
* List of All ```<form>``` Attributes  <br>
  Attribute	:     Description  <br>
  accept-charse :     Specifies the character encodings used for form submission <br>
  action   :          Specifies where to send the form-data when a form is submitted <br>
  autocomplete	:     Specifies whether a form should have autocomplete on or off <br>
  enctype	 :    Specifies how the form-data should be encoded when submitting it to the server (only for method="post") <br>
  method	  :   Specifies the HTTP method to use when sending form-data <br>
  name	   :          Specifies the name of the form <br>
  novalidate	:     Specifies that the form should not be validated when submitted <br>
  rel	   :          Specifies the relationship between a linked resource and the current document <br>
  target	:     Specifies where to display the response that is received after submitting the form <br>
 
HTML Form Elements:-
* Tag	          Description <br>
 ```<form>```	          Defines an HTML form for user input <br>
 ```<input>```	  Defines an input control <br>
 ```<textarea>```	  Defines a multiline input control (text area) <br>
 ```<label>```	  Defines a label for an <input> element <br>
 ```<fieldset>```	  Groups related elements in a form <br>
 ```<legend>```	  Defines a caption for a <fieldset> element <br>
 ```<select>```	  Defines a drop-down list <br>
 ```<optgroup>```	  Defines a group of related options in a drop-down list <br>
 ```<option>```	  Defines an option in a drop-down list <br>
``` <button>	```  Defines a clickable button <br>
 ```<datalist>```	  Specifies a list of pre-defined options for input controls <br>
 ```<output>```	  Defines the result of a calculation <br>

HTML Input Types:-
*  Here are the different input types you can use in HTML: <br>

  ```<input type="button"> ``` <br>
 ``` <input type="checkbox">  ```<br>
  ```<input type="color">```  <br>
  ```<input type="date">```  <br>
  ```<input type="datetime-local">```  <br>
  ```<input type="email">```  <br>
  ```<input type="file">``` <br>
  ```<input type="hidden">``` <br>
  ```<input type="image">``` <br>
  ```<input type="month">``` <br>
  ```<input type="number">``` <br>
  ```<input type="password">``` <br>
  ```<input type="radio">``` <br>
  ```<input type="range">``` <br>
  ```<input type="search">``` <br>
  ```<input type="submit">```<br>
  ```<input type="tel">``` <br>
 ``` <input type="text">``` <br>
  ```<input type="time">``` <br>
 ``` <input type="url">``` <br>
  ```<input type="week">```   Tip: The default value of the type attribute is "text".

#

  Input Restrictions:-
  * Here is a list of some common input restrictions:- <br>

  Attribute :	    Description <br>
  checked :	   Specifies that an input field should be pre-selected when the page loads (for type="checkbox" or type="radio") <br>
  disabled :	   Specifies that an input field should be disabled <br>
  max	 :           Specifies the maximum value for an input field <br>
  maxlength :	   Specifies the maximum number of character for an input field <br>
  min :	           Specifies the minimum value for an input field <br>
  pattern :	   Specifies a regular expression to check the input value against <br>
  readonly :	   Specifies that an input field is read only (cannot be changed) <br>
  required :	   Specifies that an input field is required (must be filled out) <br>
  size	 :           Specifies the width (in characters) of an input field <br>
  step	 :           Specifies the legal number intervals for an input field <br>
  value	  :          Specifies the default value for an input field <br>



