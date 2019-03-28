Categorizing News Articles using ULMFit

I am using the AG News corpus for training a ULMFit (https://arxiv.org/abs/1801.06146) model to classify the news articles into
1. World - Category 1
2. Sports - Category 2
3. Buisness - Category 3
4. Sci/Tech - Category 4

You can read about the AG News Corpus here http://xzh.me/docs/charconvnet.pdf


**Observations:**
We trained models with three below variants of data
1. Title and Description
2. Only Description
3. Only Title
 
The accuracy for points 1 and 2 are the same i.e. 92% accuracy.
The accuracy for point 3 (85%) is the lowest as the title of news are mostly cryptic in nature and determining the category from the same is difficult.

Following are the accuracy of the language model for the 3 variants after training it for a longer time
1. Title and Description - 43.4%
2. Description - 46%
3. Title - 45%

