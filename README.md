# md2epub

### [m3.md](https://github.com/tngyo/md2epub/blob/main/m3.md) is a sample Markdown Document that you can use as a **template** to generate an ePub book with the free pandoc terminal program. 

[Install pandoc](https://pandoc.org/installing.html) first.

Download and edit [m3.md](https://github.com/tngyo/md2epub/blob/main/m3.md) to your liking. Get your cover image ready i.e. 1600 x 2560px, and place it in the same folder as this markdown document.

Then type the following command to start coverting this markdown document to Epub like so:

`pandoc .\m3.md -o m3.epub --metadata title="Markdown To Epub V3" --toc --epub-cover-image=cover.jpg`

Note:
- Change the input markdown and output epub filenames, title, and cover image filenames to yours
- Keep the --toc parameter to automatically generate a Table Of Content based on your Headings
- Put all your images into the images folder accordingly
- If you separated out your chapters into different markdown files, then use the command like so in the beginning: `pandoc chapter1.md chapter2.md -o output.epub ...`

There are 3 ways to put up images as illustrated below:
1. cat1.jpg (only with markdown syntax)
2. cat2.jpg (html tag with center alignment and size control)
3. cat3.jpg (figure tag with caption and html tag for center alignment and size control)
Take your pick. 

m3.md also illustrates how to create a hyperlink to another part of the document i.e. Chapter 3

The font is changed at the last paragraph as an example.

<mark>This template uses the inline style for each element for now.</mark>

This is probably all you need to get started to get your Epub book out.

![Epub Preview 1](https://github.com/tngyo/md2epub/blob/main/images/preview1.jpg)


![Epub Preview 2](https://github.com/tngyo/md2epub/blob/main/images/preview2.jpg)

Note: The license is GNU GPL. It is the author's wish that you only use this for legal good purpose or at least nothing bad, not legal. Thank you.
