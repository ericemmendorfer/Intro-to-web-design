# Introduction to Web Design and Computer Principles (F21) 


Taught by Sofy Yuditskaya
<details><summary>Course Description:</summary>
CSCI-UA 40 Introduction to Web Design and Computer Principles   

  There are two primary aspects to this course. The first is learning how to build websites and prepare the various elements that comprise them. The second is understanding concepts behind computers in general and the Web in particular.

Lecture Topics:  
<ul>
<li> Unix command line  </li>
<li> HTML</li>
<li> CSS  </li>
<li> Web graphics</li>
<li> Design and accessibility</li>
<li> Website layout</li>
<li> Responsive design</li>
<li> Interactivity with JavaScript</li>
<li> Web forms</li>
<li> Web audio and video</li>
<li> Web hosting and domain names</li>
</ul>
 
</details>

Homework and projects from Introduction to Web Design and Computer Principles course Fall 2021

### Unix
<details><summary>Details:</summary>
In this assignment you will create a basic Web page and publish it on a Unix server at i6.cims.nyu.edu/~netid.  

Use Sublime Text, or Atom to create a new plain text document. Type the HTML code below into the document. Then enter your name inside the <title> tag and a short self introduction inside the <p> tag.

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Your name goes here</title>
  </head>
  <body>
    <h1>Introduction to Web Design and Computer Principles</h1>
    <p>Your self introduction goes here</p>
    <ul>
      <li>HTML</li>
      <li>CSS</li>
      <li>Raster Graphics</li>
      <li>Vector Graphics</li>
      <li>Website Layout</li>
      <li>Responsive Design</li>
      <li>JavaScript</li>
      <li>Final Project</li>
    </ul>
  </body>
</html>

Save this file as “index.html” on your computer. View the page locally in a web browser (File > Open File) to make sure it looks as it should.  

This page will serve as a directory for all future assignments--ie you will link to all future assignments from this page.  


Publishing Your Web Page

Your webpage must be named index.html otherwise it will not be resolved by the browser.

Next, you will use an SFTP client to transfer your “index.html” file from your computer to the i6 server.

Cyberduck is a free and open-source SFTP client for Mac and Windows. Alternatives include Transmit and Fetch for Mac, WinSCP for Windows, and FileZilla for Mac, Windows, and Linux. Whatever program you use, be sure to connect to i6 using SFTP (as opposed to FTP).

Fill the SFTP login screen in as follows but with your own NetID and i6 password and connect using “SFTP.” After logging in, you can upload files to the web server and also download files from the server.

SFTP login window

Upload the index.html file from your computer to the public_html folder of your i6 account. Once you have uploaded the file, check to make sure your Web page is visible at: i6.cims.nyu.edu/~netid

  
</details>

### HTML
<details><summary>Details:</summary>
In this assignment, you will create a three-page website about yourself. The focus at this stage of the development process is on describing web page content with HTML.



Project Setup
Create a new directory (folder) on your computer called “html”. Place HTML and image files associated with your new website inside of this directory. The home page of your website should be named “index.html” (this another index.html folder, do not move or delete the first index.html folder you created last week in public_html). Other pages can be named as you like, but should reflect the content of the page. Remember that all file and directory names should be limited to letters, numbers, and dashes and be lowercase, with no spaces.
When your website is finished, you will upload the “html” directory, along with its contents, to your i6 account. Your new website will then be available at: i6.cims.nyu.edu/~netid/html/



Your Website
Three HTML web pages—about you—form the heart of the current assignment. Any combination of your background, interests, or experiences will do as long as it is autobiographical. You are to write these pages using a plain text editor such as Atom, or Sublime Text. The focus of this assignment is on describing web page content with HTML; refrain from styling the pages until the next assignment, CSS.
Here is a list of required elements you should include in these pages. 


There should be semantic text elements on each page, including but not limited to paragraph (<p>) and heading (<h1>, <h2>, etc.) text. 


The pages should link to each other with “relative” URLs.
Each page should also include at least one “absolute” URL linking to an external website. You should include at least one image (JPG, PNG, GIF, or SVG) on each page. (We’ve not
covered image editing yet but feel free to use images from your camera or smartphone as well as images downloaded from the Web.)
All img elements should include src, width, height, and alt attributes with appropriate values.
You should include an HTML list somewhere on one of your pages; this can be an ordered, unordered, or description list.
There should be semantic section elements on each page, including but not limited to <main>, <header>, and <footer>.
Pay close attention to your HTML tags and be sure to test your pages locally in an up-to-date web browser as you code them.
You can also check your HTML code using the W3C Markup Validation Service.

  
</details>

### CSS
<details><summary>Details:</summary>

In this assignment, you are to use CSS to style your assignments home page—from the Unix assignment—and original pages about you—from the HTML assignment. Using a plain text editor, write CSS code for the web pages you’ve created for the first two assignments.


Here is a list of required elements to include for the assignments home page.
Create an internal style sheet (within the <head> section of the document) with at least two different CSS rule sets(consisting of a selector and declaration block) for your assignments home page.
Your assignments home page should also include two or more different inline style rules—as style attributes of HTML elements.


Here is a list of required elements to include for the website about you.
Create one external style sheet (.css document) with at least six different CSS rule sets and link it to all of your original HTML pages, about you.
Your style rules should specify font family and font size for paragraph and heading text, and link states including link, visited, hover, and active.
You should specify a background image and/or background color for your pages and style some other aspect of the CSS box model, such as border, margin, or padding.
Create two or more class attributes somewhere in your HTML that are targeted and styled with CSS.
Create an id attribute somewhere in your HTML that is targeted and styled with CSS.
You should incorporate the CSS float or display property into your styles in some way and clear it where appropriate.


Beyond these requirements, feel free to include additional CSS to design your pages as you like. Remember to test your pages locally in the web browser as you proceed.
  
</details>

### Raster Graphics
<details><summary>Details:</summary>
Did you ever want to see yourself at the top of Mount Everest, walking on a rainbow, or hanging out with world leaders at a global summit? In this assignment, you can . . .

Your Image
Using https://www.photopea.com/, create a multilayered image that features you placed in an unlikely, unique, or impossible location. The final image should be 600 × 800 pixels (horizontal or vertical orientation). Your project should consist of at least five different layers.

A picture of yourself, decontextualized from the original image
A background image layer (different from the original image) that provides context for your location
A text layer with your name, a caption, or a title
An additional image layers that enhance the overall impression of your imaginary scene

Try to make the image as realistic as possible, even as you create a fictional scene. You might place yourself in the Arctic, climbing a national monument, walking on the moon, or standing beside a celebrity. Pay attention to things like the edges of objects, shadows, and color as well as to the proportions of your objects. Use a variety of tools to enhance your image—there are many available in www.photopea.com and you are encouraged to explore them.

Saving Your Work
Export the image as a JPEG or PNG file for the Web.

You should keep your PSD file after you’ve exported the images. Do not delete it as the Photoshop document will be part of your assignment submission.

Also, pay attention to the file size of your exported images, that they are suitable for the Web. The JPEG or PNG file should be less than 2 MB.

Publishing Your Image
Create a new directory on your i6 account called “rasterGraphics”. Within this directory, create a basic web page called “index.html” for your project and give the page a title.

Use the img element to display your JPEG or PNG on the page. The img element should include src, width, height, and alt attributes that correspond to the image. Add a short paragraph of text that describes the concept for your image.

Use the embed code from a website such as vimeo.com or soundcloud.com to embed audio or video that you created. Otherwise use the <video></video> or <audio></audio> tags.

Add CSS to give your page some basic styles. At minimum, this should include rule sets for the <img> element, paragraph text, and background of the page.

Publish the web page, along with your image (the JPEG or PNG, not the Photoshop document), and the audio or video file (if you are hosting your own) to the i6 server. Your project should be available at: i6.cims.nyu.edu/~netid/rasterGraphics/.

Update the code of your assignments directory to link to this new page.

Submitting Your Assignment
Submit the following via NYU Brightspace.
    The URL to your new web page that displays the image on i6
    A compressed archive containing your Photoshop project file, JPG or PNG, Audio or Video or just link to your Audio or Video in the HTML file, HTML and CSS
    The upload may take time; wait for confirmation before closing the browser window

Please note that you are required to submit files along with the URL in order to receive credit for your work.

  
</details>

### Vector Graphics
<details><summary>Details:</summary>

  
</details>

### Webiste Layout
<details><summary>Details:</summary>
On paper layout what pages and features you would like your final project's website to incorporate. 

  
</details>

### Responsive Design
<details><summary>Details:</summary>
Create a website that has three or more elements of responsive design. ie. An action such as clicking on a shape or text changes the color value.

  
</details>

### JavaScript
<details><summary>Details:</summary>

  
</details>

### Final Project
<details><summary>Details:</summary>

  
</details>

### Midterm
<details><summary>Details:</summary>
Multiple choice test reflecting topics learned in the first half of the semester.
  
</details>

### Final
<details><summary>Details:</summary>
Multiple choice test covering all topics covered in this course.
  
</details>
