# HealthPulse Explorer: Navigating Daily Well-being

This project explores fitness, sleep, and activity patterns using health-tracking data.  
The goal is to uncover behavioral trends and offer recommendations to improve daily well-being, using R for analysis and visualization.

---

## 📊 Project Highlights

- **Tools Used**: R, ggplot2, dplyr, lubridate, janitor
- **Focus Areas**:
  - Activity and intensity by time of day
  - Sleep adequacy and time-in-bed analysis
  - Relationship between steps and calories burned
  - Daily and hourly movement trends
- **Target Outcome**: Provide data-driven insights to enhance lifestyle habits through visualization and behavioral segmentation.

---

## 🔍 Key Analyses Performed

- Feature Engineering:
  - Extracted `time`, `date`, `day_of_week` from datetime fields
  - Categorized users into sleep types and weight goals using thresholds
- Exploratory Analysis:
  - Analyzed Total Minutes Asleep vs. Time in Bed
  - Explored activity duration across types (Very, Fairly, Lightly Active, Sedentary)
  - Clustered users by average calorie burn and related it to weight maintenance
- Visualizations:
  - Mean activity minutes per type
  - Sleep category distribution
  - Calories vs. steps correlation
  - Hourly activity intensity trends
  - Violin plots for activity duration
  - Sleep vs. steps per day

---


---

## 📈 Sample Insights

- Users were most active between **5–7 PM** and around **12–2 PM**, aligning with typical work breaks.
- Sleep patterns revealed many users spending more time in bed than they actually sleep — indicating potential distractions (e.g., screen time).
- Most users fall under **light activity** levels, suggesting opportunity for motivational nudges.
- Calories burned and steps are positively correlated, validating that increasing activity helps achieve fitness goals.

---

## 📌 Key Recommendations

- Introduce **reminders or motivational alerts** during peak activity windows (e.g., 5–7 PM).
- Recommend **bedtime routines** to improve sleep efficiency (e.g., no screen time, light reading).
- Tailor fitness advice using categories like **"Maintain Weight"**, **"Gain Weight"**, and **"Lose Weight"** based on average calories burned.
- Offer **hourly nudges** during sedentary hours to promote micro-activity.

---

## 🧠 Stakeholder Summary

This analysis supports the design of health apps like Bellabeat, focusing on behavior-driven notifications, automated tracking, and user empowerment.  
By aligning app experiences with peak activity/sleep behavior patterns, companies can foster greater engagement, retention, and real impact on women’s well-being.

---

## 💻 Tools & Technologies Used

- **R Programming**: Data wrangling, feature engineering, and visualization
- **Tidyverse Libraries**: dplyr, ggplot2, lubridate, skimr, janitor
- **RMarkdown**: For narrative-driven analysis and documentation

---

## 📝 Notes

- This project is for educational and exploratory purposes.
- Data is simulated or anonymized Fitbit-style tracking data, not tied to any specific user or product.
