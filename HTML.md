# HTML

## Class Notes

HTML stands for Hypertext Markup Language
index.html - standard primary/homepage - this needs to be name of main page
To publish webpage, github will be looking for index.html or README.md file
Used in conjunction with CSS to provide visual formatting
HTML is bones or foundation of a website
CSS is decoration of a website
JavaScript or JS is added functionality of a website
uses tags to establish structural components

- opening `<p>`
- closing `</p>`
- image `<img>`
- `<body>``</body>'
- `<header>``</header>'
- `<head>` - doesn't display on webpage, but encompasses metadata like title, link css, link js, sizing data etc.
- semantic - tags that indicate where text will go? `<div>' not semantic because doesn't tell you anything. Also tags that impact screen readers, convert to braille, etc.

## Chapter 18 - Process and Design

WHO is visiting your site and design with them in mind
WHY - motivations and goals
WHAT - information do they need to achieve goals quickly and effectively
HOW OFTEN - set a schedule

Site Maps - diagram of pages that will be used to structure site
Card Sorting - helps decide what info goes on each page
Wireframe - simple sketch of key info that goes on each page of site. Shows hierarchy of info and how much space it might require
Wireframe does not include color scheme, font choices, images etc.
Wireframes built in Photoshop, Illustration, InDesign
Wireframe tools: gomockingbird.com and lovelycharts.com

Visual hierarchy - help users focus on key messages using. Order in which eyes perceive what they see - by adding visual contrast

1. Size
2. Color
3. Style

Grouping together related content into blocks or chunks makes page look simpler
Use similar style for similar function

Grouping:

- Proximity - close together are related
- Closure - real or imaginary box formed aroudn elements due to proximity and alignment
- Continuance - in a line or curve
- White Space - big gap between unrelated items
- Color - background around similar items
- Borders - line around group

Navigation:

- Concise, clear, selective
- no more than 8 links in menu
- single descriptive words where possible
- primary - top or side of page
- secondary - under primary or side of page
- tertiary - bottom of page
- good navigation provides context - color contrast of where they are now
- interactive - appearance of link should change when users hover over it
- primary navigation should be consistent

To navigate back to the main page click [here](https://hmay1415.github.io/reading-notes/)

## Chapter 1: Structure

- brackets are called HTML elements - made up of open and close tags
- opening tags can carry attributes which tell us more about the content of - that element - require name and value
- attribute name - what kind of info you're supplying
- attribute value - information or setting for the attribute, placed in double quotes
- Use TextEdit to create a page on Mac

## Chapter 17: Layout

- `<header>` and `<footer>` used for main or for article within page
- `<article>` container for any section of page that can stand alone or be syndicated. Can be nested inside each other. Each section has it's own article element
- `<aside>' When inside article, contains info related to article but not essential to overall meaning ie glossary. When outside, contains content related to entire page ie links to other sections of the site, list of posts, etc.
- `<nav>` only for major nav blocks, not for nav at end of text block
- `<section>` group related content together and typically have own heading. May contain several distinct article elements that have common theme. Can also split up article into dif sections. Not for full page wrapper - use `<div>` for that
`<hgroup>` group together `<h1>` thru `<h6>` elements so stay in single heading
- `<figure>` - contains content that is referenced from main flow of article - not just images - article should make sense without figure and not be integral to flow of page
- `<figcaption>` text description of figure contained in figure element
- `<div>` - to group together related elements and can serve as wrapper
- `<a>` - turns full block into a link

## Chapter 8: Extra Markup

- DOCTYPE declaration tells browser which version of HTML page is using
- DOCTYPE can also help broswer render a page correctly
- for HTML5 - `<!DOCTYPE html>`
- `<!-- comment -->` to add comment to code that will not be visible in browser
- id attribute - `<p id="pullquote">` - used to identify that elemen from other elements on the page - value should start with letter or underscore. IMPORTANT: no two elements on same page have same value for id attributes. Used to identify when adding style elements with CSS
- id attribute = global attribute because used on any element
- class attribute - `<p class="important">` - identify several elements at a time or groups them
- if element belongs to multiple classes, separate with a space within quotes
- block elements - `<hl><p><ul>,<li>`- start on new line in broswer window
- inline elements - `<a><b><em><img>`
- `<div>` - one block-level box like all elements of header or comments
- applying div allows to create formats of blocks on pages. always add comments after div
- `<span>` - inline equivalent of div. helps control appearance of inline text with CSS
- `<iframe>` - window to another page. Elements:

1. src specifies URL
2. height in pixels
3. width in pixels
4. scrolling - not for HTML5?
5. frameborder - not for HTML5?
6. seamless - HTML5 only - where scrollbars not desired

- `<meta>`  - lives inside `<head>` - tells search engines about page. Does not have closing tag
- `<meta name="description, keywords, robots">` - description of page
- robots - noindex if not added to search engine, nofollow if only this page added to search engine but not other pages linked to
-`<meta http-equiv="author, pragma, expires"> - pragma prevents broswer from storing page locally, expires is when page should not longer be cached
- escape codes - used to bring up special characters in the final product of HTML

To navigate back to the main page click [here](https://hmay1415.github.io/reading-notes/)
