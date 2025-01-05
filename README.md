# Movie-Recommendation-System

This time OTT Platforms Proforma high demands for their recommended systems. The OTT Platforms Recommended program base the following base recommendation type:
**1)	Content base recommendation System**
**2)	Popularity base recommendation System**
**3)	Collaboration recommendation System**

 Content base recommendation System: This Recommendation system is depending on Program content like their Story, Segments, Direction etc.

Popularity base recommendation System: This Recommendation system is depending on Popularity of the program or their rating. 

Collaboration recommendation System: This Recommendation system is depending on Same Group base public, that type of Public finding the previous Data & given that type of recommendation. (user behaviors & Data Recommendation)

We can use the Content base recommendation system, first of all Data pre-processing with Null value filling & select features which recommendation dependent features.
Feature extraction:
With using the below function & Score
1.	TF-IDF Vectorizer:The TfidfVectorizer converts the descriptions of the movies into numerical vectors, where each element in the vector corresponds to the importance of a word (term) in a document relative to the entire corpus (set of documents).
   
2.	Cosine Similarity:The cosine_similarity function compares these vectors by calculating the cosine of the angle between them. The closer the cosine value is to 1, the more similar the two vectors are.

3.	Recommendations:The function recommend_movies calculates which movies are most similar to a given movie and returns a list of movie titles with the highest similarity scores.

User input the their favorite Program or movies the machine Algorithm work with Cosine Similarity & given best & Similar movies list.
