
---

# Week 13: Making Sense of Messy Data

**Date:** April 10  
**Phase:** Wrangling the Data  
**Approach Used:** Troubleshooter

## Your Reflection

This week was easily one of the most difficult so far, but also one of the most important in terms of understanding what real data work actually looks like. Chapter 13 focused on data wrangling in R, and the assignment forced us to take a messy dataset and turn it into something usable, clean, and ready for analysis. At first, it looked simple on paper, but once I started working in RStudio, I quickly realized how many small issues can exist in raw data.

The biggest challenge for me was diagnosing all the problems in the dataset. Missing values, duplicate rows, inconsistent labels, and strange numeric values all showed up, and it took time to figure out how to identify each issue properly using functions like `summary()`, `distinct()`, and `janitor::clean_names()`. Even when I found the problems, deciding how to fix them wasn’t always straightforward.

One of the most frustrating parts was standardizing category labels. Some values looked similar but were written differently, so I had to use `str_to_lower()` and `case_when()` carefully to make everything consistent. I also had to think about when to replace values with NA and when to impute missing data using medians, which required me to slow down and justify every decision instead of just fixing things quickly.

Converting variables into factors was another step that helped me understand how important structure is for later analysis. It made me realize that cleaning data isn’t just about fixing errors, it’s about preparing the dataset so that future analysis doesn’t break or produce misleading results.

Overall, this assignment was tough, but it made the concept of “wrangling data” feel real. I now understand why clean datasets are so valuable, because most of the work happens before any actual analysis even begins.

---

**Tags:** #journal #week13
