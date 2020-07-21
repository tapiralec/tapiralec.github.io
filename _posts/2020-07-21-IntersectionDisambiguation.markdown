---
layout: post
title: "The Importance of Intersection Disambiguation for Virtual Hand Techniques"
date: 2020-07-21 12:24:30
categories: Research VR
tags: Research VR Virtual Reality Computer Science Interaction Enhancement Selection
---

Beyond just finding valuable results, it was awesome getting to mentor two undergraduates and two high school students and help them to get an early academic publication and experience with Virtual Reality research! As always, abstract follows:

Some of the most widely used selection techniques for extended reality (XR) are based on virtual hand interactions. Many existing XR frameworks provide this functionality by default; however, their implementation can differ in slight, but important ways. When preparing to make a selection with a virtual hand technique, a user's desired selection can potentially be ambiguous due to multiple intersections. Systems with varying underlying virtual hand implementations may yield contrasting selections due to resolving multiple intersections differently. This is particularly an issue when objects are smaller in size than the virtual hand representation and in dense environments. To demonstrate the importance of these differences, we present a virtual hand selection study comparing three methods that are currently used in popular XR frameworks for disambiguating selections: Closest Intersected, First Intersected, and Last Intersected. The results of our study show that the Closest Intersected method affords significantly faster selections, significantly fewer incorrect and missed selections, and yields significantly better effective throughput than the other two methods. These results show that using a framework's built-in selection technique can significantly affect an XR application's usability.


[Check out the paper][intersection-paper] for more info!

[intersection-paper]: https://ieeexplore.ieee.org/abstract/document/8943611
