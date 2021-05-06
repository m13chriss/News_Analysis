# News Analysis



This project attempts to see if there any relationship between the images used in news articles and the sentiment expressed in them. We use Cloudmersive Image Recognition API and Natural Language Processing(NLP) python package Flair for this purpose. In the following sections we first extract the articles and the corresponding images, transform the data to then input it into Image Recognition software and perform sentiment analysis. Finally, we visualise the results in bar charts. We focus on such characteristics of the images in each article as number of of people on the picture, their age and gender and compare their presence with the sentiment of the article ("POSITIVE/NEGATIVE").

You can run each specific section separately, however, each API requires a new key, that can be acquired on the corresponding websites. Be aware that recreating the same output from the first section is impossible, as the API searches for contemporary news, and that set changes all the time. For this purpose we provide the data.csv dataframe, which is loaded in the beginning of each section. However, should you decide to run the code from beginning to bottom via adding new API keys, the code will work nonetheless even with new data.

As the project only uses free access APIs and packages, the sample is very small. Thus, the analysis is in no way aimed at deriving any conslusive results, but performed as an illustration of how existing neural networks software can be used for quantitative analysis of qualititative data.
