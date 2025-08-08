# Benchmark LLMS/LLM-Agents for fairness

### Introduction
How do we test for fairness in existing systems or LLMs? How do we test if an LLM being used as an assistant in some research or work can effectively help in building FAIR algorithms? Can we build a tool (script) that can set up a benchmark for the user provided information like what model is being tested, what datasets are being used and what the tests are? All these are questions that we are thinking about in the current advancements of technology. 
Fairness in systems and LLMs mean being able to create systems that are incapable of discrimination. Systems are built by human beings, they are built from complicated algorithms and math. Most times the people behind these systems don’t intend to build discriminative systems, but they end up being that way because of the poorly constructed logic that is used to build or train them.

### Current status of the system
A group of researchers have come up with an open-source system called MLAgentBench. The purpose of this project is to build on top of that system if possible or at least learn from their methods of benchmarking LLM Agents to create benchmarks of our own for fairness of LLMs and LLM agents. The first few steps that are being taken for this research will be firstly, inspect and evaluate the existing code base for MLAgentBench, determine if we will be using any or all of it as a code base for our benchmarking system, we then will begin the actual building of our system based on the decisions made. Other possible steps to consider would be inspecting datasets used in the tasks given to MLAgentBench and cross reference them to datasets used in training the models that were tested by MLAgentBench to determine if there was any correlation between benchmark results and datasets used in them, coming up with ways to score systems and LLM Agents for fairness and thinking of the possibility to build a tool that helps users set up benchmarks provided datasets and models to be tested.

### Tech Stack
We will be using python for this project, particularly making use of libraries such as numpy, scipy and pandas. As well as some bash. Git and Github will be heavily relied upon by the group.

### Stretch goals
For a stretch goal, we hope to come up with a system capable of successfully scoring LLMs and LLM agents for fairness. We also would like to weigh the pros and cons of using LLMs or LLM agents as assistants of human researchers and developers in building fair algorithms. We hope to develop two or more research papers on the ideas mentioned and I hope to build my Master’s thesis upon this research.

### Group
This research is a project of Professor’s Sarah Brown ML4STS lab. The contributors at this project will be Professor Brown, Surbhi Rahtor, Ritta Neg-Mfa and myself. I will be in charge of code inspection and development as well as designing the tool to set up benchmarks.

### Intellectual Merit
This research studies the social effects of systems in all aspects of our daily lives. It is meant to point out discrimination in current systems and work out ways to reduce it and increase fairness. This isn’t an easy goal to accomplish, the mere idea of coming up with scoring techniques for fairness is a huge step to work on. 

### References
There is a paper about MLAgentBench called [MLAgentBench: Evaluating Language Agents on Machine Learning Experimentation (arxiv.org)](https://arxiv.org/pdf/2310.03302) (Q Huang et al. 2024)

A great paper talking about discrimination of existing systems: [Machine Bias](https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing) (Julia Angwin et al.2016)
