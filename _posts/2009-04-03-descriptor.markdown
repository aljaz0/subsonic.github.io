---
layout: post
title: "Descriptor"
---

# Descriptor #

A __"Descriptor"__ in SubSonic parlance is the first string value in a database that is not a foreign-key field . This value is _assumed_ to be some type of descriptive value for the data in that row.

Using a __Product__ table (like the one _below_) as an analogy the primary key would (normally) be the first field (like ProductID in our expample), the ProductName would be the second. SubSonic would consider ProductName to be the Descriptor and would use that for linking and display purposes.

__Example Table__

ProductID | ProductName
--------- | -----------
1         | Milk
2         | Sugar
3         | Bread
