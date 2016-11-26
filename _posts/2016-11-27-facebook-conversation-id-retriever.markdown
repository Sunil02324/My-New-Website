---
title: "Facebook Conversation ID Retriever"
layout: post
date: 2016-11-27 02:10
image: /assets/images/posts/messenger1.PNG
headerImage: false
tag:
- python
- requests
- json
- messenger
- facebook
blog: true
author: suniltatipelly
description: Python Script to Retrieve Conversation ID of Facebook from Profile ID 
---


This is a support script to the [Facebook Messages Counter](http://suniltatipelly.in/facebook-messages-counter/) I have posted earlier. This can be used to get the conversation ID from the Profile ID. 

I used the same Graph API V2.2 which I have used in the previous post also to retrieve the Conversation ID. You can use the same Access Token generated from the graph explorer. If you haven't generated till now you can generate once from [here](https://developers.facebook.com/tools/explorer/145634995501895?method=GET&path=me%2Finbox&version=v2.2).

Replaces the `<access_token>` from `url` in the script with your access token. Also specify the UserID of the person in `userId`. 

Then start running the script with `python script.py` 

The required conversation ID is printed if the conversation has been initiated before.

The final script is :

<script src="https://gist.github.com/Sunil02324/6248ffaf6ee139535fafccc4035c1f0d.js"></script>

---

### Sample :

<img class="image" src="{{ site.url }}/assets/images/posts/messenger1.PNG" alt="Alt Text" style="display:block;margin:0 auto;">

---

You can checkout the repo [here](https://github.com/Sunil02324/Facebook-Conversation-ID-Retriever). Fork it or Star if you like it. 

You can mail me at <a href="mailto:sunil@suniltatipelly.in">sunil@suniltatipelly.in</a> for any queries or doubts regarding this.
