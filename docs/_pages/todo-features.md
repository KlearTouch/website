---
title: "Strange Features of Dr Jekyll and Mr Markdown :)"
permalink: /todo-features/
layout: splash
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/unsplash-image-1.jpg
  actions:
    - label: "Download"
      url: "#"
  caption: "Photo credit: [**???**](#)"
excerpt: "Bacon ipsum dolor sit amet salami ham hock ham, hamburger corned beef short ribs kielbasa biltong t-bone drumstick tri-tip tail sirloin pork chop."
intro:
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'
feature_row:
  - image_path: assets/images/unsplash-gallery-image-1-th.jpg
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    image_caption: "Image courtesy of [???](#)"
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}



# Please, ignore. Just testing some features.

![image](/assets/images/favicon-128x128.png)



# H1 - Lorem ipsum (for Page Title) {#custom-id-for-this-h1}

Lorem ipsum dolor sit amet, *consectetur* adipisicing elit, sed do eiusmod
tempor incididunt ut **labore et dolore magna aliqua**. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. ***Duis aute irure dolor*** in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. ~~Excepteur sint occaecat~~ cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## H2

Lorem ipsum dolor sit amet, *consectetur* adipisicing elit, sed do eiusmod
tempor incididunt ut **labore et dolore magna aliqua**. Ut enim ad minim veniam,
quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
consequat. 

---

***Duis aute irure dolor*** in reprehenderit in voluptate velit esse
cillum dolore eu fugiat nulla pariatur. ~~Excepteur sint occaecat~~ cupidatat non
proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

### H3 https://www.markdownguide.org/basic-syntax/

A bulletted=unordered list:

- Syntax 1 (Most popular. Pick one and stick with it)
+ Syntax 2
* Syntax 3
  - An indented list item

An unordered list: (The number of spaces for sub-items doesn't matter, must many: >= 2, but must be consistent)

* item-1
  * sub-item-1
  * sub-item-2
- item-2
  - sub-item-3
  - sub-item-4
+ item-3
  + sub-item-5
  + sub-item-6

Starting Unordered List Items With Numbers **(Not needed for Jekyll)**

Don't do:

- 2021 is a year
- Second item

Do:

- 2021\ is a year
- Second item

An ordered list:

1. item-1
    1. sub-item-1
    2. sub-item-2
2. item-2
    1. sub-item-3
    2. sub-item-4
3. item-3

Actually, the numbers don't matter: (they can even be in the wrong order, and Markdown will ignore them)

1. First item
1. Second item
9. Third item
7. Fourth item
1. Fifth item

To add another element in a list while preserving the continuity of the list, indent the element four spaces or one tab, as shown in the following examples.

*   This is the first list item.
*   Here's the second list item.

    Paragraph below the second list item.

    > A blockquote as well.

    Code blocks are normally indented four spaces or one tab. When they’re in a list, indent them eight spaces or two tabs.

        <html>
          <head>
            <title>Test</title>
          </head>

    ![Our Logo - Alt](/assets/images/favicon-32x32.png "Our Logo - Title")

*   And here's the third list item.

**Task Lists**

- [x] Task 1
- [ ] Task 2
- [ ] Task 3

#### Header4

Use three or more hyphens (---) to create each column’s header, and use pipes (|) to separate each column. You can optionally add pipes on either end of the table.

Simpler to use a generator: <https://www.tablesgenerator.com/markdown_tables>

Table Header-1 | Table Header-2 | Table Header-3
:--- | :---: | ---:
Table Data-1 | Table Data-2 | Table Data-3
TD-4 | Td-5 | TD-6
Table Data-7 | Table Data-8 | Table Data-9

##### Header5

Image: ![Our Logo - Alt](/assets/images/favicon-32x32.png "Our Logo - Title")

Linked image: [![Our Logo - Alt](/assets/images/favicon-32x32.png "Our Logo - Title")](/#home)

You can do that but I would recommend you to use the component "image" and simply split your text.

**Emoji**

Make sure the page is in UTF-8 and copy paste from <https://emojipedia.org/>: 😂

Use Emoji Shortcodes like (rendered as **image**): :joy:. List: <https://gist.github.com/rxaviers/7360908>

###### Header6

Literal link: <https://kleartouch.com/> or <fake@example.com>

Note: https://github.com/ is **NOT** a link but this is: [GitHub Search](https://github.com/search "GitHub Search - Title").

Note: Encode any spaces with %20

**Reference-style Links**

First Part of the Link:

My sentence with a link to [kleartouch.com][1].

Second Part of the Link: (can be anywhere in this doc, but typically goes at endnotes or footnotes)

[1]: <https://kleartouch.com/> "KlearTouch Website"

**Footnotes**

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.

END

**Abbreviation** (hard to access on touch screens)

*[HTML]: Hyper Text Markup Language

The HTML specification is maintained by the W3C.

#### Quick Reference

##### Line Break Best Practices

First line with the HTML tag after.<br/>
And the next line.

**Alternative that I don't like** = Use two trailing spaces  
on the right  
to create linebreak tags  

**Not recommended** = First line with a backslash after.\
And the next line.

To create a horizontal rule, use three or more asterisks (***), dashes (---), or underscores (___) on a line by themselves.
For compatibility, put blank lines before and after horizontal rules.

---

***

___

End

##### Inline markup styles

- **bold text** OR __bold text__
- *italic text* OR _italic text_
- ***bold and italic text*** OR ___bold and italic text___
- ~~strikethrough text~~
- `code()`

NOTE: Underscore is not recommended in the middle of a word.<br/>
Better: ThisIs**Bold**ForSure, ThisIs*Italic*ForSure and ThisIs***BoldAndItalic***ForSure.
 
> Blockquote text
>> Nested Blockquote

> Blockquotes with Multiple Paragraphs
>
> ##### Second Paragraph as a header
>
> END

**Escaping Characters**

To display a literal character that would otherwise be used to format text in a Markdown document, add a backslash (\) in front of the character.

##### Syntax highlighting can be used by wrapping your code in a liquid tag

{{ "{% highlight javascript " }}%}  
/* Some pointless Javascript */
var rawr = ["r", "a", "w", "r"];
{{ "{% endhighlight " }}%}  

creates...

{% highlight javascript %}
/* Some pointless Javascript */
var rawr = ["r", "a", "w", "r"];
{% endhighlight %}

##### Code

To denote a word or phrase as code, enclose it in backticks (`).

At the command prompt, type `your command`.

Escaping Backticks
If the word or phrase you want to denote as code includes one or more backticks, you can escape it by enclosing the word or phrase in double backticks (``).

``Use `code` in your Markdown file.``

Code Blocks

To create code blocks: (with Syntax Highlighting)

```csharp
var value = await MyClass.MyMethod(123, "string");
```

```json
{
  "firstName": "John",
  "lastName": "Smith"
}
```

Or indent every line of the block by at least four spaces or one tab.

    <html>
      <head>
      </head>
    </html>

END of file