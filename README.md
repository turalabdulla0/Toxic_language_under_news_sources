Do news accounts differ in how much bigoted or toxic language they use and attract?

Overview

Twitter has grown more divisive because of its approach to content regulation since Elon Musk acquired the company in 2022 and downsized it by dismissing the majority of its moderation and trust & safety teams. On the platform, which has since been rebranded as X, a number of researchers and users have noted a discernible increase in hate speech, disinformation, and politically charged discourse. I will investigate the language usage and user behavior of accounts interacting with the most followed news sources in the platform. I aim to analyze the linguistic and sentiment characteristics of posts and comments from the top 100 followed news sources on X focusing on the prevalence of bigoted language and coded expressions (dogwhistles) in the comments or the post content itself.

Data Collection

For this project, I will collect data from X (formerly Twitter) using the open-source Python library snscrape, which allows scraping of publicly available posts without requiring API access. I plan to gather tweets from the top 100 most-followed news accounts. For each account, I will extract tweets along with metadata including the posting date, number of likes, retweets, and replies. 
To analyze the content, I will apply sentiment analysis. Additionally, I will use pre-trained toxicity and hate-speech detection models to identify racist, misogynistic, homophobic, and other forms of bigoted language. I will try to find correlation between the amount of toxic language used in the replies with the political leaning of the news source, the amount of likes and views the post has, and the date that it was posted. I will try to answer these key questions:
•	Does the political leaning of a news outlet have an effect on the amount of toxic speech it attracts?
•	Does posts with more toxic language in the comments have more views and likes or is it the other way around? Do popular posts attract more hate speech?
