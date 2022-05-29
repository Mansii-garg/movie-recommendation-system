# movie-recommendation-system

## How to get the API key?
Create an account in (https://www.themoviedb.org/), click on the API link from the left hand sidebar in your account settings and fill all the details to apply for API key. If you are asked for the website URL, just give "NA" if you don't have one. You will see the API key in your API sidebar once your request is approved.

## How to run the project?
1. Clone or download this repository to your local machine.
2. Install all the libraries mentioned in the requirements.txt file with the command pip install -r requirements.txt
3. Run the movie-recommender nb file in jupiter notebook and it it create three pkl file in the notebook directory.
4. Copy these three pkl files and paste them in your project working environment directory.
5. Get your API key from https://www.themoviedb.org/. (Refer the above section on how to get the API key)
6. Open your terminal/command prompt from your project directory and run the file main.py by executing the command streamlit run main.py.
7. Open the localhost link from terminal and thats it.

## How to deploy in Heroku:
1. $ heroku login
2. $ heroku git:clone -a NAME_OF_APP
3. $ heroku git:clone -a NAME_OF_APP
4. $ git add .
5. $ git commit -am "make it better"
6. $ git push heroku master

## Similarity Score :
It is a numerical value ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuring the similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.

## How Cosine Similarity works?
Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.

![2b4a7a82-ad4c-4b2a-b808-e423a334de6f](https://user-images.githubusercontent.com/82320159/170870950-e9023f72-1b27-42ce-8ebb-4a6581a5e487.png)


## Sources of the datasets
https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv
