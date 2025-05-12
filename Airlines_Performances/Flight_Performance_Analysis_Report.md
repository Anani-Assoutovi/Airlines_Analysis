
# Flight Delay and Performance Analysis of U.S. Airline Carriers

**Author:** Anani A. Assoutovi  
**Affiliation:** Independent Researcher / Data Scientist  
**Email:** booking.helices4s@icloud.com  
**LinkedIn:** www.linkedin.com/in/ananiassoutovi  
**Date:** May 11, 2025  

---

## Abstract

This study analyzes flight performance data from U.S. airline carriers, with a particular focus on delay patterns, operational efficiency, and time-based trends. By examining scheduled versus actual timings, delay reasons, and carrier performance, the goal is to provide actionable insights for improving flight reliability and customer satisfaction.

---

## 1. Introduction

Air travel delays can significantly impact operational costs and customer experience. This research utilizes a dataset of flight information, including details such as carrier, origin, destination, distance, and delay metrics. We aim to identify the root causes and trends in airline delays across various dimensions—carriers, routes, airports, and time.

---

## 2. Dataset Overview

- **Features**: Carrier, Origin, Destination, Departure Delay, Arrival Delay, Flight Distance, Scheduled & Actual Times
- **Data Source**: U.S. domestic airline operational statistics
- **Scope**: Thousands of flights spanning multiple carriers and airports

---

## 3. Methodology

The analysis focuses on the following dimensions:

### 3.1 Delay Analysis
- Average **departure and arrival delays** segmented by:
  - Carrier (e.g., AA, DL, UA)
  - Airport (origin and destination)
  - Time (hour of day, month, day of week)
- Identification of **top routes** with the highest average delays

### 3.2 On-Time Performance
- Percentage of flights arriving within 15 minutes of the scheduled time
- Performance rating per carrier

### 3.3 Flight Performance
- Comparison between scheduled and actual departure/arrival times
- Visualization of delays across time

### 3.4 Carrier Comparison
- Mean delays per airline
- Number of flights operated per airline
- Distribution of delay severity by airline

### 3.5 Temporal Delay Patterns
- Average delays by:
  - Hour of the day
  - Day of the week
  - Month of the year

---

## 4. Key Findings

- Certain carriers consistently outperform others in on-time arrival rates.
- Delays are often higher during peak hours (late afternoons) and winter months.
- Hub airports exhibit more severe delays, likely due to traffic congestion.
- Top delayed routes often include busy airport pairs with high volume and weather sensitivity.
- Some carriers demonstrate efficient recovery from delays, minimizing arrival deviations.

---

## 5. Conclusion

This analysis highlights the importance of temporal and operational factors in flight delays. Airlines and airports can use these insights to optimize scheduling, staffing, and runway logistics. Future enhancements could involve machine learning-based delay prediction and integration of real-time weather or air traffic data.

---

## 6. Future Work

- Incorporate weather data to explain delay variances
- Apply clustering for route delay profiling
- Develop real-time delay prediction models

---

## References

- U.S. Department of Transportation (BTS)
- Python Libraries: pandas, matplotlib, seaborn, plotly
