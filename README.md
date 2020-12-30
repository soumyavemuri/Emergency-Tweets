# Emergency Tweets

Many people around the world face unfortunate circumstances everyday. These people may require immediate aid and are dependent on others for help. The situation they are in could be classified as one of the following:

    1) Life Threats
    3) Nature Calamities
    4) Financial Issues

**Millions of users are on Twitter everyday. Our team thought that with the help of the Twitter platform, we could find a way to get tweets of users in need of help better reach. By this we could immediately connecct them with individuals that can offer them with assistance.**

We achived this by developing a feature on our Twitter clone by adding an additional section on the sidebar of Twitter. This will direct the user to the `Emergency Tweets` section where we categorise these tweets as General, Immediate, and #TwitterSOS.

<img src="https://github.com/Mugunthanraju/Emergency-Tweets/blob/main/ScreenShot/image.png" alt="Twitter Application" >

### How it's been built:

**The frontend was developed using React.js and the REST API was developed using Django. The Twitter API was used on the backend with Python, sklearn, nltk and Watson NLU API**

**The Twitter Search API is used to retrieve tweets based on queries developed after a thorough discussion and research on keywords used in tweets calling out for help. The categories can be selected from the display on the right side of the user dashboard.**

*For flagging and color coding tweets we have a combined model.*

**1) A Sarcasm Detector model filters out sarcastic tweets from the tweets returned by the Twitter API.**
<br>
**2) A Fear Detector checks for a fear in the tweets of the user that was developed by using IBM Watson NLU API.**
<br>
**3) If the tweet is not sarcastic and has fear elements, then the NLP model classifies those tweets as Immediate Attention, General(Funds/Donations), and #TwitterSOS.**


<img src="https://github.com/Mugunthanraju/Emergency-Tweets/blob/main/ScreenShot/Steps.jpg" alt="Twitter Application" >


### Developed by : 

    1) Ekrem Guzelyel (ML, Backend)
    2) Mugunthan Raju (Front-end, Database)
    3) Mert Can Bilgiç (Front-End)
    4) Soumya Vemuri (Full-Stack/REST API)
    5) Pranav Anand (ML, Backend)
