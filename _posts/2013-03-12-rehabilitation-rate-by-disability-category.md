---
title: Rehabilitation Rate by Disability Category
author: kartik
layout: post
categories: [rehabilitation rate]
---
<p>The rehabilitation rates for each type of disability at agency level were generated using RSA-911 FY2011 personal level data following these steps. Individuals were categorized into nine mutually exclusive disability groups (Visual, Hearing, Orthopedic, Intellectual, Substance abuse, Mental health, Learning disability, Traumatic brain injury and Other) based on the primary impairment and cause of primary impairment reported. Nine dichotomized dummy variables were created.</p>


<p>Individuals were categorized into two mutually exclusive outcome groups—closed after an employment outcome with an IPE (Status 26) and no employment outcome with an IPE (Status 28). Two binary dummy variables were created for these two groups. We then created our new variable by multiplication of the disability group with the outcome group:
Disability type with Status 26 (i.e. Visual x Status 26)
Disability type with the sum of Status 26 and Status 28 (i.e. [Visual x (Status 26 + Status 28)]
</p>
<p>We aggregated the sum of the two set of interactions calculated from previous step to get agency level data from personal level data.
Finally, rehabilitation rate was calculated by dividing the total number of status 26 of a specific disability by the total number of IPEs (status 26 + Status 28) of that specific disability (i.e. ∑(Visual x Status 26) / ∑ [Visual x (Status 26 + Status 28)].</p>

<div><iframe width="760px" height="646px" frameborder="0" scrolling="no" src="https://opendata.socrata.com/w/3ggm-6fg4/y34g-bnf3?cur=IQXOrUeYPQ9&amp;from=root"></iframe><a href="http://www.socrata.com/" target="_blank">Powered by Socrata</a></div>
<p>Source: RSA-911 FY2011</p>