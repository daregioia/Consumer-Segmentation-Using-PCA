# Consumer-Segmentation-Using-PCA
Principal Component Analysis (PCA) applied to a pilot survey on consumer attitudes toward discount vs. department stores.

🚀 Overview

This project analyzes responses from 30 consumers on five attitudes related to customer service, store aesthetics, and value perception.
Using PCA and K-means clustering, we identify underlying behavioral dimensions and derive three consumer segments with clear marketing implications.

🛠️ Methods
1. Descriptive & Exploratory Analysis
   - Scaling of variables X1–X5
   - Correlation matrix (strong patterns observed):
     - X1–X3 strongly positive (0.88)
     - X2 strongly negative with both X1 and X3
     - X4–X5 strongly positive (0.66)

3. Principal Component Analysis

Key results:
  - PC1 explains 53.4% of variance
  - PC2 explains 37.0%
  - First 2 PCs together explain 90.48% ➝ sufficient for dimensionality reduction

Interpretation:
  - PC1 – “Care for respectful & attentive customer service”
    (High loadings: +X1, +X3, −X2)
  - PC2 – “Interest for value & practicality in-store”
    (High loadings: +X4, +X5)
4. Consumer Segmentation

  Using K-means (k = 3) based on PC1 & PC2:
  - Cluster 0 → Service-oriented shoppers (46.7%)
  - Cluster 1 → Disengaged aesthetic seekers (20.0%)
  - Cluster 2 → Price-focused independents (33.3%)

  Clear separation shown in PCA scatter plot.

🔍 Key Insights from Analysis

Segment Profiles
(derived from segment means)

1️⃣ Service-Oriented Shoppers (47%)
- High PC1: value respect, attentive service, dislike disrespect
- Mixed attitudes toward display aesthetics & bargains
- Most likely to pay premium prices → High-margin segment

2️⃣ Disengaged Aesthetic Seekers (20%)
- Low PC1 & low PC2
- Don’t value service, not price-sensitive, do care about displays
- Low engagement → weak profitability potential

3️⃣ Price-Focused Independents (33%)
- Low PC1, high PC2
- Prefer bargains, ignore aesthetics, avoid salesperson interaction
- High-volume, low-margin potential → efficiency strategy
