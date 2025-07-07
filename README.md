# 🎵 Grammys Web Analytics Project

![Recording Academy Logo](https://www.moviedebuts.com/wp-content/uploads/2021/05/ra_ga_logo.png)

Welcome to a data-driven project for **The Recording Academy**—the organization behind the iconic **Grammy Awards**!

In this project, we analyze real web traffic data from the two primary websites:
- **grammy.com**
- **recordingacademy.com**

The organization recently split these sites to better serve different audience segments. Our goal is to explore the effects of this split and gain insights into user behavior, marketing impact, and overall site performance.

---

## 📊 Project Objective

- Evaluate how each website is performing individually post-split.
- Identify trends and patterns in user engagement.
- Compare performance during key marketing events (e.g., Awards Week & Night).
- Benchmark Grammys site performance against a competitor (American Music Awards).

---

## 📁 Data Files

You’ll be working with two CSV datasets:

- `grammys_live_web_analytics.csv`
- `ra_live_web_analytics.csv`

Each file includes:

| Column | Description |
|--------|-------------|
| `date` | Date of the data entry (`yyyy-mm-dd`) |
| `visitors` | Unique visitors to the site |
| `pageviews` | Total pages viewed |
| `sessions` | Number of user sessions |
| `bounced_sessions` | Number of sessions where users left without interaction |
| `avg_session_duration_secs` | Average session duration in seconds |
| `awards_week` | Flag indicating whether the date is part of Grammy marketing week (1 or 0) |
| `awards_night` | Flag indicating Grammy Awards ceremony night (1 or 0) |

---

## 🔍 Insights & Competitive Analysis

From April to June 2023:

- **Grammy's site**: Higher traffic and lower bounce rate
- **AMA site**: Better pages per session and session duration

**Takeaways**:
- 🎯 *Grammy.com* should improve session duration and page depth.
- 📈 *AMA* should focus on boosting its overall traffic.

> Note: This analysis is based on a limited timeframe and should not be considered a full performance audit.

---

## 🚀 Get Started

1. Clone this repository  
   ```bash
   git clone https://github.com/yourusername/grammys-analytics.git
