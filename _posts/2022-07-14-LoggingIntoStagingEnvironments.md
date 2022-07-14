---
layout: post
title: Logging in to Test Website
categories: [Wordpress Admin]
author: Anna Browell
---
{% include image.html img="logging_in.png" style="wide" lightbox="false" alt="Alt for image" caption="Staging Login" %}


## Description

For most content updates it is easy to make changes on your live site and only publish these changes when you are happy with the layout. However In other cases where the update may have an impact on multiple pages (changing Navigation, changing footer styles) or the change may have a critical effect on the website such as Editing Webforms, the development environments should be used to create and test the changes before applying them. Each website has two test environments PreProd and Develop.

Editing the sites in the test environments will make no impact on your live site. If the site breaks you can ask the hypercare team to roll back the change to the same state as the current live site.

## Your Staging environments

|Live Site|Develop Site|Preprod Site|
|-------|-------|-------|
|www.brightoncollege.edu.sg|brightoncollege-dev.cognitastaging.co.uk|brightoncollege-preprod.cognitastaging.co.uk|
|www.aavn.edu.vn|aavn-dev.cognitastaging.co.uk|aavn-preprod.cognitastaging.co.uk|
|www.ishcmc.com|ishcmc-dev.cognitastaging.co.uk|ishcmc-preprod.cognitastaging.co.uk|
|www.standrewsgreenvalley.com|standrewsgreenvalley-dev.cognitastaging.co.uk|standrewsgreenvalley-preprod.cognitastaging.co.uk|
|www.ais.com.sg|ais-dev.cognitastaging.co.uk|ais-preprod.cognitastaging.co.uk|
|www.sais.edu.hk|sais-hk-dev.cognitastaging.co.uk|sais-hk-preprod.cognitastaging.co.uk|
|www.woodlandschools.com|woodlandschools-dev.cognitastaging.co.uk|woodlandschools-preprod.cognitastaging.co.uk|
|www.standrewssukhumvit.com|standrewssukhumvit-dev.cognitastaging.co.uk|standrewssukhumvit-preprod.cognitastaging.co.uk|
|www.standrewssathorn.com|standrewssathorn-dev.cognitastaging.co.uk|standrewssathorn-preprod.cognitastaging.co.uk|
|www.standrewsdusit.com|standrewssathorn-dev.cognitastaging.co.uk|standrewssathorn-preprod.cognitastaging.co.uk|
|www.issp.edu.vn|issp-dev.cognitastaging.co.uk|issp-preprod.cognitastaging.co.uk|
|www.sais.edu.sg|sais-sg-dev.cognitastaging.co.uk|sais-sg-preprod.cognitastaging.co.uk|


## Accessing your Staging Environment


1. Find the URL of the environment you want to make your changes to. Load it in a new window.
2. Your will be requested to enter a username and password.
3. Use the following credentials
	* username: cognita
	* password: tgbygv
4. Your website should appear after adding the credentials
5. You may notice it does not look exactly the same, some different styles or missing logo but do not worry this is because some of your setting are not included
6. You can access the admin menu the same way you do on your live site
7. Go to the /admin/ or /wp-admin/ select login with username and password
8. Use the same username and password as you use on your live site
9. You will now need the authentication code that you use on your live site
10. You are now logged in to the staging environment


