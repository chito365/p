---
id: 2924
title: 'This error will report itself to end user as 508 error, &#8220;Resource Limit Reached&#8221;.'
date: 2011-05-15T04:15:21+00:00
author: chito
layout: post
guid: https://www.afriqueunique.org/?p=2924
permalink: /2011/05/15/this-error-will-report-itself-to-end-user-as-508-error-resource-limit-reached/
afift-disable:
  - 'no'
afift-disable-set-first:
  - ""
mvp_post_template:
  - temp2
mvp_post_width:
  - default
mvp_img_loc:
  - large
mvp_featured_image:
  - show
mvp_post_gallery:
  - hide
cwp_meta_box_check:
  - 'No'
swp_pinterest_image_url:
  - ""
swp_cache_timestamp:
  - "426287"
post_views_count:
  - "292"
bs_social_share_facebook:
  - "0"
bs_social_share_twitter:
  - "0"
bs_social_share_reddit:
  - "0"
bs_social_share_google_plus:
  - "0"
bs_social_share_linkedin:
  - "0"
bs_social_share_interval:
  - "1568198556"
categories:
  - LEARNING
tags:
  - Hosting
  - internet
---
This error will report itself to end user as**<span class="Apple-style-span" style="color: #ff0000;"> </span><span class="Apple-style-span" style="color: #000000;">508</span><span class="Apple-style-span" style="color: #ff0000;"> </span>**error, &#8220;**Resource Limit Reached**&#8220;. This happens due to customer hitting entry processes limit. Entry processes limit restricts the number of concurrent connections to dynamic (php & cgi) scripts for the customer. Otherwise, one site could use up all Apache slots, and cause all the sites to go down.

<div>
</div>

<div>
  You can diagnose the issue by running:
</div>

<div>
  <pre># lveinfo --period=1d --by-fault=mep --display-username</pre>
</div>

<div>
</div>

<div>
  <p>
    You can also monitor the user by running:
  </p>
  
  <pre># lvetop</pre>
</div>

<div>
</div>

<div>
  You can always increase entry processes limit by running:
</div>

<pre># lvectl set USER_ID -–maxEntryProcs NEW_LIMIT save</pre>

<div>
</div>

<div>
  If you also see that user is hitting CPU limit at the same time at the same time as entry processes limit, raising just entry processes limit will not help.User is using too much resources, and you should either increase both, CPU and entry process limits, or user should optimize their script, or user should be upgraded to VPS or something similar.
</div>

<div>
</div>

<div>
  Be careful adjusting entry processes limit, as it can adversely affect overall system stability.
</div>

<div>
</div>

<div>
</div>