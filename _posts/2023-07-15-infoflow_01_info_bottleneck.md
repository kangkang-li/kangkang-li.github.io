---
layout: post
title: info-flow 01 - Break the info bottleneck
date: 2023-07-15
categories: [information flow]
---

I am working in a big company and a team not directly facing customers.

The info flows as: customer_escalation-->sales-->analytics/product/platform-->my_team(team leads-->IC(me)).\
When I have the luxury of extra bandwidth to explore complicated but valuable problems, I harvested valuable findings from exploring upstream info, beyond the info I directly received from top-down.

This might be one of the most common problems Engs face, but surprisingly I did not read about this before.\
(LMK if there is a related writing)

![](/images/info_flow_bottleneck.png)

## Info degradation
In an ideal situation, people at each stage of an info flow:
1. Trims all information not related to them **or their downstream teams**
2. Consolidates correlated info
3. Organized the info in a structure for their own tasks

Ideally, all related info is structured from team leads and fed to an IC.

In reality, information degrades at each stage: we never have enough time to read all docs or enough meetings.
* Team leads might not need to collect all info IC might need for a project (could be wrong since I have never been a lead).
* Leads naturally have more projects and less bandwidth in one project than ICs.   
* What's worse, leads could be over-booked or relatively new to a certain problem.

As an IC, I need to sense the level of info degradation, especially for new/complex problems with a long info flow and low bandwidth from leads.

## Find the bottleneck
The processed info is smaller in size, more structured and more related to the task, so we should not only use raw info and ignore info processed at stages in between.

My current understanding: 
> the the key to mitigate info degradation is to find the bottleneck, and allocate my own bandwitdh to widen the info flowing through the bottleneck.


## Pave reverse info-path to upstream
As a common situation, leads at a stage of a top-down info-flow are the bottleneck, and we need to directly reach upstream info.\
By no means we should bypass leads.\
On the contrary, I invest in an additional info path to leads with trimmed and structured info adjusted to the current understanding.

We all have limited bandwidth, and it sounds like alot of investment.\
Still, there are tasks and info worth the effort. 