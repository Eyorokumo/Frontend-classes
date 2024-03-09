# Frontend-classes
<!-- Day 1 of our main class -->
<!-- what is html
ans:An HTML tag is a piece of markup language used to indicate the beginning and end of an HTML element in an HTML document. As part of an HTML element, HTML tags help web browsers convert HTML documents into web pages
 -->
<!-- today we talked about the Doctype html >The HTML document type declaration, also known as DOCTYPE , is the first line of code required in every HTML or XHTML document. The DOCTYPE declaration is an instruction to the web browser about what version of HTML the page is written in. This ensures that the web page is parsed the same way by different web browsers. 
html is broken down into 3 parts 
tags: HTML tags are the keywords on a web page that define how your web browser must format and display your web page. Almost all tags contain two parts, an opening, and a closing tag.
##still on tags: <! DOCTYPE> HTML. ...
<html> Head. The Head Element is used to wrap around everything you want to include on the HTML page, that isn't the content the page will show to viewers. ...
<head></head> Title. ...
<title> Body. ...
<body> H1 to H6. ...
<h1></h1> <h2></h2> ...
<p></p> Line Break. ...
<br> Commenting our HTML code.
 ####we be building a resume while learn to fast aid us get it fast
 -->

 <!-- 
 
 In a tabular format: 

1. Give 5 difference between HTML  div tag, section tag and article. 

2. How does meta- UTF-8 work, Meta tags functions
  -->


  Sure, here's a tabular format outlining the differences between HTML `<div>`, `<section>`, and `<article>` tags:

| Feature                   | `<div>`                           | `<section>`                       | `<article>`                       |
|---------------------------|-----------------------------------|-----------------------------------|-----------------------------------|
| Semantic Meaning          | Generic container for content     | Represents a thematic grouping of content within a document | Represents an independent piece of content |
| Accessibility            | Does not provide any semantic meaning on its own | Provides a clearer structure for content and assists accessibility tools | Provides a clear delineation of standalone content |
| Nesting                   | Can contain any other HTML elements, including other `<div>` elements | Can contain any other HTML elements, including other `<section>` elements | Can contain any HTML elements, but typically represents standalone content |
| SEO Impact               | Minimal SEO impact due to lack of semantic meaning | Helps search engines understand the structure and relevance of content | Helps search engines identify and prioritize standalone content |
| Styling                     | Often used for styling purposes by applying CSS classes or IDs | Can be targeted for styling, but also carries semantic meaning which may affect styling | Similar to `<section>`, can be styled, but carries specific semantic meaning |

For your second question about meta tags:

**Meta-UTF-8:** 

The `<meta>` tag with the `charset` attribute is used to specify the character encoding for an HTML document. When you set `charset="UTF-8"`, it informs the browser that the document is encoded using the UTF-8 character encoding standard.

```html
<meta charset="UTF-8">
```

**Functions of Meta Tags:**

1. **Metadata:** Meta tags provide metadata about the HTML document. This metadata includes information such as the author of the document, keywords related to the content, the description of the document, and the character encoding used.

2. **SEO:** Meta tags play a crucial role in search engine optimization (SEO). For instance, the `<meta name="description" content="Your description here">` tag allows webmasters to provide a brief description of the webpage, which may be displayed in search engine results.

3. **Viewport Configuration:** The `<meta name="viewport">` tag is used to control the layout and scaling of a webpage on different devices. This is particularly important for ensuring that web pages are displayed properly on mobile devices.

4. **Social Media Sharing:** Meta tags like `<meta property="og:title" content="Title">` and `<meta property="og:description" content="Description">` are used to customize how content appears when shared on social media platforms like Facebook and Twitter.

5. **Browser Behavior Control:** Meta tags can influence the behavior of web browsers in various ways. For example, the `<meta http-equiv="refresh" content="30">` tag can be used to automatically refresh or redirect a webpage after a specified time interval.

Overall, meta tags provide valuable information to browsers, search engines, and other web services, helping to improve the visibility, accessibility, and functionality of web pages.


## Day 2 
# ordered list and unordered list
# void element self closing tag
# image tag
# video
# iframe