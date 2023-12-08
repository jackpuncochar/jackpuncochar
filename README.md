👋 Hi, I’m Jack Puncochar, welcome to my data science portfolio! Here is an overview of some of my recent projects.

# College Football Play-by-Play Simulation for Daily Fantasy

- **Objective:** Simulate college football games play-by-play using OOP in Python to develop fantasy projections. 
- **Technologies Used:** 'cfbfastR', R, Python, pandas, Matplotlib, numpy, object-oriented programming.
- **Methods:** A Reddit user developed a play-by-play simulation of NFL games https://www.reddit.com/r/nfl/comments/ew9dog/comment/fg20mw0/ to predict game results. I wanted to apply these methods to college football data and take it a step further by tracking player results. The basis of the simulation was a combination of game logic/rules and several fairly simple linear and logistic regression models that predicted key events in a football game. 
- **Results:** Football is a complex game. Several variables impact how a game plays out. Currently, the simulation can provide realistic results of football games and realistic distributions of player statistics; however, I have yet to incorporate team and player skill, which is a huge component of each play. The complexity of the simulation has no bounds, and I hope to iterate on this in the future.

## Project Description and Code

https://github.com/jackpuncochar/cfb-simulation

# Financial Consultant Chatbot Using Cosine Similarity

- **Objective:** Develop a chatbot that answers finance-related questions. Learn how chatbots work without getting into the complexity of large language models. Generative content is gaining popularity as companies look to automate customer service and even answer questions that employees might have regarding internal documents and processes.
- **Technologies Used:** Python, pandas, nltk, TfidVectorizer, cosine_similarity, HTML, CSS, Flask
- **Methods:** I used ChatGPT to produce 100 questions and answers related to finance and saved the results to a .csv file. Then, I used cosine similarity to find the question in the .csv that matched the user's input the closest. I pre-processed the user's input such as removing stopwords, lemmatization, and stemming (algorithms that attempt to get the true meaning of a word). The chatbot was built using Flask app and some pretty basic HTML/CSS code.  
- **Results:** The results were as expected. The chatbot was able to pull from a base of questions/answers to answer the closest-matched question. It was also able to handle the case where a user's question was irrelevant. Future steps include saving a user's input if a similar question does not exist in the file, and utilizing large language models to generate more personal and nuanced responses. 

## Project Description and Code

https://github.com/jackpuncochar/financial-chatbot

## Skills and Technologies

- **Programming Languages:** Python, R
- **Libraries and Frameworks:** Pandas, NumPy, scikit-learn, TensorFlow, nltk, dplyr
- **Database:** SQL
- **Visualization:** Matplotlib, Seaborn, Plotly, ggplot, Tableau

## Contact Information

- **LinkedIn:** https://www.linkedin.com/in/jack-puncochar/
- **Email:** puncochar.jackr@gmail.com

## About Me

I have a Master's in Data Science from the University of Wisconsin - Green Bay. I am very interested in how I can leverage data to build cool things. I especially love how much sports data is out there. With the increase in the popularity of sports betting, there will be several use cases for projects similar to the ones I have already developed.

Feel free to explore each of my projects.

<!---
jackpuncochar/jackpuncochar is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
