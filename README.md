📊 Twitter Sentiment Analysis using Python + Power BI

  Analyze public sentiment on Twitter using Natural Language Processing (NLP), and visualize results with Power BI. This project cleans tweet data, extracts sentiment using    TextBlob, and presents insights through visualizations and dashboard.

📌 Features
  ✅ Load raw Twitter data
  ✅ Clean and preprocess tweets (lowercase, remove stopwords, punctuations)
  ✅ Perform sentiment analysis using TextBlob (polarity & subjectivity)
  ✅ Classify tweets as Positive, Negative, or Neutral
  ✅ Visualize results using matplotlib, seaborn, wordcloud
  ✅ Export to .csv for dashboarding in Power BI

📁 Project Structure

  ├── Sample Data.txt             # Raw tweet data
  ├── Sample data.csv             # Cleaned output with sentiment
  ├── sentiment_analysis.ipynb    # Main Python notebook
  ├── Sample data_cleaned.csv     # cleaned data for Power Bi
  ├── dashboard.pbix              # Power BI Dashboard
  ├── README.md                   # You're here!

📦 Libraries Used

  pandas, numpy – Data handling
  textblob – Sentiment analysis
  nltk – Stopwords, lemmatization
  matplotlib, seaborn – Visualization
  wordcloud – WordCloud generation
  tweepy – Twitter API integration

🧪 Sentiment Classification Logic

  Polarity > 0 → Positive
  Polarity < 0 → Negative
  Polarity = 0 → Neutral

📊 Power BI Dashboard

  Import Sample data_cleaned.csv into Power BI
  Create visuals:
  Bar chart of like count by sentiment
  WordCloud
  Card for Total tweets, avg polarity, avg subjectivity, Total likes, Total Retweets
  Slicer for date and sentiment
  Donut chart for Percentage of sentiment
  Line chart 
  
🖼 Snapshot of Dashboard

  (Add screenshot to assets/ folder or update the path)



