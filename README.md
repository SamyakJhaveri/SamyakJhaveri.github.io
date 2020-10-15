# Hello! 
## Glad that you're interested in the projects and research-work
This is a repository that holds the GitHub Pages profile of Samyak Jhaveri

## [Investment Aid using Deep Learning and NLP](https://github.com/SamyakJhaveri/Investment-Aid-using-Deep-Learning-and-NLP)
 - Collected and performed data engineering on the dynamic NIFTY-50 Stock Market Dataset that had Open, High, Low, Close, and Turnover values of 50 most influential Indian companies from June 2000 to June 2020 and ongoing. 
 - Trained a baseline linear regression model that obtained an accuracy of 65 %. 
 - LSTMs neural networks are special types of Recurrent neural networks that have loops in them, allowing information to persist. This means that not only were they able to update the weights of their nodes frequently, but they were also able to take into consideration previous weights, which makes them ideal for time-series data such as stock price data.
 - With a 9-layer neural network, having 4 50-node LSTM layers followed alternatively by 4 0.2 dropout layers and the last layer being a Dense layer with adam optimizer and mean squared error as the loss function, the model trained over 100 epochs to give an RMSE value of 13.896. 
 - To incorporate an NLP model to assess twitter or news data we have so far tried to generate a time series dataset of all the news or twitter feed related to each of the companies in the NIFTY-50 dataset and append the news entry of that day with the respective stock price of that company in the dataset. 
 - On this new dataset, we used sentiment analysis models like Bag-of-Words as a baseline and chose to test with Word2Vec, BERT, NLTIK, and ERNIE to generate scores on a scale of +10 to -10 with +10 being extremely positive for the stock’s health to -10 being the worst. 
 - The entire system updates its news scores when stock prices correlated to a particular type of news reaches new extremes. 
 - Unique because it is designed for the Indian stock market and news and deployed on a cross-platform framework for the novice investor, democratizing stock market investment and reducing reliance on other players. 
 ### Challenges:
 - Preparing a dataset of the Indian stock market on the Nifty-50 index, 
 - Correlate with the corresponding news/twitter feed of that company for that day,
 - Building a language processing model that dynamically generates vector scores of the news’/twitter feeds’ effect on the stock price and updates the LSTM model accordingly 
### Further Work
We intend to build a pipeline for this entire process to work in flow with real-time daily stock price data and news data as input which would pass from the feature engineering and correlation module to the feature loading model, and finally to the model training and testing modules. The models will be trained and updated on a GPU accelerated platform, like Kaggle’s or on Google Colab.

## [Air Quality Index from Satellite Imagery](https://github.com/SamyakJhaveri/DA-IICT-Internship)
Under the guidance of Prof. Srimanta Mandal (DA-IICT, Gandhinagar). 
- Using a deep learning model trained on an open-source multispectral satellite image dataset to determine the AQI of a given region and suggest insights about that region. 
### Challenge:
Extracting and engineering the data features to assess air quality from subtle characteristics in the satellite images without on-ground sensors. 
### APIs Used:
- Google Earth Engine API
- Azavea’s Raster Vision API
- Planet.com’s remote sensing API. 
### Further work
I intend to publish this project at an international conference in early 2021.

## [Machine Learning Internship at SilverTouch](https://github.com/SamyakJhaveri/Dropout-Prediction)  
Course Dropout Prediction model and MOOC Course Recommendation System Architecture
- The purpose of this project was to add personalization to the MOOC experience using a course recommendation system that utilizes web tracklogs and test results to assess cognitive performance and make course recommendations accordingly.
- Designed architecture of course recommendation system for MOOC platform
- Dataset included web tracking logs open-source dataset from XuetangX, a Chinese MOOC learning platform initiated by Tsinghua University that signed a contract with edX, to acquire the exclusive authorization of edX’s high-quality international courses
- A preliminary EDA revealed that the dataset has information of roughly 155000 unique students studying a total of 247 courses from the MOOC platform, taking up 5.4 GB of memory.
- Trained, tested and benchmarked dropout prediction model with accuracy of 81.87 %,  a considerable improvement over the results of previous papers we cited ranging from 65 - 78 % accuracy

## [Undergraduate Research Internship at UC Irvine](https://github.com/SamyakJhaveri/spacetime-apps)
- Worked directly with PhD students and faculty
- Developed a fully-functional multiplayer ’snake’ game on the Spacetime framework, an open source researchplatform pushing the boundaries of distributed shared state
- Even at varied frequencies of dataframe checkouts, the application was resilient enough to continue normal functioning in single-player, all-human multiplayer, human-bot multiplayer, and all-bot multiplayer settings.
- The game provides a means to test the usability of the framework and acts as a platform for a world-wide reinforcement learning ’bot’ competition
- Participated  in  several  research  events  and  meetings,  such  as  the  Southern  California  Software  Engineering Symposium (June 7), and meetings with researchers who visited the PhD group during this period


## [Detecting Cotton Disease with Transfer Learning](https://github.com/SamyakJhaveri/Plant-Disease-Classification)
- Trained and tested cotton plant disease detection model using TensorFlow Hub’s transfer learning feature
- Obtained 96.7% accuracy and deployed model on Android app



