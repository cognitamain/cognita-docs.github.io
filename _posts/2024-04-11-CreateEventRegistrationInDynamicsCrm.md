---
layout: post
title: Event Registration In Dynamics CRM Marketing.
categories: [Wordpress Admin]
author: Cognita
---
*Note : This option will be available after 13th APRIL 2024 !*

{% include image.html img="crm_events_list.png" style="wide" lightbox="false" alt="Alt for image" caption="crm_events_list" %}


## Description
This functionality is useful for generating new events upon form submission in the Dynamics CRM portal.

{% include image.html img="multi_event_form.png" style="wide" lightbox="false" alt="Alt for image" caption="multi_event_form" %}



## Enable and Manage Events 

-For the initial implementation, consider requesting the addition of an events form on the website by <a href="https://web-support.cognita.com"> submitting a ticket</a> to the website developers. We can either create a new form or use an existing one (long or short) to select events.
   {% include image.html img="enable_crm_events.png" style="wide" lightbox="false" alt="Alt for image" caption="enable_crm_events" %}
   or Long form / Short Form with Single campus only like Asian Inquiry Websites.
   {% include image.html img="LongFormEventsSingleCampus.jpg" style="wide" lightbox="false" alt="Alt for image" caption="enable_crm_events" %}

## Created And Add Events In Event Data

- Once Events are enabled, school admin can login to the CMS/website and navigate to the CRM Multi Events menu in the menu bar on the left.
   {% include image.html img="show_events_settings.jpg" style="wide" lightbox="false" alt="show_events_settings" caption="enable_crm_events" %}
-  Click on "Add Row" to create events in the Event From and update.
- If this is a new setup to add events then click on the plus icon to open the accordion.
- Enter a valid event name. It is not necessary to use any comma (,), 's, & in this field.
   {% include image.html img="event_data1.png" style="wide" lightbox="false" alt="Alt for image" caption="EventData" %}
- Select the event campus, for which option you need to add the event.
- There is no need to add or edit the "Main events shown" field. Since this is just to show where the event created will appear on the form side.
- Add event start date, start time, end date, end time to the event. Note*: End time should be greater than start time.
- To add another event, click the "Add Row" or + icon in the right side button and follow the same steps.
- Save/Update the event with "Update" button on right top side of the page.

## Link Pre-Created Event
- In "Event Name" enter the same event name as created/exists in CRM Marketing side.
   {% include image.html img="crm_event_name.png" style="wide" lightbox="false" alt="Alt for image" caption="Get CRM Event Name" %}
- TFill in all the event details and save the changes.
   {% include image.html img="add_crm_event_name.jpg" style="wide" lightbox="false" alt="Alt for image" caption="add_crm_event_name" %}

## Verify Events On Form
- Open the Front End Side form and select the campus for which the events were added from the CMS side.
- On selecting an option there will be a dropdown and we can verify the event name in the option.
  like in below screenshot for multicampus school:
  {% include image.html img="event_verification_onform.png" style="wide" lightbox="false" alt="Alt for image" caption="event_verification_onform" %}
- Like for single campus school any form event has been setup like in below screenshot :
  {% include image.html img="like_event_form_created.jpg" style="wide" lightbox="false" alt="Alt for image" caption="event_verification_onform" %}
  Then on user side it will apear like in below screenshot :
  {% include image.html img="user_side_single_campus_events.jpg" style="wide" lightbox="false" alt="Alt for image" caption="event_verification_onform" %}

## See The registered users in CRM.

- After successful form submission we can see the record in CRM Marketing Events section
   {% include image.html img="records_in_crm.png" style="wide" lightbox="false" alt="Alt for image" caption="records_in_crm" %}
 &
   {% include image.html img="crm_side_events_created.jpg" style="wide" lightbox="false" alt="Alt for image" caption="event_verification_onCRM" %}
   
   



## Pro Tip
> Prior to scheduling any events, it's essential to obtain approval and thoroughly test the form design for CRM entries with PO & website developers. When linking pre-created events, ensure that the event name matches the events in the CRM marketing side for the relevant event.
