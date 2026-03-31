# March 2026
For March 2026 check this out as the list here is not complete because of workload of this month 🙃😭: [TAAL/devlog.md at main · Tanishq172006/TAAL](https://github.com/Tanishq172006/TAAL/blob/main/devlog.md)
## 28 Feb (Imposter)
- Day 0 of `FOSSHACK`. Had our first meet where we discussed about ideas
- Read `Queuing systems volume 1 by Klienrock`
    - W book
- Read Thank you for arguing a little. Didn't like it that much but I will complete first two chapters at least to see if it is still boring or not

## 1 Mar
- Gone through the whole of the Queueing systems book roughly.
    - Learnt about Kendall's notation
    - Rough idea (intuitive) of M/M/m, G/M/m, G/G/1 and G/E/m prcoesses
- Had a look into `Kotlin` for first time
    - I like that lanuage. It is clean af

## 2 Mar
- FOSSHACK
    - Learnt about AudioEngine and its responsibilities
    - Came to know about media3 by google as an alternative to ffmpeg and LibVLC
- Queueing Theory
    - Learnt about the role of Transform like z and laplace transforms in analysis of a Queue
    - Built a solid intuition about Eigenfunctions and Eigenvalues of that function
    - The notion of linear operators
    - Familiarized myself with the formal notations used in Queueing Theory and basic terms like:
        - Arrival Time
        - Service Time and service time distributions
        - Interarrival Times and interarrival time distributions
        - Measuring of unfinished work at some time and how to define it
        - waiting and system times
        - the concept of average interarrival time and avg arrival rate

---
Well, from this point onwards, I have tuta-foota record of what I did from whatsapp groups and our FOSSHACK TAAL repo. So, it is recomended to see the FOSSHACK devlog for FOSSHACK work.

## 3 Mar

## 4 Mar
- Studying the most random thing: Mathematics of people waiting in lines. Today I learnt about:
    - Utilization Factor and derivation of all the variations which are:
    - single server
    - multi server
    - infinite capacity 
    - and parameter variations
    - Little's Result

## 5 Mar
- Studying the most random thing: Mathematics of people waiting in lines. Today I learnt about:
    - Discrete time Birth-Death process using Discrete-time markov chains on a markovian process
    - Learnt about Computational graphs
    - Operator Fusion

## 6 Mar
- FOSSHACK
    - DUNIYA BHAR KI DEBUGGING AND ERROR FIXING
    - DATABASE BRIGDE AND NATIVE INTERFACE BRIDGE
    - GRADLE K ERRORS DUNIYA BHAR K

## Rest of the March upto 25th March
- Got invited for European Rover Challenge
- I am the exploration lead for this
- My task is to perform geological analysis of the martian surface and comming up with a mission plan.
- Learnt about Basic Geology and how to make geological maps
- Learnt how to use JMars and Google Earth Pro
- Read all the rules and duniya bhar k docs to figure out what we have to do and what can we actually do, basically the dos and donts
- Made a few presentations for pitching our work
- And khoob saari meetings, it was fun though and meet many cool people across all domains. GOOD STUFF

## 23 Mar
- Started to work on the GitHub Recomendation System. Using a Two tower arch, but will use bandits instead of full blown neural networks.
- Did some very basic research and literature Review
- Studided for Science of Happiness Exam

## 24 Mar
- Today was my Science of Happiness Exam
- Didn't do much, but I installed the data from [here](https://github.com/John-K92/Recommendation-Systems-for-GitHub)
- Separated the data into multiple `.csv` files.
- Have my Numerical Methods and Computation exam tomorrow, so studied about numerical methods to solve a system of linear equations (interpolation bcha hai :cry:)

# 25 Mar
- Today was numerical methods exam
- Studied Numerical methods (ofc)
- Studied the Github Rec Sys Data set and tried to filter it out to avoid cold start edge cases

# 26 Mar
- Registered for Meta AI Hackathon organized at scalar blr
- Studided for AIML exam, in very depth actually
    - Types of Models
    - Performance Metrics for evaluation
    - PCA
    - DBSCAN
    - Hierarchical clustering analysis
    - and a lot of stuff, still my syllabus is no where close to complete
- Backed up all my bandit scheduling code on github
- Prepared a solid intro for any interview, written on the back of my rough notebook (for me to remember)
- Attended the FOSSHACK QnA session and interacted a bit with them online
- Said no for Municipal Corporation Delhi Hackathon, because my other teammates were not interested and ofc... FOSSHACK is at the same day
- Prayed for my exam (I'm cooked)

# 27 Mar
- Got cooked in my AIML exam
- Studied Backpropagation well (for the limited time I had)
    - Still have many questions though
- Worked on GitHub RecSys
    - Learnt about the spotlight library and the module which was included in the paper's repository
    - Wrote some dumb code to understand the dataset well, like what kind of features are what type and what the different particians of the dataset contained
    - Tried to save things into a pandas dataframe, but I realised that number of users != number of repos. Therefore, I need multiple tables (towers 🦅)
    - Next, I'll focus on sequence generation via spotlight and embedding generation to feed into my two towers.

# 28 Mar
- Attended FOSSHACK offline events
- Made some insane progress for FOSSHACK
    - fixed UI a bit
    - Resolved audio not playing on piano while pressing play
    - Added right clicks for desktops along with long press
- Made some insane progress on GitHub repo recomendation engine
    - Now, I understand the Interactions and SequenceInteractions objects very well.
    - Extracted and organized data for user and item towers from pickle files into less "bloated" pickle files
    - Tomorrow, I will use `Sentence-Transformers` to generate embeddings and start working on the core algorithm itself.

# 29 Mar
- Studied Greedy Algorithms for Design and Analysis of Algorithms exam
    - Will study Backtracking after this
- Worked on embedding generation
- Generated two static, repositories and user towers
- Pray for my tomorrow exam (I hate exams but I love algorithms design and analysis)

# 30 Mar
- Made my resume.
- Looked out for internship opportunities (why are there next to no recsys opportunities for undergrads, I understand why!!! BUT WHY :cry:)
- Had a long long meeting about FOSSHACK. It's already 2.30 AM
    - Tested the guitar chords feature
    - Debugging of AudioExport issues (bascially the tempo nd pitch was shifting a bit and it was sounding BAD)
    - Realsed v1.0.1 :yay:

# 31 Mar
- Have my Linear Algebra exam tomorrow. It is not difficult to understand, trivial stuff
- Worked on reorganizing the entire [github_recsys](github.com/anshulbadhani/github_recsys) repository and made it modular
    - Studied about python `dataclasses` and `field()`
    - Developed a Config class which contains PathConfig, ModelConfig and DataConfig objects
    - Refactored all the code into multiple folders
    - Tomorrow, I will write the bash script ( I have exam on 2nd too :/ ) for basic embedding generation or a very simple cli tool in python itself, let's see
    - and work on neuralBandit
- Found a few interesting papers: [Scalable Neural Contextual Bandit for Recommender Systems | Proceedings of the 32nd ACM International Conference on Information and Knowledge Management](https://dl.acm.org/doi/10.1145/3583780.3615048), [1702.08734v1.pdf](https://arxiv.org/pdf/1702.08734), [Suggest, Complement, Inspire: Story of Two-Tower Recommendations at Allegro.com](https://dl.acm.org/doi/epdf/10.1145/3705328.3748135) (this one is not very technical but can be read for fun, gives a bird eye view at a very high level of abstraction)