
## **DAY 40 (28 Oct 2023):**
### Topic: Understanding DB SCAN Clustering

I find this to be an interesting clustering technique, DBSCAN identifies clusters by exploring the density of data points within the feature space. It separates regions of high density from regions of low density, allowing for the discovery of clusters of any shape.

**Topics Discussed in Notes:**
1. Concept of DB SCAN
2. Key words in understanding DB SCAN
3. Algorithm of DB SCAN

**Key Takeaways:**
1. Epsilon (ε): Also known as the radius, ε determines the neighborhood around a data point.

2. Minimum Points (MinPts): The minimum number of data points within the ε radius to establish a core point.

3. Algorithm steps:
- Density Reachability: Determine the ε-neighborhood of each point and identify core points, directly reachable points, and outlier points.
- Density Connectivity: Create clusters by connecting points that are density-reachable. Expand clusters by iteratively connecting core points.

4. Advantages:
- It can handle noisy data effectively.
- It can identify clusters of various shapes and sizes.
- It doesn't require a predefined number of clusters.

5. Limitations:
- Appropriate parameter selection is crucial for optimal clustering.
- Challenges with high dimensional data and large datasets.

Detailed Notes: [Day 40 Commit](https://github.com/ds-teja/100_Days_MLDL/tree/main/40.%20Day%2040%20-%20Understanding%20DB%20SCAN%20Clustering)

LinkedIn post: [Day 40 Update](https://www.linkedin.com/posts/ravi6123_understanding-db-scan-clustering-activity-7124094142778916864-g9uW?utm_source=share&utm_medium=member_desktop)

---