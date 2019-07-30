---
layout: post
title:  "How to use FoxyProxy with Firefox to easily switch through proxies"
---

# How to use FoxyProxy with Firefox to easily switch through proxies

One of the best ways to look for vulnerabilities in a website is by routing traffic through a proxy like Burp Suite, you can discover hidden flaws quickly, but sometimes it's a pain in the ass to turn it on and off manually. But luckily, there is a browser extension called FoxyProxy that automates this process with a single click of a button.

# Why you should use a proxy switcher?

A proxy switcher is a very helpful tool for penetration testers because the time saved messing around with settings can but a better use.

# Adding FoxyProxy to Firefox

Firstly, open firefox and  navigate to the add-ons manager by using `CTRL + SHIFT + p`, then click on "Open menu" button in the toolbar then "Add-ons".

Now click on "find more add-ons" on the "personalize your firefox" page for "Get add-ons", and search for *FoxyProxy*

We will use FoxyProxy Basic as it offers enough functionality for what we need. Alternatively, instead of going through all of the above steps, you can just go directly to FoxyProxy Basic's extension page. 

We can then click "Add to Firefox" to add the extension.

Make sure to hit "Add" on the prompt to allow access to what it needs.

We will then be directed to FoxyProxy's page, which includes a changelog and a bit more information.

# Add a custom proxy

There should now be a little icon in the upper-right area of the browser, next to bookmarks or whatever else is in the toolbar. Click the icon and select "Options" to go to the settings page.

Next, click "Add" to add a custom proxy.

With Burp Suite up and running, go to the "Options" tab under "Proxy." We just want to confirm the default IP address and port since it needs to match in FoxyProxy.

Now we can fill in the information and give it a title to keep things organized.

Click "Save," and our proxy should now appear on the main settings page.

Now, all we have to do is enable it while Burp is running, allowing us to effortlessly switch the proxy on and off or even switch between different proxies. Click the icon and select "Use proxy Burp for all URLs (ignore patterns)" to turn it on.
