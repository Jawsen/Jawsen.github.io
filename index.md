---
layout: default
title: "Where and when do people get fined — and how can you avoid it?"
---

# 🧭 Welcome — Let’s Talk Fines

_Getting a fines in NYC sucks — but it happens a lot. Ever wondered when and where you're most likely to get one? We looked at thousands of real violations to figure out the patterns behind the fines.
This site breaks down when fines are handed out, where they happen most, and what types of cars get hit the hardest — with interactive maps and charts you can explore yourself._

![New York City Skyline](/assets/images/NYC_skyline.png)

---

## 🕒 When Do People Get Fined?

Turns out, time really matters. Most tickets aren’t random — they spike around weekday mornings, especially during street cleaning hours. You’re a lot safer overnight.
Below, you can explore when fines peak during the day and how it varies by borough.

  <iframe src="/assets/violation_by_hour.html" width="100%" height="600" style="border:none;" ></iframe>

_Figure 1: _


  <iframe src="/assets/fines_by_hour_and_borough.html" width="100%" height="600" style="border:none;" ></iframe>


---

## 📍 Where Are the Hotspots?

Some neighborhoods are way more ticket-heavy than others — and it’s not just about how many people live there.
We adjusted for population to see which areas get the most fines per 1,000 residents. Scroll around the map to see how your neighborhood stacks up.

![Top 10 neighbourhoods with most fines per 1000 residents](assets/images/top_10_neighborhoods_fines_per_1000.png)



<iframe src="/assets/parking_fines_map.html" width="100%" height="600" style="border:none;"></iframe>

This shows how parking fines are spread across NYC — adjusted for population. Darker areas = more fines per 1,000 residents. Zoom around and hover to see which neighborhoods get fined the most.



---

## 🚘 Who’s Getting Fined?

Are certain cars fined more than others? The short answer is: yes.
Sedans, SUVs, and vans top the list - might be cause they're common veichle types🧐 

We also looked at the most fined car makes — and some violations are much more common for certain types of vehicles.

<iframe src="assets/top_vehicle_makes.html" width="100%" height="600" style="border:none;"></iframe>
<iframe src="assets/top_vehicle_body_types.html" width="100%" height="600" style="border:none;"></iframe>
<iframe src="assets/top_violations_by_body_type.html" width="100%" height="600" style="border:none;"></iframe>


## 🧠 Can We Predict Where You'll Get Fined?

We trained a simple machine learning model to see if we could predict which neighborhoods are high-risk for tickets — just based on population and total fines.
It actually did pretty well, hitting 87% accuracy. The chart below shows what the model focused on most.

We also grouped neighborhoods into 3 clusters based on their population and fine rates. This helps us spot patterns — like which areas have lots of people but relatively fewer fines, and which ones get hit harder per person.

🟢 Cluster 0: Big population, moderate fines
🟠 Cluster 1: Smaller areas, fewer fines
🔴 Cluster 2: High fine rates per person — the real hotspots

You can explore the map below to see which neighborhood falls into which group. Click around to see how NYC neighborhoods were grouped by fine patterns.


<iframe src="assets/nta_clusters_map.html" width="100%" height="500" style="border:none;"></iframe>

---

## Findings

The visualizations reveal a clear temporal and spatial pattern in drug/narcotic-related crime across San Francisco.

In the calendar heatmap, we see that drug-related incidents peaked sharply in 2009, with frequent daily activity especially during the spring and summer months. Over the years, incident counts began to decline and by 2018–2019, most days recorded little or no activity. This trend suggests a gradual shift in either public behavior, policing practices, or policy emphasis.

Geographically, the folium heatmap shows that drug activity is not evenly distributed across the city. Instead, it clusters in specific neighborhoods particularly the Tenderloin, Mission, Southern, and Bayview districts. These areas consistently show high densities of incidents across the 10-year span, indicating persistent hotspots.

Finally, the interactive Bokeh chart reveals how drug-related incidents are highly concentrated in certain police districts, while other offenses such as assault are more evenly distributed. This contrast helps highlight how drug-related crime is shaped by spatial and perhaps socioeconomic dynamics that differ from other types of crime.

---

## Conclusion

Taken together, the data tells a story of concentrated but declining drug-related crime in San Francisco between 2009 and 2019. While the number of incidents has significantly decreased, especially after 2014, the geographic footprint of drug activity remains largely unchanged. The same neighborhoods continue to bear the brunt of narcotics-related crime, raising questions about the underlying structural and social factors at play.

This downward trend could reflect a range of influences: changes in public health policy, shifts in law enforcement priorities, or evolving community dynamics. However, without resolution or arrest data, we can't say whether these incidents resulted in enforcement actions or other interventions.

More importantly, the data offers a starting point for deeper inquiry. Why do certain neighborhoods remain consistent hotspots? How might urban planning, housing, or public health services play a role? And how can policymakers ensure that the decline in incidents leads to lasting improvements for affected communities?

---

_Created by Jawahir, Alec and Aya— Data source: San Francisco Open Data Portal_
