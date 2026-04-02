# Things I made

## Sept 2025
### code2doc
- Made a very cool tool to format code into a .docx file. So, I can just focus on code and dont have to worry on formatting my assignments every fucking time.
- Check this out here: [anshulbadhani/code2doc: A simple python tool which generates .docx files from source code for assignment submission](https://github.com/anshulbadhani/code2doc)

## Oct 2025
### Neural Network in java
- Simple neural network which works as a function approximator. Given an arbitrary function f(x) it tries to learn the function and outputs the value of f(x) for custom values of x.
- The idea is to compare how a neural nets of different sizes approximates functions of varying complexity like, linear functions, higher order polynomial functions, periodic function and logarithmic/exponential functions.
- **Check this out here:** [ifndef-BROS/NN-From-Scratch-Java: This is our 3rd Sem project. In which we plan to make a neural network from scratch.](https://github.com/ifndef-BROS/NN-From-Scratch-Java)

### Darwin Engine
- A simple life simulator.
- More info after completion
- **Check this out here:** [ifndef-BROS/The-Darwin-Engine: Darwin Engine is a simple life simulator made in C++ which simulates biological creatures that evolve through natural selection.](https://github.com/ifndef-BROS/The-Darwin-Engine)

## Nov 2025
### Graphical Analysis of Social Networks in our Batch
- Using Instagram "followed by" data, I investigated the social network of our batch.
- Had to scrape Instagram follower data using firefox dev tools. This made me learn about http requests more. It was nice discovering instagram network logs for hours and sending custom api requests
- Had to figure out a way to work around api restrictions by insta, so my account does not get banned
- Generated a graph using a adjacency list in a json format
- Used Prim Algorithm and Louvian's Community detection to identify friend groups
- Found best friend of a given user using weights
- Made a CLI tool
- **Check this out for more info**: [anshulbadhani/socialspine](https://github.com/anshulbadhani/socialspine)

### Genie-Us
- Made for OSDC Hacknight, along with Rashi
- Part of [code2doc](https://github.com/anshulbadhani/code2doc) project extension plan
- Uses google classroom api along with Gemini to **complete assignments**, **generate study material** and **generates project ideas**
- **Check this out here**: [anshulbadhani/genie-us: genie-us is a simple tool, whose focus is to make it easier to manage tasks and assignments.](https://github.com/anshulbadhani/genie-us)

## Dec 2025
### Markovian–Bandit Scheduling Algorithm at Human Scale
(cool lgana chahiye bus naam lol. It's very basic actually)
- Challenged a friend for an AI duel. She agreed but later backed off. But, I am continuing my crazy idea.
- It is a mega project atp.
- The basic idea is, given a list of tasks the algorithm will schedule my entire day based on my past habits and if I skip some task or fail to complete it. Then it will re calibrate my day to minimize `my` regret
- For this project I figured out multiple things
    - [anshulbadhani/bandits](https://github.com/anshulbadhani/bandits) – Implement basic bandits from scratch to get a rough idea about them
    - Read an entire book on Bandits just to figure out
    - Read about recomendation systems from multiple research papers and books
    - Learnt about Markov Models and Random Walks
    - Figured out how can I create synthetic data reliably to test my models (idk if it is legit method or not) Using markov chains
    - How to distill a language model
        - I distilled a sentence transformer to fit into my model for quick working and quick inference on low compute devices
- I might also learn about Android Dev to deploy on android
- And using fuzzy to generate user insights and have safety guards for overall user well being

I wish to provide more details on this project later!!

## Jan 2026
### Temperature Forecasting Using Multivariate Fuzzy Time Series Model
- idts I have to tell myself more about it. I am definately rememberign this
- basically my RAMSA research paper
- **Check this out here:**[FTSPaper/Temperature-Prediction: This is a repository for our research paper, where we explore the ideas of Temperature Prediction using Fuzzy Time Series](https://github.com/FTSPaper/Temperature-Prediction)
- **The Presentation Slides:**[FTSPaper/Slides: This repository contains the code for our slides](https://github.com/FTSPaper/Slides)

## Feb 2026
### DustGuard AI
- Project made for Climate Change Hackathon Delhi 2026. which got selected for finals
- Basically it is a proposal for a systematic data collection from construction sites and provide them measures based on the site specific data.
- **Check this out here:** [anshulbadhani/Construction-Sites-Monitor-Prototype](https://github.com/anshulbadhani/Construction-Sites-Monitor-Prototype)

## Mar 2026
### TAAL
- An android app (well works on every platform beside iOS, for now) which targets beginners who just want to create something and test their goofy ideas without diving deep into how to use this software or wth does this setting do.
- I love how this turned out <3
- Also read our `devlog.md`
- **Check this out here:** [Tanishq172006/TAAL: Its a music app, made for mostly making the experience of the android and other platform users easy](https://github.com/Tanishq172006/TAAL/tree/main)

### GitHub RecSys
- Made to understand RecSys better for a personal project of mine *(see Dec 2025)*. I am developing this to get an idea of how to even develop a RecSys, before implementing my own vision for the application.
- It is basically end-to-end ML pipeline which is designed to handle a large amount of users at the same time (lol my large amount is hardly 5 to 10 with host machine being my laptop).
- The basic overview of the pipeline
    - Logs User Data and stores it in a central database
    - Retrieves a small portion of repositories using Approximate Search for similar "items"
    - For this the data is separated into two towers, one is user tower which contains a numerical representation of each user and one item tower, which contains the numerical representaion of each item (here repository), we can have these with different patterns like query-item, query-user etc. depending upon our task
    - Then after retrieving top k items for the user requesting a query. We give it to a rank after basic filtering
    - Then the ranker ranks all the items wrt to the user history and preferences
    - And at the end everything is shown to the user
    - Then our ranker observes a new context and update it's believes and weights
- **Check this out here:** [anshulbadhani/github_recsys: Tower-two and NeuralUCB hybrid to generate repository recomendations](https://github.com/anshulbadhani/github_recsys)
