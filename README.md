news
====

Module to implement news functionality.

--------------------------------------------------------------
Designed to create News content type.

This module create fields for news content type. 
This module provide views blocks and pages which is listed 
under blocks.

Installation
------------

  * Copy the whole "news" directory to your modules directory - "sites/all/modules"
  * Enable the module - "admin/modules"
  * Set your desired permissions at -"admin/people/permissions"

Usage
-----
   
 * Go to /admin/structure/types where you will see News bundle.
   (structure >> content types >> news)
 * For creating news go to "node/add/news" and create News.

Feature fields
--------------

-node-news-body

Blocks
----------------

1) View: News Listing: Recent News 
	 (Recent 3 News content items on node page of a news item except the current node)
	 
2) View: News Tags
	 (List 10 tags associated with news)

Views
-----------------------------------------------------------
1) News Listing
	 (List all news items)
	 
2) News Tags
   (List all news tags)
