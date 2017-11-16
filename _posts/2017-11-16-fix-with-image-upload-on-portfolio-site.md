---
layout: post
title: Fix with image upload on portfolio site
---

I tried up uploading some evidences on my portfolio as adviced by Adon.

So, while in the process, I discovered that the images were not showing up each time I pushed to Github.

After asking Adon for help with this, it appears that the link to the location of the image was missing the `base-url`. I added the absolute path to the imgae location and that fixed it.