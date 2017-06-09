---
title:  Ripple-QEWD Swagger APIs
keywords: QEWD
sidebar: rippledocs1_sidebar
permalink: qewd-ripple-APIs.html
---


We are using Swagger to expose all the APIs  that is supported by the Ripple-QEWD middletier

The Swagger UI is crafted so it is part of the standard install process

The url should be of the style x.x.x.x/swagger-ui/dist/

For demo purposes you can currently explore [http://46.101.95.245/swagger-ui/dist/](http://46.101.95.245/swagger-ui/dist/)
NB Please read the section below about authentication so you can easily use our Swagger APIs.

Note that to help educate you in the Ripple stack, we follow the pattern the application follows, which involves an authentication step.

There are 5 steps to using Swagger

Get api initialise

```liquid
{% raw %}
{% include image.html file="jekyll.png" url="http://jekyllrb.com" alt="Jekyll" caption="This is a sample caption" %"}
{% endraw %}
```


{% include image.html file="jekyll.png" url="http://jekyllrb.com" alt="Jekyll" caption="This is a sample caption" %}

Click Try it Out

Click Execute

Copy the Response Body / token

Click Authorize

Insert secure token

Click Authorise

Authorized appears


You will now see secure APIs and you can proceed to use the rest of the APIs 

eg 
GET   /api/patients/{patientId}/allergies

Click Try It Out

Patient ID for Demo is  9999999000

Click Execute

etc
etc





