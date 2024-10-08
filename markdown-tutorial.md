# This is a main (first level) title
## This is a second level title
### This is a third level title
#### This is a fourth level title
##### This is a fifth level title

The following four words **are in bold typeface**, but the rest are not.

The following four words *are in italic typeface*, but the rest are not.

Sometimes, you want to cite someones' text. For that you use:
> text blockquote

To create ordered lists, you place a number and a point before the item:
1. Item one
2. Item two
3. Item three

And, if the list in not ordered (with bullets), then use a slash:
- Item one
- Item two
- Item three

Sometimes, it is good to highlight code, the code can be highlighted in line with the text as follows:

This sentence has `this portion of code` inline.

Or you can create blocks of code using ```:
```
def printMyName(name):
   a = name
   print(a)
```

Sometimes, you may want to include links to other documents. This can be down as the following:

[Markdown Guide](https://www.markdownguide.org/)

Likewise, you can include images, but you need to set carefully the relative paths of the image in relation to the place of the current markdown file.

![Logo do ISA](./images/logo_ISA.png)
(in this case the file is in the subfolder "images" of the folder that houses this .md file)

It is also possible to create tables in Markdowm. Simple use | to set the columns and --- below the first row with the column headings:
|ID| Column 1| Column 2| Column 3|
|--|---------|---------|---------|
|1 | item 1  | item 2  | item 3  |
|2 | item 4  | item 5  | item 6  |