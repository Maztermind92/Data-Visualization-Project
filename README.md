<h1 style="font-size: 36px;">Alice in Wonderland Analysis:</h1>

# Data-Visualization-Project
Alice in Wonderland Analysis:
This project is focused on analyzing the text of Alice in Wonderland by Lewis Carroll. The analysis includes network analysis, sentiment analysis, and word cloud generation. The project is implemented using Python and various Python libraries such as Pandas, NetworkX, TextBlob, and WordCloud.

Dataset:
The dataset used for this project is the full text of "Alice's Adventures in Wonderland" in plain text format. The text was obtained from the Gutenberg Project website (https://www.gutenberg.org/ebooks/11). The text was preprocessed by removing unnecessary characters such as punctuation marks, numbers, and special characters.

Project Structure:
Alice.txt: the full text of "Alice in Wonderland" novel.
charecters.txt: a list of characters mentioned in the novel.
NetworkAnalysis.ipynb: a notebook containing code for network analysis of characters.
Sentiment Analysis.ipynb: a notebook containing code for sentiment analysis.
WordCloud.ipynb: a Jupyter notebook containing code for creating word clouds.

Network Analysis:
We analyzed the interactions between characters and the frequency of their co-occurrences in the text. The results of our analysis can be found in NetworkAnalysis.ipynb.
The network analysis part of the project involves analyzing the relationships between the different characters in the book. This is done by creating a network graph using the Python networkx library, where each character is represented by a node and the interactions between the characters are represented by edges. The network graph is visualized using the matplotlib library.

Sentiment Analysis:
The sentiment analysis part of the project involves analyzing the sentiment of the text using the TextBlob library. TextBlob is a Python library that provides an easy-to-use interface for performing various NLP tasks, including sentiment analysis. The sentiment analysis is performed on each sentence in the text, and the overall sentiment of the text is determined based on the average sentiment score of all the sentences.
The results of our analysis can be found in Sentiment Analysis.ipynb.

Word Clouds:
We created word clouds to visualize the most frequently used words in the text. We used the Python wordcloud library to create the word clouds. The results of our analysis can be found in WordCloud.ipynb.

Conclusion:
Through our analysis, we gained insights into the relationships between characters, the sentiment of the novel, and the most frequently used words. This project demonstrates the usefulness of text analysis techniques in gaining a deeper understanding of literature.

Acknowledgments:
We would like to acknowledge the contributions of Project Gutenberg for providing the text of the novel. We also thank the developers of the NLTK and wordcloud libraries for their contributions to the field of natural language processing.
