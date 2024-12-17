Bollywood Songs Analysis Using NLP and Data Science 🎶

Project Description:
This project delves into the world of Bollywood music, analyzing lyrics and artist trends to uncover patterns and sentiments behind some of the most popular Hindi songs. By leveraging data science, web scraping, and NLP techniques, this project provides valuable insights into the artistic and lyrical dimensions of Bollywood's top hits.

Stages of the Project
Stage 1: Data Collection
1. Collected the top 100 Hindi Bollywood songs from Spotify playlists using the Spotipy library and API.
2. Stored the song details, such as title, artist, and album, in a structured CSV dataset for further analysis.

Stage 2: Lyrics Extraction & Preprocessing
1. Scraped lyrics for each song from lyricsboogie.com using BeautifulSoup and a custom fetch_lyrics() function.
2. Standardized lyrics into Devanagari script (Hindi text) using Google’s Transliterate module.
3. Cleaned and preprocessed lyrics by removing redundant symbols, special characters, and extraneous text.

Stage 3: Exploratory Data Analysis (EDA)
Performed in-depth visualizations to analyze artist and song trends:
1. Most Popular Artists: Bar plot of artists with the highest number of songs.
2. Unique Artists by Year: Time-series visualization of new artist emergence over time.
3. Longest Careers: Identified artists with the most enduring careers in Bollywood.
4. Song Distribution: Analyzed the distribution of top singles across various artists.

Stage 4: Text Analysis
Used cutting-edge NLP techniques for deeper insights:
1. Lyrics Preprocessing: Tokenized, cleaned, and normalized Hindi text for analysis.
2. Word2Vec Model: Built a Word2Vec model to identify word associations and relationships in the lyrics.
3. Word Cloud: Created a visually rich word cloud showcasing the most frequent Hindi words.
4. Latent Dirichlet Allocation (LDA):Clustered lyrics into three themes, identifying increasing positive sentiments in songs across themes. Embedded textual data using BERT and visualized clusters with t-SNE for underlying themes.
5. Sentiment Analysis: Analyzed lyrical sentiment trends over time using BERT-base-multilingual model. Compared sentiments across songs of the top 10 artists.
6. Keyword Associations: Analyzed word associations for Hindi keywords like "प्यार" (love), "दुख" (sorrow), and "खुशी" (happiness) using SkipGram. Visualized results with interactive network graphs.

Key Outcomes
1. Identified artistic trends and explored how Bollywood songs have evolved in sentiment and themes over time.
2. Mapped deep associations between Hindi keywords and lyrical patterns, revealing Bollywood's poetic richness.
3. Delivered valuable insights into artist popularity, career longevity, and lyrical themes.

Tools & Technologies
1. Programming Languages: Python
2. Libraries: Spotipy, Pandas, BeautifulSoup, Google Transliterate, Matplotlib, Seaborn, WordCloud, Gensim, TensorFlow
3. NLP Models: BERT-base-multilingual, SkipGram, Word2Vec
4. Visualization: Network Graphs, Word Cloud, Time Series Analysis, Cluster Visualizations

Impact
This project bridges the intersection of music, art, and technology by uncovering insights into Bollywood’s lyrical beauty and artist trends. It showcases how data-driven approaches can help appreciate the nuances of art in ways never seen before.
