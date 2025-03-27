<!-- ---
layout: post
title: "Mapping San Francisco's Drug Crisis: A War on Drugs or a War on the Visible?"
date: 2025-03-26
categories: drugs visualization
---

San Francisco has long been a focal point in America’s evolving relationship with drug policy—often hailed for its harm reduction efforts, but also criticized for its visible public health crises. In recent years, the city has made headlines again—not for innovation, but for a surge in arrests. With political promises to “take back the streets,” the question arises: is the city addressing a drug crisis, or staging a war on visibility?

In this story, we turn to the San Francisco Crime Dataset to better understand this shifting landscape. Through three visualizations, we explore how drug-related arrests have changed over time, where they’re concentrated, and what the data reveals about the city’s policing strategies.

---

## 📈 Arrests on the Rise — A Sudden Shift

For much of the 2010s, reported drug/narcotic offenses in San Francisco were on the decline. That trend reversed dramatically starting in 2022, with the number of arrests spiking in just a single year.

![Insert Time-Series or Bar Chart Here]

This abrupt uptick isn’t happening in a vacuum. In mid-2022, newly elected Mayor Daniel Lurie launched a sweeping crackdown on open-air drug markets—particularly in areas like the **Tenderloin**, long known as an epicenter of visible substance use. According to the [San Francisco Chronicle](https://www.sfchronicle.com/crime/article/sf-drug-arrest-data-dealers-users-police-20217830.php), arrests for minor drug offenses rose by nearly **40%**, with many involving unhoused or low-income individuals.

While the policy shift was framed as a public safety measure, the data raises a critical question: are these enforcement spikes targeting major dealers, or simply sweeping up the most visible users?

---

## 🗺️ Geography of Enforcement — The Same Neighborhoods, Over and Over

To understand where the crackdown is playing out, we mapped the geographic distribution of drug-related arrests across the city. Unsurprisingly, one neighborhood dominates.

![Insert Map Visualization Here]

The **Tenderloin** emerges as a clear hotspot, but it's far from the only one. Arrest clusters also appear around **UN Plaza**, **Civic Center BART**, and sections of **SoMa** and the **Mission**. What connects these places? Many are home to **shelters**, **public housing**, and **services for vulnerable populations**.

Cross-referencing our dataset’s coordinates with OpenStreetMap reveals that some of the most frequent arrest locations are within feet of needle exchange centers or transitional housing. This lends weight to critics’ concerns: that enforcement doesn’t necessarily follow the drug trade, but instead concentrates on **where the crisis is most visible**.

---

## 🖱️ When and Where? An Interactive Look at Enforcement Patterns

Beyond place, **time** is another layer in understanding enforcement. Using an interactive visualization built in Bokeh, we explored drug-related arrests by **hour of day**, **district**, and **year**.

👉 *(Embed Bokeh HTML or iframe your interactive plot here)*

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
 -->
