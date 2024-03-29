[previous](/lists_and_links.md)

# Bonus Tools

Congratulations on making it this far! You now know most of markdown. There are a couple of final things to do (if you want to), and you should be on your way!

>Note: Not everything here works with basic markdown.

## Line breaks

If you want to include a random line break in your file, just type:

```markdown
******
```

## Comments

Because markdown works so easily with HTML, you can use HTML tags as makeshift comments. This may not work everywhere, but it *does* work in GitHub and other places. This is the syntax for doing this:

```markdown
This is dummy text <this is a comment>
```

## Line breaks

Normally, markdown does not automatically create line breaks. So typing the following lines:

```
This 
is 
one 
line!
```
Will have the same output as:

```
This is one line!
```

To create a small newline, just keep two spaces after your line, like so:

```
This is one line__ <The underscores represent spaces here.>
This is another!
```

To create a big newline (which is used more often and in between paragraphs), just keep a blank line between paragraphs (this is what we have been doing this entire time).

```
This is one line!

Not only is this another new line, it's also another PARAGRAPH!
```

## Syntax Highlighting

On certain flavors of markdown, you can add syntax highlighting by putting the name of the language after the three tildes (/```).

```c++
#include <iostream>

int main() {
    cout << "This text should be highlighted like C++ sometimes!" << endl;
}
```

## Tables

To insert tables, simply use pipes (|). Put three or more hyphens (-) after the header to add cells. So this:

```markdown
| Header | Body |
| --- | --- |
| Italics| Formatting |
| Bold | Formatting |
```

will look like this:

| Header | Body |
| --- | --- |
| Italics| Formatting |
| Bold | Formatting |

Tables *can* be expanded.

## Footnotes

Creating a footnote is the same as creating a re-usable link, but with `^` before the footnote name. For instance,

```markdown
This is a footnote.[^1]

[^1]: A footnote can have multiple paragraphs.
    Indent the paragraphs that are to be included in the footnote.
```

Will look like this:

This is a footnote.[^1]

[^1]: A footnote can have multiple paragraphs.
    Indent the paragraphs that are to be included in the footnote.

## Strikethrough and Highlighting

To strike something through, follow this syntax:

```markdown
~~Words that need to be striked through~~ Words that are normal
```

To highlight something, follow this syntax:

```html
==Highlighted words== normal words, or, since some flavors of markdown don't support this, use the html tag liks this:
<mark> Highlighted words </mark> normal words
```

~~Words that need to be striked through~~ Words that are normal  
==Highlighted words== normal words (unfortunately, GitHub Flavored Markdown does not support highlighting)  
<mark> Highlighted words </mark> normal words

## Task Lists

If, for some reason, you want to include a *static* task list, you can follow this syntax:

```markdown
- [ ] This task is not done.
- [x] This task is!
- [ ] This task is not.
- [ ] neither is this.
```

which will look like this:

- [ ] This task is not done.
- [x] This task is!
- [ ] This task is not.
- [ ] neither is this.

## Exercises

1. Insert a line break below this section.
2. Comment out the following line:
This line should be commented out!
3. Add the following line breaks:  
This should be on one line.
This should be on another.
4. Add a table with the following heading: (food, type) and the following pairs: (eggs, dairy), (chicken, meat), (broccoli, vegetables).
5. Make the following code have the same syntax highlighting as C (programming language).

```
#include <stdio.h>

int main() {
    printf("This should look like C!\n");
}
```
6. Strike this text through.
7. Add a task list with three completed tasks and two uncompleted ones.

******

## There is a lot more to markdown!

There are a lot more flavors of markdown, and a lot more things you can do with it. Markdown is not something one spends years studying, but investing ten or twenty minutes into learning it can be very useful.
