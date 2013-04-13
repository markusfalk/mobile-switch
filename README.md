mf_mobileSwitch
===========================

This script lets user know that you have mobile websites. It asks them if they would like to go to it and if so it remembers this choice. 

User can switch between mobile and desktop Website.

Usage
-----
Include this link on your desktop website:

```html
<a 
  href="mobile.html" 
  class="switch-link" 
  data-website-type="desktop" 
  data-breakpoint="800" 
  data-msg="Zur mobile Website wechseln?" 
  >go to mobile website</a>
```

Include this link on your mobile website:

```html
<a 
  href="desktop.html" 
  class="switch-link" 
  data-website-type="mobile" 
  data-breakpoint="800" 
  data-msg="Zur mobile Website wechseln?" 
  >go to desktop website</a>
```

Then include the script and let it do the trick for you.

data-*
------
* *data-website-type*: lets the script know what the website's current type is
* *data-breakpoint*: the script will ask users to go to the mobile website if their browsers width is below this breakpoint
* *data-msg*: The message you would like to use when the script asks users to go to the mobile website

Known issues
------------

* this approach requires the mobile user to load the desktop website on first visit.