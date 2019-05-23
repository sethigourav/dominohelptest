---
layout: default
 title: addcontent
permalink: /addcontent/

--- 

1.  Login to Github or create an account.
2.	Press the “Edit me” button on the page containing the content which is needed to be updated.
3.	There will be a section showing Raw, Blame, History, and a pencil icon button. Press the pencil icon to edit the page.
4.  This theme uses [Kramdown markdown](https://kramdown.gettalong.org/). Kramdown is similar to Github-flavored Markdown. 


## What is Markdown

Markdown is a lightweight markup language with plain text formatting syntax. It is a fast and easy way  to write content for the web . Markdown is a shorthand syntax for HTML.The syntax is readable in its syntactical form. It doesn’t take long to learn the Markdown syntax, and once you know how to use it, you can write using Markdown just about everywhere.  


### No Coding Required

 You need a basic knowledge of Markdown and Github. You don’t need to know how to code, use the command line, or install Git (the version control software GitHub is built on).

```
Tip: Open this guide in a separate browser window (or tab) so you can see it while you complete the steps in the tutorial.

```

## Create Headers
Headings can be created by prefacing the phrase with a hash mark **(#)** .  Place the same number of hash marks as the size of the header you want. For example, to create a heading level four (<h4>) use four hash marks (eg., #### Heading level). 

{% include image.html file="header.jpg" border=" " %}

---

The alternate syntax involves adding == characters on the line below the text for heading level 1 or -- characters for heading level 2. 


{% include image.html file="header2.jpg" border=" " %}



## Creating Paragraphs

Creating paragraphs using markdown approach, use a blank line to set apart one or more lines of the text. Never use space or tabs to make a paragraph. 


{% include image.html file="paragraph.jpg" border=" " %}



## Images
Instead of using Markdown or HTML syntax directly in your page for images, the syntax for images has been extracted out into an image include that allows you to pass the parameters you need. Include the image.html like this:

```
{% include image.html file="jekyll.png" url="http://dominohelp.com" alt="dominohelp" caption="" %}

```
**The output will appear as:**
{% include image.html file="jekyll.png" url="http://dominohelp.com" alt="dominohelp" caption="" %}


## Links 
Links can be created by enclosing the link text in the brackets and following it immediately with the URL in parenthesis. 

### Create an external link
```
My favorite community site is [Dominohelp.com](https://dominohelp.com).

```
**The output will appear as:**

My favorite community site is [Dominohelp.com](https://dominohelp.com).

*Adding a title for a link is optional. This appears as a tooltip whenever user hovers over the link. Enclose in the parenthesis after the URL for adding a title. 

```
My favorite search engine is [Dominohelp.com](https://dominohelp.com "The best community site").

```
**The output will appear as:**

My favorite search engine is [Dominohelp](https://dominohelp.com "The best community site").

### Linking to internal pages
When linking to internal pages, you can manually link to the pages like this:

```
[Get Started](http://dominohelp.com/index.html)

```
**The output will appear as:**

[Get Started](http://dominohelp.com/index.html)



<!-- ### Automated links
### Automated links to headings on pages  -->

## Bold and Italic Text

The content have strong importance or to be highlighted can be represented as bold or italic. Add emphasis to the text by making it either bold or italic. 

   * Add two asterisks or underscores before and after the word to make it bold. 
   * Furthermore, for emphasizing the middle word to make it bold, add two asterisks or underscores around the letters without any spacing. 

```
 **Writing in Markdown is not that hard!**

```

**The output will appear as:**
    
 **Writing in Markdown is not that hard!**

   * Add one asterisk or underscore before and after the word to italicize it. 

   * Furthermore, for emphasizing the middle word to italicize it, add one asterisk or underscore around the letter without any spacing.  

```
 _Writing in Markdown is not that hard!_

```

**The output will appear as:**
    
_Writing in Markdown is not that hard!_


## Block Quotes

Block Quotation is an art of supporting a quote, therefore it is used to define direct  and long quotations. 
For this, add a > in front of the paragraph. 

```
>Dorothy followed her through many of the beautiful rooms in her castle.

```

**The output will appear as:**
    
>Dorothy followed her through many of the beautiful rooms in her castle. 

### Nested Block Quotes

Also, block quotes can be nested. Add >> before the paragraph for nesting.

```
> Dorothy followed her through many of the beautiful rooms in her castle. 
>
>>The witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood. 

```

**The output will appear as:**

> Dorothy followed her through many of the beautiful rooms in her castle. 
>
>>The witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood. 



              
