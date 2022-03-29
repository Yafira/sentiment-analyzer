# Sentiment Analyzer

### Sentiment analysis is one of the popular applications of machine learning.

- This small app is an online sentiment analysis tool using the ml5.js library along with React.

- This model scores the sentiment of text with a value between 0 ("negative") and 1 ("positive").
  - Observations:
    - when you use words like gross, ugly, disgusting, nonsense, pretentious or worthless the value is closer to 0 because the sentiment analyzer classifies this as negative.
    - when you use words like beautiful, delightful, inspiring, impressed or brilliant the value is closer to 1 because the sentiment analyzer classifies this as positive.
