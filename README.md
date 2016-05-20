# *Markdown-Tips (for Atom)*
Lightening talk for Javascript 401

## What is Markdown?

Markdown looks like regular text with a few non-alphanumeric characters, like # (octothorp) or * (asterisk)

1. Plain-text formatting syntax;
2. Converts the plain text into structurally valid HTML (written in Perl).

## Why use it?

<h6>Cause HTML is <em>annoying</em> to read</h6>
<h6>and HTML is <i>easyi> to mess-up when writing<h6>

> “The overriding design goal for Markdown’s formatting syntax is to make it as readable as possible,”
- John Gruber, creator of Markdown.


## Headers:

# H1
## H2
### H3
#### H4
##### H5
###### H6

**OR**

H1
==
H2
--



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
  1. Another item
    * Unordered sub-list.
  1. Actual numbers don't matter, just that it's a number
    999. Ordered sub-list
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

| Header One     | Header Two     |
| :------------- | :------------- |
| Item One       | Item Two       |

## Block quotes:

> “Arrow functions need arrows”
  - Tyler, Javascript 401 Instructor.

## Emoji’s:

:bear:
:new:
:camel:

http://www.emoji-cheat-sheet.com/


## Resources Used

http://daringfireball.net/projects/markdown/
https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
http://dillinger.io/
http://markdownpad.com/
http://www.markdowntutorial.com/lesson/3/
