# Hello World 

## render with image api
- <img src="https://latex.codecogs.com/gif.latex?O_t=\text { Onset event at time bin } t " /> 
- <img src="https://latex.codecogs.com/gif.latex?s=\text { sensor reading }  " /> 
- <img src="https://latex.codecogs.com/gif.latex?P(s | O_t )=\text { Probability of a sensor reading value when sleep onset is observed at a time bin } t " />

## Section 1 

<img src="/tex/b33390ca01d4d5afbfbce126f37809ed.svg?invert_in_darkmode&sanitize=true" align=middle width=143.78651925pt height=27.77565449999998pt/>

- matrix
<p align="center"><img src="/tex/99e7ddb5861b7cccdf5bf6f4f1cf4371.svg?invert_in_darkmode&sanitize=true" align=middle width=215.89810605pt height=78.9048876pt/></p>


- alignment
<p align="center"><img src="/tex/7a70d5bb48eb2351993086cb7fd60e12.svg?invert_in_darkmode&sanitize=true" align=middle width=225.09456585pt height=40.821909149999996pt/></p>

- How fast are you updating this hahahha

# online template 
- https://upmath.me/

# Upmath: Math Online Editor
### _Create web articles and&nbsp;blog posts with&nbsp;equations and&nbsp;diagrams_

Upmath extremely simplifies this task by using Markdown and LaTeX. It converts the Markdown syntax extended with LaTeX equations support into HTML code you can publish anywhere on the web.

![Paper written in LaTeX](/i/latex.jpg)

## Markdown

Definition from [Wikipedia](https://en.wikipedia.org/wiki/Markdown):

> Markdown is a lightweight markup language with plain text formatting syntax designed so that it can be converted to HTML and many other formats using a tool by the same name. Markdown is often used to format readme files, for writing messages in online discussion forums, and to create rich text using a plain text editor.

The main idea of Markdown is to use a simple plain text markup. It's ~~hard~~ easy to __make__ **bold** _or_ *italic* text. Simple equations can be formatted with subscripts and superscripts: *E*~0~=*mc*^2^. I have added the LaTeX support: <p align="center"><img src="/tex/c52604ccab36c4e3eb7930900cb30180.svg?invert_in_darkmode&sanitize=true" align=middle width=69.5262612pt height=16.66852275pt/></p>.

Among Markdown features are:

* images (see above);
* links: [service main page](/ "link title");
* code: `untouched equation source is *E*~0~=*mc*^2^`;
* unordered lists--when a line starts with `+`, `-`, or `*`;
  1. sub-lists
  1. and ordered lists too;
* direct use <nobr>of HTML</nobr>&ndash;for <span style="color: red">anything else</span>. 

Also the editor supports typographic replacements: (c) (r) (tm) (p) +- !!!!!! ???? ,,  -- ---

## LaTeX

The editor converts LaTeX equations in double-dollars `<p align="center"><img src="/tex/3e3f9590cc16a8a5e6f75ab24b5ed425.svg?invert_in_darkmode&sanitize=true" align=middle width=13.698545849999999pt height=11.4155283pt/></p>ax^2+bx+c=0<p align="center"><img src="/tex/dc046be73aaba21fc38fff0dcf5dc5ec.svg?invert_in_darkmode&sanitize=true" align=middle width=645.4188229499999pt height=14.611878599999999pt/></p>\inline p={1\over q}<p align="center"><img src="/tex/bba514c74e7e0e3ab59b59a7ac917f24.svg?invert_in_darkmode&sanitize=true" align=middle width=426.48626624999997pt height=14.611878599999999pt/></p>x_{1,2} = {-b\pm\sqrt{b^2 - 4ac} \over 2a}.<p align="center"><img src="/tex/96e4129f9e06e17580e7475b7015024d.svg?invert_in_darkmode&sanitize=true" align=middle width=700.2745744499999pt height=35.251144499999995pt/></p>|\vec{A}|=\sqrt{A_x^2 + A_y^2 + A_z^2}.<p align="center"><img src="/tex/6663919f6b64779d20552f1c2a88436c.svg?invert_in_darkmode&sanitize=true" align=middle width=386.85032924999996pt height=45.1141581pt/></p>Q_\text{плавления}>0<p align="center"><img src="/tex/53ea022411f997f8e1f0a3def1b7d3be.svg?invert_in_darkmode&sanitize=true" align=middle width=327.7625769pt height=31.324200599999998pt/></p>T^{\mu\nu}=<p align="center"><img src="/tex/258412ef8d86edf0b3015b31c9103d69.svg?invert_in_darkmode&sanitize=true" align=middle width=158.61317835pt height=78.9048876pt/></p>,<p align="center"><img src="/tex/6b2bd7478649ef70c93f50495d112e9f.svg?invert_in_darkmode&sanitize=true" align=middle width=65.43399389999999pt height=14.611878599999999pt/></p>P_\omega={n_\omega\over 2}\hbar\omega\,{1+R\over 1-v^2}\int\limits_{-1}^{1}dx\,(x-v)|x-v|,<p align="center"><img src="/tex/e4118ccde57d78efb77a9bc745d8fb65.svg?invert_in_darkmode&sanitize=true" align=middle width=127.99126889999998pt height=14.611878599999999pt/></p>\usetikzlibrary{decorations.pathmorphing}
<p align="center"><img src="/tex/0a373f14ed5c2d44f028fe98daa68417.svg" align=middle width=835.5444075pt height=154.10958914999998pt/></p><p align="center"><img src="/tex/0d20f75d8e0e5aa4dbedd80a75a1123b.svg?invert_in_darkmode&sanitize=true" align=middle width=39.360855599999994pt height=14.611878599999999pt/></p><p align="center"><img src="/tex/b8fc28eecd5e0c98ec781e0f85bcf63f.svg?invert_in_darkmode&sanitize=true" align=middle width=700.6017381pt height=94.93150754999999pt/></p>$$

and [the rest of LaTeX features](https://en.wikibooks.org/wiki/LaTeX/Mathematics).

## About Upmath

It works in browsers, except equations rendered [on the server](//tex.s2cms.com/). The editor stores your text in the browser to prevent the loss of your work in case of software or hardware failures.

I have designed and developed this lightweight editor and the service for converting LaTeX equations into svg-pictures to make publishing math texts on the web easy. I consider client-side rendering, the rival technique implemented in [MathJax](https://www.mathjax.org/), to be too limited and resource-consuming, especially on mobile devices.

The source code is [published on Github](https://github.com/parpalak/upmath.me) under MIT license.

***

Now you can erase this instruction and start writing your own scientific post. If you want to see the instruction again, open the editor in a private tab, in a different browser or download and clear your post and refresh the page.

Have a nice day :)

[Roman Parpalak](https://written.ru/), web developer and UX expert.
