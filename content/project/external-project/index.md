---
title: On-demand Meal Delivery Routing Problem
summary: Lejun Zhou, Anke Ye, Simon Hu
tags:
  - Transportation
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Meal Delivery
  focal_point: Smart


# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

Meal delivery services provided by platforms with integrated delivery networks are becoming increasingly popular. We adopt a rolling horizon approach to solve the meal delivery routing problem (MDRP). To improve delivery efficiency in scenarios with high delivery demand, multiple orders are allowed to be combined into one bundle and up to two bundles from two different restaurants can be delivered on one route. Following this strategy, an optimization-based four-stage heuristic algorithm is developed to generate an optimal routing plan in each optimization period. The algorithm first generates bundles according to orders’ spatial and temporal distribution. Secondly, we find feasible bundle pairs. Then, routes for delivering any single bundle or a bundle pair are optimized, respectively . Finally, the routes are assigned to available vehicles. In computational experiments using instances from open datasets, the system’s performance is evaluated in respect of average click-to-door time and ready-to-pickup time. We demonstrate that this algorithm can effectively process real-time information and assign optimal routes to the vehicles. By comparing the proposed method with an existing algorithm and exact solutions generated for a similar scenario, the results indicate that our method can generate solutions with slightly higher service quality and closer to the exact solutions. 
