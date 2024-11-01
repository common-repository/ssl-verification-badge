=== SSL Verification Badge ===
Contributors: philipjewell
Tags: ssl, verify, verification, badge, secure, certificate
Requires at least: 3.4
Tested up to: 4.7.2
Stable tag: 4.7
License: SSLVB_LICENSE
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Plugin will display the current status and certificate issuer for your SSL certificate in the footer of your site.

== Description ==

Enable and forget! Once the plugin is active, it will place a badge/bar in your site's footer that displays the current status and certificate issuer for your SSL certificate to notify visitors that your site is secure and who it was verified by. When active, the badge will serve as a link to SSL Shopper to backup the plugin.

== Installation ==

1. Upload `ssl-verification-badge.zip` to the `/wp-content/plugins/` directory
2. Unzip the compressed file
3. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently Asked Questions ==

= What SSL providers will this plugin work with? =

Any! The plugin captures the current certificate(s) that are on the server the domain points to. Pulls the domain(s), the certificate issuer and the dates on the certificate just like your browser does when visiting the site. No matter who you are hosted with or have your SSL with, it will find the current info from the server.

== Screenshots ==

1. This screen shot description corresponds to screenshot-1.(png|jpg|jpeg|gif). Note that the screenshot shows a site secured by an SSL. 
2. This screen shot description corresponds to screenshot-2.(png|jpg|jpeg|gif). This screenshot shows a site with an expired SSL certificate. 
3. This screen shot description corresponds to screenshot-3.(png|jpg|jpeg|gif). Note that the screenshot shows a site that doesn't match any SANs on a current certificate or simply not secured by an SSL yet. 

== Changelog ==

= 1.0 =
* Corrected php errors for the subjectAltName array.

= 0.2-beta =
* Removed pointless tab from within wp-admin to prevent PHP WARNING messages.
* Provide links to free SSL providers if site does not have one.
* Updated the color scheme for the secured result.

= 0.1-alpha =
* First attempt to release out into the wild.
