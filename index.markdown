---
layout: post
title: "Mapping San Francisco's Drug Crisis: A War on Drugs or a War on the Visible?"
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
When viewed **year over year**, the data reveals a dramatic shift. After years of decline, drug arrests rose nearly **40%** in 2022 alone. The timing aligns with a high-profile crackdown led by Mayor Daniel Lurie, aimed at dismantling open-air drug markets in neighborhoods like the **Tenderloin**. The mayor’s initiative, framed as a public safety effort, led to an increase in visible enforcement across the city.

![Yearly Drug/Narcotic Incidents](assets/images/time_series_plot3.png)

While arrest counts are often interpreted as a proxy for crime severity or prevalence, the data here may be telling a different story: one shaped not by a surge in drug use, but by a significant change in policing policy. The sharp uptick points less toward a new crisis and more toward a **renewed emphasis on visibility and control**—especially in areas where the city's most vulnerable residents live.

This surge coincides with a significant change in city policy. In mid-2022, newly elected Mayor Daniel Lurie launched a citywide crackdown on open-air drug markets, focused heavily on neighborhoods like the **Tenderloin**, long known as an epicenter of visible substance use. According to the [San Francisco Chronicle](https://www.sfchronicle.com/crime/article/sf-drug-arrest-data-dealers-users-police-20217830.php), arrests for minor drug offenses rose by nearly **40%**, with many involving unhoused or low-income individuals. Public messaging around the campaign emphasized safety and visibility—but critics argue that this enforcement-first approach may disproportionately target those already most vulnerable: unhoused individuals, people in recovery, or those simply caught using in public spaces.

While the policy shift was framed as a public safety measure, the data raises a critical question: are these enforcement spikes targeting major dealers, or simply sweeping up the most visible users?

What the time series reveals isn’t just a policy shift—it’s a story of visibility, power, and where a city chooses to act.


---

## 🗺️ Geography of Enforcement — The Same Neighborhoods, Over and Over

To understand where the crackdown is playing out, we mapped the geographic distribution of drug-related arrests across the city using two approaches.

The first, a **choropleth map**, highlights arrest concentration per police district across the city. The **Tenderloin** emerges as a clear hotspot, but it’s far from the only one. Elevated arrest counts are also seen in Mission, Southern, and Bayview districts. These areas include or border well-known hotspots such as:

    UN Plaza and Civic Center BART (Southern District)

    SoMa (South of Market) (Southern & Mission Districts)

    24th Street Corridor (Mission District)

![Drug/Narcotic Crime Hotspots](assets/images/drug_choropleth.png)

What many of these locations share is a dense presence of public housing, homeless shelters, and support services—which some argue has led to disproportionate policing of visible poverty rather than targeting organized drug networks.

According to a report by the San Francisco Chronicle referenced earlier, many of the city's drug arrests in recent years have occurred within feet of harm-reduction centers, this lends weight to critics’ concerns: that enforcement doesn’t necessarily follow the drug trade, but instead concentrates on **where the crisis is most visible**.


We also built an **interactive heatmap animation** to explore how hotspots have shifted over the past two decades. Each frame shows a year from **2003 to 2024**, capturing the evolving geography of arrests.

<iframe src="assets/images/drug_heatmap_yearly.html" width="100%" height="600" style="border:none;"></iframe>

---

## When and Where? An Interactive Look at Enforcement Patterns

WRITE SOMETHING HERE USING BOKEH

USE Iframe.

MAYBE something with time or whatever: Inspiration below:

What stands out is a consistent rhythm: arrests peak between **afternoon and early evening**, aligning not necessarily with drug activity but perhaps with standard **patrol schedules**. Meanwhile, districts like **Tenderloin**, **Mission**, and **Bayview** show consistently high arrest counts, though the intensity fluctuates year to year.

This tool lets us explore shifts in policing over time—zooming in on patterns that may reflect citywide strategies or district-level decision-making. It invites readers to investigate: does the data support the narrative of a public health intervention, or one of targeted enforcement?

---

## 🎯 Conclusion: Managing a Crisis, or Managing Visibility?

Through this data, a familiar story unfolds—one that’s been told in cities across America. San Francisco’s arrest patterns don’t merely track crime; they track social vulnerability, public perception, and politics.

Despite a dramatic rise in arrests, there is little evidence of increased investment in **treatment**, **rehabilitation**, or **housing**. Instead, the focus remains on managing what the public sees. As one harm-reduction advocate noted, “We’re not solving the crisis. We’re just pushing it around the corner.”

This story doesn’t end with data. But it does begin to reveal who bears the weight of the city’s choices—and where the real work still needs to be done.

---

## 📚 References

1. **San Francisco Chronicle**. [SF’s new crackdown on drug markets leads to spike in arrests.](https://www.sfchronicle.com/crime/article/sf-drug-arrest-data-dealers-users-police-20217830.php)

2. **OpenStreetMap**. Used for verifying geolocations near shelters and transit stations. [https://www.openstreetmap.org/](https://www.openstreetmap.org/)

3. **Segel, E., & Heer, J.** (2010). *Narrative Visualization: Telling Stories with Data.* IEEE Transactions on Visualization and Computer Graphics.

---

*Last updated: March 26, 2025*

