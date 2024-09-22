# MALL CUSTOMER SEGMENTATION

_Implemented a data analysis model to segment mall customers based on their transaction data using K-Means clustering and RFM (Recency, Frequency, and Monetary) models. The project aimed to help the mall management identify customer groups for targeted marketing strategies_

> [!NOTE]
> 
> **Technologies:**
>
> Python, Pandas, NumPy, Matplotlib, Seaborn, K-Means Clustering,Scikit-learn, Datetime.
![22 (1)](https://github.com/user-attachments/assets/97d3eafd-50fc-4507-a688-c645f611afbc)   ![21 (1)](https://github.com/user-attachments/assets/8382cc18-5ee0-48f0-9f09-111231dc4be8)

![12355645665](https://github.com/user-attachments/assets/e1a7919b-1af2-4167-8746-aa4e5d058b6a)


![23(1)](https://github.com/user-attachments/assets/090b8825-b3a0-4bd6-8a6e-38ae49e33bd7)

> [!IMPORTANT]
>
> **METHODOLOGY:**
> _The methodology followed in this research is KDD (Knowledge Discovery of Databases).This research is implemented through various stages that are explained below:_
> - Data Collection.
>
> - Data pre-processing.
>
> - Data transformation.
>
> - Data mining.
>
> - Evaluation
>
> ![method](https://github.com/user-attachments/assets/1f8fed21-ebde-4456-b670-89bbd74a28ec)

> [!TIP]
>
> **Languages Used:**
> 
> - PYTHON
> - 
> - MACHINE LEARNING LIBRARIES.
>
> **ALGORITHMS AND METHODS USED:**
>
> - RFM MODEL(Recency, Frequency, Monetary Analysis):  ![RFM](https://github.com/user-attachments/assets/d5b8b2d3-ee1a-44e8-aa06-362d9ab465d3)
>
>  - K MEANS CLUSTERING ALGORITHM : ![KMEANS](https://github.com/user-attachments/assets/2f619e9e-e59b-4d62-a4ec-0525e208e708)
>
>  - ELBOW CURVE METHOD: ![ELBOW](https://github.com/user-attachments/assets/5ae282f3-00cd-4e6e-98ea-3f15d4ac9134)

>
>
> **DATASET:**
>
> **Source:**  Kaggle - Online Retail Dataset
>
> **Description:** _This dataset contains information about online retail purchases, including customer details, purchase dates, product quantities, and prices. The data is sourced from the Kaggle platform and is relevant to e-commerce analysis and customer segmentation projects._
>
> **Date Range:**  01/12/2010 and 09/12/2011
> 
> **Columns/Variables:** CustomerID, InvoiceDate, Quantity, UnitPrice, StockCode, InvoiceNo, Description, Country.
> 
> **Size:** 541,909 rows x 8 columns
> 
> **Format:** CSV
>
> **License:** Open Database License (ODbL)
>
> **Preprocessing Steps:** _Removed missing values, and converted date strings to datetime objects._
>
> **Relevance to the Project:**
>
> _This dataset is utilized for customer segmentation using the RFM model and K-means clustering in our project on personalized marketing strategies for online retail. The data set has attributes like- InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID and Country. But we will be mainly making use of features like CustomerID, UnitPrice, Quantity, InvoiceDate, etc, and also, we would need to make new features as well to calculate the RFM score, and those features will be used further for finding the similarity to assign each customer to a cluster using k-means._
>
> 



