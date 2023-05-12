# Critical Introduction


This critical introduction provides a description of my dataset and a brief documentation of how it was collected so that the collection efforts are reproducible. The text also includes a discussion of data collection as a technical appendix to the critical introduction.

This introduction examines the affordances and limits of my dataset, discusses the curatorial choices made in creating the dataset, and contextualizes the dataset in relation to existing scholarship. It argues for the overall significance of this dataset.

Plus, it includes a reflection on issues, problems or discoveries that the process of creating the dataset illuminated, and relates this discussion to readings from the book Data Feminism that were assigned during the DH course in Spring 2022.

The MeToo movement has been a global phenomenon, with many countries having their own version of the movement. In Iran, the MeToo movement is relatively new and primarily driven by individual accounts on social media, with no organized social movement organizations involved. The data used in this study focuses on tweets related to the MeToo movement in Iran, collected before and after the spring of 2022. The dataset was created by targeting various forms of the MeToo hashtag and other relevant hashtags used in the movement in the Persian language.


The main study intended to raise several issues in the way the MeToo movement operates in Iran. In the process of data gathering, the first issue is related to the lack of an umbrella hashtag in the Persian sphere of Twitter. The movement is still relatively new, as evidenced by the inconsistency in hashtagging, and also there is a lack of organized social movement organizations involved. This makes it challenging to collect data and track the progress of the movement.


Another issue is that the digital movement is primarily based on individual accounts, unlike in its American context that there are Social Media Organizations doing it. This has made data scraping more challenging. Despite these challenges, the authors targeted various forms of the hashtag and other relevant ones to create a comprehensive dataset that captures the breadth of the movement. As the movement has evolved, many new hashtags have been developed, making it important to continually revise the dataset to capture new developments.

As also mentioned, one of the major challenges in collecting data for this study was the lack of an official social movement organization involved in the MeToo movement in Iran. The @me_too_iran account is the only consistent source on Instagram and Twitter that shares narratives about sexual assault and posts relevant content regarding the MeToo movement in Iran, even though it is not officially recognized as a social media organization (SMO) in Iran. Between August 24, 2020, and February 22, 2022, this account posted a total of 1,780 tweets, out of which 926 were original tweets and the rest were retweets without any additional content.

To collect tweets with the hashtag #MeTooIran on Twitter,we created a developer account and upgraded my account access level to "academic" to enable scraping of tweets older than seven days. We utilized Tweepy, a Python library designed for accessing the Twitter API, to develop a Python code. The output of this code was a CSV file with various columns such as date of creation, tweet text, screen name, name, date of account creation, and URL (for original tweets only). We subsequently removed duplicate entries and Latin characters from tweet texts and manually reviewed each tweet text to identify any patterns that might exist.

We then analyzed tweets from hashtags with the most relevant results, and #MeTooIran provided them with the greatest number of relevant results. This hashtag was mainly and strategically used by the @me_too_iran Twitter account, run by Shaghayegh Norouzi, an Iranian actress and women’s rights activist. The tweets were scraped with the #MeTooIran hashtag using Python code that utilizes the Tweepy library to access the Twitter API. In total, 1,780 tweets were collected from August 24, 2020, to February 22, 2022, with over half being original tweets and the rest being retweets.

The MeToo movement in Iran has highlighted several issues that women and individuals face in the country. The movement has brought attention to sexual harassment, sexual assault, and the culture of victim-blaming in the country. The tweets collected in this study reflect the experiences of mostly female-identifying individuals who have faced sexual harassment and assault in Iran.

One of the most significant themes that emerged from the tweets was the issue of victim-blaming. Many of the tweets focused on the fact that victims of sexual harassment and assault are often blamed for the crimes committed against them. Women are often told that they were somehow responsible for the harassment or assault.


The dataset utilized in this study focuses on tweets pertaining to the #MeToo movement in Iran which were labeled subjectively by @me_too_iran account. The data was collected before and after the spring of 2022, and it was obtained by targeting different variations of the #MeToo hashtag and other relevant hashtags used within the Persian Twitter community. It is crucial to acknowledge that there isn't a single overarching hashtag in the Persian Twitter sphere for the #MeToo movement. Instead, multiple hashtags are associated with this movement in Iran. Below you can see some hashtags that was primarily tried in the procedure of data collection, and they are identified to be relevant to Me Too movement in Iran:


) چرا_گزارش_ندادم why I didn’t report)
می_تو )me_too)
خشونت_جنسی ((sexual violence)
قربانی_نکوهی (victim blaming)
قربانی_نکوهی_نکنیم (no to victim blaming)
من_هم_سکوت_نمیکنم (I won’t stay silent either)
تجاوز(rape)
نام_متجاوز_را_بگو (say out your rapist’s name)
من_هم_سکوت_نخواهم_کرد ( I am not going to stay silent either)
زنان_میتو‌(women of metoo)
چرا_گزارش_نکردم (why I didn’t report)
باجگیری_جنسی (sexual blackmail)
روايت_آزار (harassment narrative)
علیه_فرهنگ_تجاوز (against the rape culture)






Given the evolving nature of the movement, continuous revisions of the dataset were necessary to incorporate new developments. However, we decided to choose what @me_too_account was chose to label by #metooiran. 

Among the various keywords and hashtags examined, the #MeTooIran hashtag provided the highest number of relevant tweets. This hashtag was predominantly used by the @me_too_iran Twitter account, managed by Shaghayegh Norouzi, an Iranian actress and women's rights activist. The tweets associated with the #MeTooIran hashtag were collected using a Python code that utilized the Tweepy library to access the Twitter API. The code for this process can be found at https://github.com/mspayam/MeTooIran. The output of the code was a CSV file with multiple columns, including the date of creation, tweet text, screen name, name, date the account was created, and URL (limited to original tweets only).

 Duplicate entries were removed, Latin characters were excluded from the tweet texts, and individual review of the tweet texts was conducted to identify any discernible patterns. In total, 1,780 tweets were collected between August 24, 2020, and February 22, 2022, with over half of them being original tweets and the remainder being retweets.


An important consideration when analyzing the data is the subjectivity involved in determining what content is labeled as MeToo-related by the @me_too_iran account. The dataset represents the perspective and categorization choices made by this specific account, and it does not encompass all potential narratives or related tweets within the MeToo movement.



Identifying the optimal keyword to collect tweets relevant to the MeToo movement in Iran posed the most significant obstacle in data collection. Currently, there is no shared keyword or hashtag that connects all narratives or related tweets in this movement, but the research yielded a valuable discovery: a comprehensive list of relevant keywords used at various stages of the movement. The official page of Me_Too_Iran labeled narratives and tweets separated by #metooiran, which narrowed down the research, although it may not provide a comprehensive view of MeToo movement-relevant tweets. The perspective offered is subjective and from the official page of the MeToo movement in Iran.

In Chapter 2 of "Data Feminism" by Catherine D'Ignazio and Lauren F. Klein, the importance of considering what data is collected, how it is collected, and what data is left out is explored. The authors argue that data is not neutral and that biases can be reflected in the way data is collected and analyzed. They advocate for a more inclusive and diverse approach to data collection and analysis, which considers the perspectives and experiences of marginalized communities. In applying this framework to the MeToo movement data in the Persian sphere of Twitter, we highlight the importance of acknowledging that the data is not fully inclusive or objective. It is not inclusive in the terms that narratives from hashtag trends such as "tell meabout your military service" (translatedby me from Persian to English) has not been considered, as an example. This trend encompasses lot of narratives from male-identifying or queer individuals who have been sexually assaulted during the obligatory military service.

Chapter 3 of "Data Feminism" emphasizes the critical role of asking good questions in any data project, as it helps to ensure that data analysis and interpretation are grounded in the needs and experiences of the people who will be affected by the results. Regarding the MeToo movement data in the Persian sphere of Twitter, asking different questions can lead to vastly different data-driven conclusions. For example, why were narratives with certain hashtags not labeled, which body parts and jobs were mentioned most in narratives, and what was the precise moment the Me Too movement was initiated in Iran and what were the initial reactions and public sentiments towards it.

By utilizing this dataset, the origin of the Me Too movement on Twitter in Iran was identified accurately. Various sources proposed different dates for the start of the movement, but analyzing the data pinpointed the precise moment the movement was initiated and helped to comprehend the initial reactions and public sentiments towards it.





Please copay and paste this link in your browser to access the dataset :
https://docs.google.com/spreadsheets/d/1y-yqSJx-sGl___MjJmeaLL87H3W3hDCT4Xc18nHgl5I/edit#gid=667916914
