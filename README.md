# Correlation Between Weather and Music Listening Habits

## Introduction
This project aimed to explore the relationship between weather conditions and music preferences. By analyzing Spotify listening history alongside historical weather data, the system was designed to categorize listening habits based on weather conditions and test for potential correlations.

## Hypothesis Testing
- **Null Hypothesis (H0):** Weather conditions and music preferences are independent.  
- **Alternative Hypothesis (H1):** Weather conditions influence music preferences.

A Chi-Square test was conducted, and the results showed no statistically significant relationship between weather conditions and general music preferences, leading to a failure to reject H0. This indicates that music preferences, in general, are not influenced by the weather.

## Weather-Based Playlists
Even though no significant correlation was found between weather and overall music preferences, the system generates personalized playlists based on past listening habits under specific weather conditions. These playlists serve as a unique way to rediscover and enjoy music associated with different weather patterns.

### Example Weather-Specific Playlists:
- **Rainy Days Playlist:** Tracks listened to on rainy days.  
- **Clear Sky Playlist:** Songs played on days with clear weather.  
- **Partially Cloudy Playlist:** Music enjoyed on partly cloudy days.

## Data Sources
- **Spotify Listening Data:** Extracted from user listening history on Spotify.  
- **Weather Data:** Historical weather information sourced from Visual Crossing, providing daily weather conditions for the relevant dates.

## Methodology

1. **Data Cleaning:**  
   - Extracted relevant attributes (e.g., track names, timestamps) from Spotify data.  
   - Cleaned and formatted weather data to ensure compatibility for merging.  

2. **Data Merging:**  
   - Merged Spotify listening data with weather data based on the 'date' column to align listening habits with weather conditions.  

3. **Hypothesis Testing:**  
   - Created a contingency table to analyze the distribution of songs across different weather categories.  
   - Performed a Chi-Square test to assess the relationship between weather and music preferences.  

4. **Playlist Creation:**  
   - Grouped songs by weather categories to generate weather-specific playlists based on historical listening data.

## Conclusion
While the analysis confirmed no significant correlation between weather conditions and general music preferences, the system effectively creates personalized weather-based playlists. This feature allows users to enjoy curated music selections that align with their past listening habits under different weather conditions, offering a personalized and engaging listening experience.
