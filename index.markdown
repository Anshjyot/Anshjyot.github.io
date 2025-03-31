---
layout: post
title: "Mapping San Francisco's Drug Crisis: A War on Drugs or a War on the Visible?"
date: 2025-03-31
permalink: /
show_excerpts: false
---


San Francisco has long been a focal point in America’s evolving relationship with drug policy—praised for progressive harm reduction strategies, but also criticized for its visible public health crises. In recent years, the city has made headlines again—not for innovation, but for a sudden spike in arrests. With political promises to “take back the streets,” the question arises: is the city addressing a drug crisis, or staging a war on visibility?

In this story, we turn to the San Francisco Crime Dataset to better understand this shifting landscape. Exploring how drug-related arrests have changed over time, where they’re concentrated, and what the data reveals about the city’s policing strategies.

---

## 📈 Arrests on the Rise — A Sudden Shift

For much of the 2010s, drug and narcotic-related arrests in San Francisco were on a steady decline. The data suggested a shift in priorities—possibly from aggressive enforcement to harm-reduction and community-based intervention. But that trajectory changed sharply in 2022, when the number of arrests suddenly spiked after more than a decade of falling numbers.

A clearer narrative takes shape when we zoom out and look at the long-term trajectory of drug-related arrests. Over the past two decades, the number of incidents steadily declined—a trend that reflected shifting attitudes toward drug enforcement and perhaps the broader embrace of harm-reduction strategies.

That pattern came to an abrupt end in 2022.
When viewed **year over year**, the data reveals a dramatic shift. 

![Yearly Drug/Narcotic Incidents](assets/images/time_series_plot3.png)

While arrest counts are often interpreted as a sign for crime severity, the data in this case may be telling a different story: What looks like a spike in drug-related arrests may have less to do with a rise in drug use and more to do with a shift in how the city is policing. The sharp uptick points less toward a new crisis and more toward a **renewed emphasis on visibility and control**—especially in areas where the city’s most vulnerable residents live.

This surge aligns with a significant shift in city policy. In December 2021, Mayor London Breed declared a 90-day state of emergency in the Tenderloin District, citing rising overdoses and deteriorating street conditions. In the months that followed, her administration took a more assertive approach—culminating in mid-2023 with the creation of a **unified command center** to coordinate law enforcement efforts across city and state agencies ([Los Angeles Times](https://www.latimes.com/california/story/2021-12-17/san-francisco-mayor-state-of-emergency-overdoses-in-tenderloin-district)).

According to a [San Francisco Chronicle](https://www.sfchronicle.com/sf/article/sf-drug-crackdown-dealers-18561747.php) report from late 2023, nearly **700 people** were arrested for selling drugs in just six months under this joint initiative, with more than **900 suspected dealers** arrested in the Tenderloin and SoMa alone that year—almost double the number from 2022. Another **800 individuals** were arrested for public drug use. Public messaging emphasized safety and neighborhood revitalization, but critics argue this campaign disproportionately affected unhoused individuals and those struggling with addiction, while offering few long-term solutions. Public messaging around the campaign emphasized safety and visibility—but critics argue that this enforcement-first approach may disproportionately target those already most vulnerable: unhoused individuals, people in recovery, or those simply caught using in public spaces. The mayor’s initiative, framed as a public safety effort, led to an increase in visible enforcement across the city. The data raises a critical question: are these enforcement spikes targeting major dealers, or simply sweeping up the most visible users?

What the time series reveals isn’t just a policy shift—it’s a story of visibility, power, and where a city chooses to act.


---

## 🗺️ Geography of Enforcement — The Same Neighborhoods, Over and Over

To understand where the crackdown is playing out, the geographic distribution of drug-related arrests across the city has been mapped using two spatial perspectives.

The first, a **choropleth map**, highlights arrest concentration per police district across the city. The color scale gives a visual cue: dark red areas represent districts with the highest number of arrests, while lighter shades indicate fewer. The exact arrest counts are shown next to the scale, giving a clearer sense of just how concentrated the activity is in certain areas. The **Tenderloin** emerges as a clear hotspot, but it’s far from the only one. Elevated arrest counts are also seen in Mission, Southern, and Bayview districts. These areas include or border well-known hotspots such as:

    UN Plaza and Civic Center BART (Southern District)

    SoMa (South of Market) (Southern & Mission Districts)

    24th Street Corridor (Mission District)

![Drug/Narcotic Crime Hotspots](assets/images/drug_choropleth.png)

What many of these locations share is a dense presence of public housing, homeless shelters, and support services—which some argue has led to disproportionate policing of visible poverty rather than targeting organized drug networks.

According to a report by the San Francisco Chronicle referenced earlier, many of the city's drug arrests in recent years have occurred within feet of harm-reduction centers, this lends weight to critics’ concerns: that enforcement doesn’t necessarily follow the drug trade, but instead concentrates on **where the crisis is most visible**.

An **interactive heatmap animation** illustrates how hotspots have shifted over the past two decades. Each frame shows a year from **2003 to 2024**, capturing the evolving geography of arrests.

<iframe src="assets/images/drug_heatmap_yearly.html" width="100%" height="600" style="border:none;"></iframe>

---

## When and Where? An Interactive Look at Enforcement Patterns


When looking at arrest patterns more in detail, we notice more subtle changes over the years.
The following visualization shows the number of arrests by hours and by districts over the past 20 years. It allows for comparisons between areas of the city, and between different drug policies.

<iframe src="assets/images/bokeh_plot.html" style="width: 110%; height: 500px; border:none;"></iframe>

What stands first out is a consistent rhythm: arrests peak between **afternoon and early evening**, aligning not necessarily with drug activity but perhaps with standard **patrol schedules**. While districts like **Tenderloin**, **Mission**, and **Southern** show consistently high arrest counts, this plot also gives an idea of focus shifts in policies. For example, in the last few years it seems the **Tenderloin** area has been receiving more attention, perhaps because of its central location.

This tool allows for a deeper exploration of shifts in policing over time—zooming in on patterns that may reflect citywide strategies or district-level decision-making. It invites us to investigate: does the data support the narrative of a public health intervention, or one of targeted enforcement?

---

## 🎯 Conclusion: Managing a Crisis, or Managing Visibility?

Through this data, a familiar story unfolds—one that’s been told in cities across America. San Francisco’s arrest patterns don’t merely track crime; they track social vulnerability, public perception, and politics.

Despite a dramatic rise in arrests, there is little evidence of increased investment in **treatment**, **rehabilitation**, or **housing**. Instead, the focus remains on managing what the public sees. As one harm-reduction advocate noted, “We’re not solving the crisis. We’re just pushing it around the corner.”

This story doesn’t end with data. But it does begin to reveal who bears the weight of the city’s choices—and where the real work still needs to be done.

---

## 📚 References

1. **San Francisco Chronicle**. [SF’s new crackdown on drug markets leads to spike in arrests.](https://www.sfchronicle.com/crime/article/sf-drug-arrest-data-dealers-users-police-20217830.php)  

2. **San Francisco Chronicle**. [SF drug crackdown: nearly 700 arrested in 6 months.](https://www.sfchronicle.com/sf/article/sf-drug-crackdown-dealers-18561747.php)  

3. **KQED News**. [Why 40 SF drug arrests led to no charges.](https://www.kqed.org/news/12033114/sf-police-made-40-arrests-market-street-raid-why-was-no-one-charged)  

4. **Los Angeles Times**. [SF Mayor declares Tenderloin emergency.](https://www.latimes.com/california/story/2021-12-17/san-francisco-mayor-state-of-emergency-overdoses-in-tenderloin-district)  

5. **OpenStreetMap**. Used for verifying geolocations near shelters and transit stations. [https://www.openstreetmap.org/](https://www.openstreetmap.org/)  

6. **Segel, E., & Heer, J.** (2010). *Narrative Visualization: Telling Stories with Data.* IEEE Transactions on Visualization and Computer Graphics.


---

*Last updated: March 31, 2025*

