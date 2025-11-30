---
layout: "../layouts/BlogPost.astro"
title: "Projects"
description: "Some Projects I've Worked On"
---

Welcome, these are a few of the projects I've worked on. I've tried to include a few details about each project, but if 
you have any questions please feel free to reach out.

# My Creations
These are ideas and projects that I've created on my own time for fun, learning, or to scratch an itch.

## [Astro Cloudflare Error Pages](https://github.com/EHLOVader/astro-cloudflare-error)
Cloudflare supports custom error pages, so you can style them to look on brand. You just have to host them somewhere for 
Cloudflare to grab a copy and cache them. With AstroJS and Github pages, it's easy to host these pages and style them too. 

## [bookmarklet.meme](https://bookmarklet.meme)
A simple website that provides bookmarklets for overlaying memes on websites. It's a fun project that
I came up with when I was browsing websites that made me feel the emotion of a meme. I wanted to be able
to share or show that, even if just to me to express the frustration or joy I was feeling at the moment.

## [Cache Checker](https://cache-checker.vercel.app/) ![New](https://img.shields.io/badge/new-FF9900)
A single page tool to check how cache is handled by different systems like Cloudflare, browser, and origin server. It shows
the headers and cache status from each system to help debug caching issues. It was another vibe code project using v0.dev 
to see what could be done quickly with AI assistance. A bit of a WIP but functional for now.

## [Furlaxation](https://furlaxation.vercel.app/) ![New](https://img.shields.io/badge/new-FF9900)
A single page app designed to help train dogs to be calm and relaxed when there is a lot of distractions around them.
It helps guide you through a relaxation protocol based on the work of [Dr. Karen Overall](https://web.archive.org/web/20240408134659/https://www.karenoverall.com/wp-content/uploads/2020/06/Protocol-for-relaxation_Overall.pdf)
. Built using React and Vite, deployed on Vercel.

## [Is it daylight saving?](https://isitdaylightsaving.com/)
I've often caught myself wondering if were in the saving time or not. I created this site to check based on the user's 
browser timezone if currently the time is saving or standard. [view source at GitHub](https://github.com/EHLOVader/isitdaylightsaving) 

## [Laravel Elixir Livereload](https://github.com/EHLOVader/laravel-elixir-livereload)
Created this NPM package to use livereload in elixir back when that was used. 
Elixir was changed to Mix shortly after I created this package. 

## [pURLs](https://purls-six.vercel.app/) ![New](https://img.shields.io/badge/new-FF9900)
A recreation of a website I'd created at a previous job which helped marketers create and clean up URLs with tracking query
strings, specifically when adding new ones. Occasionally we'd see people add the `?` amongst existing query strings instead of `&`
and we'd lose critical details for tracking campaigns. The first version used Vue.js, I've rewritten it in React before 
but this version was a quick one off using v0.dev to vibe code with AI and see what was possible. It allowed me to add 
some checks for another issue I found, short URLs and redirects losing or changing the query strings before it arrived 
where Google Analytics could read them. You will now see how the query string is treated when using a short URL service.

## [Wadsworth](https://ehlovader.com/wadsworth/) ![New](https://img.shields.io/badge/new-FF9900)
A simple site to generate the URL of a YouTube video that starts after the intro, based on the Wadsworth Constant.

# Collaborations
These are projects that I've contributed to or forked to add features that I needed and have begun to use my fork over the main 
branches of the projects.

## [2023 NYE countdown for  AdaFruit EyeLights LED Glasses](https://github.com/EHLOVader/eyelights_newyear_countdown)
A fork from [willgorman](https://github.com/willgorman) I updated the countdown code to work for the current year and changed the colors. Did a bit of cleaning up too, including the libraries.

## [Context (Chrome extension)](https://github.com/EHLOVader/Context)
A fork of [Context](https://github.com/kdzwinel/Context) Chrome extension that lets you quickly turn on and off groups
of extensions. I added features for more icons from FontAwesome when it was removed from the Chrome store and I'd need
to maintain my own fork anyway. Since manifest v2 was deprecated, I need to upgrade, so it doesn't work. But that work
has already been done by others, so I'll be merging those changes in soon. See other fork from [coing-lab](https://github.com/coing-lab/chrome-context)

## [CSS Specificity](https://ehlovader.com/css-specificity/)
A fork of [CSS Specificity](https://github.com/teleject/css-specificity) it has since [gone offline](http://cssspecificity.com/) and I occasionally like to reference it, the fun explaination of 
specificity in context of The Shining movie is memorable, so I forked it to keep a copy for myself.

## [MeetingBrew](https://meetingbrew-ehlovader.vercel.app/)
A fork of [MeetingBrew](https://meetingbrew.com/) to add support for different hour windows on each day of the selected
range.

## [Who Knows LOL](https://ehlovader.github.io/whoknowslol/)
Back when I was on IRC more frequently, another developer, [Chris White](https://github.com/cwhite92), came up with the
idea for a more intense shrug emoji for when you really don't know. He created it initially and I added some fun effects
like wrapping into block and automatically copying the shrug once you've set it.


