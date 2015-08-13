---
layout:    page
title:     en-US
permalink: /items/
---

> Most of the time a website running WordPress is hacked the culprit is not WordPress, but of any silly misconfiguration that could be avoided during its development.
> That's the idea of this project: Being a checklist of actions that you should take to increase the security of your website.

## Login Page

* <input type="checkbox" id="step-1-1" class="step" /><label for="step-1-1"> Lockdown the login page for repetitive failed login ([Login Lockdown](https://wordpress.org/plugins/login-lockdown/){:target="_blank"} or [iThemes Security](https://wordpress.org/plugins/better-wp-security/){:target="_blank"} )</label>
* <input type="checkbox" id="step-1-2" class="step" /><label for="step-1-2"> Activate 2 factor authentication ([Google Authenticator for WordPress](https://wordpress.org/plugins/wp-google-authenticator/){:target="_blank"})</label>
* <input type="checkbox" id="step-1-3" class="step" /><label for="step-1-3"> Use email address to login instead of username ([WP Email Login](http://wordpress.org/extend/plugins/wp-email-login/){:target="_blank"})</label>
* <input type="checkbox" id="step-1-4" class="step" /><label for="step-1-4"> Rename the URL of your login page ([iThemes Security](https://wordpress.org/plugins/better-wp-security/){:target="_blank"} or directly on .htaccess)</label>
* <input type="checkbox" id="step-1-5" class="step" /><label for="step-1-5"> Remove login links from the theme (if there's any)</label>
* <input type="checkbox" id="step-1-6" class="step" /><label for="step-1-6"> Use a strong password contaning uppercase, lowercase, numbers, and special characters on all accounts ([password generator](http://passwordsgenerator.net/){:target="_blank"})</label>
* <input type="checkbox" id="step-1-7" class="step" /><label for="step-1-7"> Change the passwords regularly</label>
* <input type="checkbox" id="step-1-8" class="step" /><label for="step-1-8"> Make the login error messages more generical (user/pass) ([tutorial](https://gist.github.com/zergiocosta/72f87176b236ed0c6e13){:target="_blank"})</label>

## Administrative Panel

*  <input type="checkbox" id="step-2-1" class="step" /> <label for="step-2-1"> Password protect the folder wp-admin ([unblock only the needed files](https://gist.github.com/rafaelfunchal/f9a41ea72d80600d753a){:target="_blank"})</label>
*  <input type="checkbox" id="step-2-2" class="step" /> <label for="step-2-2"> Keep WordPress up-to-date</label>
*  <input type="checkbox" id="step-2-3" class="step" /> <label for="step-2-3"> Do not create an account with username admin. If there is any, create a new Administrator account and delete the old one</label>
*  <input type="checkbox" id="step-2-4" class="step" /> <label for="step-2-4"> Create an Editor account and use it solely to publish content</label>
*  <input type="checkbox" id="step-2-5" class="step" /> <label for="step-2-5"> Implement SSL for the WordPress admin section</label>
*  <input type="checkbox" id="step-2-6" class="step" /> <label for="step-2-6"> Install any plugins to check file changes ([WP Security Scan](https://wordpress.org/plugins/wp-security-scan/){:target="_blank"}, [Wordfence](https://wordpress.org/plugins/wordfence/){:target="_blank"} or [iThemes Security](https://wordpress.org/plugins/better-wp-security/){:target="_blank"})</label>
*  <input type="checkbox" id="step-2-7" class="step" /> <label for="step-2-7"> Scan the website for viruses, malware, and security breaches</label>

## Themes

*  <input type="checkbox" id="step-3-1" class="step" /> <label for="step-3-1">Keep the theme up-to-date</label>
*  <input type="checkbox" id="step-3-2" class="step" /> <label for="step-3-2">Delete and remove unused themes</label>
*  <input type="checkbox" id="step-3-3" class="step" /> <label for="step-3-3">Download and use themes only from reputable sources</label>
*  <input type="checkbox" id="step-3-4" class="step" /> <label for="step-3-4">Remove the WordPress version from the theme ([tutorial](http://www.wpbeginner.com/wp-tutorials/the-right-way-to-remove-wordpress-version-number/){:target="_blank"})</label>

## Plugins

* <label><input type="checkbox" /> Keep all plugins up-to-date</label>
* <label><input type="checkbox" /> Delete and remove unused plugins</label>
* <label><input type="checkbox" /> Download and use plugins only from reputable sources</label>
* <label><input type="checkbox" /> Replace outdated plugins for alternative newer plugins</label>
* <label><input type="checkbox" /> Think twice before installing a ton of plugins</label>

## Database

* <label><input type="checkbox" /> Change the default table prefix ([tutorial](http://www.maketecheasier.com/the-safe-way-to-change-your-wordpress-database-table-prefix){:target="_blank"})</label>
* <label><input type="checkbox" /> Schedule weekly backup of the database ([Backup WP](https://wordpress.org/plugins/backup-wp/){:target="_blank"}, [WP DB Backup](https://wordpress.org/plugins/wp-db-backup/){:target="_blank"} etc. )</label>
* <label><input type="checkbox" /> Use a strong password contaning uppercase, lowercase, numbers, and special characters for the database user ([password generator](http://passwordsgenerator.net/){:target="_blank"})</label>

## Hosting provider

* <label><input type="checkbox" /> Hire a reliable hosting provider</label>
* <label><input type="checkbox" /> Connect to your server only through SFTP or SSH</label>
* <label><input type="checkbox" /> Set all folder permission to 755 and files to 644 ([accourding to the Codex](http://codex.wordpress.org/Hardening_WordPress#File_Permissions){:target="_blank"})</label>
* <label><input type="checkbox" /> Make sure the wp-config.php file is not accessible by others</label>
* <label><input type="checkbox" /> Remove or block via .htaccess the files license.txt, wp-config-sample.php, and readme.html</label>
* <label><input type="checkbox" /> Disable file edit via wp-config.php by adding the following code: `define('DISALLOW_FILE_EDIT',true);`</label>
* <label><input type="checkbox" /> Prevent directory listing via .htaccess by adding the following code: `Options All -IndexesOptions All -Indexes`</label>
