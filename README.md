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


