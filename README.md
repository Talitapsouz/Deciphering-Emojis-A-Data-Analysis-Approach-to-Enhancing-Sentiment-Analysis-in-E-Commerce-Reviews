# Deciphering Emojis: A Data Analysis Approach to Enhancing Sentiment Analysis in E-Commerce Reviews

## Overview

This project explores the role of emojis in sentiment analysis within e-commerce reviews. Using advanced data analytics and machine learning techniques, aim to integrate emoji sentiment to enhance the understanding of customer feedback.

## Objectives

- **Assess Multi-Feature Impact on Sentiment Classification:** Evaluate how individual review text, star ratings, total votes (likes on reviews), extracted emojis, and the integration of text with emojis as multi-features influence the performance of transformer-based deep neural networks in sentiment classification for Amazon product reviews across selected categories.

- **Enhance Emotion Detection Accuracy:** Investigate the enhancement in emotion detection accuracy and contextual understanding in natural language processing by integrating ratings, reviews, and emojis.

- **Analyze Emoji Impact in Sentiment Analysis:** Explore the impact of incorporating emojis as additional features in sentiment analysis, especially in the health and personal care category of Amazon product reviews, using a 5-class approach and compare it with a traditional 3-class approach.

- **Methodological Innovation in NLP:** Advance the methodology in natural language processing by leveraging multi-modal features to improve the accuracy and efficiency of sentiment analysis models.

- **Practical Implications for E-commerce Stakeholders:** Provide actionable insights for stakeholders in e-commerce platforms, focusing on the practical applications of advanced sentiment analysis techniques to enhance product insights and customer satisfaction.


## Methodology

This research delves into enhancing sentiment analysis in e-commerce reviews by systematically exploring the integration of multi-modal data, specifically focusing on text and emojis, alongside other review metrics like star ratings and total votes. The investigation is structured around a progressive, three-experiment framework:

1. **Text-Based Sentiment Analysis Using BERT:** This foundational experiment employs the BERT model to analyze the sentiment of Amazon product reviews based solely on text. The process involves preprocessing review texts, tokenizing using BERT's tokenizer, and sentiment classification into predefined categories. The aim is to establish a baseline understanding of sentiment analysis leveraging textual content.
   ![Text-Based Sentiment Analysis Architecture](https://github.com/Talitapsouz/Deciphering-Emojis-A-Data-Analysis-Approach-to-Enhancing-Sentiment-Analysis-in-E-Commerce-Reviews/blob/main/Diagrams/Only_Text.jpg)

2. **Integration of Emojis with Text in Sentiment Analysis:** Building on the initial text-based analysis, this experiment introduces emojis into the sentiment analysis model. It involves the demojization of emojis to their textual representation, combined encoding of text and emoji with BERT, and applying attention mechanisms to integrate insights from both modalities. The goal is to assess the added value of emojis in capturing sentiment nuances.
   ![Text and Emoji Integration Model](https://github.com/Talitapsouz/Deciphering-Emojis-A-Data-Analysis-Approach-to-Enhancing-Sentiment-Analysis-in-E-Commerce-Reviews/blob/main/Diagrams/Text_Emoji.jpg)

3. **Comprehensive Multi-Feature Sentiment Analysis:** The final experiment extends the sentiment analysis framework to include not just text and emojis but also star ratings and total votes as integral features of the model. This comprehensive approach employs a custom dataset class for data preprocessing, embedding layers for emojis, and a multi-head attention mechanism to fuse insights from all modalities, aiming to provide a holistic sentiment analysis model.
   ![Comprehensive Multi-Feature Model Architecture](https://github.com/path/to/diagram3.svg)

Each experiment is meticulously crafted to examine the incremental benefits of integrating various data modalities into sentiment analysis, ultimately contributing to a deeper and more accurate understanding of consumer sentiments in e-commerce reviews.


## Dataset

The analysis is based on a dataset of Amazon e-commerce reviews, encompassing a range of products and customer feedback. 
The details of dataset are available in `data` directory.
