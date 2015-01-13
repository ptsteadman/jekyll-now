---
layout: post
title: Adding a Lookup Field to a Page in Dynamics NAV
---
One of the problems I faced in building a non-trivial application that consumed NAV Web Services was figuring out how to "join" fields from different tables.  For example, when exposing a list of jobs from a job table which includes a resource needed for the job, you might need more than just the resource id that's a field in the table: you might also need the resource name and description.  While this is easy to get for one record, what about when you need a few hundred records in a table that has been dynamically filtered?  When exposing a Page as a web service, it's easy to include the fields of the table that the page is based on, but it's less clear how to include fields from another table.




