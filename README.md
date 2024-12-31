# Streaming Platform Analysis Project

## Overview

This project provides a comprehensive analysis of popular streaming platforms to determine which offers the best content in terms of ratings, exclusivity, and genre strengths. The analysis also examines overlap in popular titles to guide platform selection based on user preferences.

## Objectives

- Identify the platform(s) with the highest percentage of high-rated content.
- Evaluate the exclusivity of popular titles across platforms.
- Highlight platform strengths in specific genres.
- Recommend the best single platform and best pair of platforms for users.

## Methodology

1. **Data Sources**:  
   - IMDb Top Rated Titles Dataset (Movies & TV Series with a minimum rating of 7 and 10,000+ votes).  
   - Streaming platform catalogs for Amazon, Apple, HBO, Hulu, and Netflix.

2. **Tools Used**:  
   - Python libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`.

3. **Analysis Steps**:  
   - Data cleaning and preprocessing.
   - Calculating platform-specific statistics (e.g., percentage of high-rated content).
   - Generating visualizations, including genre performance heatmaps and platform overlap matrices.

4. **Visualization**:  
   - Heatmaps for platform overlap and genre-based performance.
   - Bar plots showing the distribution of high-rated and popular titles.

## Key Findings

1. **Best Single Platform**:  
   HBO offers the highest percentage of high-rated content (32.16%), excelling in genres such as *Drama*, *Comedy*, *History*, and *Music*. It also has the strongest library of exclusive high-rated titles.

2. **Best Platform Pair**:  
   Combining HBO and Netflix provides a balance of quality and variety, with HBO leading in content quality and Netflix adding a substantial catalog of exclusives in genres like *Animation* and *Sci-Fi*.

3. **Genre-Specific Performance**:  
   - HBO leads in 17 of 25 genres, including *Action*, *Biography*, and *Romance*.  
   - Hulu excels in *Talk-Show* and *War*.  
   - Amazon performs best in *Reality-TV*.  
   - Apple dominates *Documentary* and *News* genres.  

4. **Platform Overlap**:  
   There is minimal overlap in popular titles among platforms, with each platform offering a unique value proposition for its exclusives.

## Recommendations
1. For Single Platform Users:
HBO is the best option for those seeking high-rated and diverse content.

2. For Dual Platform Users:
HBO and Netflix together offer the most comprehensive content library, balancing quality, exclusivity, and variety.
