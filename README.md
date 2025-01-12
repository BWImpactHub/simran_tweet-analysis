# Disaster_tweet-analysis 
<h3> Anand Hole </h3>
<p> -- Gathered Data, did cleaning and null value handling.<br> </p>

<h3> Chandrashekhar Kadam </h3>
<P>
Exploratory Data Analysis (EDA) : <br>
1.Data Overview : Understanding the dataset structure, column descriptions, and target distribution (`disaster` vs. `non-disaster` tweets).<br>
2.Text Analysis : Analyzing the distribution of text length, unique word counts, and frequent words or phrases. <br>
3.Visualization : Using matplotlib library word clouds, bar charts, and histograms to better understand the character and words in dataset.<br>
</p>

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
            <td> 1 </td>
            <td> ['flood', 'damage'] </td>
        </tr>
        <tr>
            <td> 0 </td>
            <td> ['happy','day'] </td>
        </tr>
        <tr>
            <td> 1 </td>
            <td> ['earthquake','rescue'] </td>
        </tr>
    </table><br>
    > comDisa: A pandas Series holding the top 30 words.<br>
    > comDisa_count: A pandas Series holding the corresponding word counts.<br>
    > sns.barplot: Creates a bar plot where comDisa is on the x-axis and comDisa_count on the y-axis.<br>
    > plt.xticks(rotation='vertical'): Rotates the x-axis labels vertically for better readability.<br>
    > plt.show(): Displays the plot.<br>
    > The <b> gensim.models.Word2Vec </b> module allows you to create and train Word2Vec models for text vectorization.<br>
    
</p>

<h3> Arjun Ritapure </h3>
<h4> Naive Bayes </h4>
<p>
--Naive Bayes Classifier:GaussianNB,BernoulliNB<br>
> The purpose of the Naive Bayes classifier is to perform classificatin tasks using probability principles.It's a supervised machine learning algorithm.<br>
> The Naive Bayes classifier uses Bayes theorem of probability to predict an unknown class. as it's simple,efficient,and accurate.<br>
> Efficiency:It is a fast and efficient classifier that can handle large datasets.<br>
> Accuracy:It's fairly accurate when the conditional independence assumption holds.<br>
> Text classification:Used fo sentiment analysis and spam filtering.<br> 
<p>


