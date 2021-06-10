---
title: Creators
layout: cloud
permalink: /creators.html
cloud-fields: creator # set the field to be featured in the cloud (if left blank, none will be generated)
cloud-min:  # min size for subject cloud, too many terms = slow load time!
cloud-stopwords:
---

## Browse by Name

Use this word cloud visualization to browse videos by creator.
Word size is determined by the number of videos created.

## Browse by Major/Minors
<div id="cloud" class="text-center my-4 bg-light border rounded p-2"></div>
{% include js/cloud-js.html fields="major-minor" %}
