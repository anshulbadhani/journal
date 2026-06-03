# May 26
## 1-7 May
- Lots of lab test and ig this month will go in end semester exams

## 8 May
- Hackathon Results out, we made it to top 100 but not the winning list. I mean, I do feel like we could have won. But, I kinda feel sad. But our hackathon sumbmission could be a really strong paper.
- Today was the submission for our Design and Analysis of Algorithms Lab Semester Project. We fucking nailed it!! Ma'am was really impressed and even suggested to try for publication somewhere. The pay off was worth it! And like that the `recsys-from-scratch` projects comes to an end (in lab project context) and now I can implement all the "fancy" algorithms or at least work towards challenging the assumptions of our system and move towards a more modern pipeline in C++
- But the exams are starting from Monday, soooo ehh I would have to focus on my exams too.

## 17th May
- I am not able to write here because of busy schedule and exams. But while studying for my AI/ML exam. I came to a very very very interesting realisation!! Conway's Game of Life is basically a Convolutional Filter with a hand designed kernel which is dependent on the fact how many of the eight neighbours around a cell are alive. This is fucking awesome!!! 💀
- Like there are so many similarities between both of these. And it would a really really interesting idea to like combine both of them into something very interesting. And since Conway's Game of Life is recursive in nature. It I believe can be a very fun thing to observe from the lens of convolution and millions of ML architectures we have with us. 
- I am already excited about linking this with attention heads and RL with some modifications in our base environment of Conway's game of life to make something banger! 💥
- So, after some more thinking. I think it would be awesome to link this idea to molecular biology. Like how we tried to use Genetic Algorithms to simulate molecules with our Data Structues project but failed and did it statically, but now instead of genetic algorithms. I think it would be an amazing idea to prove equivalence of PDEs with CNNs for diffusion systems and the good news is, according to Claude (I dont have much time to dive deeper because of exams)
> Turing's 1952 morphogenesis paper already shows reaction-diffusion PDEs produce spatial patterns. LeCun's 1989 work implicitly discretizes spatial operators. There's a 2019 paper — "Neural Ordinary Differential Equations" by Chen et al. — that formally connects residual networks to ODEs. A 2020 paper by Ruthotto and Haber connects CNN architectures to PDEs explicitly. So the bridge exists partially — your specific contribution would be formalizing the equivalence for reaction-diffusion systems specifically, which is a subset nobody has cleanly closed. That's a well-scoped mathematical problem. Provable or disprovable. Not open-ended.
- CNN prebiotic chemistry: isomerism, orbital electronegativity, physics-accurate modelling. Research problem post exams
> Come back to this after Monday. I'll go as deep as you want — VSEPR, orbital hybridization effects on electronegativity, how graph neural networks handle stereochemistry, why CNNs ~ Claude

## 18 May
- Today was my AI/ML exam and it went well for the topics I stuided properly
- Now, I think I have found my major and minor project ideas. Which are going to be related to the above. So, the idea is to prove mathematical equivalance between CNNs and reaction-diffusion PDEs and this is the project I am gonna work on for next 1-2 years of my degree.
- It is not like no one else has done this. This is well formalized for Linear PDEs in different forms. But where this idea breaks is when non-linearity is introduced in the system.
- The plan is to
    - Prove the equivalance
    - Then design a CNN architecture to demonstrate it works
    - Since they both are equivalant. Show that we can represent a small ConvNet as PDE
    - And then prebiotic chemistry application
- So, the goal for this semester is dive deeper into 
    - Real and Complex Analysis (coursework)
    - Functional Analysis
    - Numerical Analysis
    - Semi-group theory
        - since the equivalance which has to be proved is not between normal fields or objects we are used to. But between two computational methods. I need to find a strong mathemaitcal representation of these two objects
        - Also because PDEs and CNNs both define an evolution operators which takes in state at time t and gives state at time t+1
- I would have to find some prof whose area of research is PDEs, numerical methods, dynamical systems or mathematical/computational biology.
- And I think this connects really really well to the idea of `fundamental laws of learning` which would eliminate the current trial and error process to discover new architectures and we can actually prove that why CNNs can classify images, RNNs work well on sequential data and GANs work so well on graphs. Because every architecture is equivalant to a Partial Differential Equation. Hence we can derive them from first principles
- I have found some cool books on the subject. Here is the list for reference for my future self:
    - *Introductory Functional Analysis with Applications* by Erwin Kreyszig. Which build upon the foundations of functioanl analysis so that I could later transition to proper non-linear functional analysis
    - *Applied Functional Analysis* by Oden and Demkowicz. It seems like a good read is more relevant for Numerical PDE theory. So, when I prove the error bounds it would be pretty staright for me
    - *Nonlinear Functional Analysis Vol I* by Zeidler. This one is the book I have to study for equivalence proof (since the system I am going to work on is nonlinear) and I might find relevant proofs here.
    - And I will use the research papers metioned above as the starting point after the exams.

## 24 May
- "Functional Analysis, Calculus of Variations and Optimal Control" by Francis Clarke

## 25-28 May
- Conculded with European Rover Challenege video.
- Chased an issue at FAISS (Doing that since exams). I realised that it requires a very specific hardware to replicate. Which sadly I do not have.
- The issue was basically something related to AVX512 intrinsics not working.
- Docs PR at tensorflow/agents
- Worked on #10116 from llama.cpp. I could not replicate the bug. But found that AVX-VNNI will not properly work on some machines. For now, I have benched the issue. I might get back to it later.
- Started to write a matrix multiplication library. So, that I could learn how to optimize performance critical systems. Will make a repository soon.
    - Figured out how to benchmark properly (WSL is a constraint I am working with, so perf is out of the window) I am using google/benchmark for benchmarking.
    - learnt about span and how awesome they are
    - fought a lot with templates in headers. It was such a headache to work with. `.hpp`, `.tpp`, `.cpp` making these work with each other was something I was not thinking would be this unintuitive.
    - built the benchmark from source as the apt version was in debug mode and may give slightly off results (in my case 2-3%)
    - Learnt about arena allocators (again)
- Got aware of cool contests like ICFP Programming contest, SSC which was basically we have to make our own Computing Cluster. I would LOVE LOVE to participate in something like that!!

## 29-31 May
- ERC video work. Done with video editing and submission
- Looked into linux internals
    - got to know that maximum stack capacity is 8192 kB on linux for C++
    - triggered stack overflow multiple times while testing the GEMM library I was writing
    - looked into `/proc` it was a really fun experience
    - force shutdow PID 1 using telinit and watched the kernel kill itself *sips tea*