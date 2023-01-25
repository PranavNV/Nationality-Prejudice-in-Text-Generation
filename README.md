# Populism-in-Text-Generation

## Objective
This project focuses on the analysis of text generation models such as GPT-2 to identify and understand populistic behaviours or biases against various nationality. 

## Abstract
Little attention is placed on analyzing nationality bias in language models, especially when nationality is highly used as a factor in increasing the performance of social NLP models. This project examines how a text generation model, GPT-2, accentuates pre-existing societal stereotypes about country-based demonyms. We generate stories using GPT-2 for various nationalities and use sensitivity analysis to explore how the number of internet users and the country's economic status impacts the sentiment of the stories. To reduce the propagation of stereotypes through large language models (LLM), we explore the debiasing method of adversarial triggering. Our results show that GPT-2 demonstrates significant bias against countries with lower internet users, and adversarial triggering effectively reduces the same.

## File Description
GPT2_Generated_Stories.xlsx: All the stories generated by GPT-2 for each country. [100 stories for each country with a total of 193 countries]
CountryInternetUsage.csv: Contains the Total Gross Income, Internet Usage Population and the Sentiment Score obtained for each country. 
Internet_Users_Cleaned.csv: Contains the total number of internet users in all countries for the year of 2019 and 2020.
Demonym_Adjective_List.csv: Contains the frequency of all the adjectives that are associated to each country from the stories generated by GPT-2.
Hand_Writted.cscv: Contains human written news articles associated to selected countries. 
Story_Adjective_List: Contains adjectives classified as positive and negative for each country. 
Story_Mean: Contains all sentiment and toxicity parameters calculated for stories generated by GPT2.

## Paper
Venkit, P., Gautam, S., Panchanadikar, R., Huang, K., Wilson, S. (2023). Analysis of Accentuation of Stereotypes by Text Generation GPT-2 Model.
