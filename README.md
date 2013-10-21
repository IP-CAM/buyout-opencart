Buyout - Opencart Button
===============

VQMOD extension - no modifications to your OpenCart

This extension will get the stock to the item to 0 after the checkout is completed on selected items with specific option.

Example: You sell photos
- Option on item: +2500$ to Buy exclusive license
- after the buyer buys the item with this option checked, the item will have stock 0 and will prevent others to buy it assuming the item has the substract option ON and the customer can't checkout with stock 0 items.

Usefull for websites selling:

    photos
    software
    themes
    extensions
    cad items
    others that i didn't think of


If you want to sell items and give the customer option to have the product only for himself (except those already sold) this extension is for you


Documentation
======

Extract the file in your opencart directory. Nothing will be overriden so your theme and opencart will not suffer any changes.


HOW TO USE THIS OPTION
======

Change the following text - Buyout - with your own option name from the following:

if ($order_option['name'] == 'Buyout') {

This can be found on line 29 on /vqmod/xml/buyout.xml

This indication will also be found in the file, telling you what to do Easy!

Sponsored by Julian
