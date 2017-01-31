#About using images in Git/GitHub

Images that are embedded into issues can be dragged and dropped in the GitHub interface, however all other images (eg. in markdown files etc) need to be referenced using a URL (at least as of now). Keeping images in a single directory enables them to be referenced more readily. Sensible file names are highly recommended, preferably without spaces as these are hard to read when encoded.
An identical file, named in two different ways is shown as an example below.
They render in the same way, but the source "code" looks ugly when spaces are used in file names.

Eg. 

| encoding needed | no encoding needed |
| ------------------ | ----------- |
| github%20organizations%20teams%20repos.png | github-organizations-teams-repos.png|
| ![](github%20organizations%20teams%20repos.png) | ![](github-organizations-teams-repos.png)|

In this example, the filename is enough of a 'url' because this file (https://github.com/OHSU-Library/github-tutorial/edit/master/images/about-images.md) and the images are in the same directory https://github.com/OHSU-Library/github-tutorial/edit/master/images.

To reference/embed an image that is *not* in the same directory, a more careful approach is needed.

Absolute path
https://github.com/monarch-initiative/monarch-app/blob/master/image/Phenogrid3Compare.png

In order to size images, use the ````width =```` syntax with the <img src= approach, as per below.

````<img src="https://github.com/monarch-initiative/monarch-app/blob/master/image/Phenogrid3Compare.png" width="53">````

<img src="https://github.com/monarch-initiative/monarch-app/blob/master/image/Phenogrid3Compare.png" width="53">


It is also possible to reference an image using an external URL, in another github repository, or anywhere on the web, however this method can be fragile if the URL changes or could lead to unintended changes. Therefore make your own copies and reference those **unless** 
 - You're  sure that referencing the originals will not end in broken links or surprising content. 
 - Copying the image is prohibited 
 - The images are too large to make copying worth the hassle.
 
For example, it is not clear for how long the image below will manage to persist at this EPA link, or sadly, for how long the image will even be an accurate reflection of the current situation in the arctic. https://www.epa.gov/sites/production/files/styles/microsite_banner/public/2016-12/epa-banner-images/science_banner_arctic.png
 
 ![](https://www.epa.gov/sites/production/files/styles/microsite_banner/public/2016-12/epa-banner-images/science_banner_arctic.png)
