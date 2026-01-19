---
# date: YYYY-MM-DDT18:30:00-05:00
date: {{ .Date }}

# Change to False before publishing
draft: true

# title: Week # | Meal Plan & Location
title: {{ replace .File.ContentBaseName "-" " " | title }}
---

**[Discussion Questions ↗]({{< relref "<!-- UPDATE ME questions/20260115-discussions.md -->" >}})**

**Location**  
The [FAMILY NAME] Household

**Date**  
MMMM DDth, YYYY

**Dinner Theme**  
[Meal]

Please check the [Small Group Planner](https://docs.google.com/spreadsheets/d/1WQ5QDqlsMrUz3jgV88aPYO7dznOzVaevGZu7B0c5nBY/edit?usp=drive_link) on Google Sheets for dish ideas and sign ups!