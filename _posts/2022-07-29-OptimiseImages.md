---
layout: post
title: Optimising Images
categories: [Wordpress Admin]
author: Anna Browell
---
{% include image.html img="optimise_image_header.png" style="wide" lightbox="false" alt="Alt for image" caption="Optimising Images" %}


## Description

The performance of you website generally refers to how quick your website loads for end users. Because your site is media rich the page load speed can be negatively impacted when images are used on your site that have not been optimised for web.

You can see if the image is suitable for web by checking the following image details. The files size, the image dimensions in pixels and the file format.

## File sizes

You should try to keep images that are used in the page content below 100kb, this is more difficult when using full width images such as headers or form backgrounds and in this case keep you should avoid images over 300kb. To reduce your image file size you may need to reduce the dimensions of the image or increase the compression.

There are useful tools online for processing images for web.

https://bulkresizephotos.com/en


## Image Dimensions

Internet browsers are unable to render images in a higher quality than 72dpi, however many cameras and photo files store images at 300dpi, when you use these images on your website the file size can be four times the size that is needed to display the same image at the right dimensions.

You can check each of your image dimensions when you select an image in your Media Library on your website. The larger the device screen the larger the dimensions need to be, but desktop websites are not usually rendered larger than 1600 pixels for the entire width of the screen. To make sure that your images are not oversized we recommend that you keep all of your banner images below 1600px.

Below we have included a chart of best practices for image dimensions for common components.


|Component|Apx. Dimension pixels|
|-------|-------|
|Hero Image|1600x800|
|Lead form BG|1600x800|
|CTA BG|1600x800|
|Blogs|800x500|
|Cards|500x300|
|Teachers|500x400|
|Testimonials|500x400|
|Menu Thumbnails|160x100|


## File type

While browsers can display many image formats, Wordpress VIP has an additional image compression option that has been activated for JPG/JPEG images. When you upload JPG images on your site Wordpress VIP will deliver the images as WEBP this is a next generation image compression that will further optimise your page load speed.




