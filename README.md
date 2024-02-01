# Frontend
## Certainly! Here's a more organized format for the three commands in the Visual Studio Code editor and terminal to generate an SSH key for connecting GitHub and VSC locally:

### Generate an SSH key: ```ssh-keygen -t ecdsa -b 521```
### Navigate to the SSH directory: ``` cd .ssh ```
### Display the public key to copy and add to GitHub: ``` cat id_ecdsa.pub ```

# HTML Introduction

* HTML stands for Hyper Text Markup Language
* HTML is the standard markup language for creating Web pages
* HTML describes the structure of a Web page
* HTML consists of a series of elements
* HTML elements tell the browser how to display the content
* HTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc.


## Example Explained

* The ```<!DOCTYPE html>``` declaration defines that this document is an HTML5 document
* The ```<html>``` element is the root element of an HTML page
* The ```<head>``` element contains meta information about the HTML page
* The ```<title>``` element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab)
* The ```<body>``` element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
* The ```<h1>``` element defines a large heading
* The ```<p>``` element defines a paragraph


https://www.w3schools.com/html/html_intro.asp

## There are two ways to specify the URL in the src attribute:

### 1. Absolute URL - Links to an external image that is hosted on another website. Example: src="https://www.w3schools.com/images/img_girl.jpg".

* Notes: External images might be under copyright. If you do not get permission to use it, you may be in violation of copyright laws. In addition, you cannot control external images; it can suddenly be removed or changed.

### 2. Relative URL - Links to an image that is hosted within the website. Here, the URL does not include the domain name. If the URL begins without a slash, it will be relative to the current page. Example: src="img_girl.jpg". If the URL begins with a slash, it will be relative to the domain. Example: src="/images/img_girl.jpg".

* Tip: It is almost always best to use relative URLs. They will not break if you change domain.

## The lang Attribute
* You should always include the lang attribute inside the <html> tag, to declare the language of the Web page. This is meant to assist search engines and browsers.

### The following example specifies English as the language:

``` <!DOCTYPE html>``` 
```<html lang="en">``` 


* Country codes can also be added to the language code in the lang attribute. So, the first two characters define the language of the HTML page, and the last two characters define the country.

### The following example specifies English as the language and United States as the country:

```<!DOCTYPE html>``` 
```<html lang="en-US">```  
```<body>``` 
```...``` 
```</body>``` 
```</html>``` 

# I Suggest: Always Use Lowercase Attributes
* The HTML standard does not require lowercase attribute names.

* The title attribute (and all other attributes) can be written with uppercase or lowercase like title or TITLE.

* However, I recommends lowercase attributes in HTML, and demands lowercase attributes for stricter document types like XHTML.

## We Suggest: Always Quote Attribute Values
### The HTML standard does not require quotes around attribute values.

### However, W3C recommends quotes in HTML, and demands quotes for stricter document types like XHTML.

* Good:
```<a href="https://www.w3schools.com/html/">Visit our HTML tutorial</a>```
* Bad:
```<a href=https://www.w3schools.com/html/>Visit our HTML tutorial</a>```
### Sometimes you have to use quotes. This example will not display the title attribute correctly, because it contains a space:
## Example
```<p title=About W3Schools>```

### Chapter Summary
* All HTML elements can have attributes
* The href attribute of <a> specifies the URL of the page the link goes to
* The src attribute of <img> specifies the path to the image to be displayed
* The width and height attributes of <img> provide size information for images
* The alt attribute of <img> provides an alternate text for an image
* The style attribute is used to add styles to an element, such as color, font, size, and more
* The lang attribute of the <html> tag declares the language of the Web page
* The title attribute defines some extra information about an element


# Solution of The HTML ```<pre>``` Element
* The HTML ```<pre>``` element defines preformatted text.
* The text inside a ```<pre>``` element is displayed in a fixed-width font (usually Courier), and it preserves both spaces and line breaks:

# HTML Styles
* The HTML style attribute is used to add styles to an element, such as color, font, size, and more.
## The HTML Style Attribute
* Setting the style of an HTML element, can be done with the style attribute.
* The HTML style attribute has the following syntax:
```<tagname style="property:value;">```

### The property is a CSS property. The value is a CSS value.

## Chapter Summary
* Use the style attribute for styling HTML elements
* Use background-color for background color
* Use color for text colors
* Use font-family for text fonts
* Use font-size for text sizes
* Use text-align for text alignment
