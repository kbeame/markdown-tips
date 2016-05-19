# *Markdown-Tips*
Lightening talk for Javascript 401

## What is Markdown?

“Markdown is a text-to-HTML conversion tool for web writers. Markdown allows you to write using an easy-to-read, easy-to-write plain text format, then convert it to structurally valid XHTML (or HTML).

Mostly, Markdown is just regular text with a few !alphabetic characters thrown in, like # (octothorp) or *

1. a plain-text formatting syntax;
2. a software tool, written in Perl, that converts the plain text into structurally valid HTML.


## Why use it?

> “The overriding design goal for Markdown’s formatting syntax is to make it as readable as possible,”
  - John Gruber, creator of Markdown.

<!-- ## Difference between markdown and github markdown? -->



## Headers:

# H1
## H2
### H3
#### H4
##### H5
###### H6


## Emphasis: *Italics* or **Bold**

### *Italics*

*asterisks* or _underscores_.

### **Bold**

 **asterisks** or __underscores__.

### _**Both**_

**_asterisks_** and **_underscores_**.

### Strike Through

 ~~two tildes on either side~~


## Codeblocks:

##### Plain code-block

```
node server.js
```
**OR** 4 spaces or 2 tabs

    node server.js


##### Language Specific

``` javascript
var salmon = ['river', 'tiger', 'mooooooo'];

const bear = function(salmon) {
  return salmon.indexOf(1);
};
```
## Lists:
###### ordered
  1. First ordered list item
  2. Another item
    * Unordered sub-list.
  8. Actual numbers don't matter, just that it's a number
    8. Ordered sub-list
  4. And another item.
	 - unordered

###### un-ordered

* asterisks
- Or minuses
+ Or pluses

Task Lists

* [x] list syntax required
- [x] this is a complete item
+ [ ] this is an incomplete item


## Images:

![bear](http://kids.nationalgeographic.com/content/dam/kids/photos/animals/Mammals/Q-Z/sun-bear-tongue.jpg.adapt.945.1.jpg)

## Links:

[bear catches salmon](https://www.youtube.com/watch?v=1HFXNrrK5YE)


## Tables:

| Header One     | Header Two     |
| :------------- | :------------- |
| Item One       | Item Two       |

**OR** ATOM IS A BOSS, and will autocomplete a table


## Block quotes:

> “Arrow functions need arrows”
  - Tyler, Javascript 401 Instructor.

## Emoji’s:

:bear:
:new:
:camel:

http://www.emoji-cheat-sheet.com/
