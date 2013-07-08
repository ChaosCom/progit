progit
======

A reworked version of the free ebook at http://git-scm.com/book where the images on your Kindle will be *LEGIBLE*.
In case you want to rebuild the ebook yourself, you'll need to download Amazon's KingleGen from 

http://www.amazon.com/gp/feature.html?ie=UTF8&docId=1000765211

Simply run 
kindlegen.exe -c1 kindlerb.opf -o progit-rework.mobi

where
-c1 is the compression ratio (can range from 0-2, 0 being no compression, 1 default, 2 max compression (would eventually recompress images, so beware))
-o <name> specifies <name> to be the name of the generated file.
