---
{{ $now := now }}
{{ $dow := $now.Weekday }}
{{ $sunday := $now.AddDate 0 0 (mul $dow -1) }}
{{ $dateValue := print ($sunday | dateFormat "2006-01-02") "T19:30:00" }}
date: {{ $dateValue }}

# Change to false before publishing
draft: true

# title: Week # | Discussion Questions
title: "Week # | Discussion Questions"

cover:
    image: "" # e.g., "img/hugo_logo_wide.svg" or "https://example.com/image.jpg"
    alt: "harvest" # Optional: Add alt text for accessibility
    hidden: false # Optional: Set to true to hide the image on the post page
    relative: false # Optional: Set to true if using page bundles and relative paths

---
<!-- Update the Pastors.ai Link (if one is provided). The link does not require quotes around it. -->

**[Pastors.ai Sermon Page ↗](<!-- UPDATE ME -->)**

## Sermon

{{< collapse summary="**Sermon Summary**">}}

<!-- Insert sermon summary from Pastors.ai here. -->

{{< /collapse >}}

{{< collapse summary="**  <!--SERMON REF. -->  **" >}}

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