# IncludeHTML

A simple JavaScript program that can include HTML files into other HTML files. The most useful case for this is nav menus and footers, or any other HTML sections which are displayed on several different pages. This program makes it so that you only have to update one file, and the changes are made to all the pages which are displaying the file.

<a href="https://mdgiii.github.io/includeHTML/">Demo</a>

## Installation Guide

1. `git clone https://github.com/mdgiii/includeHTML.git`

2. Move the `includeHTML.js` file to the root of your website/web app.

3. Place `<script src="includeHTML.js"></script>` at the bottom of the head tag on the pages you wish to include files to.

3. Define where and what you want to be included by placing `<div include-html="sample.html"></div>` anywhere within the body tag of the pages you wish to include files to. **IMPORTANT** Make sure to replace "smaple" with the name of the HTML file you wish to be included.

4. Don't forget to call the function! Copy `<script>includeHTML();</script>` to the bottom of the body tag.
