---
layout: post
title: Dynamics NAV: How to Add a Lookup Field to a Page
---

The documentation to MS Dynamics NAV 2009/2013 includes a tutorial on how to expose web services from within NAV, and how to create a few trivial applications that consume these web services.  
But I was unable to find examples of how to create a more complicated application, one that uses multiple different pages and code units, loads a significant amount of data, and lets the user modify records.  

Some questions I found myself asking:
- Should I use the web services directly, or build a data access object? 
- How to handle exceptions?
- How should I buffer large amounts of data?
- How do I synchronize model changes between NAV, the server side .NET code, and client side javascript?
