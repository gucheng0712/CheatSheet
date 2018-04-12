# Intro to Markdown
Wikipedia:
>Markdown is a lightweight markup language with plain text formatting syntax. It is designed so that it can be converted to HTML and many other formats using a tool by the same name. Markdown is often used to format readme files, for writing messages in online discussion forums, and to create rich text using a plain text editor. As the initial description of Markdown contained ambiguities and unanswered questions, many implementations and extensions of Markdown appeared over the years to answer these issues.

Markdown is a way to style text on the web. You control the display of the document; formaing words as bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown.

GitHub.com uses its own version of the Markdown syntax, GFM, that provides an additional set of useful features, many of which make it easier to work with content on GitHub.com.

## 1. How to Create a Header
```
# This is the largest size of a header
## This is the second largest size of a header ###### This is the sixth largest size of a header
```
Compare with HTML ```<h1>, <h2>...<h6>``` to represent the size of the header, the MarkDown syntax of create a header is just use `#`.



## 2. How to Create a List

In MarkDown, unordered lists use `*`.
```
* Unordered item
* Unordered item
* Unordered item
```
* Unordered item
* Unordered item
* Unordered item

Ordered lists use the digital number such as 1. 2. 3.

```
1. First item
2. Second item
3. Third item
```
1. First item
2. Second item
3. Third item

## 3. How to Make Inline markup styles (such as: bold, italics)

```
__Bold__ OR **bold**
*Italics* OR _italics_
```

__Bold__ OR **bold**  

*Italics* OR _italics_

## 4. How to create a Link

```
[GitHub](http://github.com)
```

[GitHub links here](http://github.com)

Your link __must__ start with `http://`

## 5. How to create an image
```
![Alt Text](url-of-image)
```
![Alt Text](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT8dGert7Q2Sl8RMOIoelQA_RtFxC0jrsevsgk24k7G3Hdg84zS)

## 6. Code and Syntax Highlighting

Surround it in 3 backticks on the front and back

    ```
        code...
    ```

``` javascript
var s = "JavaScript syntax highlighting";
alert(s);
```
 
``` python
s = "Python syntax highlighting"
print s
```
 
```
No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.
```

## 7. How to Make Inline markup styles (such as: bold, italics)
_italics_

**bold**

`code()`

## 8. How To Block Quote

As Tom sama said:
> I like watching anime and making anime games

## 9. How to make a Table

You can create tables by assembling a list of words and dividing them with hyphens - (for the first row), and then separating each column with a pipe | :

**Note**: This isn't a universal feature

## 10. How to Create a Horizontal Rule

```
---
```

OR

```
***
```

---
***


## 11. How to Create a Table
```
First Header | Second Header
------------ | -------------
Content cell 1 | Content cell 2
Content column 1 | Content column 2
```
First Header | Second Header
------------ | -------------
Content cell 1 | Content cell 2
Content column 1 | Content column 2




