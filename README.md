
# Sentiment-Analysis
**Sentiment analysis is the process of analyzing digital text to determine if the emotional tone of the message is positive, negative, or neutral**
Today, companies have large volumes of text data like emails, customer support chat transcripts, social media comments, and reviews. Sentiment analysis tools can scan this text to automatically determine the author’s attitude towards a topic. Companies use the insights from sentiment analysis to improve customer service and increase brand reputation. 




![App Screenshot](https://d3caycb064h6u1.cloudfront.net/wp-content/uploads/2021/06/sentimentanalysishotelgeneric-2048x803-1.jpg)

## Why is sentiment analysis important?
Sentiment analysis, also known as opinion mining, is an important business intelligence tool that helps companies improve their products and services. We give some benefits of sentiment analysis below.

**Provide objective insights**

Businesses can avoid personal bias associated with human reviewers by using artificial intelligence (AI)–based sentiment analysis tools. As a result, companies get consistent and objective results when analyzing customers’ opinions.

For example, consider the following sentence: 

I'm amazed by the speed of the processor but disappointed that it heats up quickly. 

Marketers might dismiss the discouraging part of the review and be positively biased towards the processor's performance. However, accurate sentiment analysis tools sort and classify text to pick up emotions objectively.

**Build better products and services**

A sentiment analysis system helps companies improve their products and services based on genuine and specific customer feedback. AI technologies identify real-world objects or situations (called entities) that customers associate with negative sentiment. From the above example, product engineers focus on improving the processor's heat management capability because the text analysis software associated disappointed (negative) with processor (entity) and heats up (entity).

**Analyze at scale**

Businesses constantly mine information from a vast amount of unstructured data, such as emails, chatbot transcripts, surveys, customer relationship management records, and product feedback. Cloud-based sentiment analysis tools allow businesses to scale the process of uncovering customer emotions in textual data at an affordable cost. 

**Real-time results**

Businesses must be quick to respond to potential crises or market trends in today's fast-changing landscape. Marketers rely on sentiment analysis software to learn what customers feel about the company's brand, products, and services in real time and take immediate actions based on their findings. They can configure the software to send alerts when negative sentiments are detected for specific keywords.

## What are sentiment analysis use cases?
Businesses use sentiment analysis to derive intelligence and form actionable plans in different areas.

**Improve customer service**

Customer support teams use sentiment analysis tools to personalize responses based on the mood of the conversation. Matters with urgency are spotted by artificial intelligence (AI)–based chatbots with sentiment analysis capability and escalated to the support personnel.

**Brand monitoring**

Organizations constantly monitor mentions and chatter around their brands on social media, forums, blogs, news articles, and in other digital spaces. Sentiment analysis technologies allow the public relations team to be aware of related ongoing stories. The team can evaluate the underlying mood to address complaints or capitalize on positive trends. 

**Market research**

A sentiment analysis system helps businesses improve their product offerings by learning what works and what doesn't. Marketers can analyze comments on online review sites, survey responses, and social media posts to gain deeper insights into specific product features. They convey the findings to the product engineers who innovate accordingly. 

**Track campaign performance** 

Marketers use sentiment analysis tools to ensure that their advertising campaign generates the expected response. They track conversations on social media platforms and ensure that the overall sentiment is encouraging. If the net sentiment falls short of expectation, marketers tweak the campaign based on real-time data analytics. 

## How does sentiment analysis work?

Sentiment analysis is an application of natural language processing (NLP) technologies that train computer software to understand text in ways similar to humans. The analysis typically goes through several stages before providing the final result.

- **Preprocessing** 
During the preprocessing stage, sentiment analysis identifies key words to highlight the core message of the text.

  - `Tokenization` breaks a sentence into several elements or tokens.
  - `Lemmatization` converts words into their root form. For example, the root form of am is be.
- `Stop-word` removal filters out words that don't add meaningful value to the sentence. For example, with, for, at, and of are stop words. 

- **Keyword analysis**

  NLP technologies further analyze the extracted keywords and give them a sentiment score. A sentiment score is a measurement scale that indicates the emotional element in the sentiment analysis system. It provides a relative perception of the emotion expressed in text for analytical purposes. For example, researchers use 10 to represent satisfaction and 0 for disappointment when analyzing customer reviews.

## What are the approaches to sentiment analysis?

![App Screenshot](https://lh3.googleusercontent.com/hMW-l7JdGkSadcoEvlvKiamPfIQGI0k0_z91iXOv8UmUbJoe-h60h-6WfdHCQqurNCDdbjsWlcsqbLDNPkHMd1Ec7AYd30aWUNNgjv0LbohuQ67rI_4_Jxb8Tin9E-PU5fLjWcqPLF2f6daVzy1PUsSgj2BfTxTi94p3NjTWpiXSiODyj1Kl0qCiLZPYfQ)


-  There are three main approaches used by sentiment analysis software.

### **1. Rule-based**

The rule-based approach identifies, classifies, and scores specific keywords based on predetermined lexicons. Lexicons are compilations of words representing the writer's intent, emotion, and mood. Marketers assign sentiment scores to positive and negative lexicons to reflect the emotional weight of different expressions. To determine if a sentence is positive, negative, or neutral, the software scans for words listed in the lexicon and sums up the sentiment score. The final score is compared against the sentiment boundaries to determine the overall emotional bearing.

**Rule-based analysis example**

Consider a system with words like happy, affordable, and fast in the positive lexicon and words like poor, expensive, and difficult in a negative lexicon. Marketers determine positive word scores from 5 to 10 and negative word scores from -1 to -10. Special rules are set to identify double negatives, such as not bad, as a positive sentiment. Marketers decide that an overall sentiment score that falls above 3 is positive, while - 3 to 3 is labeled as mixed sentiment. 

**Pros and cons** 

A rule-based sentiment analysis system is straightforward to set up, but it's hard to scale. For example, you'll need to keep expanding the lexicons when you discover new keywords for conveying intent in the text input. Also, this approach may not be accurate when processing sentences influenced by different cultures.

### **2. ML**
This approach uses machine learning (ML) techniques and sentiment classification algorithms, such as neural networks and deep learning, to teach computer software to identify emotional sentiment from text. This process involves creating a sentiment analysis model and training it repeatedly on known data so that it can guess the sentiment in unknown data with high accuracy. 

**Training**

During the training, data scientists use sentiment analysis datasets that contain large numbers of examples. The ML software uses the datasets as input and trains itself to reach the predetermined conclusion. By training with a large number of diverse examples, the software differentiates and determines how different word arrangements affect the final sentiment score.

**Pros and cons** 

ML sentiment analysis is advantageous because it processes a wide range of text information accurately. As long as the software undergoes training with sufficient examples, ML sentiment analysis can accurately predict the emotional tone of the messages. However, a trained ML model is specific to one business area. This means sentiment analysis software trained with marketing data cannot be used for social media monitoring without retraining.


![App Screenshot](https://lh5.googleusercontent.com/n3r32ilA49bFS2I3LEBoMHit-EOCghmobhhfQp-sx4b45tXAdUod4Ph2rdvC3yXnboDd_3rH6XqyGlFJV1T78iOPiREivy3KVAEznwAlYBDIEohls2ESf4M7w_KEohmqxPeo9aSknK2TXk2tofMtbl3UoBZrhC3PXZ9QhrM3wUYWk0ADAc32MJWWFpCduw)


### **3. Hybrid**
Hybrid sentiment analysis works by combining both ML and rule-based systems. It uses features from both methods to optimize speed and accuracy when deriving contextual intent in text. However, it takes time and technical efforts to bring the two different systems together. 



![App Screenshot](https://lh3.googleusercontent.com/uE6rlSYw1kCM2V3GqUhL331rJCBJMQ2G0LiKjPvF6HEF1Svlc09ttzH9AtRnMToPjdtfL3lBA3U_R0TC5Akvi6xFFaMx5IIuaDBrb67Q5pkpGzXUh80P7LRZjmcHoyLa92mcg1f7MP_ZuDyyl3yBYoIyBJNRscFmfOyEaNXNB2fslPyPpuUZ7Wl19ldmQg)


