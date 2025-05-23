# Potential Talents

Introduction:
Built a recommondation system that could help finding the talented Candidates whom are suitable for the announced job roles and assigning them as a Human resources and staffing company to the technology companies.


Data Description:
The Dataset consists of 104 rows and 5 columns categorized into #id, #job_title, #location, #connection, #fit. 


Methodology:
1. Applying EDA (Exploratory Data Analysis) techniques to understand the structure and the content of the dataset and analyze its nature and the required processing steps.
2. Cleaning the dataset by removing all the missing values (Nulls) from the dataset.
3. Removing the #location column and #id column from the dataset.
4. Removing the #fit column since its a Null column, while considering to re-fill it again after building and training the model to apply the ranking process.
5. Applying Word Embedding technique by using FastText, Mini_LM, and Google Bert (Uncased version) Models.
6. Calculating the Cosine_Similarity for the Embeddings from each Word Embedding Model.
7. Applying Feature Scaling techique on #connection column.
8. Applying the Ranking Formula by using a 30% for each Word Embeddings and adding it with 10% from the scaled connections.
9. Sorting the dataset using Descending Sorting technique.
10. Ranking the candidates based on their qualifications for the annonuced roles from the most suitable ones up to the lowers.


Conclusion:
Results reached to 86.4% ranked from the highest selected candidates up to the lowest.
