# AOL
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/Holminer/AOL/master?filepath=AOL1_3_example.ipynb)


# h1 Heading

## h2 Heading

### h3 Heading

#### h4 Heading

##### h5 Heading

###### h6 Heading




## Horizontal Rules
___

---

***


## Text Colors

{color:red}red{color} light {color:yellow}yellow{color} light {color:green} light {color}

{color:blue}__abc__{color}

#### {color:red}Hello{color}

See all available color names:
[available color names](https://www.w3schools.com/colors/colors_names.asp)


## Latex and AsciiMath Equations

Inline latex equation: `$E = mc^2$`
Inline AsciiMath equation: `@(1/2[1-(1/2)^n])/(1-(1/2))=s_n@`

Block Latex code:
```math
\oint_C x^3\, dx + 4y^2\, dy

c = \pm\sqrt{a^2 + b^2}
```

Block AsciiMath code:
```AsciiMath
oint_Cx^3 dx+4y^2 dy

(1/2[1-(1/2)^n])/(1-(1/2))=s_n

((1,2,3),(4,5,6),(7,8,9))

|x|= {(x , if x ge 0 text(,)),(-x , if x <0.):}

c = \pm\sqrt{a^2 + b^2}
```

Color your equations:
{color:red}`@((1,2,3),(4,5,6),(7,8,9))@`{color}







## Typographic Replacements

(c) (C) (r) (R) (tm) (TM) (p) (P) +-

dots.. dots... dots..... dots?..... dots!....

!!!!!! ???? ,,  -- ---

"Smartypants, double quotes" and 'single quotes'


## Emphasis

**This is bold text**

__This is bold text__

*This is italic text*

_This is italic text_

~~Strikethrough~~


## Blockquotes

> Blockquotes can also be nested...
>> ...by using additional greater-than signs right next to each other...
> > > ...or with spaces between arrows.


## Lists

Unordered

+ Create a list by starting a line with `+`, `-`, or `*`
+ Sub-lists are made by indenting 2 spaces:
  - Marker character change forces new list start:
    * Ac tristique libero volutpat at
    + Facilisis in pretium nisl aliquet
    - Nulla volutpat aliquam velit
+ Very easy!

Ordered

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa


1. You can use sequential numbers...
1. ...or keep all the numbers as `1.`

Start numbering with offset:

57. foo
1. bar





## Code

Inline `code`
Indented code

    // Some comments
    line 1 of code
    line 2 of code
    line 3 of code


Block code "fences"
```
Sample text here...
```

Syntax highlighting
``` javascript
var foo = function (bar) {
  return bar++;
};

console.log(foo(5));
```

``` bash
#!/bin/bash

# example of using arguments to a script
echo "My first name is $1"
echo "My surname is $2"
echo "Total number of arguments is $#" 
```

Highlight lines:
```js{1,2,4-5}
function foo() {
  return bar()
    .then(res => {
      return res.doSomething()
    })
}
```


## Tables

| Option | Description |
| ------ | :-----------: |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |

Right aligned columns

| Option | Description |
| ------:| -----------:|
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |

## Links

[link text](https://fbr.io)

[link with title](https://feedbackr.io "title text!")


## Images

![Minion](https://octodex.github.com/images/minion.png =200x)
![Stormtroopocat](https://octodex.github.com/images/stormtroopocat.jpg "The Stormtroopocat" =200x)

Set size of images:

![Minion](https://octodex.github.com/images/minion.png =150x)
![Minion](https://octodex.github.com/images/minion.png =x50)
![Minion](https://octodex.github.com/images/minion.png =50x30)












### Emojies
> Classic markup: 😉 😥 :laughing: :yum:
>
> Shortcuts (emoticons): 🙂 🙁 😎 😉

[available Emojies](https://github.com/markdown-it/markdown-it-emoji/blob/master/lib/data/light.json)

## Subscript / Superscript

- 19^th^
- H~2~O


## Footnotes

Footnote 1 link[^first].

Footnote 2 link[^second].

Inline footnote^[Text of inline footnote] definition.

Duplicated footnote reference[^second].

[^first]: Footnote **can have markup**

    and multiple paragraphs.

[^second]: Footnote text.


## Videos

@[youtube](sDD2wuuKvC0)

```
@[youtube](https://www.youtube.com/embed/ocwnns57cYQ)
@[youtube](https://youtu.be/ocwnns57cYQ)
@[youtube](Vhh_GeBPOhs)
```

```
@[vimeo](https://vimeo.com/266286146)
@[vimeo](266286146)
```

```
@[vine](https://vine.co/v/OdiFKizniE9)
@[vine](OdiFKizniE9)
```

```
@[prezi](qls54c5eelol)
@[prezi](https://prezi.com/qls54c5eelol/adventures-of-a-contract-developer/)
```
