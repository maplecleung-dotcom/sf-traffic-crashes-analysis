# Afternoon Commutes and Busy Neighborhoods See the Most Injury Traffic Crashes in San Francisco

Traffic crashes are not evenly distributed across San Francisco. Some neighborhoods see far more reported injury crashes than others, and crashes also vary by time of day.

This project uses San Francisco’s open data on traffic crashes resulting in injury to examine where and when injury crashes happen most often. I focused on crashes by neighborhood and time of day to better understand which areas and time periods show the highest crash totals.

## Dataset

The dataset used for this project is **Traffic Crashes Resulting in Injury** from the **DataSF Open Data Portal**.

The data is maintained by the City and County of San Francisco and includes reported traffic crashes that resulted in injury. The dataset includes information such as crash date, time, neighborhood, weather, collision type, and number of people injured.

Dataset source: [DataSF Traffic Crashes Resulting in Injury](PASTE-YOUR-DATASET-LINK-HERE)

## Analysis Process

I downloaded the dataset as a CSV file and imported it into Google Sheets. I used pivot tables to summarize the number of crashes by several categories, including neighborhood, time of day, day of week, and weather.

For the final visualizations, I focused on two questions:

1. Which San Francisco neighborhoods had the most injury traffic crashes?
2. What time of day had the most injury traffic crashes?

Google Sheets analysis: [View my Google Sheet](PASTE-YOUR-GOOGLE-SHEET-LINK-HERE)

## Finding 1: Injury crashes are concentrated in a small number of neighborhoods

![Top neighborhoods with the most injury crashes](neighborhood_crashes.png)

**Figure 1.** The Mission had the highest number of reported injury traffic crashes in the dataset, followed by South of Market, the Financial District, Tenderloin, and Bayview Hunters Point. These areas may have higher crash totals because they include busy streets, commercial activity, and heavy vehicle, bicycle, and pedestrian traffic.

## Finding 2: Injury crashes peak in the afternoon

![Injury crashes by time of day](time_of_day_crashes.png)

**Figure 2.** Injury traffic crashes were most common between 2:01 p.m. and 6:00 p.m., followed by the evening period from 6:01 p.m. to 10:00 p.m. Overnight hours had the fewest reported injury crashes.

## Methods and Limitations

This analysis counts the number of reported injury crashes in each category. It does not measure crash risk per driver, pedestrian, cyclist, or trip.

One major limitation is that neighborhoods with more crashes may simply have more traffic, more people, or more intersections. The dataset does not include traffic volume, pedestrian counts, or bicycle counts, so it cannot prove that one neighborhood is more dangerous than another on a per-person basis.

The dataset also only includes crashes that resulted in injury and were reported. It does not include every possible traffic incident, property-damage-only crash, or near miss. Some fields also include missing, unknown, or “Not Stated” values.

Weather is another limitation. Most crashes occurred during clear weather, but that does not necessarily mean clear weather is more dangerous. It may simply reflect that clear weather is common in San Francisco.

## Ethical Considerations

This data could be misread if crash counts are treated as direct proof that certain neighborhoods are unsafe. Higher totals may reflect higher traffic volume rather than worse road design or more dangerous behavior. A complete story would require additional reporting, including interviews with transportation officials, residents, cyclists, pedestrians, and traffic safety advocates.

## Final Takeaway

The data shows that reported injury traffic crashes in San Francisco are concentrated in busy neighborhoods and are most common during afternoon and evening travel periods. The Mission, South of Market, and the Financial District had some of the highest crash totals, while the 2:01 p.m. to 6:00 p.m. period had the most crashes by time of day.

These findings suggest that traffic activity and urban density may play an important role in where and when crashes occur. However, the data alone cannot explain why crashes happen. More reporting and additional data on traffic volume, street design, and pedestrian and cyclist activity would be needed to fully understand the causes behind these patterns.

## Sources

- DataSF Open Data Portal, Traffic Crashes Resulting in Injury
- City and County of San Francisco
