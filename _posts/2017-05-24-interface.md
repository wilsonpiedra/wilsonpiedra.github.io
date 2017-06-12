---
layout: post
title:  "One interface"
date:   2017-05-18 18:28:58 -0300
categories: hci
---

Incorporate admin functions into the public interface
Admin screens — the screens used to manage preferences, people, etc. — have a tendency to look like crap. That's because the majority of development time is spent on the public-facing interface instead.

To avoid crappy-admin-screen syndrome, don't build separate screens to deal with admin functions. Instead, build these functions (i.e. edit, add, delete) into the regular application interface.

If you have to maintain two separate interfaces (i.e. one for regular folks and one for admins), both will suffer. In effect, you wind up paying the same tax twice. You're forced to repeat yourself and that means you increase the odds of getting sloppy. The fewer screens you have to worry about, the better they'll turn out.
