# Bellabeat Data Analysis Study

## Overview
This project analyzes smart device data to extract insights about user activity, sleep, and health metrics for Bellabeat, a company focused on women's wellness. The analysis provides recommendations to optimize Bellabeat's product offerings and marketing strategies.

## Data Sources
- **Daily Activity Data:** Steps, distance, calories burned, and sedentary minutes.
- **Sleep Data:** Sleep duration, time in bed, and sleep quality.
- **Weight Data:** Average weight and BMI of users.
- **Hourly Steps Data:** Activity trends throughout the day.

## Installation
To run the analysis locally, follow these steps:
1. Clone the repository:
   ```sh
   git clone https://github.com/muhakankaya/bellabeat-data-analysis.git
   ```
2. Navigate to the project directory:
   ```sh
   cd bellabeat-data-analysis
   ```
3. Install required R packages:
   ```r
   install.packages(c("tidyverse", "lubridate", "ggplot2"))
   ```
4. Run the analysis scripts:
   ```r
   source("scripts/data_analysis.R")
   ```

## Key Findings
- **Average Daily Steps:** 7,500, with peak activity between **6 AM - 10 AM** and **5 PM - 8 PM**.
- **Least Active Day:** Sundays, averaging **5,800 steps**.
- **Users who sleep >7 hours per night** show a **15% increase in activity levels**.
- **Higher BMI (>30)** correlates with **25% lower step count**.
- **Most active hours:** 6 AM - 10 AM and 5 PM - 8 PM.

## Recommendations
- **Encourage increased daily steps**: Promote morning and evening activity.
- **Implement sleep optimization programs**: Suggest ideal sleep duration for better performance.
- **Targeted health campaigns**: Develop wellness challenges for users with high BMI.
- **AI-based smart alerts**: Provide reminders to reduce sedentary behavior.
- **Marketing strategy enhancement**: Personalize content around sleep and movement.

## Authors
- **Hakan KAYA**

## License
This project is licensed under the MIT License - see the LICENSE file for details.
