
# Fake news detection

"Fake news" is a term used to describe false or misleading information presented as factual news.

INTENTIONS COULD BE ANY:

1.Mislead the reader

2.De-Fame a Person

3.Clickbait(profits on no. of clicks)

# Use Case

Fake news detectors are used in various contexts and industries to combat the spread of misinformation and disinformation others like fact checking websites gov 
agencies etc.   

# Concepts

1. Tokenisation
2. Stop word removal.
3. Deep Learning Model (LSTM)

# 

1. Import necessary libraries
2. Load and check data
 -  Adding    an  extra   coloumn 'target'    with    value   0   for Fake    data    and value 1 for True data.

 3. Visualization of dataset
 -      Fake data->23481(52.3%)
-       True data->21417(47.7%)       


4.  Data cleaning 
- Deleting unwnanted coloumns
- Removal of HTML contents
- Removal of Punctuation Marks and Special Characters
- Removal of Stopwords
- Lemmatization

5. Modeling
- Train Test Split
- Tokenizing
    - Tokenizing Text -> Repsesenting each word by a number
    - Mapping of orginal word to number is preserved in word_index property of tokenizer

 - Training LSTM Model

 6. Analysis

 - Accuracy of the model on Training Data is -  98.42603802680969 %

 - Accuracy of the model on Testing Data is -  98.39643836021423 %   