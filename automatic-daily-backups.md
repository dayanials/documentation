---
title:  "Automatic daily backups"
date:   2015-02-11 19:53:00
categories: Techical
tags: Techical, SelfHosted
permalink: /automatic-daily-backups/
keywords: backup, files, database, server, restore
---
_This guide is only for [Yclas Self Hosted](https://yclas.com/)!_

![Backups](//open-classifieds.com/wp-content/uploads/2015/02/800x524xlarge_ss_3-b5f35a82-e1423684533150.jpg.pagespeed.ic.LRNk8IVspN.jpg) 

<br>
From the many support tickets I have covered and issues that were reported by our users, I noticed the huge importance of having automatic backups. As we have explained before, doing a backup before any update can save your life more than once! 

I've done a guide about [how to do backups]({{ site.baseurl }}/backup-classifieds-site/) some time ago, but it's an ugly manual process, let's be honest. 

It is not nice to deal with it and, in the best scenario, you don't forget to do the backup and pray while restoring the data it works all good... 

I had done in my [personal time an script](http://garridodiaz.com/ftp-backup-for-mysql-and-files/) that automates this process, but that requires an external FTP to upload backups good enough. But remember every few and then to download the backup, and really important to verify the backup! 

Since a month ago, I am using [CodeGuard](http://mbsy.co/CodeGuard/17761100) to backup [Yclas](https://yclas.com) servers from any problem may happen.

**Things I am loving so far**

  * It was really easy to setup
  * They do a daily backup
  * Notification every time there's a modification on the files (get an email)
  * MySQL backups for 1 DB
  * Restore your website from any point. WOW!
  * Great support

**Wha is not so great**

  * If your website is huge, se service will be a bit expensive. But if it's huge, you are making money, right?
  * You need to pay by card and in USD, with paypal is a bit more complex
  * $5 for each extra site

  Luckily, I haven'thad the need to use the restore option, but it looks awesome! 

  My recommendation is to take the [ninja plan for $5 month](http://mbsy.co/CodeGuard/17761100) and exclude the "media" files such as images or css from the backup if you already do monthly backups. Think that you get 5GB, use them wisely! 

  ![Plans and Pricing Sign Up for Website Backup CodeGuard](//open-classifieds.com/wp-content/uploads/2015/02/Plans-and-Pricing-Sign-Up-for-Website-Backup-CodeGuard.png)

  <br>
  Honestly, I sleep better having this working for us.If you try it, let me know how was your experience.


