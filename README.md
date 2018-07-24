# Twitter-Sentiment-Analysis-with-Python---Part-II
PhD project - part II

## Text Cleaning
The possible noise elements that should be removed as follows:

- Decoding data: transforming information from complex symbols to simple and easier to understand characters (i.e., UTF-8 encoding is widely accepted and is recommended to use)
- HTML characters: it looks like the data obtained from web usually contains a lot of html entities such as &amp in the text field, which should be removed
- URLs: URLs and hyperlinks in text data like comments, reviews, and tweets should be removed
- Emoticons: textual data can contain facial expression using characters. This information doesn't add value to build sentiment analysis model
- @mention: same with emoticons, even though it carries some information, for sentiment analysis purpose, this can be ignored
- Hash-tags: leave the text intact and just remove the '#'
- Stop-words: the commonly occurring words such as 'a', 'the', 'it', 'to' should be removed. One can either create a long list of stop-words or one can use predefined language specific libraries
- Split: check if there's any contracted or negated term i.e., 'isn't', and replace it with its original form- Decoding
