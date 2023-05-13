# Critical Introduction


## What does this short essay encompass?

This critical introduction provides a description of my dataset and a brief documentation of how it was collected so that the collection efforts are reproducible. The text also includes a discussion of data collection as a technical appendix to the critical introduction.

This introduction examines the affordances and limits of my dataset, discusses the curatorial choices made in creating the dataset, and contextualizes the dataset in relation to existing scholarship. It argues for the overall significance of this dataset.

Plus, it includes a reflection on issues, problems or discoveries that the process of creating the dataset illuminated, and relates this discussion to readings from the book Data Feminism that were assigned during the DH course in Spring 2022.

## What is this dataset about?
The MeToo movement has been a global phenomenon, with many countries having their own version of the movement by the same terminology, or with its translation in other languages. In Iran, the MeToo movement is relatively new and primarily driven by individual accounts on social media, with no organized social movement organizations involved. To read more about the history of this movement in Iran, you can read chapter 5 of this book.

The dataset in discussion in this critical introduction is a collection of tweets related to the MeToo movement in Iran, gathered before and after the spring of 2022. It is important to note that this dataset does not claim to consist of all relevant tweets available about MeToo movement on this date range in Persian language and on Twitter social platform. 

## What does this dataset consist of?
The dataset was created by targeting various forms of the MeToo hashtag and other relevant hashtags used in the movement in the Persian language. 

## How was this dataset made and what for?

The dataset was created for the main study, which aimed to raise several issues in the way the MeToo movement operates in Iran. We searched for, and eventually found, a contextual pattern for creating themed categories. This gives us and many other scholars a better statistical picture of the reality of topic distribution, the users’ approach to this activism, and the predominantly used vocabulary about sexual assault by Iranian users. Additionally, the research was supposed to answer the question of how and when this movement in Iran, and specifically on Twitter, was launched.
The methodology of the research started with a literature review. The literature review had two parts: First, we reviewed all works on the MeToo movement in Iran and gathered various assumptions regarding our research questions. For instance, we looked at how scholars or journalists analyze the MeToo movement in Iran in terms of users’ vocabulary for referring to or discussing sexual assault on social media, specifically on Twitter. Also, in this first part of the literature review, we looked to see when resources have dated back the MeToo movement in Iran and to which event they related it. There are some books available, such as Performing #MeToo: How not to look away edited by Judith D. Rudakoff, in which a glossary has been offered, and they have tried to find the root of the event on Persian sphere Twitter. Our results demonstrated a different date and a different launching event as the initiation of the MeToo movement in Iran. Second, in our literature review, we went through similar works and analyzed their strategy and data work to see how various scholars Twitter data analysis have done regarding MeToo in the past in various contexts. The deliverable chapter, therefore, consisted of this literature review and the results of our data work.




During the data gathering process, the first issue we encountered was the lack of an umbrella hashtag in the Persian sphere of Twitter. It is not precisely accurate to assume that relevant topics can be found simply by searching for the word MeToo in English or its translation in Persian. Additionally, the movement is still relatively new, as evidenced by the inconsistency in hashtagging, and there is a lack of organized social movement organizations involved to help the Twitter trend or pin a unified terminology for it. In fact, we found multiple hashtags with different terminologies that belonged to social movements in which sexual assault survivors were encouraged to speak up or narratives of sexual assault were spontaneously shared on Twitter with official or anonymous accounts, or users on Twitter were engaged in relevant discussions. This made it challenging to collect data and track the progress of the movement.

Another issue is that the digital movement is primarily based on individual accounts, unlike in its American or Western context, where there are official social media organizations involved. This has made data scraping more challenging. Despite these challenges, we targeted various forms of the hashtag and other relevant ones that we found through trial and error, to create a comprehensive dataset that captures the breadth of the movement. That being said, we have created various datasets with various keywords and hashtags. As the movement has evolved, many new hashtags have been developed, making it important to continually revise the dataset to capture new developments. However, this introduction is about one of them, with this keyword and hashtag: #MeTooIran. The capitalization of letters does not affect the results.


As also mentioned, one of the major challenges in collecting data for this study was the lack of an official social movement organization involved in the MeToo movement in Iran. According to our research, the @me_too_iran account is the only consistent source on Instagram and Twitter that shares narratives about sexual assault and posts relevant content regarding the MeToo movement in Iran, even though it is not officially recognized as a social media organization (SMO) in Iran from institutions. Between August 24, 2020, and February 22, 2022, this account posted a total of 1,780 tweets, out of which 926 were original tweets and the rest were retweets without any additional content. We noticed, this account, used the #MeTooIran for the first time to label relevant tweets. (We did interview the admin of the account to get approval and learn more about how such selection has been made.)


## How was the data collected? 


To collect tweets with the hashtag #MeTooIran on Twitter, we created a developer account and upgraded my account access level to "academic" to enable scraping of tweets older than seven days. We utilized Tweepy, a Python library designed for accessing the Twitter API, to develop a Python code. The output of this code was a CSV file with various columns such as date of creation, tweet text, screen name, name, date of account creation, and URL (for original tweets only). We subsequently removed duplicate entries and Latin characters from tweet texts and manually reviewed each tweet text to identify any patterns that might exist.

We then analyzed tweets from hashtags with the most relevant results, and #MeTooIran provided them with the greatest number of relevant results. This hashtag was mainly and strategically used by the @me_too_iran Twitter account, run by Shaghayegh Norouzi, an Iranian actress and women’s rights activist. The tweets were scraped with the #MeTooIran hashtag using Python code that utilizes the Tweepy library to access the Twitter API. The code can be found here: https://github.com/mspayam/MeTooIran. In total, 1,780 tweets were collected from August 24, 2020, to February 22, 2022, with over half being original tweets and the rest being retweets. 

## What is the importance of this dataset?

The MeToo movement in Iran has highlighted several issues that women and individuals face in the country. The movement has brought attention to sexual harassment, sexual assault, and the culture of victim-blaming in the country. The tweets collected in this study reflect the experiences of mostly female-identifying individuals who have faced sexual harassment and assault in Iran.

One of the most significant themes that emerged from the tweets was the issue of victim-blaming. Many of the tweets focused on the fact that victims of sexual harassment and assault are often blamed for the crimes committed against them. Women are often told that they were somehow responsible for the harassment or assault. After going to analyze the tweets in terms of word counts, interestingly, the word silence was the most repeated words after words such as “sexual” , “assault” or “rape”. We removed them as stop words, as they’re directly pointing to the topic of the content. We were interested to see what words has been most repeated in the narratives themselves. “The word “silence” has been found to be the most repeated word among
the tweets from the category of narratives and reports of sexual assaults,
which can mean most of the survivors have mentioned or pointed out this
concept in some way in their narrative.” (Rezai & Sedaghat Payam, 2023)
“The most common content words here were as follows: 1.58 ,)rape( تجاوز ;sexual), 1.75 percent( جنسی ;narrative), 2.5 percent( روايت تعرض silence), 0.5 percent; and( سکوت ;harassment), 1.58 percent( آزار ;percent (assault), 0.5 percent. The word “silence” was found to be the most repeated content word after predicted topic-relevant words such as “rape,” “harassment,” “sexual,” “narrative,” and “assault.” There are many possible reasons or potential interpretations that make talking about an alleged sex crime complex in a real- life setting in Iran or among Iranians, including cultural and sociopolitical issues or the power dynamics involved in the assault. It seems that social media and this movement specifically have been a platform for these narratives to emerge and stand out, by real names or anonymously. Yet, the word “silence,” whether it is endured or broken, appears to be the most repeated word in the narratives. “(Rezai & Sedaghat Payam, 2023)

One of the challenges we faced in word counts was deciding which stop words to choose. Apart from prepositions or some verb structures in the Persian language that have a similar form to phrasal verbs in English, we wanted to keep the original words from tweets that were anything but the topic of the content. As mentioned earlier, we decided to remove words that are translated as "rape," "sexual," "assault," or "narrative."

## What are other terminology or hashtag trends in Persian used to refer to what is known as MeToo movement in the west?

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



## What were the challenges on the way?
 

An important consideration when analyzing the data is the subjectivity involved in determining what content is labeled as MeToo-related by the @me_too_iran account. The dataset represents the perspective and categorization choices made by this specific account, and it does not encompass all potential narratives or related tweets within the MeToo movement. As mentioned before, we did gather tweets from many other keywords and hashtags as well, and we made the decision to focus on only this term: #MeTooIran.


Undoubtedly, the most significant hurdle in data collection was identifying the optimal keyword that would yield the highest number of tweets relevant to the MeToo movement in Iran. Currently, there is no shared keyword or hashtag among Persian tweets that connects all narratives or related tweets in this movement. However, this research has resulted in a valuable discovery: a comprehensive list of relevant keywords used at various stages of the movement. For instance, the hashtag "tell me about military service" refers to the narratives of male-identifying users who have experienced sexual assault in the presumably single-sex environments of military compulsory service. This opens up the door to valuable narratives from men or the queer community that highlight sexual violence and oppression against the queer community in Iran. While there are various hashtags indicating the MeToo movement, each with distinct terminology, we focused on narratives and tweets labeled by the official page of Me_Too_Iran and separated by #metooiran to narrow down our research. It should be noted that this perspective may not offer a comprehensive view of MeToo movement-relevant tweets, but it provides us with a subjective perspective from the official page of the MeToo movement in Iran. The perspective offered is subjective and from the official page of the MeToo movement in Iran. However, the main reason was that in the absence of an official SMO, we were hoping to shed light on the performance of @me_too_iran’s account as the only known organization dedicated solely to Me Too narratives and sexual assault.


In Chapter 2 of "Data Feminism" by Catherine D'Ignazio and Lauren F. Klein, the importance of considering what data is collected, how it is collected, and what data is left out is explored. The authors argue that data is not neutral and that biases can be reflected in the way data is collected and analyzed. They advocate for a more inclusive and diverse approach to data collection and analysis, which considers the perspectives and experiences of marginalized communities. In applying this framework to the MeToo movement data in the Persian sphere of Twitter, we highlight the importance of acknowledging that the data is not fully inclusive or objective.


Apart from the challenges of choosing the right keyword for this research and acknowledging the shortcomings of such selections and this dataset, we still found this research and creating this dataset to be beneficial. During our trials and errors, we could trace the data to the root of the beginning of this movement. Our first part of the literature review provided various hypotheses of how this movement started. However, our data work (and not only this single dataset), combined with gathering what is thought to be the root of the MeToo movement, has allowed us to pinpoint a root of this movement that not too many scholars have previously agreed with. Our data work supports our finding, and this can be considered one of the benefits of this dataset, rather than giving us a rough picture of how public discourses by Twitter users about sexual assault and the MeToo movement look.


In conclusion, by utilizing this dataset, the origin of the Me Too movement on Twitter in Iran was identified accurately. Various sources proposed different dates for the start of the movement, but analyzing the data pinpointed the precise moment the movement was initiated and helped to comprehend the initial reactions and public sentiments towards it.


Chapter 3 of "Data Feminism" emphasizes the critical role of asking good questions in any data project, as it helps to ensure that data analysis and interpretation are grounded in the needs and experiences of the people who will be affected by the results. Regarding the MeToo movement data in the Persian sphere of Twitter, asking different questions can lead to vastly different data-driven conclusions. For example, why were narratives with certain hashtags not labeled, which body parts and jobs were mentioned most in narratives, and what was the precise moment the Me Too movement was initiated in Iran and what were the initial reactions and public sentiments towards it.





Please copay and paste this link in your browser to access the dataset :
https://docs.google.com/spreadsheets/d/1y-yqSJx-sGl___MjJmeaLL87H3W3hDCT4Xc18nHgl5I/edit#gid=667916914


### Cited Works
- Rezai, Yasamin, and Mehdi Sedaghat Payam. “Twitter Data Analysis on #MeTooIran.” The #MeToo Movement in Iran: Reporting Sexual Violence and Harassment, 2023.

- Rudakoff, Judith, ed. Performing# MeToo: How not to look away. Intellect Books, 2021.
