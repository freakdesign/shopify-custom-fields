Shopify custom fields
=====================

![My image](https://freakdesign-us.s3.amazonaws.com/shopify/custom_fields/i/custom_fields_lrg.png)

This a javascript tool to emulate Custom Fields within the Shopify dashboard. The main use would be for Shopify designers and developers wanting to give their clients a simple way to edit metafields with less confusion.

Do note that there's no interface for a Store Owner to make any new fields using this (simply to avoid explosions) so it's up to you - the developer - to help add them. To add the required metafields you'll need to either use [ShopifyFD](http://shopify.freakdesign.com.au/), the [Shopify API](http://docs.shopify.com/api/metafield), or a metafield [app](https://apps.shopify.com/) of your choice. 


Installation and help
---------------------

tl;dr Use the [Chrome Extension](https://chrome.google.com/webstore/detail/custom-fields-for-shopify/alfplfpobekffinigeidgmmfjollghln).

The Chrome Extension is simply a helper script that loads the files from here. If you don't run Chrome or just prefer to load via a bookmarklet you can follow the instructions on [this page](https://rawgithub.com/freakdesign/shopify-custom-fields/master/installation.html).

A very basic help guide is [available](https://freakdesign-us.s3.amazonaws.com/shopify/custom_fields/freakdesign-custom-fields-for-shopify-guide.pdf).


Support Development
-------------------

If this tool makes you look awesome to your paying customer or helped you land that project, [consider leaving me a tip](http://freakdesign.com.au/pages/shopify-custom-fields). 


Exclusions / notes
------------------

* This tool will NOT show metafields under the Global namespace. This is more of a sanity check than anything else.
* Custom field whitelist is loaded once on load. If you change the whitelist after loading it, you'll need to force refresh.


Custom field markers
--------------------

Add these strings into the value (or key) for added magic. Not all of these work yet so consider them a suggestion only that may change at any time.

* "[a]": limit display to articles only
* "[c]": limit display to collections only
* "[cu]": limit display to customers only
* "[g]": limit display to pages only
* "[o]": limit display to orders only
* "[p]": limit display to products only

* "[_c]": mark as a collection field
* "[_f]": mark as a file field
* "[_i]": mark as an integer field
* "[_g]": mark as a page field
* "[_p]": mark as a product field
* "[_d]": mark as a number field
* "[_n]": mark as a date field
* "[_co]": mark as a color field
