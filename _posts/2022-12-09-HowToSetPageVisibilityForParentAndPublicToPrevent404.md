---
layout: post
title: How To Set Page Visibility  
categories: [Wordpress Admin]
author: Himani Guleria
---
{% include image.html img="subpage_afterupdate.png" style="wide" lightbox="false" alt="Alt for image" caption="Timeline Settings" %}


## Description

A subpage should not have its parent page's visibility set to private to prevent a 404-page error. The parent page should always be set to public if we want to show its subpages for the correct permalink structure.


## Using the Page Visibility

In the below screenshot if we see the parent page and subpage and their page properties. We can see in the subpages that the parent page is not set (no parent). The parent page's visibility is set to private.


Parent page :

{% include image.html img="parentpage_visibility_private.png" style="wide" lightbox="false" alt="Alt for image" caption="Timeline Settings" %}

Subpage: 

{% include image.html img="subpage_beforeupdate.png" style="wide" lightbox="false" alt="Alt for image" caption="Timeline Settings" %}

Before any change in subpage content if we see *permalink* and page properties section. We can see that there is no parent selected and the parent page slug is added to the link.

If a page was previously set to private, and this time if we have made some changes (like content changes).

After a few content updates without any other settings the subpage will look like this in the admin side:

{% include image.html img="subpage_URLchanges_afterupdate.png" style="wide" lightbox="false" alt="Alt for image" caption="Timeline Settings" %}

And we update and save the subpage without parent, it will cause 404 error on frontend.  

{% include image.html img="subpage_afterupdate.png" style="wide" lightbox="false" alt="Alt for image" caption="Timeline Settings" %}

So, to prevent this we need to make *parent page* visibility public and then in *subpage* select parent page from dropdown of page attributes (parent) and then update/save that page with latest changes. 

In parent page we have to do setting like:

{% include image.html img="parentpage_visibility_changedTopublic.png" style="wide" lightbox="false" alt="Alt for image" caption="Timeline Settings" %}

After these changes if we see the page, it will be like below screen

{% include image.html img="choose_parentPage.png" style="wide" lightbox="false" alt="Alt for image" caption="Timeline Settings" %}

After these changes if we see the page, it will be like below screen

{% include image.html img="working_subpage_afterupdate.png" style="wide" lightbox="false" alt="Alt for image" caption="Timeline Settings" %}
  

## Pro Tip
> Make sure the parent page's visibility should always be public for its inner pages to work. And the parent page in the subpages should be selected appropriately.
