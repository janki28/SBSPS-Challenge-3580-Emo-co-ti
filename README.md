## Sentiment Analysis of COVID-19 Tweets – Visualization Dashboard


> Problem Statement: The sentiment analysis of Indians after the extension of lockdown announcements to be analyzed with the relevant #tags on twitter and build a predictive
analytics model to understand the behavior of people if the lockdown is further extended. Also develop a dashboard with visualization of people reaction to the govt announcements 
on lockdown extension

> Solution: Using various IBM Cloud and IBM Watson services we have come up with a dash board that gives you the situation of corona in the world as well as in India. After gathering the tweets on lockdown extension dates (fetching them from the tweet ids in the IEEE csv files) and pre-proccessing them we have used many techniques (visualizations, ML etc.) to get better unserstanding of the data and have mad a UI that is interactive, insightful, easy to use for a layman.

### Prerequisites
* To use any IBM Cloud service (Node Red, Tone Anaslyser etc.) an IBM Cloud account is necessary.
* A Twitter developer account to fetch tweets (from id or a topic name).

### Installing
* Various Python Libraries and how t o install them
  * tweepy - pip install tweepy (Helps in getting tweets)
  * textblob - pip install textblob (For getting tweet's subjectivity and polarity)
  * Twython -  pip install Twython (Helps in getting tweets) 
  * WordCloud - pip install wordcloud  (Helps in forming a word cloud)
  * pandas - pip install pandas (Making and Manipulating a dataframe)
  * numpy - pip install numpy(Helps in various vector and matrix calculations)
  * matplotlib- pip install matplotlib (For plotting various visualizations)
  * PIL - pip install PIL(To get a mask in word cloud)
  * sklearn - pip install scikit-learn (For Machine Learning)
  * ibm-watson - pip install ibm-watson (For using the features of a tone analsyer)
  
#### The app contains the following features:

1. Node Red: All our front end code has been designed by the IBM Cloud service Node Red.
 [Node Red](https://node-red-emocoti.mybluemix.net/ui) (For viewing the UI). You can download the json file from the Node-Red folder and change in in your IBM Cloud acount.
2. Cognos Dashboard: We have used the Cognos Dashboard service to plot interactive graphs of various tweets (live as well as stored).
3. Tone Analyzer: We have used this service on cloud as well as in Jupyter notebooks to get the tone of the tweets.
4. Tweet Analyser: This is a feature where in a person can check the sentiment of his tweet before posting it. (Created with the help of Node Red and Tone Analyser)
5. Jupyter Notebooks: All the preprocessing code has been provided in the notebook files and we have provided the csvs (Input and Output both) as well. The input csvs have helped us in fetching  the tweets while the output csvs have been helpful in Cognos Dashboard.

#### Code and Explaination:
Youtube :video_camera: : [Youtube](https://youtu.be/Rv6r3Ey-q9I) <br>
Github :octocat: : [Github](https://github.com/SmartPracticeschool/SBSPS-Challenge-3580-Emo-co-ti)

#### Authors
* Janki Patel
* Aneri Shah
* Sanjeev Khatwani
