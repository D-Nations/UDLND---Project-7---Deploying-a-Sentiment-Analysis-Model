# UDLND---Project-7---Deploying-a-Sentiment-Analysis-Model

For this project I created a sentiment analysis model and deployed it, all on AWS services.  I had to use SageMaker, S3, Lambda, and an API.  I also had to enable a GPU for use in SageMaker.

## Project

The final project was a sentiment analysis model using an RNN architecture, but the real task was getting a website set up that could accept input and run the model to produce a prediction in real-time.  The subject material was movie reviews from IMDB, and the model was trained to predict whether they were positive or negative reviews (ideally verifiable against the review's star rating).  By far the most time-consuming part of this project was understanding how to enable the GPUs for SageMaker for use with both training and deployment of the model (the instructions in the project were outdated and misleading).

![Real-time Predictions from the Deployed Model](https://github.com/D-Nations/UDLND---Project-7---Deploying-a-Sentiment-Analysis-Model/blob/master/Negative%20Review%20Snippet.JPG)

## Conclusion

This was a learning experience, but I was a little disappointed by how much of the project had been done for me.  The lambda function, the API, and the site had all been done for me.  Regardless, I learned a lot about navigating the dauntingly complex world of AWS and how to use the services directly related to machine learning and model deployment.  I was really intrigued by SageMaker's ability to automatically detect and employ the best hyperparameters for a model by doing multiple trainings.  It still required specified ranges, but this seems like it could be a really powerful tool that could save a lot of time.
