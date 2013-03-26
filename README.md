WebUI
=====

We need to create a JS overlay menu system for our domain. I want it to start with just accessing our internal WP and phpBB site. The goal is to use a custom bootstrap theme and then have it extend into the blog+forum, or else simply access the content and repost it.

Second phase goals will be:
* Adding actual Heroku/Cloud JS simulations as a viewable through our domain.
* One or two way information streams to the Reddit API or JSON, Github, then Facebook page, G+, etc.

Late phase:
* Migrate data storage to Mongo where possible.
* Incorporation of web JS tools like Cloud9, and possibly our own home-built content design tools.

=====

As a starting base, we have a theme from wrapbootstrap.com, which we can gut or reskin, I just like the layout and iconography. Plus all the add-ins will be perfect for building a marketplace for users to buy/sell access to their worlds and view their revenue streams.

Here is the demo page on our domain:
http://rsimulate.com/bootstrap/

Github user shibulijack created a custom phpBB theme (proBoot) that incorporates a JS-bootstrap layer and improves the load speed of the page. He also has some useful wordpress plugins:
https://github.com/shibulijack

Which we currently have applied to our forums:
http://rsimulate.com/forums/

Lastly, we have our primary blog, which is the master domain, www.rsimulate.com
For this, I've grabbed the free theme from 320press as a guiding example for how to bridge bootstrap onto WP:
http://320press.com/themes/wp-bootstrap/

The user account for the WP blog is already tied to the phpBB username with this plugin:
http://wordpress.org/extend/plugins/wp-phpbb-bridge/

phpBB should also have some mods that will let us associate it with Facebook and Google accounts, and maybe we can later pass on the OAuth tokens from phpBB to our apps.