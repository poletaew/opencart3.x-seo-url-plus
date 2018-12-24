# SEO URL+ for OpenCart 3.x

## What's new?

This module's based on standard **SEO URL** functionality, but fix link generation.
By default OpenCart 3.x generates SEO link only for following entities:

* `product`
* `category`
* `manufacturer` 
* `information page`

This module extends standar SEO URL module and allows to generate SEO links for any other entities. 
Even for main page (just add key `/` for `common/home` query in admin panel).

In addition, there is a caching now. Which, according to real data tests, speeds up performance by  by 2-3 orders of magnitude (minimum 200 times faster).

## Installation

There are two way of installation:

### Manually uploading files

1. Download zip-archive
1. Extract directory `upload` and move extracted files into your project directory
1. Agree with replacing original files

### Applying git patch (for experienced users)

1. Download `SEO_URL+.patch` only 
1. Use `git apply` to aply the path to your project directory
