---
layout: post
title: Portfolio with Jekyll
---

In class today, Elise gave a brief presentation (a recap) on tasks that are required to be done, both as a group and individual.

Most of this was about the portfolio for the projects that has been carried out all through the semester. She also emphasised on the need to focus on having a final deliverable ready for submission.

I sought for her help with the portfolio, after spending the previous night on getting my online portfolio jekyll site to function properly without any success.
All attempts to get the site hosted and github pages with a custom theme was to no avail.

After several trials of suggestions from Elise, it appeared that the problem came from the `_config.yml` file.
In the `_config.yml`, the `baseurl` variable was set to null, which means that the `/asset/main.css` file had no location to point to on the site build.

So, realising that, I changed the values of the baseurl to `baseurl: "/refugeehub"`. The `refugeehub` is the repo name for the portfolio on Github.

After doing this, my portfolio was live and presented properly!...(Thanks to Elise!). 

Despite the fact that the site has the default theme - `Minima` rather than a customised, I was still satisfied. 
This is because more time and effort would be needed to override the default theme, which neither do I have before the semester ends. 

However, I planned on researching on how to go about that over the holidays.
