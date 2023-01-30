# Iray Thumbnail Creator
Daz project's default thumbnail is too bad. So this one can render your thumbnail with iray.  

This script will render an iray image as current scene's or user selected file's thumbnail. 

# Version
0.2

# Daz forum
There are screenshots in Daz forum:  
[https://www.daz3d.com/forums/discussion/451746/free-script-iray-thumbnail-creator](https://www.daz3d.com/forums/discussion/451746/free-script-iray-thumbnail-creator)  



# How to use
## Prepare
* Copy script to your Daz Lib's script folder
* In Daz Studio, find this script from Content Library, right click it, select: "**Create Custom action**", click "Accept".
* Now this script can be run from menu->Scripts
* Thumbnail size is 256x256, if you like 512x512 better, you can just edit script, change "thumbnailSize"'s value from 256 to 512.  


## Use it
* This script offers 2 choices:
    - Create Iray thumbnail for current scene
    - Or, for a file you selected from Content Library

* Right click your file, select "Refresh" to check the result.

## Notice
* If you don't run this script as Custom Action, after you click this script, your selected file will always be this script, not your scene file. Which makes it won't work.  

## How it works
* It will save your render setting, then change render setting to render a 256x256 png image as thumbnail.
* After that, it will restore your render setting.


# Update Log
## 0.2
* Now script will set iray's render setting->Max Samples to 100 automatically, and restore it after rendering.
* Script will also set "Rendering Quality Enable" to "false" and "Post Denoiser Start Iteration" to 100, to make "Max Samples" works, also will restore them after rendering.
