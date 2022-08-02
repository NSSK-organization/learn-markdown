# The Basics

In this tutorial, we will learn the basics of markdown.

## Code

There are two forms of code: `in-line code` and code blocks. To create in-line code, surround the text you would like to code-ify with one (1) grave accent/backtick (\`). The backtick can be found on the same key as the tilde (~). 

To create a code block universally, indent the lines of code.

    this is code
    so is this

When creating a code block in customized markdown (GitHub markdown, for example), surround the code with three (3) backticks and a newline. 

```
This is a code block. It spans multiple lines.

Here is some dummy code:

#include <stdio.h>

int main() {
  return 0;
}
```

## Headers

Headers are simple in markdown. To create a header, simply put a hashtag (#) before the word.

```
# This text would be a header (if it weren't in a code block).
## This text would be an even smaller header!
#### This text would be normal-sized!
##### This text would be smaller than normal!
###### This text would be about the size of a footnote! 
```

## Bold and Italics

To create bold text, surround your text with **four asterisks** (two on each side). To make your text italic, surround it with two *asterisks* or _underscores_. Sometimes, you can surround your text with __four underscores__ to make it bold.

```
*This text would be italic!*
_So would this!_
**This text would be bold!**
__So would this! (Sometimes)__
```

You can make your text **bold** and *italic* ***at the same time!***

## Blockquotes

To create a blockquote, simply put a `>` sign on a newline and type. **DO NOT KEEP A SPACE AFTER THE `>`, or IT WILL NOT WORK!**

```
>This would be a blockquote!
```

>Note: This is what a blockquote looks like!

## Exercises

1. Put the below text inside a code block:
Hey! This text should not be outside a code block!
2. Turn the following words into inline code: turn me into inline code, please!
3. Uncomment the following code lines to see what the headers look like:
```
# This text would be a header (if it weren't in a code block).
## This text would be an even smaller header!
#### This text would be normal-sized!
##### This text would be smaller than normal!
###### This text would be about the size of a footnote! 
```
4. Do the following:
Make this text bold!
Make this text italic!
Make this text both bold and italic!
5. Turn the following line into a blockquote:
Why is this not a blockquote?

[next](/lists_and_links.md)
