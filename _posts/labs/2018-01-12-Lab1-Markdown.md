---
layout: page
subheadline: "Lab #1"
title: "Understanding Textual Structure with Markdown"
categories:
    - lab assignments
comments: false
show_meta: true
header:
  image_fullwidth: 4880254551_9a35151a0d_b-banner.jpg
  caption: Creative Commons licensed photograph, "Underwood," by Flickr user Canned Muffins
  caption_url: https://flic.kr/p/8rfzDR

---

## What is Markdown?

Markdown is a lightweight standard for writing in plain text while encoding the **structure of your document** for later representation in a format like Word, PDF, or HTML. If you have ever marked up a text using HTML tags, Markdown works quite similarly, but uses simple typographical symbols to encode text rather than longer HTML tags. One advantage to composing in Markdown is that you can then easily convert a single `.md` file into a range of other formats, giving you flexibility when you wish to publish your writing. For our class, writing in Markdown will help you reflect on the relationship of your texts' structure to the media of their presentation. You will compose your [fieldbook entries](http://s18tot.ryancordell.org/assignments/fieldbook/) in Markdown or [R Markdown](http://rmarkdown.rstudio.com/), the latter of which will allow you to embed code written in the R programming language directly into a Markdown document.

## Markdown References and Applications

Below I will describe the most common Markdown syntax, but for additional reference you can consult:

+ The [Markdown Wikipedia page](https://en.wikipedia.org/wiki/Markdown), which includes a very handy chart of the syntax.
+ John Gruber's [introduction to Markdown](https://daringfireball.net/projects/markdown/syntax). Gruber developed the standard and knows what he's talking about!
+ This [interactive Markdown tutorial](http://www.markdowntutorial.com/), which will teach you the syntax in a few minutes.
+ You can also download [the Markdown version of this page](https://www.dropbox.com/s/njkptabfreylyys/code1-markdown.md?dl=0) if you'd like to compare what you see in your browser with the marked up text that created it.

In short, in Markdown your text will not include any visible stylistic variations such as italics or bold text; Markdown is a *plain text* format. One advantage to this is that you can write valid Markdown in many, many editors, including the free text editors (such as TextEdit on the Mac or Wordpad on the PC) that come with most computers. You can also write in Markdown in my favorite writing application, [Scrivener](https://www.literatureandlatte.com/scrivener.php). There are many dedicated Markdown composition applications with additional features, such as syntax highlighting or the ability to preview what your documents. If you use a Mac, you might consider the free applications [Macdown](http://macdown.uranusjr.com/) or [Mou](http://25.io/mou/). For Windows you might try [Markdownpad](http://markdownpad.com/), or [Remarkable](https://remarkableapp.github.io/linux.html) for Linux. You can also compose online through platforms like [Hashify](http://hashify.me/IyBUaXRsZQ==). 

## Markdown Syntax

So, a few basics:

1. If you want your text to be italicized, then *enclose it in single asterisks*. 
    i.e. \*enclose it in single asterisks\*
2. If you want your texts to be bold, then **enclose it in double asterisks**. 
    i.e. \*\*enclose it in double asterisks\*\* 
3. To start a new paragraph, simply hit return twice (so there is a space in between paragraphs)
4. To create a hyperlink, enclose the [words you want linked in brackets and the link in parentheses following](http://s17tot.ryancordell.org/). 
    i.e. \[words you want linked in brackets and the link in parentheses following\]\(http://s17tot.ryancordell.org/\)

You can also create headlines of descending sizes, lists (numbered or bulleted),footnotes, embedded images, and more. See the reference materials above for details on these other elements. 

## Code Lab Assignment

Your assignment for this coding session is pretty straightforward: create a document encoded in markdown that encodes (at least):

+ Some italicized text
+ Some bold text
+ At least one link
+ At least one ordered (numbered) or unordered (bulleted) list
+ Headlines for different sections
+ I won't require it, but *extra kudos* if you can include an image and/or a footnote. 

If you have already drafted your Fieldbook entry for our lab at the MFA, you could mark it up for this assignment and kill two birds with one stone. 

## R Markdown

Another reason I am asking you to write in Markdown is that understanding these conventions will make it much easier for you to write about computer code. Once we start working with R in our coding sessions, we will use [R Markdown](http://rmarkdown.rstudio.com/) for writing up anything that includes R code. Essentially, R Markdown blends the markdown conventions you are learning today with a few customizations that let you embed snippets of code, as well as any outputs (e.g. graphs, maps) produced by that code into Markdown documents. This lets you weave together prose and code, so your readers can see the technical aspects of your work while reading about their interpretive significance. We will talk about this more in the near future (and you'll see some examples of R Markdown), but I want you to understand that we are learning Markdown both for its flexibility in representing the typical kinds of texts literature students write *and* for writing about code.

 