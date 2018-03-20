---
title:  2 Step Authentication
date:   2016-03-31 09:13:09
categories: General
tags: General, Settings
permalink: /2-step-authentication/
keywords: settings, general, authentication, login, profile, qr code
---
<div class="alert alert-warning">
<strong><i class="glyphicon glyphicon-warning-sign"></i> </strong> This feature is available with our 2.8.0 release and on all of the sites hosted at <a href="https://yclas.com/">Yclas.com</a> 
</div>

This feature gives you and your users two-factor authentication. You can protect your account with both your password and your phone. 

## How to configure 2 step authentication

1. Login to your **admin panel**.
2. Go to **Settings -> General**.
3. Activate **2 Step Authentication**.
4. Press **Save**.

<a href="//docs.yclas.com/images/2step.png" class="thumbnail gallery-item" data-gallery>
![2step admin]({{ site.baseurl }}/images/2step.png)
</a>

## Enable 2 Step Authentication on your profile

1. **Login** to your website.
2. Go to **[Edit Profile](http://docs.yclas.com/how-to-edit-your-profile/)**.
3. If you don't have **Google Authenticator** app installed on your mobile phone, you can choose below **Android** or **iOS**  to get it.
4. Run the app on your mobile phone, click **Set up account** from the options and **scan the QR code**.
5. In the "2 Step Authentication" section, scan the QR code.

<a href="//docs.yclas.com/images/2step-auth-enable.png" class="thumbnail gallery-item" data-gallery>
![2step admin]({{ site.baseurl }}/images/2step-auth-enable.png)
</a>

6\. Once the QR code is scanned, you will see the account created with a verification code (there's no need to write down or memorize the verification code because it changes every 30 seconds.)

7\. Now you will be redirected to enter the verification code and press "Send". If the code is valid, the 2 Step Authentication will be enabled, otherwise you will have to scan QR code and enter the verification code again.   

<a href="//docs.yclas.com/images/2step4.png" class="thumbnail gallery-item" data-gallery>
![2step admin]({{ site.baseurl }}/images/2step4.png)
</a>

## How to use it

1. Go to your website and choose to log in.
2. Enter your **Email** and **Password** and click **Login**.
3. You will be redirected to **Enter the Verification Code** (Run the Google Authenticator app to find the verification code.)
4. Click **Send**.
5. Now you are logged into your website!

<a href="//docs.yclas.com/images/2step5.png" class="thumbnail gallery-item" data-gallery>
![2step admin]({{ site.baseurl }}/images/2step5.png)
</a>






