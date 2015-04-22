=== Send From ===
Contributors: Benjamin Buddle
Tags: mail, mailer, phpmailer, change, from, send, email
Requires at least: 3.2.1
Tested up to: 4.1.2
Stable tag: 2.2

Plugin for modifying the from line on all emails coming from WordPress.

== Description ==

I have issues with my hosting service not allowing me to easily set the 'From line' for my server email. Whenever a new user signs up they see username@hostingservice.com even though they should see user@site.com. Before Send From you would be required to modify your installation of Wordpress just about every time you do an update. No longer! With Send From, you simply go into 'Settings->Send From' and set what the end user will see on their emails from line.

== Installation ==

1. Download
2. Upload to your `/wp-contents/plugins/` directory.
3. Activate the plugin through the 'Plugins' menu in WordPress.

= Set Defaults =

1. Under the 'Settings' area, click the link for 'Send From'
2. Change the From Name and From Email
3. Click Update Options

== Frequently Asked Questions ==

= Why create this? =

My host is Host Monster, who does not allow me to easily set the email address my server communicates with. I was not willing to outright hack Wordpress; so, I created a plugin that has worked solidly for me since Wordpress version 3.

= What is the minimum version that is useable with this plugin? =

I'm told that WordPress 2.7 changed several settings, including the way things are sent via mail. So I can't guarentee support before version 2.7.

= This pluging doesn't work with x, y, z. Will you add support? =

Chances are if it's not working with another plugin then I have not encountered the issue and am not likly to fix it. So no, I'm sorry but I will not be adding support for x, y, z.

== Screenshots ==

1. Screenshot of the Plugins > Send From panel.

== Support Questions ==

If there are any issues that crop up, I will be happy to take a look at solving them. I don't often check the support forum for issues, so if you have anything that needs immediate attention, reach out to me on twitter @mahoskye. 

== Changelog ==
 2.2 - Added missing quotation marks on line 63, moved config location under Settings
 2.1 - Tested and confirmed working in WP 4.1.2
 2.0 - Updated the code to fix naming conventions, reduce size, and fix and issue with the options page
 1.3 - Fixed typo
 1.2 - Fixed issue with update message not displaying properly
 1.1 - Fixed Error where default address was not properly used
 1.0 - Send Test Working and showing proper messages
 0.9 - Send Test Implemented and working, showing 'Settings Saved.'
 0.8 - Working without Send Test option
 0.7 - Added Options Page
 0.5 - Revision / working draft
 0.1 - Initial approact to content