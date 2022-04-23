# Game_Analysis
![image](https://user-images.githubusercontent.com/51332449/163271754-6e662d9b-5f96-4a57-8ec6-9a2b63716870.png)
## 💪 Motivation  
[As of 2021, there are over two billion gamers across the world, which is 26% of the world’s population <br />
In 2020, the gaming industry generated $155 billion in revenue, which is predicted to grow to more than $260 billion by 2025](https://www.investopedia.com/articles/investing/053115/how-video-game-industry-changing.asp ) 
## 🤷‍♂️ About
Mini project for SC1015 (Introduction To Data Science And Artificial Intelligence) <br />
Aim to predict the Games Sales using data from [Kaggle Video Games Sales Dataset](https://www.kaggle.com/datasets/sidtwr/videogames-sales-dataset?select=Video_Games_Sales_as_at_22_Dec_2016.csv)


## 💻 Contributors
- [Tan Meng Hong](https://github.com/MangoTMH) (Exploratory data analysis)
- [Brian Lua](https://github.com/Sealpillow) (Linear regression, Github)
- [Ernest Lee](https://github.com/dihcuierc) (Ridge, Lasso, Random Forest Regression, Importance values)  <br />                                       
![penguin](https://user-images.githubusercontent.com/51332449/163318284-c45377c4-3194-4cd6-b0bf-88ce4401f528.gif)


## 🔍 Problem
- Are we able to predict global sales?
- What factors affect global sales for video games?
- Which regression model would be best fit to show relationship?

## 📈 Model Used
- Linear Regression
- Random Forest Regression
- Ridge, Lasso Regression

## ✏️ Steps we took
1. [Cleaning and Restructure](https://github.com/Sealpillow/Game_Analysis/blob/main/NoteBooks/1.%20Cleaning%20and%20Restructure.ipynb) 
  ```
   - In this notebook, we did basic data preparation, by removing columns contains NaN values. 
   - Restructuring from a Dataset having 583 Publisher to top 20 Publisher with the most number of sales
   - Removing presence big outlier, which belonged to the data for ‘Wii Sports’.
   - We felt that this data would greatly affect the model between the variables and Global Sales.
  ```
2. [Data Visual](https://github.com/Sealpillow/Game_Analysis/blob/main/NoteBooks/2.%20Data%20Visual.ipynb)
  ```
   - In this notebook, we plotted multiple Countplots
   - Based on Publisher, Genre, Platform, Year of Release
   - We also plotted Boxplots for variables: Critic score, User score, Platform, Publisher, Genre,
     against Global Sales
   - Ending off with a heat map, showing the correlation between all the variables.
  ```
3. [Linear Regression](https://github.com/Sealpillow/Game_Analysis/blob/main/NoteBooks/3.%20Linear%20Regression.ipynb)
  ```
   - In this notebook, we plotted multiple Linear regression models against Global Sales 
   - Based on Critic Score,User Score, Year of Release and Critic Score with User Score as a combined variable
  ```
4. [Removing Outliers](https://github.com/Sealpillow/Game_Analysis/blob/main/NoteBooks/4.%20Removing%20Outliers.ipynb)
  ```
   - In this notebook, we removed outliers to further clean the dataset.
  ```
5. [Linear Regression After Filter](https://github.com/Sealpillow/Game_Analysis/blob/main/NoteBooks/5.%20Linear%20Regression%20After%20Filter.ipynb)
  ```
   - In this notebook, we plotted multiple Linear regression models against Global Sales 
   - Based on Critic Score and User Score to check any improvement in Linear Regression Model
  ```
6. [Random Forest Regression](https://github.com/Sealpillow/Game_Analysis/blob/main/NoteBooks/6.%20Random%20forest.ipynb)
  ```
  - In this notebook, we plotted non-linear regression using Random Forest regression
  ```
9. [Lasso, Ridge Regression, Importance Values](https://github.com/Sealpillow/Game_Analysis/blob/main/NoteBooks/7.%20Lasso%2C%20Ridge%2C%20Importance%20value.ipynb)
  ```
  - In this notebook, we plotted did Lasso and Ridge regression
  - We then determined the importance of each subcategory(Genre, Publisher, Rating, Platform) 
    and what games Game Creators should create
  ```
## 💡 Conclusion
From our machine learning we learnt the following. Video game creators should create a simulation game as it would generate the highest global sales. They should also liaise with Nintendo as they have the highest probability of generating highest revenue and the game rating is recommended to be ‘AO’. We also recommend that games be created on the PS2 or Wii platform as they are the more popular gaming platforms and would have the highest global sales. 

However, we do note that these variables in the data set are not the only factors that can affect the sales of a video game. Factors such as advertisement, quality of the game and improvements in technology in the gaming industry, can help to boost the sales of the games greatly, which will hinder the effectiveness of our model.

![ezgif com-gif-maker](https://user-images.githubusercontent.com/51332449/163321790-eaedd7db-3bb6-457e-98da-496c29c0b3e7.gif)

## 📖 Application of Knowledge
1. Exploratory Data Analysis
2. Cleaning DataSet (Drop Nan, Remove Outliers)
3. Use of plots (Boxplot, Catplot, Countplot, Heatmap)
4. Correlations
5. Linear Regression

## 📚 Something new we learn from this project
1. [Obtaining the top 20 Publisher based on count](https://stackoverflow.com/questions/46623583/seaborn-countplot-order-categories-by-count)
2. [Changing Categorical Data to one hot values](https://www.youtube.com/watch?v=7EgN_71Xtdw)
3. [Export DataFrame to CSV](https://datatofish.com/export-dataframe-to-csv/)
4. [Random Forest Regression](https://towardsdatascience.com/random-forest-in-python-24d0893d51c0)
5. [Lasso, Ridge Regression](https://www.pluralsight.com/guides/linear-lasso-ridge-regression-scikit-learn)
6. [Importance feature](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Ridge.html)
7. [Collab work using Google Colab](https://colab.research.google.com)
