# TwitterSentimental_analysis

The data contain series of text which is classified as.. positive, negative and neutral emotions about an airline.
Code explain,
1. How these tweets are helpful in getting the emotion of an individual.
2. Text contains many unrequired details.
3. First remove all these things( numbers, emojis, stopwords etc...) and extract features.
4. Once feature is extracted we will convert text into data format using CountVectorizer().
5. Train data using SVC() classifier with linear kernel and obtain predictions.