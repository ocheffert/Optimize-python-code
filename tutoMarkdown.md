# Tuto  Markdown (.md files)

## Headers

Simply put '#' before a title, '##' before a subtitle, '###' before a third tier heading, .... until six tier '######'


## Text

* **bold** with ** before and after the word
* *italic* with * before and after the word
* link: you  can [link to Google!](https://google.com) by writing the text to link into [...] followed (without space) by the link into parenthesis (...) for example `[link to Google!](https://google.com)`
* Two feed line to render one
* Cross out a ~~word~~ by putting "~~" before and after the word without space

## List

### Numbered
1. first element
2. second one

Simply put '1.' before the first element, '2.' before the second, .... (with a space)

### Bullet points

Same with '*' or '-' before each element (with a space):
* first element
* second element

### List into list

- first element
- second element
  - first sub element
  - second one

simply ident the sub list with two spaces

## Images

Put an image following this rule: "![comment](link to image)"

## Code

For inline code, just put it wrapped by backticks `  (with µ on a AZERTY Belgium keyboard or 7 on a AZERTY French one).

This gives `print("Hello World")`

For a block of code, just indent it with 4 spaces:

    while(not done):
        i += 1

**but** github supports syntax highlighting and can be using by specifying the language by three backticks then the name of language (for ex. python), the block of code not necessarily indented and finally the ending three backticks:

```python
print("Hello World")
```


## Tasks list

- [x] first element
- [ ] second one

To do this, make a list with `*` or `-` followed by `[]` or `[x]` for an empty case or filled one (resp.).

## Quotes

Put `>` before the line to cite

> Unlimited power !
> -Emperor Palpatine

## Tables

first column | second column
-------------|--------------
cell1 | cell2
cell3 | cell4

Use `-` between first row and second one to create headers.

Use `|` between each column to separate them (this also has to cross the line of `-`).


## Separations
Simply put three dashes or asterisks:

---


## Table of contents with clickable links:

Make an ordered list (with sublists if needed) and put the name of the section into `[]` followed without space by `(#nameOfALabel)` with an unique lable for each entry. Link to the section you want to by putting `<a name="nameOfALabel"></a>`


### Table of contents
1. [Intro](#introduction)
2. [First part](#first)
    1. [First sub part](#firstSub)
3. [Last part](#last)

#### My introduction <a name="introduction"></a>

insert text

#### My first part <a name="first"></a>

insert text

##### My first sub part <a name="firstSub"></a>

insert text

#### My ast part <a name="last"></a>

insert text