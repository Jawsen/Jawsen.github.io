---
layout: default
title: "Narcotics in San Francisco"
---

# Narcotics and Drug Use in San Francisco

_A data-driven story exploring drug/narcotic-related crime patterns in San Francisco._

---

## Introduction

San Francisco has long struggled with drug/narcotic-related crimes. In this story, we are going to explore when and where these crimes occur and how trends have shifted over time. Our analysis will focuse on the period from 2009 to 2019.
The dataset used in this analysis contains detailed records of crime incidents reported in San Francisco between 2009 and 2019. Each row represents a single crime incident and includes information such as the date and time of the incident, the type of crime, a short description, the day of the week it occurred, the police district it was reported in, and the geographic coordinates (latitude and longitude). The data was cleaned and filtered to focus on selected categories of crime in order to uncover meaningful patterns and trends across time and space. This dataset was originally sourced from the City of San Francisco’s open data portal and has been widely used for urban safety research and public policy analysis.

---

## Trend Over Time
To begin understanding how narcotics-related incidents unfolded, we’ll first examine when they occurred. Did they spike in certain years? Was crime seasonal? The calendar heatmap below reveals these temporal dynamics.

![Calendar Heatmap of Drug/Narcotic Crime in SF](/assets/images/calendar_plot.png)

_Figure 1: Calendar plot showing daily drug/narcotic incident frequency from 2009–2019 in San Francisco._

The calendar visualizes a detailed year-by-year overview of drug/narcotic-related incidents. Each row represents a calendar year, and each square represents a single day. Color intensity (shades of green) reflects the frequency of incidents, where darker green indicates higher crime counts.

What stands out is the dense clustering of incidents in 2009, especially around early spring and summer. This suggests drug and narcotic related crime was not only more prevalent but also more consistent throughout the year.

From 2014 onward, the green fades significantly. By 2018–2019, the calendar is mostly pale — a visual confirmation of the steady decline in drug/narcotic offenses over the decade.

---

## Where Do These Crimes Occur?
Beyond when they happen, it’s important to look at where these incidents take place. The following heatmap shows the physical distribution of drug-related crime across the city.

Here’s a map showing the hotspots of drug/narcotic related-crime across San Francisco neighborhoods.

<iframe src="/assets/interactive_map.html" width="100%" height="600" style="border:none;"></iframe>
_Figure 2: Interactive heatmap showing the spatial distribution of drug/narcotic-related incidents across San Francisco neighborhoods._

The geospatial heatmap visualizes the geographical distribution of drug/narcotic-related crimes in San Francisco. Areas with higher concentrations of incidents appear in warmer colors (yellow to green), while lower activity is shown in cooler tones (blue to purple). Because the map is citywide, specific hotspots may be difficult to distinguish at first glance but zooming in reveals clearer clusters of activity. Some of the most prominent hotspots emerge around the Tenderloin, Mission, Southern, and Bayview districts.

## Comparing Crime Across Neighborhoods

To put drug-related crime in perspective, we looked at how it compares to another common offense: assault. The chart below allows you to explore incident counts by police district and see how these two crime categories differ in their geographic distribution.

<iframe src="/assets/bokeh.html" width="100%" height="600" style="border:none;"></iframe>
_Figure 3: Bokeh interactive chart comparing drug/narcotic and assault incidents by police district._

What becomes clear is that drug-related incidents are highly concentrated in specific districts, particularly the Tenderloin while assault incidents are more evenly spread across the city. This difference highlights how certain neighborhoods may face unique challenges related to drug activity, while others experience broader patterns of violence or disorder. The persistent prominence of the Tenderloin in drug-related crime reinforces its role as a long-standing hotspot, potentially shaped by overlapping factors such as housing, public health infrastructure, and socioeconomic conditions.

---

## Findings

The visualizations reveal a clear temporal and spatial pattern in drug/narcotic-related crime across San Francisco.

In the calendar heatmap, we see that drug-related incidents peaked sharply in 2009, with frequent daily activity especially during the spring and summer months. Over the years, incident counts began to decline — and by 2018–2019, most days recorded little or no activity. This trend suggests a gradual shift in either public behavior, policing practices, or policy emphasis.

Geographically, the folium heatmap shows that drug activity is not evenly distributed across the city. Instead, it clusters in specific neighborhoods — particularly the Tenderloin, Mission, Southern, and Bayview districts. These areas consistently show high densities of incidents across the 10-year span, indicating persistent hotspots.

Finally, the interactive Bokeh chart reveals how drug-related incidents are highly concentrated in certain police districts, while other offenses such as assault are more evenly distributed. This contrast helps highlight how drug-related crime is shaped by spatial and perhaps socioeconomic dynamics that differ from other types of crime.

---

## Conclusion

Taken together, the data tells a story of concentrated but declining drug-related crime in San Francisco between 2009 and 2019. While the number of incidents has significantly decreased — especially after 2014 — the geographic footprint of drug activity remains largely unchanged. The same neighborhoods continue to bear the brunt of narcotics-related crime, raising questions about the underlying structural and social factors at play.

This downward trend could reflect a range of influences: changes in public health policy, shifts in law enforcement priorities, or evolving community dynamics. However, without resolution or arrest data, we can't say whether these incidents resulted in enforcement actions or other interventions.

More importantly, the data offers a starting point for deeper inquiry. Why do certain neighborhoods remain consistent hotspots? How might urban planning, housing, or public health services play a role? And how can policymakers ensure that the decline in incidents leads to lasting improvements for affected communities?

---

_Created by Jawahir, Alec and Aya— Data source: San Francisco Open Data Portal_

