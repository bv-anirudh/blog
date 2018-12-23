---
title: Seamless WordPress Migrations
date: '2018-12-23'
---

## What does migration mean in context to WordPress?

> Migration: movement from one part of something to another.

WordPress migrations mean moving your site from source to destination. This means all the files and tables from your source to your destination server.

**However, moving your site is not a straightforward task.**

In this post, I shall discuss reasons for moving your site, the key things you should keep in mind while migrating and the services which can help you do this. 

## Why would I want to migrate my site?
There are a *host* of reasons why you would want to move your website.
A few are:

### Switching your hosting provider

Usually the number one reason for moving your site.
A few reasons you might want to move away from your existing hosting provider:

* High costs
* Too much downtime
* Shared hosting is slowing your site down

### Pushing changes from staging to live or vice-versa

You want to create a staging to test the changes you're about to make on your website.
I have already written an [article](https://noicewordpress.wordpress.com/importance-of-wordpress-staging-sites/)
on why it is vital to test your changes on staging before pushing them to your live website. 
Alternatively, you would like to make the changes from your staging website to your live website.

## Zero-Downtime Migrations

Irrespective of the reasons why you are trying to move your website, it is essential that you and your users/viewers shouldn't be directly affected while the site is in transit. Also, the migration process should be hassle-free and seamless for you. 

For instance, you could have a WooCommerce website, which has a decent amount of traffic. If your site goes down for even an hour, you would've lost a significant amount of money and potential customers :(.

## Things to consider while migrating

* Copy all files and tables from source to destination
* Ignore redundant files such as log files and cache files for faster migrations
* Update values such as URLs and paths according to the destination server
* Update configurations based on the destination server
* The migration process shouldn't slow down your system
* Migration should be independent of your system and shouldn't be dependent on you

## Services you can use to migrate your site
*Full disclosure: I am a developer at BlogVault and one of Migrate Guru's author, so this section might be a little biased.*

### BlogVault

BlogVault is one of the most trusted names when it comes to WordPress migrations as it has partnered with many hosting providers such as *WPEngine, Pantheon, FlyWheel, LiquidWeb, Cloudways, and Pressable*. 

There are two standout features while using BlogVault:
* Understanding the destination server's configuration and updating the values to match them
* Migration is entirely independent of your live site. It brings all the files to its servers and then moves the files to the destination server. This process runs on the background thus never overloading your site and makes the process super easy and straightforward.

You can read more about BlogVault, and it's migration feature [here](https://blogvault.net/wordpress-migration/).

### Migrate Guru

Migrate Guru is a product of BlogVault which focuses solely on migrations. It does all the above things mentioned above and does it for free.
It is an entirely free plugin. It is growing at a fast pace, reaching 10,000+ active installs and nearing 100 5 \*s in the short time it has been released.

You can read more about Migrate Guru [here](https://wordpress.org/plugins/migrate-guru/)

### Duplicator

Duplicator is a WordPress plugin that enables you to do two things: create a copy — or duplicate — of your site, then install it somewhere else.
Duplicator creates a package that bundles all the site’s plugins, themes, content, database and WordPress files into a simple zip file called a package. This package can then be used to migrate a WordPress site to any location you wish easily.


You can read more about Duplicator [here](https://wordpress.org/plugins/duplicator/)

---

WordPress migrations can either be breezy or make you want to pull your hair out. I hope this article is useful and helps you keep your sanity in check when it comes to website migrations.

<p align="center">Keep Migrating :)</p>
