# Apple Social Media Analytics – Case Study

## Task-1: Data Preprocessing & Cleaning

| Task | Summary of work done in Excel |
|------|-------------------------------|
| Remove duplicate Apple posts | Selected dataset → Data tab → Remove Duplicates. Selected all columns to check duplicates. Result: No duplicates found. |
| Standardize date & platform names | Set the “Date” column format to Date. |
| Format numeric columns (Likes, Reach, Impressions, Ad Spend) | In Posts sheet, set numeric format with zero decimal places for Likes, Shares, Comments, Clicks, Reach, Impressions. Did the same in Engagement sheet for New Followers, Unfollows, Total Followers, Ad Spend, and Impressions. |
| Split hashtags into separate tags | Used **Text to Columns** with space delimiter. Created columns: `hashtag1` and `hashtag2`. |

---

## Task-2: Engagement Analysis (Using Posts Dataset)

| Task | Summary of work done in Excel |
|------|-------------------------------|
| Calculate average engagement rate per platform | Added a new column `engagement_rate` in Posts dataset. Formula: (Likes + Shares + Comments) / Impressions. Then used pivot table to calculate platform-wise average. |
| Identify Top 10 posts with highest engagement | Sorted `engagement_rate` column from largest to smallest. Top 10 rows represent highest engagement posts. Highlighted top 10 rows. |
| Pivot: Total Likes, Shares, Comments by Content Type & Platform | Created pivot table: Rows → Content Type, Platform. Values → Likes, Shares, Comments (Sum). |
| Pivot: Average Clicks per post by Hashtag | Created pivot table: Rows → hashtag1, hashtag2. Values → Clicks (Average). |
| Highlight top-performing hashtags | Created pivot: Rows → hashtag1, hashtag2. Values → engagement_rate (Average). Sorted from largest to smallest to identify top hashtags (#ShotOniPhone, #AppleEvent, #iPhone16Launch, #MacBookAir). |

---

## Task-3: Platform Analysis

| Task | Summary of work done in Excel |
|------|-------------------------------|
| Identify platform with highest engagement | Created pivot: Rows → Platform. Values → engagement_rate (Average). Sorted descending. Result: Twitter has highest engagement. |
| Compare follower growth rates | Created columns: Net_Follower_Growth = New Followers − Unfollows. Net_Follower_Growth_Rate = Net_Follower_Growth / Total Followers. Pivoted by platform and sorted descending. Result: Twitter has highest growth rate. |
| Visualize Engagement vs Ad Spend | Created pivot: Rows → Platform. Values → Sum of Ad Spend, Avg Engagement Rate. Built scatter chart to compare. |
| Strategic advice | YouTube shows high engagement with lower ad spend. Instagram shows strong follower growth. Recommended focus: YouTube + Instagram, while maintaining Twitter presence. |

---

## Task-4: Hashtag & Content Strategy

| Task | Summary of work done in Excel |
|------|-------------------------------|
| Identify most frequently used hashtags | Created pivot counting occurrences of hashtag1 and hashtag2. Sorted descending to find most used hashtags. |
| Compare average performance per hashtag | Used pivot: Rows → Hashtags. Values → engagement_rate (Average). |
| Compare content performance | Created pivot: Rows → Content Type, Platform. Values → Avg Likes, Avg Engagement Rate, Post Count. |
| Key findings | Videos dominate engagement across platforms. Twitter carousels perform well for likes. Images perform well on Twitter and LinkedIn but less on Instagram. |
| Content recommendations | YouTube: Videos. Instagram: Better product images. LinkedIn: Video-first strategy. Twitter: Mix of tweets, images, and carousels. |

---

## Task-5: Campaign Effectiveness

| Task | Summary of work done in Excel |
|------|-------------------------------|
| Total & average impressions, likes, clicks per campaign | Created pivot: Rows → Campaign. Values → Sum and Average of Impressions, Likes, Clicks. |
| Measure engagement uplift | Compared campaign-period engagement vs pre-campaign levels using campaign pivots. |
| Highest ROI campaign | Identified using engagement vs spend comparison in campaign pivot tables. |
| Strongest follower growth campaign | Compared follower growth during campaign periods across platforms. |

---

## Overall Strategic Recommendations

- Focus on **YouTube and Instagram** as primary platforms.
- Maintain **Twitter** for announcements and engagement.
- Prioritize **video content** across platforms.
- Use high-performing hashtags consistently.
- Invest more during major product launch campaigns.
