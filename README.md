# Imageparty

This repo is a collection of Jupyter notebooks that accomplish a variety of image filtering techniques. For the moment there is no machine learning involved, we simply paint on top of the images.

## Arabeseque Tiling

Arabesque Tiling.ipynb

Given an input image and a binary image tile with an arabesque pattern, this notebook will:
- add colored tiling to an upper portion of the image
- add colored tiling as a type of vignette
- replace the image as a mosaic of tiles colored with the median of the input image within the tile

## Painting Rainbows

Painting Rainbows.ipynb

This notebook does 3 effects based on k-means clustering of the image colors: 1) paints a vertical rainbow beam of representative colors in the center of the image, 2) paints targets using the same colors in the corners, and 3) tone vignetting: adds a gaussian blurred radial filter of the centroid color bands.

## Rainbowization

Rainbowization.ipynb

This notebook transforms the color palette of input photos into one distributed in hue. There are two effects: 1) Hue shift where the hues are moved along the color wheel and 2) Widen Hue where the hues of color clusters in the image are widening according to their distribution.
 
