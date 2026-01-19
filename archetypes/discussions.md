---
# date: YYYY-MM-DDT19:30:00-05:00
date: {{ .Date }}

# Change to false before publishing
draft: true

# title: Week # | Discussion Questions
title: {{ replace .File.ContentBaseName "-" " " | title }}
---
**[Meal and Meeting Plan ↗]({{< relref "<!-- UPDATE ME   plans/20260108-Meal Plan.md-->" >}})**

**[Pastors.ai Sermon Page ↗](<!-- UPDATE ME -->)**

## Sermon

{{< collapse summary="**Sermon Summary**">}}

<!-- Insert sermon summary from Pastors.ai here. -->

{{< /collapse >}}

{{< collapse summary="**Revelation 21:1-8**" >}}

> <!-- Insert the sermon passage here -->
>
> *English Standard Version (ESV)*

{{< /collapse >}}

## Discussion Questions

### Question 1

<!-- Question #1 text -->

### Question 2

<!-- Question #1 text -->
### Question 3

<!-- Question #1 text -->



<!-- Use the same collapse language as shown above for specific verse references or cross references contained in the questions. -->