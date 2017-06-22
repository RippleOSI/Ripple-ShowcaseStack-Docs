---
title:  Ripple-QEWD Swagger APIs
keywords: QEWD
sidebar: rippledocs1_sidebar
permalink: qewd-ripple-APIs.html
---


We are using Swagger to expose all the APIs  that is supported by the Ripple-QEWD middletier

The Swagger UI is crafted so it is part of the standard install process

The url should be of the style DomainNameOrIPaddress/swagger-ui/dist/

For demo purposes you can currently explore [http://showcase2.ripple.foundation/swagger-ui/dist/](http://showcase2.ripple.foundation/swagger-ui/dist/)

NB Please read the section below about authentication so you can easily use our Swagger APIs.

Note that to help educate you in the Ripple stack, we follow the pattern the application follows, which involves an authentication step.

There are 5 steps to using Swagger

Get api initialise




{% include image.html file="/qewd/start_Swagger.PNG" alt="Jekyll" caption="This is a sample caption" %}

Click Try it Out
{% include image.html file="/qewd/getInitialise.PNG" alt="Jekyll" caption="This is a sample caption" %}

Click Execute
{% include image.html file="/qewd/getInitialiseExecute.PNG" alt="Jekyll" caption="This is a sample caption" %}

Copy the Response Body / token
{% include image.html file="/qewd/getInitialiseToken.PNG" alt="Jekyll" caption="This is a sample caption" %}

Click Authorize
{% include image.html file="/qewd/ClickGreenAuthorise.PNG" alt="Jekyll" caption="This is a sample caption" %}

Insert secure token
{% include image.html file="/qewd/InsertAuthToken.PNG" alt="Jekyll" caption="This is a sample caption" %}

Click Authorise
{% include image.html file="/qewd/ClickGreenAuthorise.PNG" alt="Jekyll" caption="This is a sample caption" %}

Authorized appears
{% include image.html file="/qewd/AuthorisedView.PNG" alt="Jekyll" caption="This is a sample caption" %}

You will now see secure APIs and you can proceed to use the rest of the APIs 

eg 
GET   /api/patients/{patientId}/allergies
{% include image.html file="/qewd/getAPIPtsAllergy.PNG" alt="Jekyll" caption="This is a sample caption" %}
Click Try It Out

Patient ID for Demo is  9999999000

{% include image.html file="/qewd/getAPIPtsAllergy_Pt999.PNG" alt="Jekyll" caption="This is a sample caption" %}

Click Execute
{% include image.html file="/qewd/getAPIPtsAllergy_Pt999_Results.PNG" alt="Jekyll" caption="This is a sample caption" %}
etc
etc





