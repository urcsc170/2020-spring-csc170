# Project 2: Formatting and Layout

*Due: Thursday, March 26, 2020*

In this assignment, you will work with the HTML document you created in Project 1 and style it using CSS. 
The result will be a **formatted document** that uses some version of a **columnar layout**, i.e. some side-by-side content

## The HTML Document

- Start with the final version of your HTML document you created for Project 1.  
  - Project 1 and Project 2 will be compared against each other to make sure the content is all there and similar.  Although the *content* from Project 1 has to be in Project 2, the HTML code *may* change in limited ways. Still though, the intent is to leave the Project 1 content as-is, as much as possible.
  - The content must be in one HTML file.  (Do not split your content into multiple HTML files!)
  - You can add classes to elements.  For example, you can change a `<p>` into `<p class="lead">` , or add a `<div>` as need ...whatever is necessary for styling.
  - IF NEED BE, you can shuffle content around in the HTML document – move blocks of content from one area to another, but only if you really have to.
- The **title** in the `<title>` tag (in the `<head>`) must be updated to say, "**Project 2 -** " followed by your topic, for example: `<title>Project 2 - Marc Andreessen</title>`

Note: although you know how to create *in-page* (jump) links, navigation is *not* required for Project 2

## The CSS document

- You must create an external CSS document and link it from your HTML document. 

- You may not use any inline or embedded CSS styles, or old fashioned HTML attributes that format content in any way.
- You must REMOVE the **border** attribute from the TABLE element you used in Project 1 and write styles for the table so it appears like a data table. Suggestion: in your CSS, target the elements, TABLE, TR, TH, and TD and write styles for them.
- You must clean up your CSS.  There must be no unused CSS statements (selectors or declarations) cluttering up your CSS document.

## Formatting

- The CSS must apply an ample amount of formatting to prove that you know how to style an HTML document using:
  - Fonts (typefaces, font sizes, font weights, and other typography settings)
  - The box model (margins, paddings and various borders)
  - Other embellishments – whatever you can find!  Pseudo-classes, background images and background colors.


- DO NOT USE the code provided from lab assignments as-is.  You can refer to them and learn from them (obviously) but do not use code from the labs in Project 2 without *extreme* customization. 

## Container

- Project 2 must use a “container” to constrain its content in some way and keep it "floated" in the center of the web browser window.  You don’t have to constrain *all* your content (although that’s okay if you do), but you must demonstrate good use of the trick.  
- The goal of a container is to *keep any paragraph* from extending any wider than say, 600px or so, which would be a readability problem.  
  - Note: you must *not* constrain all the content within 600px.  (That would be a waste of space.)  Just make sure that no <u>paragraph</u> of text is allowed to get any wider than 600px.

## Layout

Required: a **columnar layout** is any layout where some of the content is positioned side-by-side.  

- **No floats for layout:** a columnar layout is *more than* floated images where an image or figure is positioned left or right and text is allowed to flow around it. That’s just a float – which is okay to include – but it does not constitute a columnar layout.

- At some point in your web page, you must **break the normal document flow** and position content side-by-side to create a columnar layout. 

- You may *not* create a simple C-Clamp layout!  You must do better than that.

- You can use either of the approved following page layout techniques:
  - **CSS Flex** for one-dimensional positioning of elements in a side-by-side layout
  - **CSS Grid** for two-dimensional positioning of content within an established top/bottom and side-by-side layout

_Use of the same layout as demonstrated in the lab assignments (a basic C-Clamp) will lose points._

## Usability and Aesthetics

The webpage appearance must be usable (readable) without strain.  Your design (formatting and layout) must have a subjectively pleasant aesthetic. Although artistic capabilities are not being graded, the webpage must not be "sloppy".

- We will be very flexible when it comes to judging aesthetics. Only really, *really* ugly or sloppy designs will be penalized (unless you're being ironic, in which case you need to make it clear that you're being so.)

- Proper contrast between foreground and background must be maintained to make the webpage easy to read
- Fonts (type, size, style and color) must be appropriate for desktop viewing.
- Ample use of the box model (margin, padding,borders) to create white space must be used to separate areas of content into clearly delineated sections.
- Your layout must work on all normal desktop sizes
  - Part of the grading process will include shrinking and stretching the browser width to see what happens to your design on large and small desktop sizes.  
  - Your layout must “hold together” (make sense) at any width between about 960px and 1200px

### At small browser widths - as low as 960px wide...

- There must be NO horizontal scroll bars
- The content should still be usable and look normal
- Content must not "crash" into each other – e.g. images, figures or tables must not hang over edges or cause nearby text to become broken or hard to read.

### At larger browser widths - as high as 1200px wide...

- No line of text should be so long it becomes difficult to read, i.e. no line of text should stretch more than say, 600px wide

## Location

-  Your one-page web site must be installed on the class web server, within your directory where you’ll create a new folder that must be exactly this: **project2** ...all lower case, spelled exactly like that.
-  The name of the HTML document must be exactly this: **index.html** (not *start*.html this time)
-  The image(s) you use must be in a sub-directory of the **project2** folder named  **images**
-  The CSS documents you use must be in a sub-directory of the **project2** folder named **css**
-  Validate the HTML file (**http://validator.w3.org**)
-  Validate the CSS file (**https://jigsaw.w3.org/css-validator**)

## Report your work

To receive credit for this lab: in our CSC 170 Blackboard section, in the the "Projects" area, in the **Project 2** assignment, post a link to your webpage.