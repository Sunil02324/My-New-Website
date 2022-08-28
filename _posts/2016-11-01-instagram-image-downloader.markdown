---
title: "Instagram Image Downloader"
layout: post
date: 2016-02-21 22:50
image: /assets/images/posts/instagram1.jpg
headerImage: true
tag:
- python
- bs4
- instagram
blog: true
author: suniltatipelly
description: Python Script to Download Images from Instagram
---

My friend has a very bad habit of stalking people on Instagram. You can find him online all the time in Instagram. One day he came to me and asked to write code to download the images from instagram.

I have gone through the source code of instagram and seen that the images are loaded in same way in all pages. So I used BeautifulSoup (bs4) in python to extract the image url from the given post url. I have also added some functionalities like downloading images from various Urls single time, specifing download location.

---

### Usage:

insta.py [OPTION] [URL]


### Options:

-u [Instagram URL] Download single photo from Instagram URL

-f [File path] Download Instagram photo(s) using file list

-h, --help Show this help message


### Example:

python insta.py -u https://instagram.com/p/xxxxx

python insta.py -f /home/username/filelist.txt


---

### Code:

<script src="https://gist.github.com/Sunil02324/91d002d433e56c726a9f.js"></script>

---

### Source on Github : [Instagram Image Downloader](https://github.com/Sunil02324/Instagram-Image-Downloader)


Please comment your views/suggestions below.
