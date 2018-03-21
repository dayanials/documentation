---
title:  "Automatic emails sent to users"
date:   2013-08-27 09:37:50
categories: Content
tags: [Content]
permalink: /automatic-emails-sent-to-users/
keywords: email, email templates, send
---
When an user of your classifieds website does certain actions, like registering, posting an ad or requesting to change the password, he receives an **automatic email for confirmation**. To see and manage those emails, go to **Panel** and choose **Content** > **Email** from the left sidebar. Email templates are already created and translated to multiple languages. You can **Edit** them according to your needs by clicking he tblue button next to the template.

<a href="{{ site.baseurl }}/images/editemail.png" class="thumbnail gallery-item" data-gallery>
![Automatic emails sent to users](//docs.yclas.com/images/editemail.png)
</a>

<br>
Be sure to set the **locale** that you are currently using for your site (see: [How to change language of the site?]({{ site.baseurl }}/how-to-change-language)). You can edit **title** of the email, its **body** and the senders **email** displayed. For everything to work properly, you need to remember to choose the **type: email** and click on **status** check box to make it **active**.

## Available templates of emails

_Change Password (_**_auth-remember_**_):_ <br>
Sent to the user for confirmation after a request to change password 

<br>
_Welcome to [SITE.NAME]! (_**_auth-register_**_):_ <br>
Welcoming email sent to the user after completing registration and reminding data for logging in 

<br> 
_Hello [USER.NAME]! (_**_user-contact_**_):_ <br>
Mail informing that the user that he/her has been contacted regarding his advertisement, quoting the message 

<br>
_Hello [USER.NAME]!(_**_user-profile-contact_**_):_ <br>
Message sent to the user to notify when another user is contacting him/her directly via their profile 

<br>
_[EMAIL.SENDER] wants to contact you! (_**_contact-admin_**_):_ <br>
Message sent to the admin when a visitor uses a contact form 

<br>
_Your advertisement at [SITE.NAME], has been activated! (_**_ads-activated_**_):_ <br>
Message sent to the user when his/her ad was activated after the moderation by the admin 

<br>
_Success! Your advertisement is created on [SITE.NAME]! (_**_ads-notify_**_):_ <br>
Message notifying that an message was created and informing how to edit it and that it still have to be validated by administrator 

<br>
_Advertisement is created on [SITE.NAME]! (_**_ads-user-check_**_):_ <br>
Message sent to the registered user when the advertisement was created using their account to inform about creating the ad and confirm that they are responsible for posting it 

<br>
_Advertisement [AD.TITLE] is created on [SITE.NAME]!_ (**_ads-subscribers_**): <br>
Message sent to the registered user to recommend the related ads 

<br>
_Advertisement [AD.TITLE] is created on [SITE.NAME]!_ (**_ads-to-admin_**): <br>
Message sent to the admin with a link that is worth to visit 

<br>
_Advertisement [AD.TITLE] is sold on [SITE.NAME]!_ (**_ads-sold_**): <br>
Message sent to user to confirm the sale of an advertisement and to provide the information concerning the ID of order and sold product 

<br>
_Advertisement [AD.TITLE] is out of stock on [SITE.NAME]!_ _(**out-of-stock**):_ <br>
Message sent to inform about an inactive and invisible advertisement for users and to provide a link which enable admin to activate and increase stocks 

<br>
_Advertisement [AD.TITLE] is purchased on [SITE.NAME]!_ _(**ads-purchased**):_ <br>
Message sent to the user to confirm a purchase of an advertisement and to provide the confirmation of a purchase (Order ID / Product ID) 

<br>
_Receipt for [ORDER.DESC] #[ORDER.ID]_ _(**order-new**):_ <br>
Message sent to inform the user about an order that needs be completed with the payment (Checkout URL) 

<br>
_Success! Your advertisement is created on [SITE.NAME]! (_**_ads-confirm_**_)_: <br>
Message sent to users after creating an advertisement with a confirmation link

<br>
_Your ad [AD.NAME] has expired (_**_ad-expired_**_)_: <br>
Message sent to inform the user that his/her ad has expired. It sends that message one day after the expiration.

<br>
_Your ad [AD.NAME] is going to expire (_**_ad-to-expire_**_)_: <br>
Message sent to inform the user that his/her ad is going to expire. It sends that message two days before the expiration.

<br>
_[FROM.NAME] sent you a direct message (_**_messaging-user-contact_**_)_: <br>
Message sent to inform the user that he/she has a direct message. It includes the name of the sender, the content of the message and the link to this message.

<br>
_Hello [TO.NAME]! (_**_messaging-ad-contact_**_)_: <br>
Message sent to inform user that he/she has been contacted regarding an advertisement. It includes the name of the sender, the ad he/she is interested in, the content of the message and the link to this message.

<br>
_New review for [AD.TITLE] [RATE] (_**_ad-review_**_)_: <br>
Message sent to inform the user about a new review on an ad.

<br>
_There is a new reply on the forum (_**_new-forum-answer_**_)_: <br>
Message sent to inform the admin about a new reply on the forum. Users that have participated on the topic will get informed as well.

<br>
_Your plan [PLAN.NAME] has expired (_**_plan-expired_**_)_: <br>
Email sent to the user with a link to pay and renew his subscription.


## Set Email from

<div class="alert alert-warning">
<strong><i class="glyphicon glyphicon-warning-sign"></i> </strong> This feature is currently available only on all sites hosted at <a href="https://yclas.com/">Yclas.com</a> 
</div>

Previously, when you wanted to replace the Email From field from all the email templates, you had to go to Content -> Email and edit all the templates one by one. Now there's an option that allows you to change that field from all email templates directly.

Go to **Content** -> **Email**, choose **Set Email From**, set a new _From Email_ and click **Send**. 

<a href="{{ site.baseurl }}/images/email-from.png" class="thumbnail gallery-item" data-gallery>
![email-from]({{ site.baseurl }}/images/email-from.png)
</a>

<a href="{{ site.baseurl }}/images/email-from1.png" class="thumbnail gallery-item" data-gallery>
![email-from1]({{ site.baseurl }}/images/email-from1.png)
</a>


