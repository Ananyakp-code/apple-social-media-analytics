# Apple Social Media Analytics

## Project Overview
This project analyzes Apple’s social media performance across platforms such as Twitter (X), Instagram, YouTube, and LinkedIn.  
The goal is to identify high-performing content, evaluate campaign effectiveness, and recommend strategies to improve engagement and ROI.

## Objectives
- Identify top-performing platforms and content types
- Analyze engagement rates and follower growth
- Evaluate campaign ROI and performance
- Recommend data-driven marketing strategies

## Datasets
Located in the `/data` folder:

1. **posts_cleaned.csv**
   - Social media posts data
   - Used for engagement and content analysis

2. **engagement_summary_cleaned.csv**
   - Weekly platform metrics
   - Used for follower growth and ad spend analysis

3. **campaign_metadata_cleaned.csv**
   - Campaign-level performance data
   - Used for ROI and campaign effectiveness analysis

## Analysis Files
Located in the `/analysis` folder:

| File | Description |
|------|-------------|
| engagement_analysis.csv | Engagement metrics per platform |
| platform_analysis.csv | Platform comparison metrics |
| hashtag_analysis.csv | Hashtag performance results |
| campaign_effectiveness.csv | Campaign ROI metrics |
| follower_growth.csv | Weekly follower trends |

## Key Metrics
- Engagement Rate = (Likes + Shares + Comments) / Impressions
- Follower Growth Rate
- Campaign ROI based on engagement vs spend

## Tools Used
- Microsoft Excel
- Pivot Tables

## Project Structure
```
  apple-social-media-analytics/
│
├── data/
│   ├── posts_cleaned.csv
│   ├── engagement_summary_cleaned.csv
│   ├── campaign_metadata_cleaned.csv
│
├── analysis/
│   ├── analysis.xlsx
│
├── case-study.md
└── README.md

```
## Project Tasks

### Task 1: Data Preprocessing & Cleaning (12 Marks)
- Remove duplicate Apple posts.
- Standardize date and platform names.
- Format numeric columns:
  - Likes
  - Reach
  - Impressions
  - Ad Spend
- Split hashtags (e.g., `#ShotOniPhone`, `#iPhone16`, `#AppleEvent`) into separate tags for analysis.

---

### Task 2: Engagement Analysis (8 Marks)
Using the **Posts Dataset**:

- Calculate average engagement rate per platform.

**Formula:**
Engagement Rate = (Likes + Shares + Comments) / Impressions


- Identify **Top 10 Apple posts** with the highest engagement.
- Create a pivot table showing:
  - Total Likes, Shares, Comments by **Content Type & Platform**
  - Average Clicks per post by **Hashtag**
- Highlight top-performing hashtags:
  - `#ShotOniPhone`
  - `#AppleEvent`
  - `#iPhone16Launch`
  - `#MacBookAir`

---

### Task 3: Platform Analysis (12 Marks)
- Identify the platform with the **highest engagement**.
- Compare **follower growth rates** across platforms.
- Visualize **Engagement vs. Ad Spend** per platform.
- Provide strategic advice:
  - Should Apple focus on **YouTube + Instagram (videos + visuals)**?
  - Or continue a **multi-platform strategy**?

---

### Task 4: Hashtag & Content Strategy (16 Marks)
- Identify the **most frequently used hashtags**.
- Compare average performance of posts containing each hashtag.
- Compare performance by content type:
  - **Videos** (launch events, ads, product demos)
  - **Images** (product close-ups, lifestyle shots)
  - **Carousels** (feature highlights, comparisons)
- Recommend which content type performs best on each platform:
  - Example:
    - Videos → YouTube
    - Product images → Instagram

---

### Task 5: Campaign Effectiveness (16 Marks)

#### Calculate:
- Total impressions per campaign
- Average impressions per campaign
- Total likes per campaign
- Total clicks per campaign

#### Measure:
- Engagement uplift **during vs. before campaigns**
  - Example: iPhone 16 launch spike


## Author
Ananya K P 
