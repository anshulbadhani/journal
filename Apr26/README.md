# Apr 26
Finally, it is the new month, the last one was really productive ngl.

## 1 Apr
- Today was my Linear Algebra exam and it was easy
- Tomorrow, I have Time Series Analysis and Forecasting and the lore goes soo deep. But, sadly, I gotta stick the course else I will be cooked
- GitHub RecSys
    - I dived into indexing; I am using FAISS by Meta for indexing from the paper I shared yesterday here.
    - Read the FAISS Wiki and it was veryy readble and unlike many other libraries it had some useful examples which could be reffered.
    - Wrote a simple indexing class to index my "database" of repositories (It was an headache because of how I stored it. But, at the end I made it work.
    - Did a bunch of refactoring and now I can say. The code is a little reusable now.
    - Tomorrow, if I get some time. I will work on the more indexing and start with my bandit arch design
- I also found out about Gaussian Splats and it was literally what I though of compressing 3D space using Legender Polynomials as basis for real world object as a bunch of numbers. I was veryyy delighted knowing that it is really possible and it exists. But, it is wayy different than I imagined it to be. But the core idea is same.
- Pray for my Time Series Exam 🙏

## 2 Apr
- Exams finally over
- Went through the Recommendation Systems using Python and JAX again
- Wrote clearly the complete pipeline in a file on the repository
- Finally completed the FAISSRetriever class (3 AM btw)

## 3 Apr
- The day after exam feels... great. Made a lot of progress today.
- GitHub RecSys
    - Completed the Retriever class
    - Implemented Bloom Filter to remove duplicates
    - Added reward estimation using MLP
    - And finally, implemented the ranker! One thing I realised is, that behind some scary and crazy symbols, lies very simple and novel ideas which has such deep meaning. Like nothing about it is extraordinary. But the implications are just beyond the human mind, I feel like. Read this beautiful paper: [Neural Contextual Bandits with UCB-based Exploration - 1911.04462v3.pdf](https://arxiv.org/pdf/1911.04462)
- Had the ERC meeting today after so long
- and furthur discussions about upcomming competetions (I'm excited).
- Tomorrow, I will compile all the code into one symphony and hopefully, get the results I believe in. If I get time, i will complete the MVP by calculating the evaluation metrics.

## 4 Apr
- Completed the project and now it actually recommends stuff.
- But the issue is that the recommendation quality is not good. The precision and recall is very poor.
- And I realized that debugging a machine learning model is **HELL!!**
    - We cannot debug it in the traditional way
    - Training everytime takes **hours!**
    - On smaller training sets (to debug) I am not sure if the issue is due to smaller dataset of because of poor recommendation!!?
    - What exactly leads to bad choices.
    - Is bandit the issue, or the retriever? or is it the filter itself.
- Currently, it is training and I am waiting for the results
- Also, had the ERC Team meeting again to finalize our sensors and prepare a budget
- I explored some ideas for upcoming competetions. Tomorrow, I will start working on them and update here.

