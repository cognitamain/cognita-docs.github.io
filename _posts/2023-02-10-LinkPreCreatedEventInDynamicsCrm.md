---
layout: post
title: Link Pre-Created Event In Dynamics CRM Marketing.
categories: [Wordpress Admin]
author: Himani
---

{% include image.html img="crm_events_list.png" style="wide" lightbox="false" alt="Alt for image" caption="Blog Articles" %}


## Description

On landing page form submission to get registered or submitted user records in pre-created events on CRM portal.

{% include image.html img="crm_events_list.png" style="wide" lightbox="false" alt="Alt for image" caption="Blog Articles" %}



## Add Event ID In Form   

- Click Edit Form : Duplicate or use hidden field
   {% include image.html img="add_eventid_inform.png" style="wide" lightbox="false" alt="Alt for image" caption="New Post" %}
- Duplicate or use hidden field and add Parameter Name: <b>sag_eventid</b>
- Update the form
- Use https://web-support.cognita.com/ to reachout to website developers to map the sag_eventid field with CRM.

## Create Events Landing page

- Add new or edit page 
- Add new element from custom Nextgen options ie: <b>Lead Form with Background Settings</b>
   {% include image.html img="use_leadform.png" style="wide" lightbox="false" alt="Alt for image" caption="New Post" %}
- Inside Lead Form with Background Settings scroll down towards D365 Event Id
   {% include image.html img="choose_event_form.png" style="wide" lightbox="false" alt="Alt for image" caption="New Post" %}
- Choose the form where sag_eventid is added.
- In the <b>D365 Event Id</b> we need to add the event ID from the CRM events section.

## Copy And Paste Event ID From The CRM Platform.
- Go to CRM Events in Marketing section
   {% include image.html img="crm_events_list.png" style="wide" lightbox="false" alt="Alt for image" caption="New Post" %}
- Open or add new event
- From the very top of a browser window <b>Address bar</b> copy the event ID using Address bar.
-  We need to copy the eventId text after _event&id= 
   {% include image.html img="copy_paste_id.png" style="wide" lightbox="false" alt="Alt for image" caption="New Post" %}
-  Paste the D365 Event Id in Lead Form with Background Settings
   {% include image.html img="save_eventid.png" style="wide" lightbox="false" alt="Alt for image" caption="New Post" %}
-  Save the element and form.

## See The registered users in CRM.

-  After successful submission from forms we can see the records at CRM marketing events section
   {% include image.html img="records_in_crm.png" style="wide" lightbox="false" alt="Alt for image" caption="New Post" %}


## Pro Tip
> Value of D365 Event Id should be matched with the EventId in CRM Marketing side for respective Events. 
