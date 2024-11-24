---
layout: post
title: Reflection Blog Post
---

In this post, I reflect on my final music classifier project and my experiences creating it. The project repository is located [here](https://github.com/jiahao303/music-classifier).

### Overall, what did you achieve in your project?

We were able to first visualize and gain insights from a dataset of song lyrics and their genre and sentiments. Then, we created and trained a neural network that predicted the genre of the song based off of its lyrics and sentiments, with about 80% validation accuracy. We exported this tensorflow model and created a web app that hosts this model and allows  users to input their lyrics and Spotify song ID (to derive the song's sentiments) to predict the song's genre. Afterwards, to try to improve the model's accuracy, we attempted to use the BERT model developed by Google. While we learned more about the BERT architecture, we were not able to implement it for our model.

### What are two aspects of your project that you are especially proud of?

I'm especially proud of the fact that our web app works quite seamlessly with our model—it was a hassle to export our model and import it into our flask web app and have it interact with the interface.

I'm also proud of the fact that we looked into BERT and transfer learning—it was interesting to learn more about how the model works and how it could be applied to many NLP applications.

### What are two things you would suggest doing to further improve your project? (You are not responsible for doing those things.) 

I would suggest further looking into transfer learning with other models, perhaps with the models on https://tfhub.dev/. Transfer learning was incredibly powerful, especially in Blog Post 5, and we hypothesize it could improve our accuracy by a lot. 

I would also suggest looking into other layers for our neural networks, perhaps layers we haven't seen in class. I'd like to get a deeper understanding of neural networks before I do this. Having other layers that are applicable to our situation could be helpful.

### How does what you achieved compare to what you set out to do in your proposal? (if you didn't complete everything in your proposal, that's fine!)

We were able to create a model that predicts genre based on lyrics and a song's sentiments. We were also able to create a webapp that interacts with this model so users provide their own input and use the model. We didn't use soundwave data or implement our model for songs in other languages, however, which were extra proposal items.

Overall, we achieved everything promised in our proposal.

### What are three things you learned from the experience of completing your project? Data analysis techniques? Python packages? Git + GitHub? Etc? 

I learned how to download a tensorflow model and implement it in a flask webapp. I was also able to learn a little about how to format the input for a BERT model. Lastly, I learned about lemmatization, a technique used to reduce a word to its stem to simplify the input data for a NLP model.

### How will your experience completing this project will help you in your future studies or career? Please be as specific as possible. 

I'll be working at a technology company as a product manager, so I hope my experience with Git is helpful so I can understand how the software engineering workflow is. I also hope to continue learning about data science and machine learning, and will actively search for opportunities in those fields at my company. Ideally, I hope to work on a product that implements machine learning so I can apply what I've learned in this project. Whether it be NLP or other applications of machine learning, such as image classification, I know my knowledge of neural networks and tensorflow will be helpful.