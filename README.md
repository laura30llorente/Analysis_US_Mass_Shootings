# US Mass Shootings Analysis (1966-2017)
Analysis of a Kaggle dataset: Mass Shootings in the United States (1966-2017), using text mining techniques and social network analysis to extract deeper insights from the data.

## Data Source
The dataset used in this project was obtained from Kaggle: [US Mass Shootings](https://www.kaggle.com/datasets).  
The specific version used is: **Mass Shootings Dataset Ver 5**.

## Introduction
This project focuses on the analysis of mass shootings in the United States between 1966 and 2017. During this period of over five decades, 398 mass shootings occurred across the country, resulting in 1,996 fatalities and 2,488 injuries. The analysis of this phenomenon is not only crucial for its social and humanitarian impact but also for the political and public policy implications it brings.

The dataset includes detailed information about each of these violent incidents, providing critical context such as location, date, incident summary, and demographic and psychological information about the attackers, including race, gender, and mental health status. It also includes precise geographic information, allowing for in-depth spatial analysis.

## Project Overview
The purpose of this project is to leverage **text mining** and **social network analysis (SNA)** techniques to extract deeper insights from the data. Through text mining, we aim to better understand the circumstances and characteristics associated with these events. Additionally, SNA will allow us to visualize and analyze patterns and relationships that emerge from the data, such as connections between incidents based on common characteristics or patterns of victimization.

In this analysis, I have employed various techniques including **text mining**, **social network analysis (SNA)**, and **large language models (LLMs)**. These methods have enabled me to extract valuable insights and offer a deeper understanding of the events.

## Text Mining
Several tools and libraries were used to perform quantitative text analysis:

- **Quanteda**: for quantitative text analysis.
- **Tidytext**: for manipulation and analysis of tidy data.
- **Topicmodels**: for topic modeling, including **Latent Dirichlet Allocation (LDA)**.
- **SentimentAnalysis**: to evaluate the sentiments and emotions associated with the incident descriptions.

These techniques helped identify recurring patterns and specific characteristics of the shootings, such as declared motivations and the mental states of the attackers.

## Social Network Analysis (SNA)
SNA was used to visualize the connections between different incidents based on their relation to the target (victims, location, etc.). By constructing a graph, I identified communities within the network and examined which incidents were most prominent in the generated graph. This helped highlight patterns and connections between different shootings.

## Deep Language Models (LLMs)
I employed large language models (LLMs), specifically **Hugging Face's BERT model**, to extract additional details from the incident summaries. This process automatically retrieved the location of each shooting from the text, providing a more detailed and specific understanding of where the events occurred. This method not only filled in missing location fields but also offered precise information on establishments, buildings, and more, going beyond cities and states.
In overall terms, this process helped enhance the dataset by providing detailed geographic information for cases where location data was missing or incomplete.

## Technologies and Tools Used
- **Text Mining**: quanteda, tidytext, topicmodels, SentimentAnalysis
- **Social Network Analysis (SNA)**: Igraph, Gephi
- **Deep Learning (LLMs)**: Hugging Face, BERT
- **NLP**: Named Entity Recognition (NER), Python, Pandas
