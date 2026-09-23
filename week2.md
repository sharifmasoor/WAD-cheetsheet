Request Methods:
GET: 
Asking for a resource located at a specified URL.
POST:
Transmit data to the server using HTML form. Data transmitted through the header of the request.
PUT:
Overwrite command.Update version of resource is provided
DELETE:
Removal of a resource

Point to remember:
An API has no styling contet unlike a webpage and consists of structured/semi-structured data

Response Codes:
2xx: Successful
3xx: Redirection
4xx: Client side / request error
5xx: server side error

Fetching and rendering a webpage:
The experience of seeing a single web page is facilitated by the client’s browser, which requests the initial HTML page, then parses the returned HTML to find all the resources referenced from within it, like images, style sheets, and scripts.
The algorithms within browsers to download, parse, layout, fetch assets, and create the final interactive page for the user are commonly referred to collectively as the rendering of the page

Web Server Application Stacks:
OS: Windows, Linux
Webserver: Apache, nginx, IIS, 
Database: MySQLPostgreSQL, SQLite, SQL Server
Scripting: PHP, ASP.NET

#from here sharif ullah starte
# HTML/CSS Notes

## Markup
Markup = tags used to make HTML in browsers, which become HTML elements/methods.
Example: `<h1> WAD </h1>`

## XML
XML = Extensible Markup Language

**HTML Syntax:**
- Tag name (opening): `<h1>`
- Content: `BSCCS`
- Tag name (closing): `</h1>`

Example: `<p>BS Computer Science...</p>` → valid HTML

## XHTML Syntax
Self-closing / non-valid tag example:
```html
<email add="aba@gmail.com" />
<!-- or -->
<email add="aba@gmail.com"></email>
###Semantic Markup
- **HTML** – focus on structure
- **CSS** – Cascading Style Sheet
##Hyperlinks
Links are created using the <a> element.
a stands for anchor.
<a href="http://www.centralpark.com">Central Park</a>
href = "destination"
Text between tags = label/text
##Common Text-level Semantic Elements
<a> – Anchor, used for hyperlinks
<abbr> – Abbreviation
<br> – Line break
-`<cite>` – Citation (i.e., a reference to another work)
<code> – To display code
<em> – Emphasis
<mark> – Highlighted text for display
