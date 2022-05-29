# Movie Recommendation Engine
The code for building a content based movie recommendation system could be found in this repository.

## **What Is a Recommendation Engine?**
A recommendation engine is a data filtering tool that use machine learning algorithms to suggest the most relevant products to a certain user or customer. It works on the premise of identifying patterns in customer behavior data, which can be collected either implicitly or explicitly.

## **What Sorts of Recommendation Engines Are All there?**
Collaborative filtering, content-based filtering, and a mix of the two are the three main types of recommendation engines.
![This is an image](https://miro.medium.com/max/1300/1*a1JCAwOr5_TVJWlzg44BKg.png)

### **Content-Baesd Filtering**
Content-based filtering works on the principle that if you like a particular item, you will also like this other item. To make recommendations, algorithms use a profile of the customer’s preferences and a description of an item (genre, product type, color, word length) to work out the similarity of items using cosine and Euclidean distances. 

### **Collaborative Filtering**
Collaborative filtering is the process of gathering and analysing data on user behaviour, activities, and preferences in order to forecast what a user will like based on their similarities to other users. Collaborative filtering use a matrix-style method to plot and calculate these similarities.

### **Hybrid Model**
A hybrid recommendation engine considers both meta (collaborative) and transactional (content-based) data when making recommendations. As a result, it outperforms both.

## **How Does a Recommendation Engine Work?**
A recommendation engine uses a combination of data and machine learning technologies to make recommendations. Data is critical in the creation of a recommendation engine since it is the foundation from which patterns are created. It will be more efficient and effective in making appropriate revenue-generating ideas if it has more data.

Recommendation engines execute a four-step operation:

**Step 1: Data collection**: Gathering data is the first and most critical stage in constructing a recommendation engine. 
There are two types of data that must be gathered:
- **Implicit Data** 
- **Explicit Data**

**Step 2: Data storage**: After the data has been gathered, it must be kept. The amount of data will expand enormously over time. This necessitates the availability of substantial, scalable storage. Different forms of storage are available depending on the sort of data you collect.

**Step 3: Data analysis**: The data must then be explored down into and examined before it can be used. You can analyze the data in a multitude of ways. These are some of them:
- **Real-time analysis**: Data is processed in real time.
- **Batch analysis**: Data is handled on a regular basis.
- **Near real time analysis**: When data isn't needed right away, it's analysed in minutes rather than seconds.

**Step 4: Data filtering:** Filtering is the final stage. Depending on whether collaborative, content-based, or hybrid model recommendation filtering is employed, different matrixes or mathematical rules and formulas are applied to the data. The recommendations are the result of this filtering.

## **Cosine Similarity**
This formulation, also known as vector-based similarity, considers two objects and their ratings as vectors, and defines similarity as the angle between them:
![This is an image](https://www.machinelearningplus.com/wp-content/uploads/2018/10/soft-cosine.png)
![This is an image](https://wikimedia.org/api/rest_v1/media/math/render/svg/0a4c9a778656537624a3303e646559a429868863)

## **Flowchart of recommendation engine**
![This is an image](https://www.analyticsvidhya.com/wp-content/uploads/2015/08/3.jpg)

## **Recommender**
- The user can select his favourite movie (or the movie on the basis of which he wants the system to recommend movies).
- Recommendations are created based on the user's input by ordering the similarities in descending order.

## **Lets Get Started**
Now we will create a movie recommendation system in Python using streamlit, CSS, and a Jupyter notebook, in which we'll leverage a user's previous viewing experience to forecast movie recommendations.

## **Steps**
Step 1. **Download tmdb 5000 movies dataset**
- tmdb_5000_movies.csv
https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv
- tmdb_5000_credits.csv
https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_credits.csv

**unzip both data files and save as tmdb_5000_movieslist.csv & tmdb_5000_creditslist.csv respectively**

Step 2. **Launch Jupyter Notebook**
- Create a new folder named Movie Recommendation Engine Sytem
- Create a new sub folder named Movie Recommendation Engine under Movie Recommendation Engine System
- Upload both unzip data set in the sub folder
- Create a new python 3 file named recommendation engine under sub folder
- copy the code from recommendation engine sytstem.ipynb
- run each line of code
- you will see two new folder named movie_list.pkl & similarity.pkl will be formed in the sub folder  
