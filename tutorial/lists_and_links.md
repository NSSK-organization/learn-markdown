[previous](./the_basics.md)

# Links and Lists

In this section, we talk about the different types of lists and links.

## Types of lists

There are two types of lists: **unordered** and **numbered**. Here's how to do both.

### Unordered lists

To create an unordered list, simply put several different words on newlines, with asterisks (\*) before each one. So the list below:

* Eggs
* Milk
* Spinach
* Bread
* Cheese

would look like *this* in markdown:

```markdown
* Eggs
* Milk
* Spinach
* Bread
* Cheese
```

### Numbered Lists

To create a numbered list, all you have to do is write the numbers in order from 1 (with a period in front of it. So the list below:

1. Line 1
2. Line 2
3. This is line 3
4. Line 4

would look like *this* in markdown:

```markdown
1. Line 1
2. Line 2
3. This is line 3
4. Line 4
```

## Links

There are two ways to create a link in markdown: a one-time link and a reusable link. If you are planning to link one page several times in a document, reusable links are better. If you are planning to link one page *once*, use a one-time link.

### One-time links

To create a one-time link, follow this syntax:

```markdown
lorem ipsum [text you want to highlight](linktoredirect.to)
```

For instance,

Learn more about markdown, click [here](https://anvilproject.org/guides/content/creating-links).

### Reusable link

>Note: These are sometimes called "reference links".

To create a reusable link, follow this syntax:

```markdown
lorem ipsum [text you want to highlight][link name].

[link name]: linktoredirect.to
```

For instance,

[Google][google] is a great search engine, though lacking in privacy. [It's home page][google] allows you to explore the internet with ease.

[google]: https://google.com

### Relative Links v.s. URLs

To create a relative link (if you are redirecting to a file on your computer), include the relative path. For instance,

[the previous chapter of the tutorial](/the_basics.md)

To create a URL, include the https:// link.

[GitHub](https://github.com)

## Images

To include images, follow this syntax:

```markdown
!(alt-text)[link to image]
```

For instance:

![the github logo](https://imgs.search.brave.com/Fm3h67kVyDkwjUTr3xk9h7-NT7j3adk4zAyerka2ikM/rs:fit:1200:1200:1/g:ce/aHR0cDovL3d3dy5w/bmdhbGwuY29tL3dw/LWNvbnRlbnQvdXBs/b2Fkcy8yMDE2LzA0/L0dpdGh1Yi1QTkct/SW1hZ2UucG5n)

## Exercises

1. Create an unordered list with the following names: Abigail, Betty, Cooper, Dylan, Eric, Frank.
2. Create a numbered list with the same names as exercise 1.
3. Make this text redirect to YouTube.
4. Make this text redirect to `../README.md`.
5. Add [this image](https://imgs.search.brave.com/Yyy8J98CVVE3JDmqsBtNkXMDV7EN2inma7DugwdUzd0/rs:fit:1200:1024:1/g:ce/aHR0cDovL2tpcmtz/dHJvYmVjay5naXRo/dWIuaW8vd2hhdGlz/bWFya2Rvd24uY29t/L2ltZy9tYXJrZG93/bi5wbmc) below.

[next](/bonus.md)
