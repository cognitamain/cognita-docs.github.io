---
layout: post
title: CTA Menu Bar Settings
categories: [Wordpress Admin]
author: Himani
---

{% include image.html img="cta_bar.png" style="wide" lightbox="false" alt="Alt for image" caption="cta_bar" %}


## Description

From Nextgen global options to control show hide of CTA menu bar in page and post.
{% include image.html img="cta_vc_line_shortcode.png" style="wide" lightbox="false" alt="Alt for image" caption="cta_vc_line_shortcode" %}




## Visual Content Components

- After login to CMS go to Visual Composer Content Item.
- Create a new CTA header line or search for an existing one
   {% include image.html img="paste_cta_bar_shortcode.png" style="wide" lightbox="false" alt="Alt for image" caption="paste_cta_bar_shortcode" %}
- Copy the vc_content id/shortcode and use in Nextgen options.

## Use Of vc_content id In Next-Gen Global Options

- Go to Next-Gen options in the left-hand menu
   {% include image.html img="cta_next_gen_settings_icon.png" style="wide" lightbox="false" alt="Alt for image" caption="cta_next_gen_settings_icon" %}
- See "CTA bar shortcodes" in the Definitions tab
- Paste vc_content id and save changes
   {% include image.html img="paste_cta_bar_shortcode.png" style="wide" lightbox="false" alt="Alt for image" caption="paste_cta_bar_shortcode" %}
- CTA header line will display in front-end side like below screen
   {% include image.html img="cta_bar.png" style="wide" lightbox="false" alt="Alt for image" caption="cta_bar" %}

## Hide Or Disable CTA Bar Form Specific Page Or Post
- Go to page or post edit.
- In "Page Attributes" tab on left side we can see Disable CTA bar checkbox to show/hide CTA bar from specific page.
   {% include image.html img="cta_page_post_disable.png" style="wide" lightbox="false" alt="Alt for image" caption="cta_page_post_disable" %}

 
   

## Pro Tip
> In next-gen options the shortcode value must be properly enclosed in square brackets like so: [vc_content id="1283"]
