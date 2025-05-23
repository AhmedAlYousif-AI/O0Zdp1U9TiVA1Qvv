# Potential Talents

Introduction:
Built a recommondation system that could help finding the talented Candidates whom are suitable for the announced job roles and assigning them as a Human resources and staffing company to the technology companies.


Data Description:
The Dataset consists of 999 rows and 5 columns categorized into #id, #job_title, #location, #connection, #fit. 


Methodology:
1. Applying EDA (Exploratory Data Analysis) techniques to understand the structure and the content of the dataset and analyze its nature and the required processing steps.
2. Cleaning the dataset by removing all the missing values (Nulls) from the dataset, the samples decreased from 999 entites to 104 entites.
3. Removing the #location column and #id column from the dataset.
4. Removing the #fit column since its a Null column, while considering to re-fill it again after building and training the model to apply the ranking process.
5. Applying Word Embedding technique by using FastText, Mini_LM, and Google Bert (Uncased version) Models.
6. Calculating the Cosine_Similarity of the Embeddings for each Word Embedding Model.
7. Applying Feature Scaling technique on #connection column by using Minimum Maximum Scaler.
8. Applying the Ranking Formula by using a 30% from each Word Embeddings combined and adding it with a 10% from the scaled connections.
9. Applying Sorting technique by Sorting the Ranking column in a Descending order.
10. Ranking the candidates based on their qualifications for the annonuced roles from the most suitable ones up to the lowers.


Conclusion:
Results reached to 86.4% ranked from the highest qualified candidates up to the lowest.
