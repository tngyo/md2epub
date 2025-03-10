
# Chapter 1

This is a sample Markdown Document that you can use as a **template** to generate an ePub book with the free pandoc terminal program. 

[Install pandoc](https://pandoc.org/installing.html) first. Edit this document to your liking. Get your cover image ready and place it in the same folder as this markdown document. Then type the following command to start coverting this markdown document to Epub like so:

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

Not far below also illustrates how to create a hyperlink to another part of the document i.e. Chapter 3

The font is changed at the last paragraph as an example.

<mark>The style are defined at the end of this markdown so you can use as an example to modify (No separate stylesheet needed).</mark>

This is probably all you need to get started to get your Epub book out.

<hr></hr>

![Love](images/cat1.jpg)

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam facilisis dignissim pretium. Donec accumsan blandit condimentum. Quisque ut auctor dolor. Etiam tincidunt odio a mauris pulvinar ultrices. Nunc lobortis enim felis, vel efficitur odio facilisis vel. Etiam ut hendrerit ipsum. Praesent orci purus, ultricies convallis erat non, aliquam finibus augue.

[Jump to Chapter 3](#chapter-3)

Etiam a neque risus. Ut ex lorem, scelerisque sit amet dolor et, egestas vestibulum dolor. In imperdiet luctus dignissim. Curabitur bibendum imperdiet mollis. Etiam quis mollis metus. Nulla sit amet lorem eleifend, dictum metus sed, aliquam nibh. Nam ultricies metus id nunc ultricies maximus. Aliquam tempus tincidunt imperdiet. Nullam a velit quis tellus euismod pharetra eu eget nibh. Integer finibus viverra augue rutrum mattis. Aliquam at erat ut dolor dictum fermentum sit amet ac erat. Cras enim massa, pharetra in euismod non, laoreet eget lectus. Aliquam erat volutpat.

Ut dignissim quam volutpat pellentesque pharetra. Cras pellentesque auctor enim nec porttitor. Proin consectetur condimentum leo in ultrices. Vestibulum vulputate, massa a eleifend efficitur, nibh lorem fringilla enim, non dignissim neque est nec ex. Phasellus lacinia ligula orci, vitae consectetur lacus molestie non. Nunc ac imperdiet enim. Suspendisse sed rhoncus tortor. Sed iaculis augue id turpis ornare scelerisque. Nunc sit amet laoreet orci, non ultrices dui. Curabitur et accumsan leo, ut vehicula tellus. In ipsum erat, porttitor vel sollicitudin non, sagittis vulputate ex. Maecenas sit amet convallis metus, id pulvinar orci. Sed sit amet orci a ex fringilla finibus. Duis porta semper facilisis. Vivamus a mi nulla.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam facilisis dignissim pretium. Donec accumsan blandit condimentum. Quisque ut auctor dolor. Etiam tincidunt odio a mauris pulvinar ultrices. Nunc lobortis enim felis, vel efficitur odio facilisis vel. Etiam ut hendrerit ipsum. Praesent orci purus, ultricies convallis erat non, aliquam finibus augue.

Etiam a neque risus. Ut ex lorem, scelerisque sit amet dolor et, egestas vestibulum dolor. In imperdiet luctus dignissim. Curabitur bibendum imperdiet mollis. Etiam quis mollis metus. Nulla sit amet lorem eleifend, dictum metus sed, aliquam nibh. Nam ultricies metus id nunc ultricies maximus. Aliquam tempus tincidunt imperdiet. Nullam a velit quis tellus euismod pharetra eu eget nibh. Integer finibus viverra augue rutrum mattis. Aliquam at erat ut dolor dictum fermentum sit amet ac erat. Cras enim massa, pharetra in euismod non, laoreet eget lectus. Aliquam erat volutpat.

Ut dignissim quam volutpat pellentesque pharetra. Cras pellentesque auctor enim nec porttitor. Proin consectetur condimentum leo in ultrices. Vestibulum vulputate, massa a eleifend efficitur, nibh lorem fringilla enim, non dignissim neque est nec ex. Phasellus lacinia ligula orci, vitae consectetur lacus molestie non. Nunc ac imperdiet enim. Suspendisse sed rhoncus tortor. Sed iaculis augue id turpis ornare scelerisque. Nunc sit amet laoreet orci, non ultrices dui. Curabitur et accumsan leo, ut vehicula tellus. In ipsum erat, porttitor vel sollicitudin non, sagittis vulputate ex. Maecenas sit amet convallis metus, id pulvinar orci. Sed sit amet orci a ex fringilla finibus. Duis porta semper facilisis. Vivamus a mi nulla.


# Chapter 2

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam facilisis dignissim pretium. Donec accumsan blandit condimentum. Quisque ut auctor dolor. Etiam tincidunt odio a mauris pulvinar ultrices. Nunc lobortis enim felis, vel efficitur odio facilisis vel. Etiam ut hendrerit ipsum. Praesent orci purus, ultricies convallis erat non, aliquam finibus augue.

Etiam a neque risus. Ut ex lorem, scelerisque sit amet dolor et, egestas vestibulum dolor. In imperdiet luctus dignissim. Curabitur bibendum imperdiet mollis. Etiam quis mollis metus. Nulla sit amet lorem eleifend, dictum metus sed, aliquam nibh. Nam ultricies metus id nunc ultricies maximus. Aliquam tempus tincidunt imperdiet. Nullam a velit quis tellus euismod pharetra eu eget nibh. Integer finibus viverra augue rutrum mattis. Aliquam at erat ut dolor dictum fermentum sit amet ac erat. Cras enim massa, pharetra in euismod non, laoreet eget lectus. Aliquam erat volutpat.

<div style="text-align: center;"><img src="images/cat2.jpg" alt="Love again" width="200"></img></div>

Ut dignissim quam volutpat pellentesque pharetra. Cras pellentesque auctor enim nec porttitor. Proin consectetur condimentum leo in ultrices. Vestibulum vulputate, massa a eleifend efficitur, nibh lorem fringilla enim, non dignissim neque est nec ex. Phasellus lacinia ligula orci, vitae consectetur lacus molestie non. Nunc ac imperdiet enim. Suspendisse sed rhoncus tortor. Sed iaculis augue id turpis ornare scelerisque. Nunc sit amet laoreet orci, non ultrices dui. Curabitur et accumsan leo, ut vehicula tellus. In ipsum erat, porttitor vel sollicitudin non, sagittis vulputate ex. Maecenas sit amet convallis metus, id pulvinar orci. Sed sit amet orci a ex fringilla finibus. Duis porta semper facilisis. Vivamus a mi nulla.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam facilisis dignissim pretium. Donec accumsan blandit condimentum. Quisque ut auctor dolor. Etiam tincidunt odio a mauris pulvinar ultrices. Nunc lobortis enim felis, vel efficitur odio facilisis vel. Etiam ut hendrerit ipsum. Praesent orci purus, ultricies convallis erat non, aliquam finibus augue.

Etiam a neque risus. Ut ex lorem, scelerisque sit amet dolor et, egestas vestibulum dolor. In imperdiet luctus dignissim. Curabitur bibendum imperdiet mollis. Etiam quis mollis metus. Nulla sit amet lorem eleifend, dictum metus sed, aliquam nibh. Nam ultricies metus id nunc ultricies maximus. Aliquam tempus tincidunt imperdiet. Nullam a velit quis tellus euismod pharetra eu eget nibh. Integer finibus viverra augue rutrum mattis. Aliquam at erat ut dolor dictum fermentum sit amet ac erat. Cras enim massa, pharetra in euismod non, laoreet eget lectus. Aliquam erat volutpat.

Ut dignissim quam volutpat pellentesque pharetra. Cras pellentesque auctor enim nec porttitor. Proin consectetur condimentum leo in ultrices. Vestibulum vulputate, massa a eleifend efficitur, nibh lorem fringilla enim, non dignissim neque est nec ex. Phasellus lacinia ligula orci, vitae consectetur lacus molestie non. Nunc ac imperdiet enim. Suspendisse sed rhoncus tortor. Sed iaculis augue id turpis ornare scelerisque. Nunc sit amet laoreet orci, non ultrices dui. Curabitur et accumsan leo, ut vehicula tellus. In ipsum erat, porttitor vel sollicitudin non, sagittis vulputate ex. Maecenas sit amet convallis metus, id pulvinar orci. Sed sit amet orci a ex fringilla finibus. Duis porta semper facilisis. Vivamus a mi nulla.

# Chapter 3

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam facilisis dignissim pretium. Donec accumsan blandit condimentum. Quisque ut auctor dolor. Etiam tincidunt odio a mauris pulvinar ultrices. Nunc lobortis enim felis, vel efficitur odio facilisis vel. Etiam ut hendrerit ipsum. Praesent orci purus, ultricies convallis erat non, aliquam finibus augue.

<div style="text-align: center;">
<figure>
<img src='images/cat3.jpg' alt='Love Thrice' height='200'></img>
<figcaption>Love Thrice</figcaption>   
</figure>
</div>

Etiam a neque risus. Ut ex lorem, scelerisque sit amet dolor et, egestas vestibulum dolor. In imperdiet luctus dignissim. Curabitur bibendum imperdiet mollis. Etiam quis mollis metus. Nulla sit amet lorem eleifend, dictum metus sed, aliquam nibh. Nam ultricies metus id nunc ultricies maximus. Aliquam tempus tincidunt imperdiet. Nullam a velit quis tellus euismod pharetra eu eget nibh. Integer finibus viverra augue rutrum mattis. Aliquam at erat ut dolor dictum fermentum sit amet ac erat. Cras enim massa, pharetra in euismod non, laoreet eget lectus. Aliquam erat volutpat.

Ut dignissim quam volutpat pellentesque pharetra. Cras pellentesque auctor enim nec porttitor. Proin consectetur condimentum leo in ultrices. Vestibulum vulputate, massa a eleifend efficitur, nibh lorem fringilla enim, non dignissim neque est nec ex. Phasellus lacinia ligula orci, vitae consectetur lacus molestie non. Nunc ac imperdiet enim. Suspendisse sed rhoncus tortor. Sed iaculis augue id turpis ornare scelerisque. Nunc sit amet laoreet orci, non ultrices dui. Curabitur et accumsan leo, ut vehicula tellus. In ipsum erat, porttitor vel sollicitudin non, sagittis vulputate ex. Maecenas sit amet convallis metus, id pulvinar orci. Sed sit amet orci a ex fringilla finibus. Duis porta semper facilisis. Vivamus a mi nulla.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam facilisis dignissim pretium. Donec accumsan blandit condimentum. Quisque ut auctor dolor. Etiam tincidunt odio a mauris pulvinar ultrices. Nunc lobortis enim felis, vel efficitur odio facilisis vel. Etiam ut hendrerit ipsum. Praesent orci purus, ultricies convallis erat non, aliquam finibus augue.

Etiam a neque risus. Ut ex lorem, scelerisque sit amet dolor et, egestas vestibulum dolor. In imperdiet luctus dignissim. Curabitur bibendum imperdiet mollis. Etiam quis mollis metus. Nulla sit amet lorem eleifend, dictum metus sed, aliquam nibh. Nam ultricies metus id nunc ultricies maximus. Aliquam tempus tincidunt imperdiet. Nullam a velit quis tellus euismod pharetra eu eget nibh. Integer finibus viverra augue rutrum mattis. Aliquam at erat ut dolor dictum fermentum sit amet ac erat. Cras enim massa, pharetra in euismod non, laoreet eget lectus. Aliquam erat volutpat.

<span class="font2">Ut dignissim quam volutpat pellentesque pharetra. Cras pellentesque auctor enim nec porttitor. Proin consectetur condimentum leo in ultrices. Vestibulum vulputate, massa a eleifend efficitur, nibh lorem fringilla enim, non dignissim neque est nec ex. Phasellus lacinia ligula orci, vitae consectetur lacus molestie non. Nunc ac imperdiet enim. Suspendisse sed rhoncus tortor. Sed iaculis augue id turpis ornare scelerisque. Nunc sit amet laoreet orci, non ultrices dui. Curabitur et accumsan leo, ut vehicula tellus. In ipsum erat, porttitor vel sollicitudin non, sagittis vulputate ex. Maecenas sit amet convallis metus, id pulvinar orci. Sed sit amet orci a ex fringilla finibus. Duis porta semper facilisis. Vivamus a mi nulla.</span>

<style>

.font2{color: #B2BEB5; font-family: Montserrat;}

</style>

