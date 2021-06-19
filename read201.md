# HTML-JavaSecipt reading notes.

## HTML
### Intoduction
**How People Access the Web?**

you can access the web via Browsers, Web Servers and Screen readers

**How Websites Are Created?**

the Websites we dealing with daily are created via many languages, like *HTML*, and codes, like *JavaSecipt*.

Before you learn how to create a webpage, you should know 
**how the web works**.

When you visit a website, the web server hosting that site could be anywhere in the world. In order for you to find the location of the web server, your browser will first connect to a `Domain Name System (DNS)` server.

1. first you connect to the internet via `internet service provider(ISP)`. And type a domain name or a web address you want to visit.

2. Then your computer connect to the domain name system. they tell your computer the IP address associated with the requested domain name. Every device connected to the web has a unique IP address; it is like the phone number for that computer.

3. The IP that the DNS server returns to your computer allows your browser to contact the `web server` that hosts the website you requested.

4. Finally, The web server then sends the
page you requested back to your
web browser.


### Structure
**How Pages Use Structure?**

like the stories in the newspaper, the page will divide to a heading line for the main topic, subheadings for some topics and paragraphs. there may be images and comics. the same is in web page , when a story viewed online, it may incloude videos and audio. 

via `HTML language` the Structure of Pages will be Described to the web browser to rendare it, so it could meaningful to the readers. 

HTML Uses Elements and tags to Describe the Structure of Pages
>**<html>**

>> **< head >**

>>> **< title>**This is the Title of the Page**< /title >**

>>**< /head >**

>>**< body >**

 >>>**< h1>**This is the Body of the Page**< /h1 >**

 >>>**< p >**Anything within the body of a web page is
 displayed in the main browser window.**< /p >**

>>**< /body >**

>**< /html >**

- `Opening Tag` **<p>** 
>The characters in the brackets
indicate the tag's purpose.
For example, in the tags above
the p stands for paragraph.
- `Closing Tag` **</p>**
- `Element` comprises *the opening
tag* and *the closing tag* and any
*content* that lies between them.
- `Attributes` **<p `id="paragraph01"`>** Tell Us
More About Elements.
- `<body>`Everything inside this element is
shown inside the main browser
window.
- `<head>`
Before the <body> element you
will often see a <head> element.
This contains information
about the page (rather than
information that is shown within
the main part of the browser
window that is highlighted in
blue on the opposite page).
You will usually find a <title>
element inside the <head>
element.
- `<title>`
The contents of the <title>
element are either shown in the
top of the browser, above where
you usually type in the URL of
the page you want to visit, or
on the tab for that page (if your
browser uses tabs to allow you
to view multiple pages at the
same time).

### Extra markup
**The Evolution of HTML**

Each new version was designed
to be an improvement on the
last (with new elements and
attributes added and older code
removed).
- HTML 4
- XHTML 1.0
- HTML5

HTML5 is which used commonly nowadays in web structure building.

**Elements & Attributes**
- `Doctype` Because there have been
several versions of HTML, each
web page should begin with a
DOCTYPE declaration to tell a
browser which version of HTML
the page is using
 
|      Doctype               |         HTML version       |
|----------------------------|-------------------------|
| <!DOCTYPE html> | `HTML5` |
| <!DOCTYPE html PUBLIC"-//W3C//DTD HTML 4.01Transitional//EN""http://www.w3.org/TR/html4/loose.dtd"> | `HTML4` |
| <!DOCTYPE html PUBLIC"-//W3C//DTD XHTML 1.0 Transitional//EN""http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd"> | `Transitional XHTML 1.0` |
| <!DOCTYPE html PUBLIC"-//W3C//DTD XHTML 1.0 Strict//EN""http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd"> | `Strict XHTML 1.0` |
| <?xml version="1.0" ?> | `XML Declaration` |

- `Comments in html` 

If you want to add a comment
to your code that will not be
visible in the user's browser, you
can add the text between these
characters:
>`<!-- comment goes here -->`

- `ID Attribute`

 It is used to uniquely identify that element from other elements on the page.
>`<p id="pullquote">`
- `Class Attribute` 

It is used to identify several elements as being different from the other elements on the page.
>`<p class="important">`
>>If you would like to indicate that
an element belongs to several
classes, you can separate class
names with a space
>>>`<p class="important 2nd">`
- `Block Elements`

Some elements will always
appear to start on a new line in
the browser window.
>`<h1>, <p>, <ul>, and <li>.`

- `Inline Elements`

Some elements will always
appear to continue on the
same line as their neighbouring
elements.
>`<a>, <b>, <em>, and <img>.`

- `Grouping Text & Elements In a Block`

The `<div>` element allows you to
group a set of elements together
in one block-level box.

In a browser, the contents of
the `<div>` element will start on
a new line, but other than this
it will make no difference to the
presentation of the page. 
- `Grouping Text & Elements Inline`

The `<span>` element acts like
an inline equivalent of the <div>
element. It is used to either:

1. Contain a section of text
where there is no other suitable
element to differentiate it from
its surrounding text
2. Contain a number of inline
elements
- `IFrames`

It is like a little window
that has been cut into your
page — and in that window you
can see another page.
>`<iframe>`
>>`width="450"`
>>`height="350"`
>>`src="http://maps.google.co.uk/maps?q=moma+new+york`
>>`&amp;output=embed">`
>`</iframe>`

- `Information AboutYour Pages`

The `<meta>` element lives
inside the <head> element and
contains information about that
web page.

>`<head>`
 >>`<title>Information About Your Pages</title>`
 >>`<meta name="description"`
 >>`content="An Essay on Installation Art" />`
 >>`<meta name="keywords"`
 >>`content="installation, art, opinion" />`
 >>`<meta name="robots"`
 >>`content="nofollow" />`
 >>`<meta http-equiv="author"`
 >>`content="Jon Duckett" />`
 >>`<meta http-equiv="pragma"`
 >>`content="no-cache" />`
 >>`<meta http-equiv="expires"`
 >>`content="Fri, 04 Apr 2014 23:59:59 GMT" />`

>`</head>`

### HTML5 layout.
**Some New HTML5 Layout Elements**
- `<header>` & `<footer>`
- Navigation
`<nav>`
- Articles
`<article>`
- Asides
`<aside>`
- Sections
`<section>`
- Heading Groups
`<hgroup>`
- Figures
`<figure>` or `<figcaption>`

There are more to search. the find more details about them and description to their function read *`Jon Duckett - HTML & CSS
Design and Build Websites - Chapter 17: HTML5 Layout, p428 `*

### Process & Design.
**understand who your target audience**

Every website should be designed for the
target audience—not just for yourself or the
site owner. It is therefore very important to
understand who your target audience is.

In order to understand and target the web audience, you should answer these questions:

1. Who is the Site For?
2. Why People Visit YOUR Website?
3. What Your Visitors are Trying to Achieve?
4. What Information Your Visitors Need?
5. How Often People Will Visit Your Site?

**Getting your message across using design**

There are some elements that must be taken into account when designing any website, and these are the most important:
- Site Maps
- WireFrames
- Visual hierarchy
- grouping and
- Similarity
- Designing Navigation

Read more about details in *`Jon Duckett - HTML & CSS
Design and Build Websites - Chapter 18: Process & Design, p452 `*

***
---
## JavaSecipt
**Intoduction**

**The A B C of programming**

**[Back to: Homepage](https://omarhumamah.github.io/reading-note/).**