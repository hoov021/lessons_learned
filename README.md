# BLOC
MODULE: WDT Frontend & Programming Fundamentals
Section 1: Frontend Programming Fundamentals-Intro
Goals to Achieve
Foundation to design Websites
Ability to design a fantasy football website
Understanding of the business world behind the website (servers, domain names, etc)
Foundation to design Web Apps
Creating mobile friendly apps
Costs of designing these apps
Ideas on how to build a tech platform
Transition into a developer role
Find a Remote Job
Questions for mentor
Best way to learn through Bloc
What is the script tag
What is metadata
Alternatives than dreamweaver-currently using notepad

Links:
Markdown Syntax Overview
https://guides.github.com/features/mastering-markdown/
GitLab Emojii Codes
https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md
CEO Letter
https://blog.bloc.io/tips-for-new-bloc-students/

Section 2: Front End Formations
Checkpoint 1: HTML Document Structure
Vocabulary
Doctype-First thing in any HTML document. Doctype declares the type of HTML version the page is written in
HTML tags-Building blocs of web page. HTML tags define how your web browser must format and display the content
HTML uses pairs of opening and closing tags. I.e. <html> opening and </html> closing
Nested Elements: Just like excel, most recent tags need to be closed before closing previously opened tags
Code Lines
<head> Tag- holds meta information without displaying it. It should be used immediately after the opening html tag and end directly before the opening body tag
<script> tag used to define a client-side script
<body> tag is where content will go
<div> holds additional contents with body tags.
<p> tag-stands for paragraph
<!-->tag is for comments that will not be displayed in a browser
Checkpoint 2: HTML Layout
Vocabulary
<Div>-Divided Areas. Every webpage is composed of these. Mock up web pages are immediately divided into separate sections
<section> creates a section of text
<Aside> creates sidebar text
<Class> affects target group tags
<Id> attributes to specific singular parts of a page
<h1> through <h6>
<header>-creates a logo or top navigation
<footer>creates content at the bottom of the screen
<main> represents the main content of a document
Checkpoint 3: Navigation
Vocabulary
Anchors tags<a>-often called hyperlinks or links are the primary way that users navigate the web.
hre3f= declares where browsers navigate to when the link is selected. The attribute could be links in the site, pictures, ect. 
Hyperlinks
Links
<ol> ordered list tags-A list that counts from 1
<ul> unordered list tags-A bulleted list
<li> used to nest the list
<nav> tag defines a set of navigation links. It is intended for major block of navigation links.
target=’_blank’
Anchors
Example: <a href=’http://www.bloc.io>Go to Bloc</a>
Within the first <a> is the link followed by the text that people would click on
URLs to other sites can be linked within <a>
Forcing Text to Open New Tabs
By using target=’blank’ it forces a new tab to open to the page.
Example: <a href='https://www.facebook.com' target='_blank'>Go to Facebook</a>
Jumping to Content
To jump to desired content, id the section and then use an anchor that uses the sections name
Example: <a href='#lastSection'>Go to the last section</a>. Links to a section like this <section id=’lastSection’>
Checkpoint 4: Basic HTML Tags (Quiz)
Completed
Checkpoint 5: Tables
Tables are used to display data
<table></table>
<thead>-Header cells are the most important part of every table. They specify a label of what the data represents
<tr>-table row tab
<th>-add header cells to row
Table Code Example
<table>
  <thead> <!-- table header declaration -->
    <tr> <!-- start table header row -->
      <th>Food</th> <!-- table header cell -->
      <th>Description</th> <!-- table header cell -->
      <th>Price</th> <!-- table header cell -->
    </tr> <!-- end table header row -->
  </thead>
</table>
<tr> is used before <th>
<tbody> is the table body tag
<td> is used for the cells in the table instead of <th>
Checkpoint 6: HTML Forms
Overview and Purpose
Forms allow users to send data using a web request
Web requests are performed whenever you use your browser to request a pic, file, etc., and the server sends back a response
HTML forms consists of one or more elements. The elements can be text fields, select menus, buttons, checkboxes, or radio buttons
Vocabulary
<form>-form tag tells a browser where the form starts and ends. It is a parent tag which contains child elements.
Example: <form action="https://bloc.io/users/add" method="post">
<form action=””- specfies where to send the form data when submitted
<form method=””> specifies the HTTP method used when sending the form data.
Options for method are GET or POST
<input> -element is what a user typically interacts with when using a form. The input tag is a self closing tag which means <input> instead of <input></input>. Input tags depend on the value of the attribute. Default if not attribute is assigned is text. The available types for inputs are as follows: button, checkbox, color, date, datetime-local, email, file, hidden, image, month, number, password, radio, rage, reset, search, submit, tel, text time, url, week
Examples: Name, Address, phone number, these are all inputs
<input type="text" id="" name="">

<label> element defines a label for an input element. For in the label tag <el for=””> should be equal to the id attribute of the related <input>
Example: <form action="form.php" method="post">
    <input type="email" id="emailInput">
    <label for="emailInput">Email</label>
</form>
<fieldset> element is used to group inputs and labels within a form. Each fieldset has a <legend> element that is optional
Example: <form action="form.php" method="post">
    <fieldset>
        <legend>Contact Form</legend>
        <input type="email" id="emailInput">
        <label for="emailInput">Email</label>
        <input type="submit" value="Submit">
    </fieldset>
</form>
<select>-element represents a form control that provides a menu of options. You use options to specify the select. Selected can be used to set a default
Example: <!-- The second value will be selected initially -->
<select name="type">
  <option value="Phone">Phone</option>
  <option value="Email" selected>Email</option>
  <option value="Text">Text</option>
</select>
<textarea>-represents a multi-line text input.
Example: <textarea cols="50" rows="4"></textarea>
cols=”” attributes to control the width of an element
rows=”” attributes to control the height of an element
Checkpoint 7: More HTML Tags
Quiz
Checkpoint 8: Media
Vocabulary
<img> tag declares an image in your HTML script. <img> tag does not require a closing tag. Tag attributes are used to store all info about the image
Src-attribute that declares the source of an image. The source can be a URL or a path to any file on your computer


Example: <img src="https://cdn1.bloc.io/assets/landing/logo-white-dfacaffb2b5dc8c2631fd141f0da410c.png">
Links to an image that you can add to a site
Alt-alt attribute provides an alternative information for an image if a user cannot view it-this could be do to an error in the src attribute or a slow connection. Providing an accurate description for an alt attribute will provide context. Including Alt also optimizes search engines. An Alt looks like the following:
<img src='./images/logo.png' alt='Logo for Bloc.io'>.
<video> tag-tag used for videos. <video> tags use open and closed tags </video>
<source> tags are placed within video tags to list out sources that can be used to play a video
<audio> tag works similar to a video tag and almost share the same attributes
Images from URLS
Sourcing Images on the web allows access to the image once on the website
Do Not Hot-Link-Hot-linking is setting an image tag’s source to an image that is already online, then publishing that site.
Instead, download picture and download it to your personal computer. This way you control the image’s source and server
Instead of Hot-Linking, you will need to host the image as well as your webpage
Linking Images from your computer
Linking an image is simply using the following formula
<img src='./images/logo.png'>
You include the file path as seen above. Unlike excel, you use / instead of \
Video Tags
Video Tags include details regarding height, width, and controls attributes.
Example: <video width="300" height="250" controls>
  <source src="blocMovie.mp4" type="video/mp4">
  <source src="blocMovie.ogg" type="video/ogg">
  Your browser does not currently support the video tag.
</video>
Height, width, and controls control the height, width, and player controls for a video
Multiple source tags tell a browser where to go if something doesn’t display. Including a line that says a browser does not support a video tag helps
Type attribute is used to tell the browser what type of file source it is
Audio Tags
Audio Tags use open and closing tags
Example: <audio controls>
  <source src="song.ogg" type="audio/ogg">
  <source src="song.mp3" type="audio/mpeg">
  Your browser does not support the audio tag.
</audio>
The formats for audio tags are really the only different to video tags
Checkpoint 9: Accessibility
Vocabulary
Accessibility focuses on the ability for all people to interact with a site/system or application.
Semantic HTML-use of HTML tags to convey meaning and purpose of content
Importance of Accessibility
Usability.gov claims that websites should be accessible by all potential users, including those with disabilities. The goal is to ensure users have good experiences and can easily access your information.
Search Engine Spiders/bots rely heavily on accessibility features to determine the nature and relevance of you content. This is the difference between page 1 of google and page 329 in google
Screen readers are software programs that allow users to interact with a site using auditory info. Siri, Google Assistant, and Amazon Alexa are screen reading features.
What makes sites inaccessible
Excessive use of non-sematic HTML tags, or improper use of semantic HTML tags
Low contrast between text and its background
<img> tags without alt attribute
Auto-playing audio or video
UI components that require users to use fine motor skills to accomplish tasks
What is Semantic HTML
Examples of semantic elements:Form, table, article
Examples of non-semantic elements: div, span
Its impossible to create a 100% semantic site but you should strive to be as descriptive as possible
Creating an Accessible site
Us tables for tabular data, not for layouts
Use tags to describe context: link to content- https://www.w3schools.com/html/html5_semantic_elements.asp
Use labels in forms
Understand colorblindness deficiencies-use strong contrasting colors
Avoid creating nested drop downs
This site provides more info- https://webaim.org/
Checkpoint 10: CSS Basics
Vocabulary
CSS-Cascading Style Sheets is used to describe how HTML elements display on a website. The key to understanding CSS is understanding selectors. Selectors allow you to retrieve specific HTML elements and apply styles to them so that you can make a beautiful website. CSS allows the control of text, style fonts, spacing between blocks of text, layout design, and more.
Inline Styling-when CSS is written inside of an HTML Tag using the [style] attribute. The below example shows the change of color and font of a paragraph. Use double quote “ when using style this way
Example: <p style="color: black; font-size: 1.1em;">I am a styled paragraph.</p>
Internal Styling-should be used when a single document has a unique style. You use a style tag in the HTML page. The below example would provide color change to the head tag and change the font size of paragraphs for the document
Example: <head>
    <style>
      h1 { color: black; }
      p { font-size: 1.1em; }
    </style>
</head>
External Styling-should be used when using a external style sheet to change the look of an entire website. Each page that uses the external style sheet must include a reference <link> element in its head tag. This is the most common styling type. The below example’s <link> tag links to an HTML style sheet. External Stylying Sheets must be saved with a .css extension. In the example, the type attribute is “text/css” as that is the file type 
Example: <head>
  <link rel="stylesheet" type="text/css" href="style.css">
</head>
<style> tag-used for internal styling in HTML pages.
[rel]-attribute that defines the relationship that the linked resource has to a document
“Stylesheet” means the referenced document is a style sheet.
:hover-pseudo class style  which hovers when a cursor is over a link
Example: a:hover{}
:active- pseudo class style to activate an element when clicked, like an element on a touchscreen device
Example: a:active{}
:visited-pseudo class style to style visisted links
Example: a:visited{}
:first-child: pseudo class style used to represent the first element among a group of sibling elements
Example: li:first-child{}
:last-child: pseudo class style used to select the last child of its parent element.
Example: li:last-child{}
:nth-child pseudo class style used to select the nth child of its parent element
Example: li:nth-child(2){}
pseudo -class selectors-keyword added to a selector that specifies a specific state of the selected element
CSS Overview:
Saves time-You can define each HTML element and apply it to as many pages as you want
Faster Page Loads-not writing individual HTML tag attributes means less code writing
Easier Maintenance-changing the stylesheet is the only thing needed to change a site. All stylesheet elements will update in all sheets
Multiple Device Compatibilities-altering style sheets allows optimization for various devices
Adding Style to HTML
Applying CSS can be accomplished in the following ways
Inline Styling-used for single elements on an html page
Internal Styling-used for single webpage on an html site
External Styling-used for an entire website by linking each page to a document
Creating an External Style Sheet
Using a text editor, create a new document and save the file with a .css extension. 
Example: filename.css
Using selectors, we add style elements to the document
body {
  color: black;
  font-size: 1.5em;
}
h1 {
  color: azure;
}
#iamanid {
  font-size: 1.5em;
}
.iamaclass {
  color: purple;
}
Next, link the style sheet to the HTML file
<!DOCTYPE html>
<html>
  <head>
    <title>Styling!</title>
    <link rel="stylesheet" type="text/css" href="style.css">
  </head>
  <body>
    <h1>External Style Sheets are Cool</h1>
    <p id="iamanid">I allow you to define styles for a whole website with an ID!</p>
    <p class="iamaclass">I'm applying a style with a class!</p>
  </body>
</html>
By linking the sheet to the file, all HTML document can use the styles from your external style sheet which results in a consistent look and feel.
Primary CSS Selectors
Tag Selectors-<body>,<h1>. Tag selectors must match the tag selectors in a website to provide consitency
ID Selectors-declared using a hash symbol preceding a string of characters. The selector matches any HTML element that has an ID attribute with the same value as that selector. ID selector must match elements in a webpage but can be used for any HTML tag that has an ID. Only one element should have a specific ID
Example: #iamanID
Class Selectors-declared with a dot preceding a string. It is used to match all elements on a page that have matching class names. We can reuse styling by having multiple elements with the same class name.
Example .iamaclass
Combinators
Descendant Combinator/descendent selector-let you combine two or more selectors to be more specific in your selection method. The below example allows a selector to affect all class elements that are within an ID element
#outerelement .innerelement {
  float: left;
Child combinator/child selector-similar to descendant combinator excet that it targets only immediate child elements. The below example shows the use of > to specify an immediate child which prevents the affecting of multiple elements between descendants above
#outerelement > .innerelement {
  float: left;
}
Example of innerelement in html text: <div id = "outerelement">
  <div class = "innerelement"></div>
</div>
Pseudo classes
See vocabulary
Checkpoint 11: CSS Properties and Values
Vocabulary
CSS Property-when using CSS for styling HTML document, you will use different CSS properties to tell the web browser what you want to do with the HTML element you selected. For instance, the background propert is used for the background color of an element
CSS Value of Property-each CSS property has a value associated with it. Most properties have multiple values you can use to change the appearance of HTML. For example, choosing color percentages, for a background vs a color name
Styling HTML
CSS property and values are used for HTML
Example for background element:    body {
      background: blue;
    }
The property is the background and the value is the color in the above example. Properties are followed by : and the value is followed by ;
There are 350 CSS3/CSS properties. CSS properties are googled instead of memorized
Creating a Save Button
The values we will use to create a save button are as follows: color, background, width (in pixels), text-align (right, left, center), padding (used for spacing), border, border radius, fonts-face
Padding: the spacing between letters and the outer edge. We use four values for padding (top, right, bottom, left). If all values are the same we can just use one value
Example:      padding: 20px; vs padding: 20px 20px 20px 20px;
Borders: Borders factor in Thickness, type of border, and the color of the border.
Example border: 2px solid rgb(0,0,0);
Border Radius: Used to add a border to a button, just a simple pixel amount
Example: border-radius: 20px;
Font-family: is used to provide the font type. You can use Google Fonts but need to hyperlink the source with an @import url)
Example: font-family: 'Indie Flower', cursive;
Example: Import (at top of screen) @import url('https://fonts.googleapis.com/css?family=Indie+Flower');
Checkpoint 12: Quiz
Checkpoint 13: Layout
Overview
Well designed web pages are multi-columned layouts 
There are three different ways to create layouts for a site
Three Ways to Lay Out a Site
Box model-most prevalent of all the layout techniques
Flexbox model-research on your own
https://www.w3.org/TR/css-flexbox-1/
http://flexboxfroggy.com/
developer.mozilla.org/en-..._layout/Flexbox
Grid Model-research on you own
https://www.w3.org/TR/css-grid-1/
developer.mozilla.org/en-...CSS_Grid_Layout
Creating a layout
The CSS property {float} is crucial for creating a layout
The {float} removes the default breaking property that most HTML elements have.
Code:<div id='column-1'>
  <p>This is column 1 content</p>
</div>

<div id='column-2'>
  <p>This is column 2 content</p>
</div>
Example to create float: #column-1 {
  float: left;
}
Result (after adding padding, background color, and width: 
This code allows text to “float” next to each other. If you add padding, background, and width, you can clearly see a separation of content.
Using the Web Inspector
Open files with chrome [right click on file, click open with, select chrome]
Click inspect at the bottom of the menu after right clicking on a page
You can also access Chrome’s developer tools
Link: https://developers.google.com/web/tools/chrome-devtools/
Checkpoint 14: CSS Frameworks
Three Popular CSS frameworks:
Bootstrap-developed by twitter. Good for mobile-first projects. Inludes documentation for common HTML and CSS components, jQuery plugins, and an advanced 12-column grid system. To get started, simply use the Bootstrap CDN, and include the stylesheet <link> in your <head> before all other stylesheets, and <script> tags near the end of your pages, right before the closing <body> tag. For example:
<!doctype html>
<html lang="en">
  <head>
    <title>Hello, world!</title>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta.2/css/bootstrap.min.css" integrity="sha384-PsH8R72JQ3SOdhVi3uxftmaW6Vc51MKb0q5P2rRUpPvrszuE4W1povHYgTpBfshb" crossorigin="anonymous">
  </head>
  <body>
    <h1>Hello, world!</h1>

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.3/umd/popper.min.js" integrity="sha384-vFJXuSJphROIrBnz7yo7oB41mKfc8JzQZiCq4NCceLEaO4IHwicKwpJf9c9IpFgh" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta.2/js/bootstrap.min.js" integrity="sha384-alpBpkh1PFOepccYVYDB4do5UnbKysX5WZXm3XxPqe5iKTfUKjNkCk9SaVuEZflJ" crossorigin="anonymous"></script>
  </body>
</html>
Foundation-open-source project that is used for developing websites, creating email templates, building mobile and web apps. Foundation allows developers to share responsive prototypes and create flexible navigation patterns,
Material Design-launched by google, it is a defacto design engine behind googles apps.
Vocabulary
Framework-the package consisting of files and folders of standardized code to support development and design. Frameworks help save development time so that developers don’t have to start from scratch but instead can reuse the provided code.
Front-end framework (or CSS framework) consists of files and folders of standardized code-HTML, CSS, and JS
Usually contain Typography style definitions for HTML elements, including icons, buttons, forms, and modal windows
Creation of standard CSS classes to style user interface components
CSS source code to create a grid that allows developers to position elements in a simple and versatile fashion
Solutions for browser incompatibility issues that might arise, so the site displays correctly in all browsers

Checkpoint 15: Quiz
Section 3: System Tools
Checkpoint 1: Basic System Setup
Vocabulary
Operating System (OS)-Software that manages computer hardware and software resources and provides common services for computer programs. Common operating systems are Windows, MacOS, and Linux
Web Browser-Application or program for viewing web content such as websites, games, images, and more. Common browsers are Chrome, Internet Explorer, Edge, Safari
Text Editor-A tool for creating plain text files. Common text editors are VS Code, Atom, Notepad++, and WebStorm
Terminal- A text based app where you input command to interact with other programs and perform tasks
Checkpoint 2: Command Line-through codeacademy
Command Line Overview
The command line is a text interface for your computer-fully text-based
You can navigate through files and folders on your computer
The advantage of using the command line is its power
Running programs, writing scripts to automate common tasks, combine simple commands to handle difficult talks
Vocabulary
Command: directive to computer to perform a task
Directories: folders synonym for command line
Filesystem: directories and files are organized into filesystems. The first directory in a filesytem is the root directory. It kinda works like a family tree. Each parent directory can contain more child directories and files
Options: used to modify the behavior of commands
Navigation Tools
$: Shell prompt-appears when a terminal is ready to take a command
ls (lower case L): shows the files and folders inside the current folder you are accessing. ls is an example of a command
Pwd:print working directory-outputs the name of the directory you are currently in, called the working directory
cd: stands for change directory
Argument: when a file directory or program is passed into a command
cd ..-command to navigate up one directory
mkdir: make directory-takes in a directory name as an argument and then creates a new directory in the current working directory
touch: command creates a new file inside a working directory. It takes the filename as an argument and then creates an empty file in the current working directory
Manipulation (used with -ls first)
-a: modifies the behavior of an ls command to also list files and directories starting with a dot(.). Used as ls -a. -a is an option. 
-l: list all contents of a directory in long format (used with -ls first)
-l shows access rights, number of hard links, username file owner, group that owns file, size of file, date and time the file was last modified, name of file or directory
-t: order files and directories by the time they were last modified (used with -ls first)
-alt uses -a, -l, -t all at once (used with -ls first)
cp: copies files or directories-example: cp frida.txt
cp * asterisk adds a select groups of files
Special characters are wildcards
Cp m*: selects all files in a directory starting with the letter m
Mv command move files
Rm: command deletes files
-r: modifies the behavior of the rm command. -r stands for recursive and is used to delete a directory and all of its child directories. There is not an undo for this action
Redirection
Redirection can direct the input and output of a command to and from other files and programs and chain commands together in a pipeline
Echo: accepts a string and returns the string
Standard Input: stdin is the info inputted into a terminal
Standard Output: stdout is the info outputted after a process is run
Stderr: standard error is an error message outputted by a failed process
>: command redirects the standard output to a file. > takes the standard output of the command on the left and redirects to the file on the right. < overwrites all original content all original
Cat: command outputs the contents of a file to the terminal
>> takes the standard output of the command on the left and adds it to the file on the right
< takes the standard input from the file on the right and inputs it into the program on the left
| is a pipe. It takes the standard output of the command on the left and pipes it as standard input to the command on the right
sort: takes the standard input and orders it alphabetically for the standard output. 
Uniq: stands for unique and filters out adjacent, duplicate lines in a file
Grep: stands for global regular expression print. It searches files for lines that match a pattern and returns the results. It is case sensitive
grep -i: enables the command to be case insensitive
grep- -R searches all files in a directory and output filenames and lines containing matched results. -R stands for recursive
grep -Rl searches all files in a directory and outputs only file names with matched results
sed: stands for stream editor. It accepts standard input and modifies it based on an expression before displaying it as output data. Similar to find and replace. Example: 's/word 1/word 2/':
s: stands for substitution
word 1: word to find  
word 2: word to replace
Environment
Environment: command settings and preferences make up the command line environment
nano: nano is a command line text editor. It works just like a desktop text editor like TextEdit or Notepad, except that it is accessible from the command line and only accepts keyboard input
ctrl O: saves a file
ctrl X: exits the nano program
ctrl G: Opens help menu
~: represents the user’s home directory
.: indicates a hidden file
source: makes the changes available right away in the session we are in
alias: alias command allows you to create keyboard shortcuts or aliases for commonly used commands. For example: alias pd=”pwd” creates pd as the shortcut for pwd
history: shows the history of command in the current session
export: makes the variable to be available to all child sessions initiated from the session you are in
User: USer is a variable to set the name of the computer’s owner
$ must always be used when returning a variable
PS1: variable that defines the makeup and style of the command prompt
We used PS1 to change the default command prompt from $ to >>
Home: variable is an environment variable that displays the path of the home directory
Path: Path is a variable that stores a list of directories separated by a colon
env: env command stands for environment and returns a list of environment variables for the current user
returns the variables including PATH, PWD, PS1, HOME
Checkpoint 3: Introduction to Git and GitHub
Concepts
Git-free and open-source code management and version control system
Local Repository-located on your computer and has all the files and their commit history
Remote Repository-is not located on your history; it is typically shared by the team you work on and is hosted on a server
Git Basic Commands
git init initializes a brand new Git repository and begins tracking an existing directory. It adds a hidden subfolder within the existing directory that houses the internal data structure required for version control.
git clone creates a local copy of a project that already exists remotely. The clone includes all the project’s files, history, and branches.
git add stages a change. Git tracks changes to a developer’s codebase, but it’s necessary to stage and take a snapshot of the changes to include them in the project’s history. This command performs staging, the first part of that two-step process. Any changes that are staged will become a part of the next snapshot and a part of the project’s history. Staging and committing separately gives developers complete control over the history of their project without changing how they code and work.
git commit saves the snapshot to the project history and completes the change-tracking process. In short, a commit functions like taking a photo. Anything that’s been staged with git add will become a part of the snapshot with git commit.
git status shows the status of changes as untracked, modified, or staged.
git branch shows the branches being worked on locally.
git merge merges lines of development together. This command is typically used to combine changes made on two distinct branches. For example, a developer would merge when they want to combine changes from a feature branch into the master branch for deployment.
git pull updates the local line of development with updates from its remote counterpart. Developers use this command if a teammate has made commits to a branch on a remote, and they would like to reflect those changes in their local environment.
git push updates the remote repository with any commits made locally to a branch.

