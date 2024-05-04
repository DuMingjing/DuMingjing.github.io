---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

## Research Area
- #### Cluster analysis
- #### Time series analysis
- #### Three-way decision

**Note:** *A list of open source code is maintained on [Github](https://github.com/Du-Team). More source code will be released as it is ready for publishing.*

## Grants & Awards
### **Density-based Clustering for Mixed Data Under Open Environment - 2021.1-2023.12**
- *National Natural Science Foundation of China (Youth Program)*
- *No: 62006104*

### **Density-based clustering for mixed data and its application in disease diagnosis - 2020.12-2022.12**
- *Natural Science Foundation of the Jiangsu Higher Education Institutions*
- *No: 20KJB520012*

## Professional Services
### **Journal Reviewer**
- *Pattern Recognition*
- *World Wide Web*
- *Information Sciences*
- *Soft Computing*
- *Complex & Intelligent Systems*
- *Data Technologies & Applications*

## Teaching
- #### Artificial Intelligence
- #### Math for Artificial Intelligence
- #### Introduction to Intelligent Science and Technology




<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}