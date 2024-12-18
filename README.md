# Customer Segmentation Analysis Using Clustering 

**Objective:**  
The primary goal of this project was to segment customers into distinct groups based on their purchasing behavior, demographic characteristics, and lifestyle preferences. By understanding these segments, businesses can tailor their marketing strategies, optimize resource allocation, and improve customer satisfaction.  

**Data Overview:**  
The dataset used for clustering contained key features such as:  
- **Demographic Attributes:** Income, Age, Education Level, Family Composition.  
- **Purchasing Behavior:** Amount Spent, Product Categories Purchased, and Preferred Purchase Channels (Web, Catalog, or Physical Stores).  
- **Frequency Metrics:** Number of purchases across different channels.  

**Clustering Methodology:**  
1. **Data Preparation:**  
   - Preprocessed the data by handling missing values, scaling numeric features, and encoding categorical features.  
   - StandardScaler was applied to normalize numerical variables.  

2. **Feature Selection:**  
   - Selected meaningful variables for clustering, such as Income, Age, Amount Spent, and Purchase Frequency.  

3. **Clustering Approach:**  
   - Applied the K-Means clustering algorithm after determining the optimal number of clusters using the **Elbow Method** and the **Silhouette Score**.  
   - Divided the customers into three distinct groups.  

4. **Cluster Validation:**  
   - Evaluated cluster performance using metrics such as intra-cluster distance and inter-cluster separation.  
   - Analyzed the differences among clusters based on demographic and behavioral insights.  

**Business Results:**  
As a result of clustering, three groups of buyers were identified:  

### **Cluster 0:**  
- **Income Range:** $68,000–$82,000  
- **Average Age:** 55 years  
- **Education Levels:** Graduation, 2nd Cycle, Master, or PhD  
- **Family Composition:** Individuals without families or families with one or no children  
- **Average Amount Spent:** $1,350  
- **Popular Purchases:** Wines and Meats  
- **Preferred Channels:** Web and Catalog  
- **Purchase Frequency:** High (average number of purchases is 19)  

### **Cluster 1:**  
- **Income Range:** $23,000–$42,000  
- **Average Age:** 51 years  
- **Education Levels:** Basic, Graduation, 2nd Cycle, Master, or PhD  
- **Family Composition:** Families with children (1 or 2)  
- **Average Amount Spent:** $50  
- **Popular Purchases:** Wines and Meats  
- **Preferred Channels:** Physical stores  
- **Purchase Frequency:** Low (average number of purchases is 5)  

### **Cluster 2:**  
- **Income Range:** $50,000–$68,000  
- **Average Age:** 59 years  
- **Education Levels:** Graduation, 2nd Cycle, Master, or PhD  
- **Family Composition:** Families with children (1 or 2)  
- **Average Amount Spent:** $650  
- **Popular Purchases:** Wines  
- **Preferred Channels:** Web and physical stores (occasionally)  
- **Purchase Frequency:** Moderate (average number of purchases is 16)  

**Insights and Recommendations:**  
- **Cluster 0:** Represents affluent, middle-aged individuals who make frequent, high-value purchases. Marketing strategies should focus on web and catalog channels with premium product offerings.  
- **Cluster 1:** Includes low-income, middle-aged customers who shop infrequently and spend minimally. Store-specific promotions and discounts on basic necessities may attract this segment.  
- **Cluster 2:** Comprises moderate-income, older individuals who exhibit average purchase behavior. Balanced promotional strategies across both web and physical stores can effectively engage this group.  

**Conclusion:**  
By identifying these distinct clusters, businesses can develop targeted marketing campaigns and personalized recommendations to enhance customer engagement and maximize revenue. This segmentation provides actionable insights to align business strategies with customer preferences.  
