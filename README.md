<!-- <i class="fa-solid fa-graduation-cap"></i> -->
# Online Learning Engagement Analysis

## Project Overview
This project focuses on analyzing and understanding user behavior, participation, and completion statuses across online education platforms. By exploring structural indicators—such as course types, learning modes, forum posts, and study hours—the analysis uncovers key metrics driving student completion rates and historical performance.

---

## Repository Structure & Core Files

* **`online_learning_engagement_dataset.csv`**: The initial, raw relational dataset containing background learner demographics, platform engagement metrics, and academic results across 5,010 individual entries.
* **`online_learning_engagement_cleaned.csv`**: The refined production dataset. Missing numeric records were treated using computed means, object structural values were missing-mode imputed, and a feature-engineered binary column (`completion_status_binary`) was introduced to simplify statistical probabilities.
* **`EYOUTH-31012042601655_online_learning_engagement.png`**: The primary analytical distribution visual showcasing the historical spread, trendlines, and frequencies of students' final grades across the dataset.

---

## Key Methodology & Statistical Insights

### 1. Data Cleaning & Pipeline Handling
* Null metrics identified across `age`, `device_type`, and `study_hours_per_week` were resolved through systematic structural imputation.
* Created categorical binary conversions to map explicit course passings.

### 2. Base Observations
* **Platform Baseline Success:** The absolute mathematical probability of an online student successfully reaching course completion is **59.661%**.
* **Student Risk Assessment:** Approximately **18.92%** of all active profiles fall under the **"Needs Support"** status category, pinpointing key student segments requiring immediate intervention strategies.

---

## Visual Summary
The project maps overall system behavior using distribution visuals to balance learning thresholds. The `EYOUTH-31012042601655_online_learning_engagement.png` artifact details these continuous trends to easily isolate visual drops and peaks in candidate performance across varying dynamic course setups.
