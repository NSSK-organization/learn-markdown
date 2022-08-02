[previous](/lists_and_links.md)

# Bonus Tools

Congratulations on making it this far! You now know most of markdown. There are a couple of final things to do, and you should be on your way!

## Line breaks

If you want to include a random line break in your file, just type:

```
******
```

## Comments

Because markdown works so easily with HTML, you can use HTML tags as makeshift comments. This may not work everywhere, but it *does* work in GitHub and other places. This is the syntax for doing this:

```
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

```
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

## Exercises

1. Insert a line break below this section.
2. Comment out the following line:
This line should be commented out!

******

## There is a lot more to markdown!

There are a lot more flavors of markdown, and a lot more things you can do with it. Markdown is not something one spends years studying, but investing ten or twenty minutes into learning it can be very useful.
