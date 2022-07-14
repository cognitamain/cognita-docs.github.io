---
layout: post
title: Editing Form Details
categories: [Wordpress Admin]
author: Anna Browell
---
{% include image.html img="form_forms.png" style="wide" lightbox="false" alt="Alt for image" caption="Form Entries" %}


## Description

Your webforms are linked to Dynamics in order for leads to be directly loaded into your own schools workspace, this connection requires the forms to be set up in a specific way and small modifications to the form can break this connection. For this reason all changes to forms should be tested in the staging environments.

This tutorial will guide you through making changes to the forms and testing your changes. Please see the linked guides for instructions on logging into the staging environments and exporting and importing your forms.



{% include image.html img="form_edit.png" style="wide" lightbox="false" alt="Alt for image" caption="Edit Form" %}

## Editing your form


1. Log in to your testing environment, you will need School Admin access to make changes to forms
	* Guide to Access [Testing environment](/nextgen/LoggingIntoStagingEnvironments/)
2. Navigate to Forms and select 'Forms' on the dropdown menu
3. This screen will show you a copy of your existing forms on your live site
4. Find the form you want to update or duplicate an existing form to make changes to
5. Click Edit to modify the order of fields or add any additional fields
	* Please note that additional fields will only be added to the lead entries on your site or in the lead notification emails.
	* Please consult Hypercare to see if field data can be added to the Dynamics connection


{% include image.html img="form_settings.png" style="wide" lightbox="false" alt="Alt for image" caption="Form Settings" %}


## Changing your form name

1. Go to Form Settings
2. Edit the Form Title - this is how the form will be named in Dynamics
3. Scroll to the bottom and click 'Save Settings'


{% include image.html img="form_notifications.png" style="wide" lightbox="false" alt="Alt for image" caption="Notifications" %}


## Adding email addresses to the Lead notification distribution

1. Go to Form Settings and navigate to Notifications
2. Open the Notification named 'Admin Notification'
3. From this page you can add email addresses to the distribution list by separating emails with a comma
4. You may also remove email addresses from the distribution list
5. After making your changes, scroll to the bottom and click 'Update Notification'



{% include image.html img="form_talend.png" style="wide" lightbox="false" alt="Alt for image" caption="Portal/Talend Config" %}


## Preparing your form for testing

1. Go to the Form Settings -> Portal/Talend Config
2. Change the field from Production to UAT, scroll to the very bottom of the page and click 'Save Settings'


## Export your form

Please see the guide [here](/nextgen/ImportExportForms/) to export your form

