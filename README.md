shopify-custom-fields
=====================

This a javascript tool to emulate Custom Fields within the Shopify dashboard. The tool shows fields based on pre-existing metafields. 

Do note that there's no interface for the Store Owner to make any new fields using this (simply to avoid explosions) so it's up to the developer to help add them.

To add the required metafields you'll need to either use [ShopifyFD](http://shopify.freakdesign.com.au/), the Shopify API, or a metafield app of your choice. 


Installation
------------

tl;dr Use the [Chrome Extension](https://chrome.google.com/webstore/detail/custom-fields-for-shopify/alfplfpobekffinigeidgmmfjollghln).

The Chrome Extension is simply a help script that loads the files from here. If you don't run Chrome or just prefer to load via a bookmarklet you can follow the instructions on [this page](https://rawgithub.com/freakdesign/shopify-custom-fields/master/installation.html).


Requirements
------------

* metafields must be named under the "custom_fields" namespace (though some support has been added for a custom alternative).
* to show the collection dropdown make sure you keyname contains "[_c]"

Custom field markers
--------------------

Add these strings into the key name for added magic. Not all of these work yet so consider them a suggestion only.

* "[a]": limit display to articles only
* "[c]": limit display to collections only
* "[g]": limit display to pages only
* "[p]": limit display to products only
* "[_c]": mark as a collection field
* [_f]": mark as a file field
* [_i]": mark as an integer field
* [_g]": mark as a page field
* [_p]": mark as a product field


To do
-----

* Add custom fields to pages and articles. 
* Get file uploads workings
* Add products and page selectors