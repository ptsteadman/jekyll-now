---
layout: post
title: How To Make Visual Studio Insert Spaces for Newline Indents
published: false
---
It's really annoying when Visual Studio shows you this:

But the plain text files on github look like this:

If you use the "show whitespace" Visual Studio chord (CTRL-R, CTRL-W), 
you'll see that visual studio inserts tabs instead of spaces by
default for newline indent:

Visual Studio displays tabs as having the same 
width as four spaces.  But if you're collaborating with someone working 
in another text editor like vim, your automatically-inserted tabs will
appear larger than four spaces.

How to fix:


Better:
