Ex.No.6 Development of Python Code Compatible with Multiple AI Tools

Aim: 

Write and implement Python code that integrates with multiple AI tools to automate the task of interacting with APIs, comparing outputs, and generating actionable insights with Multiple AI Tools.

Explanation:

Develop a python code that integrates multiple AI tool by interacting with their APIs.
Compare outputs from different APIs.
Analyze the response and the Output.

The aim is to understand how to request help from AI tools for tasks like writing Python code, integrating with APIs, comparing outputs, and generating actionable insights.
```
from nltk.sentiment import SentimentIntensityAnalyzer
import nltk

nltk.download('vader_lexicon')

# Simulated AI-generated text
generated_text = input("  ")
print("Generated Review:\n")
print(generated_text)

# Sentiment analysis
sia = SentimentIntensityAnalyzer()
sentiment = sia.polarity_scores(generated_text)

print("\nSentiment Analysis:")
print(sentiment)
```
output:

<img width="1782" height="719" alt="565596566-a0d77ba0-011a-43c0-8144-9e74ee9dcfa1" src="https://github.com/user-attachments/assets/848eb5e9-12f7-4d81-89d1-bc31b0707b4a" />


<img width="1827" height="732" alt="565596302-5ca75401-14cb-4a65-a4f0-a16312b751b4" src="https://github.com/user-attachments/assets/d5da0beb-eb2d-480a-918d-e54b08f3b1c5" />




Result: 

The code executed successfully.
