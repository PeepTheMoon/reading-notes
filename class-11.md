# HTML “Images” (pp.406-427)
Controlling sizes and images in CSS helps pages to lad more smoothly because HTML and CSS tell the browser how much space to leave for the images and allow it load the rest of the page without waiting for the images to download.

When you use consistenyl sized images across many pages in your site, use CSS to control the dimensions instead of HTML.

The float property allows you to move elements to the right or left of its containing block and have the text flow around it.  To do this with images, add a class to the HTML like "align-left" and called in the CSS with float.

To center an image, turn it into a block-level element (images are inline by default) using display: block;

background images will repeat by default to fill the entire page.  You can call a background image on a specific element.  background-repeat: repeat-x; will only repeat horizonatally, repeat-y repeats vertically.  no-repeat only shows the image once.

background-attachment property specifies whether the image stays in one position or moves at the usr scrolls the page.  (fixed or scroll).

When an image is not being repeated, you can specify where in the browser window the background image should be placed.  Shorthand for calling several background properties at once on p. 416.  You have to call each of the following in order:
1. back-ground color
2. background-image
3. background-repeat
4. background-attachment
5. background-position

image rollovers and sprites:
p. 417-418

you can make color gradients

you can make backgrounds high contrast, low contrast, or have a screen if you want to overlay text.  These will help make it easier to read.

## HTML “Practical Information” (476-492)
Search engine optimization, using analytics, and putting your site on the web.

SEO improves your website's visibility in search engines.  Keywords and phrases used are important.  Learning about your visitors, what they're looking at and where they're coming from is key information that you can get from Google Analytics for free.  

You need a domain name and web hosting to put your site on the web.  You use an FTP to transfer code and images from your computer to your hosting company.  Using platforms can save you from writing everything from scratch.  

### MDN Guide Video and audio API
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Video_and_audio_APIs

< video> and < audio> elements allow these to be embedded into a page.  
Native browser controls are different in every browser.  

The HTMLMediaElement API allows you to do this programmatically.  Add .play() or .pause() 

You can use icon fonts to display data-icons.  Helsp cut down on HTTP requests, great scalability, and can be used with properties for styling.

Good CSS examples for achieving certain styling goals!

#### Skim ch. 9 p. 201-206.  On flash, not used often anymore, but helpful to know about.
Can add animations, video and audio toy our website. Every file you make in Flash is referred to as Flash movies.
When you create a flash file (must be done in the Flash authoring environment) it has a .fla extension which needs to be changed to .swf to be used on a webpage. To use Flash, browsers need a plugin (an extra piece of software).  Not used frequently but it's best for animations.  It was replaced by JQuery which allows for animations using JavaScript.  