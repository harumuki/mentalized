---
layout: post
title: Microsoft to be taken seriously?
date: '2002-11-21 12:36:08 +0100'
mt_id: 628
categories:
- technology
---
Yet another critical security hole has been discovered in a piece of Microsoft software. Naturally I want to close that hole, so I download and run the patch. Now I am faced with a dialog telling me that I need to reboot my server after patching.

Are you kidding me? I patch the data access components, which are far from an internal part of the Windows kernel (I am not even sure I use them on the server, but I don't feel like taking any chances) and they want me to shut down a server in production? How can they even suggest it? Doing a quick restart of invidual services I could go along with, but rebooting the server, I don't think so.
