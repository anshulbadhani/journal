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

## 5-7 Apr
- Tonnes of European Rover Challenge stuff
    - metting professors from physics and bio-tech department for sample tests related advice.
    - have to submit the preliminary report tomorrow.
- Written the offline evaluation script for the bandit github recys.
    - Will upload it later
    - did a lot of improvements (hardly one-two lines and getting insane metrics boosts)
    - I might have to make it work on real offline data, collected by hand to test if it works well in practice or not
- Worked a bit on my resume
- Some hackathon stuff, will share more details later down the line.

## 8-11 Apr
- Took some rest after ERC Prelim Report submission. IT WAS PEAKKK HAPPINESS AND PURE CELEBRATION among the team lol.
- Had Algorithms lab test on Friday
- Implemented a few interpolation techniques in MATLAB (Newton frwd/bcwd, Gauss frwd/bcwrd, Strling, Bessel, Langrange etc.)
- Tried to write some docuementation for `github recsys` (Probably push it before sleeping)
- Back to Queuing Theory, it is soo fun. Starting with the basic M/M/1 system. I would absolutely lovee to read from `kleinrock` once I get it from library.
- Worked on resume, tried to find revelant roles and sadly, there aren't many near me. So, I might have to apply for remote roles.
- got selected for `Meta-PyTorch OpenEnv` Hackathon finale.
- Working on Google's MLSys26 problem statement on task scheduling
- Went back to QFin again, after such a long time. Implement a few alphas on worldquant brain. But they didn't get accepted. Now, I *have* to cook something crazy! 😤
- Updated linkedin a little (added the ERC role and resume); I hope to update the [ThingsIMade.md](../ThingsIMade.md)
- Also, planned system arch for my Algorithms lab project. Compute would be a veryyy bigg issue and most of the time will go in training rather than re-iterating. I might to avail the computing facilities at my university.
- Also, we discussed about HPC, CUDA Programming, GenAI and RL courses as a viable alternative to the redundant Full Stack development (Web dev) course. We already did that last sem. But it is now finalized and the prof with whom we dicsussed these new curriculum was a bit disappointed (seemed like finally, someone (us) wanted to start some cool ahh course at our college). But it is what it is.

## 12 Apr
- Applying continues, it is hard to find relevant companies.
- Worked on WorldQuant Brain Alphas. Formulaed a few hypothesis and alphas.
- Worked on the technical report for my GitHub RecSys project.

## 17 Apr
- After a small vacation. I started to work on DAA project. [ifndef-BROS/recsys-from-scratch: We are attempting to make a recommendation system in C++.](https://github.com/ifndef-BROS/recsys-from-scratch)

## 18 Apr
- Worked on [recsys from scratch](https://github.com/ifndef-BROS/recsys-from-scratch)
- Learnt about curl
- Learnt about how to choose a proper dataset (sparsity nd all)
- What kind of recsys (sequential and history based) to use for what kind of task
- Out of Memory (OOM) issues with WSL while loading datasets (still an open problem for me to figure out)
- Chose and installed the amazon software review dataset
- Wrote a bash script, so someone new can set this up quickly on their own machine
- Watched Project Hail Marry and it reminded me of the Astro-Bio task for ERC. I wish we too had that spectrometer which Grace used in the movie :<

## 19 Apr
- Filtered the dataset
- Generated items embeddings
- Writing a parser for `.csv` files in C++ for project continuation
- All of the python part is done now heavy coding only 😈

## 20 Apr
- Written a csv parser in C++ for our embeddings data
- Designed and implemented a Bloom Filter in C++ and studied a few papers on Bloom filters. The details can found at `anshulbadhani/recsys-from-scratch/random_stuff.md`.

