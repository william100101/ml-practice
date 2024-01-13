# Chapter One Answers
1. How would you define machine learning?

I would define machine learning as a methodology towards solving problems that does not require
explicit step-by-step instructions. When applying a machine learning solution, the solution will take in experience to make a solution, judge its performance against some performance metric,
and then somehow improve itself.

2. Can you name four types of applications where it shines?

- One example would be a spam filter, which would be a supervised learning program.
- Another example would be in simulating a player in a game such as chess or go. This would be a reinforcement learning program.
- Image classification would be another example, and it would be utilizing unsupervised or semi-supervised learning. 
- A final example would be some kind of forecasting program. This would likely be a supervised learning program.

3. What is a labeled training set?

A labelled training set is a set of training instances that is used to make a supervised training program. Each instance in this program has a "label" indicating what the program should predict it as.

4. What are the two most common supervised tasks?

- One common type of task would be classification. An example of this would be the email task that was mentioned earlier in this chapter.
- Another would be a numerical approximation task. This kind of task would involve interpolating or extrapolating values.

5. Can you name four common unsupervised tasks?

- Clustering
- Anomaly detection
- Association Rule Learning
- Novelty Detection
- Dimensionality Reduction

6. What type of algorithm would you use to allow a robot to walk in various unknown terrains?

You would use a reinforcement algorithm

7. What type of algorithm would you use to segment your customers into multiple groups?

You would use an unsupervised learning algorithm.

8. Would you frame the problem of spam detection as a supervised learning problem or an unsupervised learning problem?

You would probably want to use a supervised learning algorithm.

9. What is an online learning system?

A learning system can be either online or batch-based. An online system will constantly take in new input and update itself to new data being plugged into it.
An offline, batch based learning will create a model based off of one training set and will need to retrained to stay relevant.
While online systems tend to work better with volatile data, they consume more resources than an offline system.

10. What is out-of-core learning?

Out-of-core learning is when a model is trained incrementally on a training set due to limitations on the machine its being trained on.

11. What type of algorithm relies on a similarity measure to make predictions?

An instance-based algorithm.

12. What is the difference between a model parameter and a model hyperparameter?

A model parameter is a parameter that is relevant to the conditions parameters of the problem. They  condense a situation's independent variables. A model hyperparameter
is a parameter specific to the function of the algorithm being used to solve the problem. This would things like the number of nodes in each layer of a neural net or learning rate.

13. What do model-based algorithms search for? What is the most common strategy they use to succeed? How do they make predictions?

A model-based algorithm will look through a data-set to try and try to fit it to some categorized trend like a linear regression. When predicting values they will interpolate or extrapolate
values on this trend line

14. Can you name four of the main challenges in machine learning?

- Bad quality data
- Low quantity of data
- Not having the data for the points you want to generalize to
- Overfitting/underfitting data

15. If your model performs great on the training data but generalizes poorly to new instances, what is happening? Can you name three possible solutions?

In this case, you are probably overfitting your data.

Some solutions to this are the follow
- Change your model so that it is taking in less parameters or (i.e. choose a less complex model), adjust your hyperparameters, or take in less features from your training data
- Get more training data
- Better clean and process your data before putting it into the model

16. What is a test set, and why would you want to use it?

A test set is a set of data that is collected so that you can "check", the quality of your model.
This test set should not be used in training and checks if your model can be used on somewhat random data.

17. What is the purpose of a validation set?

A validation is essentially the set of data that you use to performance check your data in while training.

18. What is the train-dev set, when do you need it, and how do you use it?

A train-dev set fulfills a similar purpose as the validation set in that it is a portion of the training set
that is set aside to test the performance of the model before going to the test set. 

19. What can go wrong if you tune hyperparameters using the test set?

You essentially make it so that you are overfitting to the test set, thus losing its neutrality.