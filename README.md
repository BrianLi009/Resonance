What it does
Resonance analyses personal and investment traits to make the best matches between an individual and an advisor. We use basic information any financial institution has about their clients and financial assets as well as past interactions to create a deep and objective measure of interaction quality and maximize it through optimal matches.

How we built it
The whole program is built in python using several libraries for gathering financial data, processing and building scalable models using aws. The main differential of our model is its full utilization of past data during training to make analyses more wholistic and accurate. Instead of going with a classification solution or neural network, we combine several models to analyze specific user features and classify broad features before the main model, where we build a regression model for each category.

Challenges we ran into
Our group member crucial to building a front-end could not make it, so our designs are not fully interactive. We also had much to code but not enough time to debug, which makes the software unable to fully work. We spent a significant amount of time to figure out a logical way to measure the quality of interaction between clients and financial consultants. We came up with our own algorithm to quantify non-numerical data, as well as rating clients' investment habits on a numerical scale. We assigned a numerical bonus to clients who consistently invest at a certain rate. The Mathematics behind Resonance was one of the biggest challenges we encountered, but it ended up being the foundation of the whole idea.

Accomplishments that we're proud of
Learning a whole new machine learning framework using SageMaker and crafting custom, objective algorithms for measuring interaction quality and fully utilizing past interaction data during training by using an innovative approach to categorical model building.

What we learned
Coding might not take that long, but making it fully work takes just as much time.

What's next for Resonance
Finish building the model and possibly trying to incubate it.
