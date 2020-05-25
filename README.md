# Twitter-to-Word2Vec
Turns scraped twitter data into word vectors

This is a simple conversion of scraped Twitter data into a word vector.

The data has been cleansed.
Any words that started with @ or # or an integer were removed from the Twitter data.
Web links were removed by removing the string containing 'http://' or 'https://' or 'www'.
All capitalisations were reduced to lower case.
Extra white spaces were removed. 
