# Postfix Administration

This module administers a Postfix Mail Server with a MySQL Backend through 
the new/refactored Forms API in Drupal 4.7.

The Database schema, and server setup may be specific, 
it is based on the howto [Virtual Users And Domains With Postfix, Courier And MySQL (+ SMTP-AUTH, Quota, SpamAssassin, ClamAV](http://www.howtoforge.com/virtual_postfix_mysql_quota_courier) by Falko Timme.

## Features

- Adminstration of Domains
- Adminstration of Users and Quotas
- Adminstration of Forwardings
- Adminstration of Transports

## Installation and Configuration

1. Place the module within *site/all/modules* of your Drupal 4.7 installation.
2. enable this module.
3. visit *admin/postfix* to configure the database connection for the postfix database connection.

## Trivia

- My first module, written in late 2006, for Drupal 4.7 rediscovered within a backup of on one of our servers.
- This module was the reason why i created a [drupal.org account](https://www.drupal.org/user/51103) :D
