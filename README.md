<h1 font-size:40px align="center">ClimaConvo</h1>

This repository contains the data and code for our paper **<a href="https://aclanthology.org/2024.lrec-main.88/">Analyzing the Dynamics of Climate Change Discourse on Twitter: A New Annotated Corpus and Multi-Aspect Classification**</a> published at LREC-COLING 2024.

## Abstract

The discourse surrounding climate change on social media platforms has emerged as a significant avenue for understanding public sentiments, perspectives, and engagement with this critical global issue. The unavailability of publicly available datasets, coupled with ignoring the multi-aspect analysis of climate discourse on social media platforms, has underscored the necessity for further advancement in this area. To address this gap, in this paper, we present an extensive exploration of the intricate realm of climate change discourse on Twitter, leveraging a meticulously annotated *ClimaConvo* dataset comprising 15,309 tweets. Our annotations encompass a rich spectrum, including aspects like relevance, stance, hate speech, the direction of hate, and humor, offering a nuanced understanding of the discourse dynamics. We address the challenges inherent in dissecting online climate discussions and detail our comprehensive annotation methodology. In addition to annotations, we conduct benchmarking assessments across various algorithms for six tasks: relevance detection, stance detection, hate speech identification, direction and target, and humor analysis. This assessment enhances our grasp of sentiment fluctuations and linguistic subtleties within the discourse. Our analysis extends to exploratory data examination, unveiling tweet distribution patterns, stance prevalence, and hate speech trends. Employing sophisticated topic modeling techniques uncovers underlying thematic clusters, providing insights into the diverse narrative threads woven within the discourse. The findings present a valuable resource for researchers, policymakers, and communicators seeking to navigate the intricacies of climate change discussions. The dataset and resources to reproduce the experiments are available at https://github.com/shucoll/ClimaConvo.

### Accessing the Tweets
>Please refer to this link in the official Twitter API guide to get the tweet contents from the tweet IDs
>https://developer.twitter.com/en/docs/twitter-api/tweets/lookup/api-reference/get-tweets


## Annotation terminology

### Relevance
|  Class | Terminology | 
| :--------: | :--------: | 
| Non-Relevant | 0 | 
| Relevant | 1 | 


### Stance
|  Class | Terminology | 
| :--------: | :--------: | 
| Support | 1 | 
| Denial | 2 | 
| Neutral | 3 | 


### Humor
|  Class | Terminology | 
| :--------: | :--------: | 
| No-Humor | 0 | 
| Humor | 1 | 


### Hate
|  Class | Terminology | 
| :--------: | :--------: | 
| No-Hate | 0 | 
| Hate | 1 | 

### Direction of Hate Speech

|  Class | Terminology | 
| :--------: | :--------: | 
| Undirected | 0 | 
| Directed | 1 | 

### Targets of Hate Speech
|  Class | Terminology | 
| :--------: | :--------: | 
| Individual | 1 | 
| Organization | 2 | 
| Community | 3 |
