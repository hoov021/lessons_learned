# BLOC
MODULE: WDT Frontend & Programming Fundamentals
Section 2: Front End Formations
Checkpoint 1: HTML Document Structure
Vocabulary
Doctype-First thing in any HTML document. Doctype declares the type of HTML version the page is written in
HTML tags-Building blocs of web page. HTML tags define how your web browser must format and display the content
HTML uses pairs of opening and closing tags. I.e. <html> opening and </html> closing
Nested Elements: Just like excel, most recent tags need to be closed before closing previously opened tags
Vocabulary
Anchors tags<a>-often called hyperlinks or links are the primary way that users navigate the web.
Forms allow users to send data using a web request
Web requests are performed whenever you use your browser to request a pic, file, etc., and the server sends back a response
<img> tag declares an image in your HTML script. <img> tag does not require a closing tag. Tag attributes are used to store all info about the image
Src-attribute that declares the source of an image. The source can be a URL or a path to any file on your computer
Video Tags include details regarding height, width, and controls attributes.
Accessibility focuses on the ability for all people to interact with a site/system or application.
Primary CSS Selectors
Tag Selectors-<body>,<h1>. Tag selectors must match the tag selectors in a website to provide consitency
ID Selectors-declared using a hash symbol preceding a string of characters. The selector matches any HTML element that has an ID attribute with the same value as that selector. ID selector must match elements in a webpage but can be used for any HTML tag that has an ID. Only one element should have a specific ID
CSS Property-when using CSS for styling HTML document, you will use different CSS properties to tell the web browser what you want to do with the HTML element you selected. For instance, the background propert is used for the background color of an element
CSS Value of Property-each CSS property has a value associated with it. Most properties have multiple values you can use to change the appearance of HTML. For example, choosing color percentages, for a background vs a color name
Operating System (OS)-Software that manages computer hardware and software resources and provides common services for computer programs. Common operating systems are Windows, MacOS, and Linux
Web Browser-Application or program for viewing web content such as websites, games, images, and more. Common browsers are Chrome, Internet Explorer, Edge, Safari
Text Editor-A tool for creating plain text files. Common text editors are VS Code, Atom, Notepad++, and WebStorm
Terminal- A text based app where you input command to interact with other programs and perform tasks
The command line is a text interface for your computer-fully text-based
Command: directive to computer to perform a task
Directories: folders synonym for command line
Filesystem: directories and files are organized into filesystems. The first directory in a filesytem is the root directory. It kinda works like a family tree. Each parent directory can contain more child directories and files
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

