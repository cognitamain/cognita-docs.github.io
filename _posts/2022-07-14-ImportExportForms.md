---
layout: post
title: Import / Export Forms
categories: [Wordpress Admin]
author: Anna Browell
---

## Description

The forms section provides the option to export the form settings of an individual forms or all of the forms on hosted your site. This gives users an easy way to transfer forms between different environments. However when you are testing the forms you will need to switch between the your testing Dynamics environment (UAT) and the live Dynamics environment (Prod). This ensures that the leads you create when testing do not go into your active Dynamics workspace.


## Importing your form


1. Navigate to Forms-> Import/Export -> Import Form
2. Select the form you want to import from your device and click Import
3. You will receive a notification that the import was successful
4. Now if you navigate to Forms you will see the form you just imported
5. Remember to Switch the Portal/Talend Mapping from UAT to Production
	* Further details on this can be found [here](/nextgen/EditingForms/)

{% include image.html img="form_import.png" style="wide" lightbox="false" alt="Alt for image" caption="Import Forms" %}

## Exporting you form


1. Navigate to Forms-> Import/Export -> Export Form
2. Select the form or forms you want to export and click Download Export File
3. This will save the form settings on your device in a JSON file

{% include image.html img="form_export.png" style="wide" lightbox="false" alt="Alt for image" caption="Export Forms" %}

