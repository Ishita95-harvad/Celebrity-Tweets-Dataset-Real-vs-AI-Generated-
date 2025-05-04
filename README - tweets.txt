🐦 Celebrity Tweets Dataset (Real vs AI-Generated)


This dataset contains 120 tweets from 8 well-known celebrities, a mix of real tweets and AI-generated imitations. Each tweet is labeled to support machine learning projects, particularly in the areas of text classification, stylistic analysis, and authorship prediction.


---


📦 Dataset Overview


- 120 tweets total
- 8 celebrities
- 15 tweets per celeb
- Mix of humorous, chaotic, and casual tweet styles
- Balanced `is_real` values (True/False)


---


📁 Columns


| Column    | Description                                 |
|-----------|---------------------------------------------|
| `name`    | The celebrity who tweeted (or mimicked)     |
| `tweet`   | The content of the tweet                    |
| `is_real` | Boolean — `True` = real tweet, `False` = AI |


---


🎯 Use Cases


- Train a classifier to guess the tweet's author
- Distinguish real vs. AI-generated writing
- Stylometry: detecting writing style or tone
- NLP tutorials and projects
- Fun apps and games (like TweetLike 🎤)


---


🔁 Note on Duplicates


A few tweets appear more than once — that’s intentional.


We applied controlled oversampling to ensure each celebrity had exactly 15 examples. This prevents class imbalance and helps machine learning models generalize more accurately, especially in beginner projects.


---


💡 Fun Facts


- Some tweets were generated using GPT-style prompts to match the celebrity's voice.
- This dataset was used in a hackathon project called TweetLike — a web app where you guess the celebrity based on a tweet and find out how AI can trick you.


---


License


MIT License — free to use, remix, and build on.


---


Credits


Created by Gor Abaghyan - https://www.kaggle.com/abaghyangor 
Project repo: https://github.com/abaghyangor/ripgor