---
layout: post
title: How To Set Page Visibility  
categories: [Wordpress Admin]
author: Himani
---
{% include image.html img="subpage_beforeupdate.png" style="wide" lightbox="false" alt="Alt for image" caption="Timeline Settings" %}


## Description

To prevent a subpage from having 404-page error the visibility of its Parent Page should not be set as Private. The Parent Page should always be set to public if we want to show its subpage for the right permalinks structure. Please see below in the screenshots how to set the Parent Page to Public. 


## Using the Page Visibility

In the above screenshots we want to show “Choosing the Right School Page” under the “Admissions”. So, when we will edit the Subpage (Choosing the Right School Page), we will have to select Admissions as its parent from the dropdown -> Page Attributes as shown in above screenshot. And if the Parent page (Admissions) is set to Private it will not be visible in the dropdown list. In such case there will be no parent as shown below: `

Subpage: 

{% include image.html img="subpage_beforeupdate.png" style="wide" lightbox="false" alt="Alt for image" caption="Timeline Settings" %}

If any page was set on private before, and this time if we have made some changes (like content changes). 

Parent page :

{% include image.html img="parentpage_visibility_private.png" style="wide" lightbox="false" alt="Alt for image" caption="Timeline Settings" %}

Subpage after some content update with out doing any ohter setting:

{% include image.html img="subpage_URLchanges_afterupdate.png" style="wide" lightbox="false" alt="Alt for image" caption="Timeline Settings" %}


And we update and save the subpage without parent it will cause 404 error on frontend.  

{% include image.html img="subpage_afterupdate.png" style="wide" lightbox="false" alt="Alt for image" caption="Timeline Settings" %}

So, to prevent this we need to set page visibility to public & then choose the parent page from the dropdown of page Attributes (Parent) and then update/save that page with the latest changes. 


In parent page we have to like :
{% include image.html img="parentpage_visibility_changedTopublic.png" style="wide" lightbox="false" alt="Alt for image" caption="Timeline Settings" %}

And in subpage we need to do like :

{% include image.html img="choose_parentPage.png" style="wide" lightbox="false" alt="Alt for image" caption="Timeline Settings" %}

After if we see the page it will be working

{% include image.html img="working_subpage_afterupdate.png" style="wide" lightbox="false" alt="Alt for image" caption="Timeline Settings" %}
  

## Pro Tip
> Make sure the visibility of parent page should always be public for its inner pages working.
