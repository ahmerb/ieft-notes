# Sentiment Analysis

- Sentiment analysis used to understand opinions/views/feelings of crowd
- Can be used for prediction
- Less objective than prediction markets, but more widely applicable

## Social data mining

- The web, particularly twitter, provides lots of real-time information about what is going on in people's lives
- This can be both in 'ordinary' and 'extraordinary' circumstances - e.g. aftermath of a disaster
- Automated analysis of such datasources can provide useful info about society: social data mining

## Twitter Flu Pandemic

- Monitor twitter for 'flu marker' word steams (eg 'temperatur', 'throat')
- Weight depending on number of stems per tweet
- Search engine queries also used (but not localised)
- True positive result, but false positives also possible

- Results similar to actual flu rate

## Supporting Disaster Relief

- Humanity Road is a US NGO which provides online support during disasters
- TweetTracker (Arizona State Uni) used by them to monitor unfolding disasters and collate support information
- -> e.g. Haiti hurricane, rerouting of ambulances to hospitals with spare beds

## Sentiment Analysis aka Opinion mining

- The web is full of publically broadcase opinions and emotions: blogs, review articles, tweets
- These are valuable source of data for a number of resasons:
    - aggregating more 'objective' reviews for a purchser
    - tracking concerns about your product (indirect customer feedback)
    - spotting opinions which may impact a stock price
    - predicting outcomes of election

### Types of Sentiment Analysis

- **Document-level sentiment analysis**:
    - for a given document, e.g. a review, identify its overall attitude to the objects under discussion

- **Sentence or phase-level sentiment analysis**:
    - for a given sentence, identify if it expresses a positive, negative or neutral (no) opinion

- **Aspect level sentiment analysis**:
    - for a given document, identify all opinions expressed with regard to any aspect of any object

#### Document level sentiment analysis

##### Supervised approach

- Goal: classify document as positive or negative (towards some target)

- Supervised learning
    - Features are counts of words ('bag of words')

- 78% with Naive bayes, 73% with SVM

- Outperformed human-generated feature set of opinion words
- But, not as good as usual with traditional non-opinion ML tasks

##### Unsupervised approach

- Identify 'interesting' pairs of words using part-of-speech tags (eg adjective followed by noun - 'beautiful sound'; 'noisy engine')
- Calculate **Pointwise Mutual Information** measure for this pair and the words "excellent" and "poor"

```
PMI(term_1, term_2) = log( Pr(term_1 and term_2) / Pr(term_1)Pr(term_2) )
```

- Probabilities found by counting hits from a search engine.
- Top performance on car reviews of 84%.

#### Aspect Level Sentiment Analysis

- A document may contain multiple expressions of sentiment with regard to different ‘aspects’ of one or more objects.
- E.g. “The voice quality of this phone is amazing, but it is rather expensive.”
- E.g. “Apple is doing very well in this bad economy”
- E.g. “The photo quality is not good.”


