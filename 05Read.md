Read05: CSS   

There are two display values: block and inline. 

A block-level element always starts on a new line and takes up the full width available. 

An inline element does not start on a new line and it only takes up as much width as necessary. 

CSS works w with HTML to determine mine how the content will display on live . 

 

A CSS rule contains two parts: a selector and a declaration. 

 

The selector indicates which element the rule applies to (with commas you can apply the rules to more than on selector) 

 

Deceleration: what stylings we will use, its split into two parts (a property and a value), and are separated by a colon, you can specify several properties in one declaration, each separated by a semi-colon. 

 

Using external CSS  

<link> element can be used in an HTML document to tell the browser where to find the CSS file used to style the page you will put this tag inside the head tag. 

The attribute for the link tag : 

Href :will define the path for the css file  

Type: This attribute specifies the type of document being linked to. The value should be text/css 

rel :This specifies the relationship between the HTML page and the file it is linked to. The value should be stylesheet when linking to a CSS file. 

 

Using external CSS 

CSS rules within an HTML page by placing them inside a <style> inside the head tag . 

We will use on attribute for now here which is the TYPE :text/css . 

 

 

When building a site with more than one page, you should use an external CSS style sheet. This: 

 ● Allows all pages to use the same style rules (rather than repeating them in each page). 

 ● Keeps the content separate from how the page looks.  

● Means you can change the styles used across all pages by altering just one file (rather than each individual page). 

 

Sometimes you might consider placing CSS rules in the same page as your HTML code. 

If you have one page . 

If you have some extra rules . 

 

To avoid any errors : 

Test the page on more than one website . 

Test it on more than one operating system.  

 

Colors /background attribute: 

The color name itself. 

Hex (pi These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash # sign. For example: #ee3e80). 

RGB values These express colors in terms of how much red. 

 

Every color on a computer screen is created by mixing amounts of red, green, and blue 

 

It is important to ensure that there is enough contrast between any text and the background color (otherwise people will not be able to read your content). 
CSS3 has introduced an extra value for RGB colors to indicate opacity. It is known as RGBA.

X CSS3 also allows you to specify colors as HSL values,with an optional opacity value. It is known as HSLA