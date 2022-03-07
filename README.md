# NLP-Rap-Project

A personal project using natural language processing and data analysis to compare the song lyrics of 12 rappers/rap groups. Ten songs were chosen for each artist, using the top ten most popular songs for each on genius.com. If the artist was not the primary artist, that song was removed and the next most popular song was chosen. This project was inspired by this article: https://pudding.cool/projects/vocabulary/index.html and many of the techniques, especially for topic modelling were learnt from user adashofdata: https://github.com/adashofdata/nlp-in-python-tutorial and https://www.youtube.com/playlist?list=PLGTJdqDBAxoyyxKqcS9b0A89NRXZxfK5i 


Conclusions: Why do I prefer the Wu-Tang Clan to other rap artists?
1. They have a wider vocabulary than 2/3 of the artists looked at. 
2. They swear more than 3/4 of the artists looked at.
3. If default stop_words are included (removing meaningless words such as prepoisitions, pronouns, etc.) they use the most words per minute, at 88. 
4. They drop to 9/12 if stop words are removed, meaning other artists rap faster but use more meaningless words than the Wu-Tang Clan.
5. Their rap tends to be about violence more than any other artist (although this is not as clear a conclusion). 

Limitations: 
1. I attempted to remove songs that feature other artists in the song, so that the study focused purely on the artist intended. However, I only realised late on that genius.com does not always show clearly whether an artist features. As a result, many songs feature other artists. This is especially prevalent for Tyler, The Creator, Nas and Jay-z & Kanye West, so their results may not be a completely fair representation. 
2. More time could have been spent on cleaning the lyrics as I suspect there were many meaningless words and sounds that should have been removed. This was tougher as there were as many as 8000 words to look at. Something else that could have been done is stemming and lemmatisation.
3. Better visualisations for most common words needed. 
4. Topic modelling is not at all conclusive, so more time should be spent on that in the future. 
