---
layout: post
title: "Many to Many"
---

# Many to Many #

Many to Many joins are joins between tables that are "non-structural" and are instead *logical*. 
This means that the relationship is _not necessarily enforced by your database_ engine and must be handled in code for the most part (_this is only sort of true_). 

For instance, if you have a Products table that can have one or more Categories assigned to it, and a Categories with one or more Products assigned to it, you have a __Many to Many__ relationship. To facilitate this structure in your database you need a "joining" or "mapping" table, which has a composite primary key made up of the primary key of the main tables - so in this example it would be ProductID and CategoryID together defining the primary key.  

You don't have to do it this way, but if you do SubSonic will love you for it because we can then spin some magic up for you which is cool, i guess :smile: . Everyone loves magic, right ?
