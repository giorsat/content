# How to contribute to this project

This project was build in gatsby.js v2

To contribute, first pick the issue that you would like to resolve. Please don't resolve anything that its not an issue (event if you want to write a blog post or a lesson), if you would like to propose new enhancementes create the issue first to discuss it with the project mantainers and other members of the community.

Once you have the issue that you like to solve, add a comment letting anyone know that you are going to be working on it.

Fork this project and clone it to have it on your local envirnoment.

> This projects follows [the all-contributors specification](https://github.com/kentcdodds/all-contributors) and your contribution will be recognized in the main README.md of the project.


## Writing a Blog Post or Lesson in BreatheCode's Blog

### Where can I find the lessons that I want to edit ?

`http://docs.content.breatheco.de/lesson/`

### How do I edit the Headers ?

You type the size of your header, hit space and write your first headline 
 
 + \# = Header 1
 + \## = Header 2
 + \### = Header 3
 + And so on 

### How do I edit the parragraphs ?

+ You hit Enter twice after the paragraph ends and start your new parragraph in a new line 
+ For line breaks you can type space 2 times and enter right where you want the line to break. If that doesn't work, type `<b>` where you want the line to break 

### How do I emphazise ?

If you want to make your text **Bold** 

+ Put 2 asterisks (\*\*) before and after the text. EXAMPLE:`**hello**`
  
If you want to make it *Italics* 

+ Put 1 asterisk (\*) before and after the text. Example `*hello*`

If you want to make it ***Italics and Bold***

+ put 3 asterisks (\*\*\*) bfore and after the text. Example `***hello***`

### How do I escape symbols that have a meaning in markdown ?

+ use the backslash `\` before the symbol symbol
  
For example, if you want to use the number symbol `#` and avoid making it look as a header, type it like this `\#` and the same works for all symbols 

### How do I Blockquote my text ?

> If you want to blockquote your text like this 

Use the `>` symbol, press space and write your text 

### How do I make a list ?

+ For unordered lists like bulletpoints use `+` and `Space` to start listing your text
+ For ordered list like numerical you press for example `1.` and `Space` to start listing your text 

### How do I code block ?

If you want this html tag `<a href=https://www.google.com/><Google></a>` not to turn into a link and look like this  <a href=https://www.google.com/><Google></a>

Press 4 spaces from the begning of your line, type it and it will look like this:

    <a href=https://www.google.com/><Google></a>

### How do I make a horzontal line ?

for horizontal lines like the ones below the headers, use 3 asterisks in a row or more `***`.

It would look like this in your editor:

```
## How do i make a horzontal line ?
```
### How do I embed a link ?

This how you embed a[Link]() in the text : `[Google](www.google.com)`

### How do I insert images ?

To insert an image you use `![Description](image link)`

Type `!`, a short description of the image inside the squared quotes and the link inside the parenthesis.

### How do I make small code blocks like `this` ?

Yo Have to use this symbol `\`` before and after the text

so `this` would look like \`this\`

### How do I make tables ?




### Icons

[[info]]
|:link: for links of webistes with information  
dsfsdf

[[warning]]
| :point_up:
 to warn students about important details

[[demo]]
| :point_up: For live demos 

[[info]]
| :tv: for external videos

[[info]]
| :point_up: for Aditional info 


## Special Components

### Before and after

Example:

```html
<before-after 
    before="https://ucarecdn.com/3681f907-21eb-4e0e-828e-f7e2690e8942/" after="https://ucarecdn.com/d6648701-2af4-4e2d-890c-17ed222bb66c/" />
```

Image

<img src="https://path/to/image.png">

### info boxez

Info, Demo, Wrning, Error
