---
layout: post
title: Dynamics NAV Web Service Programming Resources
---
Here are some of the resources I found helpful for learning to develop Dynamics NAV web service based applications.

#####C/AL Programming:
[Introduction to CAL Programming](http://www.consultec.es/DocTutoriales/Introduction_to_CAL_Programming.pdf)
This provides a good overview of the basics of CAL programming, which can become necessary in building a web service applications when a custom codeunit or page extension is required.

#####Setting up Web Services:
[Vjecko Web Service Recorded Session](http://vjeko.com/blog/connecting-to-nav-through-web-services-recorded-session)
Vjecko.com has a lot of detailed articles about web service programming, but this older post has a pdf and recorded session that shows how to expose and connect to web services from a .NET application.  Unfortunately, he shows how to create Web Service references in .NET using the now-deprecated Web Refrence method (from .NET 2) instead of the more current Service Reference method.

[Using Service Reference to Connect to Web Services](http://blogs.msdn.com/b/freddyk/archive/2010/01/20/connecting-to-nav-web-services-from-c-using-service-reference-config-file-version.aspx)
This explains how to use Service Reference, using code instead of XML web.config configuration, which I found difficult to configure.  (Each time I updated the service reference, I would have to reconfigure the XML).

#####NAV Upgrade Process
[Migration to SQL Server from C/SIDE Database](http://saurav-nav.blogspot.com/2012/12/nav-2013-upgrade-part-iv-sql-migration.html)
In order to use web services, you don't need to be using the Role Tailored Client, but you must be using the a SQL server based NAV database.  Web Services can be configured and exposed using the Classic Client for SQL Server Databases.
