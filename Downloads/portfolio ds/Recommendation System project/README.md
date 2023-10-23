# ===============================RECOMMENDATION SYSTEM===============================

__End-to-end project involving:
    1/ Web Scraping 
        1.1/ Using Beutiful Soup to extract data from the web
        1.2/ Clean the text and drop null entries
        
    2/ Clustering Analysis
        2.1/ Tokenizing, stemming and are vectorized using NLTK's TF-IDF vectorizer
        2.2/ From the TF-IDF matrix, the similarity distances between the texts are computed by substracting the cosine of vectors from 1.
        2.3/ Using Unsupervised learning techniques Kmeans, DBSCAN, Hierchy & natural language processing (NLP) 
        2.4/ Finally, recommendations are queried using the matrix: once a game is selected, the top 5 closest games are returned.
    
    3/ Web App Development
        3.1/ Using Streamlit to build local Web
        3.2/ To be... Deploy global Web App