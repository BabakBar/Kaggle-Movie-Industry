Automatic text summarization

Automatic text summarization is the process of shortening long texts or paragraphs and generating a concise summary that passes the intended message. There are 2 main methods to summarize texts:

    Extractive summary: In this method, the output text will be a combination of meaningful sentences extracted directly from the original text.
    Abstractive summary: This method is more advanced, as the output is a new text. The aim is to understand the general meaning of sentences, interpret the context, and generate new sentences based on the overall meaning. 

In both methods, NLP is used in the text interpretation steps, which are:

    Cleaning the text from filling words
    Sampling the text into shorter sentences (tokens)
    Creating a similarity matrix that represents relations between different tokens
    Calculating sentence ranks based on semantic similarity
    Selecting sentences with top ranks in order to generate the summary (either extractive or abstractive)