# Impact of Bus Transport Accessibility on Rental Prices in Greater Manchester

## Summary:
This project investigates the relationship between bus transport accessibility and rental prices across Greater Manchester, utilizing a combination of traditional hedonic pricing models and advanced spatial analysis techniques. The study focuses on how proximity to bus routes and unique bus lines influences rental prices, particularly within different regions of Greater Manchester.

## Data Source:

The dataset includes 5,703 unique rental listings from PropertyData (2024), encompassing various property attributes (e.g., number of bedrooms, property type) and geographical coordinates.
Bus transport data was processed to calculate the number of unique bus lines and routes within 200m and 400m of rental properties.
## Methodology:

## Hedonic Pricing Models (HPM): 
Employed to assess the impact of bus transport accessibility, using variables like proximity to unique bus lines/routes, distance to the nearest train station, and various neighborhood amenities.
Geographically Weighted Regression (GWR): Applied to capture spatial variability in the relationship between transport accessibility and rental prices. This model allows coefficients to vary with geographical location, revealing significant spatial heterogeneity.
Machine Learning Techniques: Random Forest and Extreme Gradient Boosting (XGBoost) models were used to handle non-linear relationships and provide more robust predictions. These models were optimized using Bayesian Optimization to enhance performance.

## Key Findings:

Proximity Impact:
Properties within 200 meters of unique bus lines see a decrease in rental prices by approximately 0.77% per additional line in less central areas, but an increase by about 1.44% per additional line in suburban areas, indicating the value of bus lines in regions with less established connectivity.
Properties within 400 meters of unique bus routes show a 2.38% increase in rental prices for every additional route, demonstrating the importance of route diversity.
Spatial Variability:
The GWR model revealed significant spatial variability with an R² of 0.7050, indicating that the relationship between transport accessibility and rental prices is not uniform across Greater Manchester. The effect is more pronounced in suburban areas compared to central ones.
The analysis identified that rental prices in the east of Greater Manchester increase by 3.83% with closer proximity to bus routes, while central areas exhibit a negative impact of 1.10% for additional lines, suggesting a saturation effect.
Importance of Connectivity:
The study found that proximity to train stations significantly boosts rental prices, with a 5.38% increase for properties located nearer to a station, underscoring the importance of multimodal connectivity.
## Conclusion:

The findings support the hypothesis that bus transport accessibility significantly influences rental prices in Greater Manchester, with substantial spatial variations. Proximity to bus lines and routes is associated with increased rental prices, particularly in suburban areas where connectivity is less established. The GWR model highlighted that in areas with poor connectivity, rental prices could increase by up to 3.83% for closer bus route access. Conversely, in central areas with better-established networks, additional bus lines might decrease rental prices by up to 1.10% due to over-saturation. These insights are crucial for urban planners aiming to enhance connectivity and support equitable economic growth across Greater Manchester.
