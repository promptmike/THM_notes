# How Websites Work

## Task 1 - How websites work

You must know how websites work to understand the security implications of them.
You will learn how websites work with THM so that you can find vulnerabilities in websites.

A Server is a dedicated computer that handles your Requests for information.
Your Browser sends a Request to a Server to view a particular page and the Server Responds with data that your Browser uses to display the page.

The Front-End (Client-Side) of a website is handled by the browser, while the Back-End (Server-Side) is handled by the Server.
Your Browser sends Requests to Servers which process Back-End data and send the resulting Front-End data back to the Browser.

You make a Request to a Server and it responds with data your Browser can use to display information to you.
Servers process Back-End data and use it to respond to Requests from your Browser which then uses Front-End data to display information for you.

## Task 2 - HTML

Websites are mainly built from HTML for content and layout, CSS for styling and Javascript for complex interactive features.
Servers process Back-End data and send Front-End HTML, CSS and Javascript to your Browser to use for displaying pages to you.

HTML is the basic language web pages are written in, and it consists of tags telling your Browser how to handle content.
Servers process Back-End data and send Front-End HTML to your Browser to give it the page layout, with CSS and Javascript for additional data.

```
<!DOCTYPE html>
<html>
      <head>
            <title>Page Title</title>
      <head>
      <body>
            <h1>Example Heading<h1>
            <p>Example Paragraph..</p>
      </body>
</html>
```

__`<!DOCTYPE html>`__ tells the browser that the document is written in HTML5.
Servers process Back-End data and send Front-End data such as HTML documents to the Browser.

__`<html>`__ is the parent element for everything else on the page, so it must come first.
Servers process Back-End data and send Front-End data such as HTML documents to the Client for the Browser to display.

__`<head>`__ contains information about the page, such as the page title, language or stylesheets.
Servers process Back-End data and send Front-End data such as HTML documents to the Client with information on how to process it.

__`<body>`__ defines the document body, so only content inside the `<body>` element is actually displayed in the Browser.
Servers process Back-End data and send Front-End HTML documents to the Client, with content in the Body and additional information in the Head.

__`<h1>`__ is the main heading for the page.
Servers process Back-End data and send HTML documents to the Browser to process Client-Side, with Head information on how to process it.

__`<p>`__ defines a paragraph.
Servers process Back-End data and send Front-End HTML to the Client containing a Body of Content and a Head with additional information.

These are just a small selection of the most important HTML tags, but there are many others for defining different element types.
Servers process Back-End data Server-Side and send Front-End data to the Browser to process Client-Side, and HTML Head of additional information.

HTML elements can have Attributes to further define them, such as classes for styling or sources for image paths.
Servers process Back-End data and send Front-End HTML to the Browser with a Body of content tags that can have attributes for function or style.

HTML elements can have an ID Attribute as a unique identifier for CSS styling or for identifying the element in Javascript.
Servers process Back-End data and send Front-End HTML to the Browser with attributes for style, functions or unique identification.

You can view the HTML code of a website by right clicking in the Browser and selecting "View Page Source".
Servers process Back-End code and send Front-End code to the Browser which can be viewed in Page Source.

## Task 3 - JavaScript

Javascript (JS) provides additional interactivity by changing the page in response to events.
Servers process Back-End code and send Front-End code to the Browser, including HTML for content and Javascript for interactive features.

__`<script>`__ tags can contain Javascript inside the HTML document, or load it from a separate source file using the src attribute.
Browsers display the Body content of HTML documents, follow instructions in the Head and run Javascript either from the same file or from another.

__`:document.GetElementByID("demo").innerHTML = "Hack the Planet";`__ finds element __id = demo__ and changes its content to "Hack the Planet".
Browsers process Front-End code to display pages, including HTML for content and layout with Javascript to dynamically change content.

HTML elements can contain events as attributes, such as __onclick__ or __onhover__ that execute Javascript when the event occurs.
Browsers process Front-End HTML to provide content and layout while also executing JS either from inside the HTML document or a separate file.