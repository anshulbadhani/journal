# June 2026
The previous month was mostly exams. But now, I have summer vacations and I want it to be something fruitful for me. Since, I didn't land an internship. I will rather chill than panicking about stuff.

## 1-2 Jun
- Rested, didn't do much and neither do I wanted to do anything. I tried to do some stuff but ehh. I think I was kinda burnt out so, I just slept.

## 3 Jun
- Till the time of writing, I made a plan on how to utilize this month and I dont want this month to be too productive in terms of writing and shipping code for the sake of it. I just want to slow things down.
- I am planning to complete all the pending projects and focus on other areas of my life for sometime.
- I will try to complete the GEMM library I was working on but since it is a new project I will put it on hold for now.

## 4 Jun
- I started working on my bandit scheduler. My oldest running task since December.
- So, I opened the codebase after soo long and realised that I dont understand it well now. Cherry on top! There were no comments in that codebase.
- I tried to refactor the codebase, started to document things, how one module is related to other
- Had a look into Hidden Markov Model Theory, realised that it has many many limitations for this application. I would have to overcome those anyhow and it is going to be an insanely difficult task, while keeping all the constraints in my mind.

## 5 Jun
- It was a very sad day :(
- My laptop got burnt
- I was working on llama.cpp and planning to open an issue. I had almost fixed it and the only thing which was left to do was profiling of my fix, since it was a performace and build fix.
- So, I flashed my usb stick with PopOS! Then I shutdown my laptop and it never woke up :((( 

## 6 Jun
- I installed termux on my phone. I cannot do heavy programming ofc. But I can do something at least. Writing this commit from my phone.

## 7 Jun
- Planned a few things. Mostly on how I want to learn proper proving methods

## 8 Jun
- Solved puzzle by 0xPARC (if I remember the name right) which was basically given a secret tuple what is the most optimal way to find it using query vector(s) and we will get dot product everytime. (the answer is not n for arbirtary tuple on $\mathcal(R)$, if we are being clever and try to "cheat" the assumptions)
- Now, I will start to learn formal proves.
- I started with the book Hamlock and after the `P(P(R²))` question. I started to imagine it... realised we can also go one abstraction above. Tried to explore this notion more and I stumbled upon modern set theory
- The conclusion is... everything is a set :skull:

## 9 Jun
- I started to apply again and mostly applied through out the day... and tbh applying from phone is a headache. Not every webpage is designed for phones. I apllied to two places
- One is more of a research contribution for EAI language benchmark. I would be contributing for my lanugage Kumaoni. It just feels good in a way, not because of contribution and opportunity to become a co-author.
- But who knows in very late future what would happen. It is that, my language will be preserved in the dataset. Which would be an open source dataset <3

## 10 Jun
- I was scrolling through linkedin and found a rather interesting post. SciPy-india and Rust india are going to organize a small offline meetup. I am thinking to give a talk there.
- The topic would be something like "The GOAT abstraction". I will be diving into the ideas I discovered on night of 8th June.
- It was basically that division algorithm `a = bq + r` can be abstracted into more ideas like PCA, SVD, Fourier Analysis, Linear Filters, Compression and even crazier ideas. They share the same structures i.e. approximation of a quantity. Division is literally approximating a by using b qs and the error in that approximation is r.
- I just have to weave it into an entertaining narrative. Because it seems like a perfect idea for a talk with that audience. Scipy people would love the mathematics and rust people would love the beauty of abstraction.

## 11 Jun
- Got my laptop working finally!
- Tried to setup latex tools offline on my machine. Idk why it still is a pain to do so

## 12 Jun
- Worked on scipy x rust delhi proposal.
- Before submitting anything. I developed a narrative around the concept and how to introduce it to the audience so it is not boring to them.
- Tried to test my intuition by writing a custom quantization algorithm and tested it on TinyLlama1.1B, but it failed and generated pure garbage.
- It was not purely random, it had some meaning in the words it wrote (besides the special characters) but it was not at all related to what I asked.
- But, on the brighter side the size reduced to 2.05 GB to about 1.46 GB. So, I would say, it did a few things and the SMA was around 45dB... idk it should have worked but idk, would have to look more into it, or prepare some other application of what the abstraction I want to propose.

## 13 Jun
- Read the Logic chapter from Book of proofs by Richard Hammack.
- One read section 2.1 tbh... because I started to explore the idea of Axiom of Anti Foundation aka Anti Foundation Axiom, which allows sets like `A = {A}` which are "non-standard" non-ZFC sets, allowing infinite recursive structures.
- I looked into why are they useful and where would they be useful. The answers were not convincing enough for me. But, it was also not nothing. I guess my understanding is limited by how much I know and can comprehend. I understood we can use it to represent recursive structures like graphs. But that can be done with references and arrays easily. So, I dont see a point why would they be useful.
- One interesting application I found was to prove that two objects are same from inside out, say I have two pieces of code, let's say pattern printing to print this pattern

```
*
**
***
****
*****
```

- This pattern can be printed using prints, loops and recursion. Now, these recursive sets can be used by softwares like compilers to prove that two pieces of codes have same output or at least same internal behaviour and output. Hence it can eliminate it.
- Or it can be mathematically proven that a piece of code can never be reached, idk if I have shared this idea here before, but we can theoritically bypass certain compilation errors if we use -O3 and compiler eliminated the "unreachable" code. This can be used in lab tests lol to show that the code compiles but gives no output for "right looking" code. For more info chec out my logs for GEMM library I was writing
- To prove such eliminations wont affect our output. These could be useful, but I am not convinced.
- One rather interesting thing which I am very convinced with is, proving an infinitely running program will never crash, say a web server. 
- Or we can prove things like, a bandit and HMM based task scheduling algorithm will "converge" and give "sane" outputs.
> *Note: idk how to word it formally, I lack that lingo, but if I use my application for say, more than 5 years, the storage used would not explode on an android device, or due to same algo running for so long. it does not generate noisy recommendations and optimizations for the user using the program* For more info check out my logs about bandit task scheduler.
- Ahh! one more thing I found it useful was for language models, and modelling language sementics (that is where i got idea of Dead code elimination or compilers in the first place).
- To test it, I tried to vibe code sementic engine for a toy language inspired from game called [Baba Is You](https://en.wikipedia.org/wiki/Baba_Is_You) and tried to write a program to identify redundant or paradoxical rules and tried to handle those cases or eliminate such rules for a scale which might not be needed, so I cannot model it using simple if elses. But, I failed miserably.
- So, for now, I see potential in the idea of `not-well-founded sets` but I am not convinced by them.

## 14 Jun
- I have figured something out, I think if I take smaller steps then I will do much better than I am already doing. So, I suppose it is okay to sacrifice some development speed for stronger foundations and higher quality of work
- With that note, I started to work on the pre-print. Man! finding a good latex template is hard. Tbh I dont want a research paper like template. I want something like a 1960s technical report from NASA. It looks cool that way, for a technical report. For now, I am sticking to ICML Template. It is good besides the centering it forces everywhere. Like, ugh I just don't like it. It works for now though.
- I opened a few issues on github for the same repo.

## 15 Jun
- Laptop repair guy came. There were a few more concerning issues. It took sometime but I would say that it is fine.
- I continuted the work on pre-print. I have written 13 pages in last 2 days, well a lot of it was already written for DAA report. I just used a more formal language this time.

## 16 Jun
- I worked on my recsys report mostly.
- I also waste a lot of my day in stress testing my laptop to find any issues again. I found the thermal throttling to be crazy and not effective at what it is for.
- and I just realized that I am writing wrong dates lol. Today is 17 and this entry should be of 15. But since the dates are now fucked so, I will keep it this way to avoid too much work and confusion
- Researched a bit about linux distros after installing like a million gigabytes of updates on my live usb.

## 17 Jun
- Almost done with the report, just a few todos
- No longer unemployed, working under Dr. Sushil Kumar from NITKKR.
<!-- - Anisha is smart, Anisha is cool, Anisha is Anisha, Anisha thinks a lot, Anisha is a simple insane, Anisha is chota sa baccha, All I can think about is Anisha, Anisha is something to be obssesed with, Anisha owns an island called Anishia, Anisha is a good friend, Anisha is someone I can't forgot, Anisha is deadly, Anisha is pretty, Anisha talks a lot, Anisha is funny (rarely), Anisha is fun, Anisha is someone I always to hangout, Anisha is a project... Project Anisha (iykyk), Anisha told to me to do this, Anisha is seedhi saadhi insaan, Anisha k baare mai jitna bole utna kam hai, Anisha is cute, Anisha is pyari, Anisha is basic, Anisha is mid, Anisha has good hair (never noticed idk), Anisha is old, Anisha takes a lot of stress (mat liya kro yawr), this is co-authored by Anisha, Anisha why, Anisha hello, Anisha sleep a lot but not on time, Anisha is so done, Anisha k baare mai jitna bolo utna kam hai, Anisha is like me, Anisha is crazy, Anisha is 152cm tall, Anisha is 49kg, Anisha is chatori, Wish her happy birthday on 1 Jun, Anisha is intelligent, Anisha is inspiring, Anisha is interesting, Anisha is nalli (as of 17th Jun), Anisha is someone I can ruin my sleep for, I love my sleep but I love Anisha more (I'm held at gun point), Anisha is the meanest person alive (disagree), Anisha has a good humor, Anisha goes by vibes, Anisha gives good vibes to me, Anisha is nice, Anisha gets angry quickly, Anisha is a good person. -->
- I studying about Fuzzy C means and PSO and read a paper on Tumor detection
- Booted AntiX linux for the first time, and I fucked my laptop's clock lol
- Worked on report and numerical stability proofs for Welford's Algorithm

# 18 Jun
- Didn't do much besides setting up antiX
- Touchpad is not working at all
- So, I decided to install drivers
- Learnt a lot because of this experience (connmanctl, how to use variables as copy past in shell scripting – it is kinda smart thing to do, awk and a lot more)
- All this to realize that I could not enable mouse support
- And discovered that I cannot easily access files on my Ventoy drive (it should not be that way tbh) and as a backup I cannot access through nvme because all the data was stored in WSL.

# 19 Jun
- Studied floating point arthematic and damn! why the hell is this not taught to us at all! It is legit the most important thing that everyone who learns to program should know (okay not everyone but it is litearlly very important in most of the domains)
- I just got to know that `sum += x[i]` accumulates errors like crazy and applications where precision is crucial like some aircraft, spacecraft, satellite, scientific simulation, trading systems etc. This is literally a death sentence :skull:
- I had a look into proves involving numerical stability for my report. I have written something using AI but for now I cannot verify if the proof is correct or not. So, I would learn about floating point arthematic for a few days and then I will verify the proof and move forward.
- I have to verify all the numbers by proper profiling (testing on bare metal and removing WSL overhead).
- Update: the dates are not wrong, idk wtf is happening lol

## 20 Jun
- Took all the day to write proofs of numerical stability, sub suboptimality of Adaptive MMR (met my friend matroid again) and verified each and every number in my report.
- Took the entire day to fix all the inconsistencies.
- Fixed all the calculations and verified all the clock cycle numbers properly using `perf`.
- only one thing is left that the ratio of percentages and clock cycles in the latency pie chart are not matching and I am too lazy to fix it atp. Let's see if I do it tomorrow or not.
- Besides that I have to read my paper as well on FCM PSO CNN for brain tumor detection. Tomorrow I will get more than enough time for it.
- and and and I almost wiped off my ssd while turning on persist all on antiX. Cancelled at the very last second.

## Wild card
Well I have some todos left:
- [ ] Read FCM PSO CNN paper
- [ ] Open issue in llama.cpp
- [ ] Read the "What every computer scientist should know about floating point arthemetic" paper
- [ ] Set up the platonic universe pipeline
- [ ] Also learn how to prove stuff

## 21 Jun
- Completed the recsys from scratch report and uploaded it on ssrn

## 22 Jun
- Formatted for arxiv submission. Now, I just have to figure out the endorsement. Lets see what happens.
- Looked in KNN and FCM for PSO CNN paper

# 23 Jun
- Laptop went to service center might take a few days... I think it is better to get a proper hardware inspection when the warranty covers it rn
- Well this gave me a lot of time to think. I didnt do much today besides this thought.
- I think what I lack is not more technical knowledge... it is the technical maturity
- I think having a mentor for me is necessary... and by mentor I just mean someone experienced in a particular field.
- Well currently my interests are things which have ownership, stakes and depth. I think I did a bad job explaining it.
- Basically, I want do something which is not something aleady done, something novel or something deep or something where stakes are high
- Currently those things are qfin, ai research involving a lot of math. like converting bandit problem into linear program to define tighter bounds or mathematically proving reliability of CNNs for physics simulations with reasonable error bounds. Or it could be making rockets, spaceships, satellites... cool stuff like that involving huge stakes or trading bots where every microsecond counts.
- and mentor if I elaborate more I think of it like an older friend. To whom I can just talk about stuff
- someone who can tell me things like... sum += x(i) is not something to use in a critical system as it accumulates error in O(n) 
- if I tell them Im optimising this algo and they respond with... have you even checked if this part is bottle neck or not? Are your assumptions even right?
- was the cache warm? did you pin the thread? how much is the variance... p1, p50 and p99?
- or things like... yes this algo is working but is it feasible to run this for 2 years straight? for a user? what would be the infra maintaince required? what part is online and what is offline... will this explode?
- I mean yeah not all these at once... but at least someone who can point these things out to me. I lack these small small nuances.
