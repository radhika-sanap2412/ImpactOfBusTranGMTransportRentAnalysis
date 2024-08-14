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

Proximity Impact: Proximity to bus lines within 200m generally increases rental prices, especially in suburban areas. In contrast, in central and eastern parts of Greater Manchester, additional bus lines show a negative impact, likely due to already established connectivity.
Spatial Variability: The GWR analysis revealed that the effect of bus transport accessibility on rental prices varies significantly across different regions, with more pronounced effects in less central areas.
Importance of Connectivity: The study underscores the need for developing bus transit corridors in less central areas to enhance connectivity and potentially increase rental prices.

## Conclusion:

The study supports the hypothesis that bus transport accessibility significantly influences rental prices, with notable spatial variations across Greater Manchester. These insights can inform urban planning and public transport development strategies to enhance connectivity and equitable growth in the region.
