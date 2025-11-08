# Goal 

This project focuses on utilizing advanced Unsupervised Machine Learning to segment a wholesale distributor's customer base based on spending patterns across six critical product categories. The primary goal is to move beyond basic classification (like the known Horeca/Retail split) and discover four distinct, data-driven segments that offer actionable insights for targeted inventory management, marketing, and pricing strategies. The analysis is built upon a rigorous comparative study between the optimized K-Means Clustering algorithm and the Gaussian Mixture Model (GMM).

---

# Project Background

A large wholesale distributor operates within a complex market, serving clients categorized broadly by their Channel (Horeca for hotels/restaurants, and Retail). However, successful strategic planning—including optimized inventory, targeted marketing, and predictive sales forecasting—requires a deeper, more granular understanding than these broad labels allow. Customers within the same channel often exhibit wildly different spending habits across the six major product categories.

This analysis addresses the critical business challenge of heterogeneous customer behavior by answering core strategic questions:

- Behavioral Differentiation: What are the underlying, distinct spending patterns that define unique customer segments, independent of the known Channel label?
- Resource Allocation: Which segments represent high-value opportunities versus high-volume commodity opportunities?
- Model Validation: How effective are advanced unsupervised algorithms (Optimized K-Means and GMM) in uncovering these hidden structures compared to simple Channel classification?

By systematically transforming the data, and rigorously comparing clustering algorithm performance, this project provides the distributor with a data-driven segmentation strategy for immediate, actionable business intelligence.

---

# Interpretation of Clusters

1. Horeca Segments (Clusters 1 and 3): These are clearly defined by their reliance on Fresh and Frozen goods and their minimal use of commodities (Detergents_Paper is 700 vs. 6,800 for Retail). The key difference is the Fresh vs. Frozen mix, which dictates logistics and speed requirements.

2. Retail Segments (Clusters 0 and 2): These are defined by extremely high proportional spending on Milk, Grocery, and Detergents_Paper. The segmentation here successfully identifies the commodity buyers who drive the highest volume in non-perishables.

3. Validation of k=4: The model successfully split the two known channels into two distinct segments each, showing that within the Horeca group, the Fresh vs. Frozen reliance is the most important behavioral differentiator.

--- 

# Recommendations 
