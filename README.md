# Public Perception of Volume-Based Procurement in China: A Social Intelligence Analysis

This repository accompanies a research project analysing public opinion on China's Volume-Based Procurement (VBP) policy in the pharmaceutical sector during January 2025. Employing advanced topic modelling techniques, the study aims to uncover the underlying themes and sentiments expressed by the public regarding VBP. 

China's VBP policy seeks to reduce drug prices through bulk purchasing agreements, impacting various stakeholders within the healthcare system. Understanding public perception of such policies is crucial for policymakers and healthcare providers. This project utilises Natural Language Processing (NLP) methods to analyse public discourse and extract prevalent topics and sentiments.

## Key Points

1. Media Coverage Triggered Public Debate

The public discourse on VBP was significantly influenced by reports from traditional media outlets. A notable surge in Weibo discussions occurred following a Sanlian Lifeweek article on 13 January 2025, which highlighted the withdrawal of foreign medicines from the Chinese market due to their exclusion from the VBP selection process. This media coverage acted as a catalyst, sparking widespread public engagement and debate on the topic.

2. Negative Sentiment Dominated Online Discourse

Sentiment analysis revealed that negative sentiments towards VBP spiked dramatically after the Sanlian Lifeweek report. Despite the article's positive tone, public reaction was overwhelmingly negative, indicating a disconnect between media framing and public perception. This negative sentiment persisted throughout January 2025, dominating online discussions and highlighting deep-seated public concerns.

3. Inequality and Distrust Emerged as Central Themes

Topic modelling identified that discussions evolved to focus on issues of inequality and distrust in the healthcare system. Concerns about preferential treatment for certain groups and the quality of domestically produced drugs under VBP were prevalent. These themes underscored a broader scepticism towards institutional practices and policies.

4. Sustained Engagement Fueled by Data Integrity Concerns

Public interest in the VBP debate was further sustained by revelations of data duplication in consistency assessment reports, which cast doubt on the integrity of evaluations for generic drugs. This controversy intensified scrutiny of regulatory processes and contributed to the ongoing negative sentiment.

5. Implications for Policy and Trust Restoration

The study highlights the critical need for transparent communication and equitable policy implementation to restore public trust. Addressing concerns about drug quality, ensuring fairness in procurement processes, and engaging with public sentiment are essential steps for policymakers to consider in the wake of the VBP debate.

## Methodology

* **Data Collection**: Publicly available textual data related to VBP were collected from Weibo.
* **Preprocessing**: Data cleaning involved removing noise, normalising text, and eliminating stop words.
* **Topic Modelling**: Implemented both BERTopic and Latent Dirichlet Allocation (LDA) models to identify and compare thematic structures within the data.
* **Analysis**: Interpreted the results to understand public concerns, misconceptions, and areas requiring policy attention.

### Repository Contents

* `data_clean.ipynb`: Jupyter Notebook detailing the data preprocessing steps.
* `example_data.xlsx`: Sample dataset used for analysis.
* `stop_words.txt`: List of stop words utilised during preprocessing.
* `write-up.pdf`: Comprehensive report of the study's findings and interpretations.