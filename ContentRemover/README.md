# ContentRemover
If you installed a Daz product without Install Manager, you gonna find out it is very hard to remove it. If you installed a lot of products like this, your Daz library gonna be a mess.  

This script, will try to remove your selected product file in content library with its data and image files.  

Select a product file in Content Library, then this script will Remove the Whole Product From Disk, including all related files and folders in data and runtime folder. So you can clean your Content Library very easily.  


# Version
0.5

# Notice
* This script will try not to delete anything on Genesis x Base folders and library base folders. But there are some bad and old products, may link to an official folder I may not know. So, even I tested this script again and again, use it at your own risk.  


* In a few cases, nothing gonna happen after you running this script. That's because the product you selected has an info.duf file, and its content is not json data, so this script failed to parse it. Just delete this info.duf file, then run this script again. 

* There are some bad product creators, put all their products' data into the same folder. Even uses same data files in multiple products. But this script can not know that. So, if you remove a product like this, other prodcuts from the same creator may not work anymore. You have to re-install them.  


# Tip
* Run this script from Script IDE Pan will show all the details about which folders are handled.



# How to use
## Prepare
* Copy script to your Daz Lib's script folder
* In Daz Studio, find this script from Content Library, right click it, select: "Create Custom action", click "Accept".
* Now this script can be run from menu->Scripts

* If you don't run this script as Custom Action, after you click this script, your selected file will always be this script, not the product file. Which makes it won't work.  


## Use it
* Select a product file you want to delete from content library.
* Select this script from Menu->Script
* Then this product will be removed with its images, data, uv and morph files.


## Daz forum
[https://www.daz3d.com/forums/discussion/comment/7173531/](https://www.daz3d.com/forums/discussion/comment/7173531/)  




# Update Log
## 0.5
fix more bugs

## 0.4
Now it can only remove used texture files, won't remove the whole texture folder. So, it won't remove other product's texture file by mistake.

## v0.3
Add more morph folders into protected folder list.

## 
Add Genesis x Base's detail morph's folder into protected folder list.




