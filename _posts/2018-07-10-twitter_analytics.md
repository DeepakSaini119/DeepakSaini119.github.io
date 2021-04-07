---
layout:     post
title:      Twitter Analytics System
date:       2018-07-10
summary:    Some details about the MTP project.
categories: Projects
thumbnail: cogs
tags:
 - M.Tech Thesis
 - System Design
 - Twitter Analytics System
---


![TwitterAnalyticsLogo](https://i.postimg.cc/jdvYsNK4/Twitter-Analytics-Logo.png)

Joint work with Abhishek Gupta under the guidance of [Amitabha Bagchi](https://www.cse.iitd.ac.in/~bagchi/){:target="_blank"}, [Sayan Ranu](https://www.cse.iitd.ac.in/~sayan/){:target="_blank"}, [Srikanta Bedathur](https://www.cse.iitd.ac.in/~srikanta/){:target="_blank"} 
<br>
<br>
Twitter generates millions of tweets each day. A vast amount of information is hence available for different kinds of analyses. The end users of these analyses however, may or may not be technically proficient. This necessitates the need of a system that can absorb such large amounts of data and at the same time, provide an intuitive abstraction over this data. This abstraction should allow the end users to specify different kinds of analyses without going into the technicalities of the implementation.

Our aim here is to build a system that tries to meet precisely the above needs. Running on streaming data, the system provides an abstraction which allows the user to specify real time events in the stream, for which he wishes to be notified. Also, acting as a data-store for the tweet network, the system provides another abstraction which allows the user to formulate complex queries on this historical data.

You can find the final presentation that we made as part of the thesis defense [here](https://docs.google.com/presentation/d/1loqvxicfwagtSwh-7bAZi7PO1oaUr4LiRA7YIdPo5fU/edit?usp=sharing){:target="_blank"} and the detailed documentation about the system [here](https://drive.google.com/file/d/1EYJyq41A7mn53hrRohFkVYtmdqr8lamZ/view?usp=sharing){:target="_blank"}.