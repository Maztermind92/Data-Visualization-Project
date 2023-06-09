
# Data-Visualization-Project
<h1 style="font-size: 28px;">Alice in Wonderland Analysis:</h1>

This project is focused on analyzing the text of Alice in Wonderland by Lewis Carroll. The analysis includes network analysis, sentiment analysis, and word cloud generation. The project is implemented using Python and various Python libraries such as Pandas, NetworkX, TextBlob, and WordCloud.

<h1 style="font-size: 28px;">Dataset:</h1>

The dataset used for this project is the full text of "Alice's Adventures in Wonderland" in plain text format. The text was obtained from the Gutenberg Project website (https://www.gutenberg.org/ebooks/11). The text was preprocessed by removing unnecessary characters such as punctuation marks, numbers, and special characters.

<h1 style="font-size: 28px;">Project Structure:</h1>

Alice.txt: the full text of "Alice in Wonderland" novel.
charecters.txt: a list of characters mentioned in the novel.
NetworkAnalysis.ipynb: a notebook containing code for network analysis of characters.
Sentiment Analysis.ipynb: a notebook containing code for sentiment analysis.
WordCloud.ipynb: a Jupyter notebook containing code for creating word clouds.

<h1 style="font-size: 28px;">Network Analysis:</h1>

We analyzed the interactions between characters and the frequency of their co-occurrences in the text. The results of our analysis can be found in NetworkAnalysis.ipynb.
The network analysis part of the project involves analyzing the relationships between the different characters in the book. This is done by creating a network graph using the Python networkx library, where each character is represented by a node and the interactions between the characters are represented by edges. The network graph is visualized using the matplotlib library.

<h1 style="font-size: 28px;">Sentiment Analysis:</h1>

The sentiment analysis part of the project involves analyzing the sentiment of the text using the TextBlob library. TextBlob is a Python library that provides an easy-to-use interface for performing various NLP tasks, including sentiment analysis. The sentiment analysis is performed on each sentence in the text, and the overall sentiment of the text is determined based on the average sentiment score of all the sentences.The sentiment score is a measure of the positivity or negativity of a text, with a score of 0 indicating a neutral sentiment, and scores closer to 1 or -1 indicating positive or negative sentiment, respectively. The main emotions considered are happiness, sadness, surprise, anger, and neutral.
The results of our analysis can be found in Sentiment Analysis.ipynb.

<h1 style="font-size: 28px;">Word Clouds:</h1>

We created word clouds to visualize the most frequently used words in the text. We used the Python wordcloud library to create the word clouds. The results of our analysis can be found in WordCloud.ipynb.

<h1 style="font-size: 28px;">Conclusion:</h1>

Through our analysis, we gained insights into the relationships between characters, the sentiment of the novel, and the most frequently used words. This project demonstrates the usefulness of text analysis techniques in gaining a deeper understanding of literature.

<h1 style="font-size: 28px;">Acknowledgments:</h1>

We would like to acknowledge the contributions of Project Gutenberg for providing the text of the novel. We also thank the developers of the NLTK and wordcloud libraries for their contributions to the field of natural language processing.
