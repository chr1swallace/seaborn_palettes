# seaborn_palette

I really like the colour choice in the [seaborn plotting library for python](https://github.com/mwaskom/seaborn) but I use ggplot2 in R, so I created ggplot2 palettes with those colours. I copied the colour choice directly, so thank you to [Michael Waskom](https://github.com/mwaskom) for creating them with an open license.

These are the colours

<img src="data:image/png;base64,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" /><!-- --></p>



<!-- badges: start -->
[![Travis build status](https://travis-ci.org/chr1swallace/seaborn_palette.svg?branch=master)](https://travis-ci.org/chr1swallace/seaborn_palette)
<!-- badges: end -->

