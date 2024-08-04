# 0x00. Advanced HTML
In this project, i learned how to use HTML tags to structure a web page. No CSS, no styling - Although, the final page of the project will look “ugly” which is normal, it’s for the learning purpose of this project.


# Learning Objectives 

Which guidelines to follow for HTML
How to create the skeleton of an HTML5 page
How to use semantic HTML tags to structure a web page
Which use cases to use div vs span
The semantic value’s of header, main, footer, article, nav, section, aside
How to use headings (and why it’s important to follow the hierarchical order)
How to make lists in HTML
The differences between medias (SVG, GIF, PNG, JPG)
How to structure data in a table
How to integrate a video in a webpage
How to integrate an audio file in a webpage
How to embed external content
How to correctly structure an HTML page

# TASK

0. Create your first webpage
Create your first HTML file 0-index.html with:

Add the doctype on the first line (without any comment)
After the doctype, open and close a html tag
Add the language tag, specify English for ISO language code and add the direction tag (ltr or rtl) on the html tag.
Open your file in your browser (the page should be blank)
W3C won’t pass - you can ignore it

1. Structure your webpage

Copy the content of 0-index.html into 1-index.html

Create the head and body sections

inside the html tag, create the head and body tags (empty) in this order
W3C won’t pass - you can ignore it

2. The head - meta charset, viewport, title, description, favicons

Copy the content of 1-index.html into 2-index.html



Meta charset:

add a meta tag inside the head:
add the charset attribute with the value utf-8
Viewport:

add a meta tag inside the head:
add an attribute name on the tag and specify that it is the meta viewport
add the key width with the value device-width
add the key initial-scale with the value 1.0
add the key viewport-fit with the value cover
Title:

add the title tag just after the meta viewport with value: Homepage - Techium
Description:

add a meta tag inside the head section
add an attribute name on the tag and specify that is the meta description
add another attribute called content
add the following description: Techium is a digital agency
Favicons:

download the image above to use as a favicon
Use the tool at https://realfavicongenerator.net/ to generate all the favicon formats
take the favicon.ico and favicon.png and place these at the root of your project directory, so that it is siblings with your [0-9]+-index.html files.
inside the head, create 2 link tags with these 3 attributes: rel, type, and href.
the first link tag:
rel: icon
type: image/x-icon
href: ./favicon.ico
the second link tag:
rel: icon
type: image/png
href: ./favicon.png


