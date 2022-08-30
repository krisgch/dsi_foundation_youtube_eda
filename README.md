# DSI Python Foundation Capstone Project:
## Exploratory Data Analysis on 'Dog Training' YouTube Channels
---
### Table of content
* [Project Overview](#project-overview)
* [Problem Statement](#problem-statement)
* [Goal and Target](#goal)
* [Social Impact](#social-impact)
* [Hypotheses](#hypotheses)
* [Technologies](#technologies)
* [Project Scope](#project-scope)
* [Future Investigation](#future-investigation)
* [Source](#source)
---
### Project Overview
This project is part of TDA's DSI Python Foundation Capstone Project, as a key requirement to complete the course. Combining my passion of data analysis and dog training, I've chosen to analyse 'dog training' YouTube channels in order to identify key insights and good practices done by other channels. The ultimate goal of this project is to grow my own 'dog training' YouTube channel to become an educational platform that are more accessible to Thai people, which will eventually lower the number of unethical breeders/trainers in Thailand.

__Here are the 5 strategies that we can follow, to grow our 'dog training' youtube channel:__
1. __Contents that are more generic__ will relate to more audience, potentially increasing the number of subscribers and ultimately increases the number of views per videos.
2. __Video duration should be kept around 10 minutes__, as long videos tend to be too intimidating for people to watch, and short videos could easily be disregarded as not enough content to worth watching
3. __Writing informative title helps audience grasp key concepts__ of what this video will provide them, and quickly decide whether or not they will want to watch the video.
4. __Publish about 1 video per week__ as this will help maintain an audience that we've built
5. __It is better to post on weekends__ than on weekdays, so I must schedule my publishing day to weekends


### Problem Statement
- Thailand is a country with less dog training knowledge in comparison to Europe or even our neighbor Singapore
- One of the main reason is the lack in available educational resources which has stalled developments of both the training skills of trainers and the knowledge of the people
- Which allows many ‘poor’, ‘abusive’ and ‘unethical’ dog trainers/breeders to easily take advantage of their customers – from selling ineffective (even counter-productive) courses to breeding and selling of unhealthy dogs

### Goal and Target
- Identify key action points to build and expand my own educational dog training YouTube channel by analyzing insights from dog training channels
- Target : +100 subscribers & +100 views per videos

### Social Impact
- "More eduacted dog owners" = "Less unethical/abusive dog trainer/breeders"

### Hypotheses
In order to grow my subscribers and views, I asked the following questions and form my hypothesis:
- Which content relates to the viewers?  		
- Effects of good title writing? 			
- What’s the best video duration?			
- How many times posts per month?		
- Is it better to post on weekdays or weekends?

### Technologies
Project is created with:
- python 3.10.5
- build (googleapiclient.discovery) - for API request
- JSON (IPython.display) 8.2.0 - for easier JSON viewing
- numpy 1.21.5
- pandas 1.4.2
- parser (dateutil) 2.8.2
- isodate 0.6.1
- seaborn 0.11.2
- matplotlib.pyplot 3.5.1
- nltk 3.7
- stopword (nltk.corpus) - make sure we use nltk.download('stopwords')
- WordCloud (wordcloud) 1.8.2.2

### Project Scope
![alt text](https://github.com/krisgch/youtube_api_eda/blob/993a66bde6d98b358784be6b5598955c4dd4a31a/project_pipeline.png)

### Future Investigation
- __Thumbnail__ is another interesting area to investigate, if there is a way to identify custom uploaded thumbnail vs selected frame of uploaded video then that's worth exploring
- Explore the __timeline__ of each channel to identify how each grow their own channel (potentially identifying spikes in subscribers and viewers)
- Compare __contents__ in each video vs performance and comment feedback (categorize each video into specific topics from title keywords)

### Source
API tutorial https://github.com/thu-vu92/youtube-api-analysis
