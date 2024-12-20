# Part 4 - Classification Writeup

After completing `a6_part4.py` answer the following questions

## Questions to answer

1. Comment out the StandardScaler and re-run your test. How accurate is the model? Why is that?
When StandardScaler is commented out, the system loses almost 16% of its accuracy, making it about 70% accurate.

2. How accurate is the model with the StandardScaler? Is this model accurate enough for the given use case? Explain.
The model is about 85% accurate w/ StandardScaler, making it singificantly more accurate, but still unreliable for accurate predictions.

3. Looking at the predicted and actual results, how did the model do? Was there a pattern to the inputs that the model was incorrect about?
While the model seems more accurate with standardized data near zero, no clear pattern for incorrect predictions is evident without plotting them collectively for analysis.

4. Would a 34 year old Female who makes 56000 a year buy an SUV according to the model? Remember to scale the data before running it through the model.
No.
