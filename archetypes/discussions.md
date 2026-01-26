---
# date: YYYY-MM-DDT19:30:00-05:00
date: {{ .Date }}

# Change to false before publishing
draft: true

# title: Week # | Discussion Questions
title: {{ replace .File.ContentBaseName "-" " " | title }}
---
<!-- Update the Pastors.ai Link (if one is provided). The link does not require quotes around it. -->

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