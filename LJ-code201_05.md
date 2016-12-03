# Learning Journal Code 201

## Day 5 - Dec 1, 2016
Today we opened with how our pair-programming went and what are the pros of that, which were greater than the cons. Examples of pro's: slowing down, fresh pair of eyes, collaborative environment,

Chapters Covered: Images, Colors, Text

Being able to see things from other's perspective is very important in regards to images, colors, & text, because it helps with familiarity and use of the page by people of all ages, and backgrounds (disabilities too).

All websites look the same (online article: novolume.co.uk)

Images (HTML):
choosing and storing images:
using images has to be factored in as a cost (i.e. stock images). You have to take in the storage of images and the uses. The memory usage in the "cloud",  user browser cache, the connection speed of user). The sizes of the images and how they affect the browser, load speed, etc.

<img> tag with 'height' & 'width' attributes
Aspect Ratio: when using the <img> tag keep in mind of aspect ratio (i.e Pic 1 = 200px x 200px & Pics 2 = 300px x 200 px, if you try to specify that Pic2 = <img

img alignment in text
 Rules! : Save img in right format, right size, & use correct resolution/size.
extensions:
 JPGs are great for photos & no transparency. GIFs are great for line art (fewer colors), animation, lean (small size / storage), & fast, but bad for photos. PNGs are great for photos + transparency

-Colors (CSS):
Foreground color:

Background color:

Understanding color:
RGB: R (0-255), G (0-255), B (0-255) - binary
Hex: 0-F; F =15 ... SO, 255 = FF

Opacity & HSL colors

Text (CSS): (next week)

CSS Layout:
learnlayout.com tutorial:

#main {
  max-width: 600px;
  margin: 0 auto;
}
<div id="main">
Using max-width instead of width in this situation will improve the browser's handling of small windows. This is important when making a site usable on mobile. Resize this page to check it out!

By the way, max-width is supported by all major browsers including IE7+ so you shouldn't be afraid of using it.

Git:

Working with partners and authorized collaborators, and creating branches.

Not using anymore : git push origin master. We're using: git checkout -b branchname. This means that master will only "live" in GitHub and the branch will "live" locally.

functions:

wow, this part was crazy... I learned a bunch of things, mainly that this is pure math. i.e. f(x) = a === x = a or in Js: function x (parameter) ===  parameter
