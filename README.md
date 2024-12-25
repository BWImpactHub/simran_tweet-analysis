# simran_tweet-analysis
<h3> Anand Hole </h3>
<p> -- Gathered Data, did cleaning and null value handling.<br> </p>

<h3>Author - Simran Mulla</h3>
<p> --Text processing:Tools and Libraries Used<br>
    > NLTK: For stopword removal, tokenization, and stemming.<br>
    > spaCy: For lemmatization and advanced tokenization.<br>
    > RE (Regular Expressions) and string: For removing special characters and cleaning text.<br>
    > pandas: For handling and organizing text data.<br>
    </p>

<h3> Shubham Sodanwar </h3>
<h4> Word2Vec </h4>
<p>
    > Word2Vec is a technique for representing words as vectors in a continuous vector space. <br>
    > The WordCloud class you are referring to is from the wordcloud Python library, which is used to generate word clouds—visual representations of text data where the size of each word indicates its frequency or importance.
        1. Prepare text Data.
        2. Generate the Word Cloud.
        3. Display the Word Cloud.<br>
    > Sets the size of the plotting canvas in inches (15 inches wide and 6 inches tall).<br>
    > Visualizes the word cloud object named Disaster_wc.<br>
    > Filters the DataFrame dftrain to include only rows where the target column equals 1<br>
    > Refers to the tokens column, which is expected to contain tokenized text (e.g., lists of words).<br>
    > Iterates over each token (word) in the tokenized message.<br>
    > Adds each word to the Disaster_corpus list.<br>
    Example:<br> 
    <table border="1">
        <tr>
            <th> Target </th>
            <th> Tokens </th>
        </tr>
        <tr>
            <td> 1, ['flood', 'damage'] </td>
        </tr>
        <tr>
            <td> 0, ['happy','day']</td>
        </tr>
        <tr>
            <td> 1, ['earthquake','rescue']</td>
        </tr>
    </table>
    <br>
    > comDisa: A pandas Series holding the top 30 words.<br>
    > comDisa_count: A pandas Series holding the corresponding word counts.<br>
    > sns.barplot: Creates a bar plot where comDisa is on the x-axis and comDisa_count on the y-axis.<br>
    > plt.xticks(rotation='vertical'): Rotates the x-axis labels vertically for better readability.<br>
    > plt.show(): Displays the plot.<br>
    > The <b> gensim.models.Word2Vec </b> module allows you to create and train Word2Vec models for text vectorization.<br>
    
</p>