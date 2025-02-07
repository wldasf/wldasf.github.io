Personalizing Guided Project Learning with LLMs
===============================================

Feb 02, 2025

I find blogs that guide learners into creating programming projects interesting but also limited because they are often outdated, and lack the customizability of your familiar technologies. Often I find that when I want to learn certain concepts in computer science these kind of guided projects don't fill in the gaps. 

As an alternative, I found that I can just use an LLM to guide me through projects of my choosing whiel integrating concepts that I want to learn in order to make it more fun and practical. To make sure I'm properly learning and not just typing code I specify in my prompt to explain every piece generated and a high level overview to make sure I understand what I'm doing. I write every line of code by hand just like I would do with a guided project blog but I get the customizability that I want and active engagement while building the project.

A rough example of what I would prompt the LLM with:
```
I want to work on personal projects to learn. You will be my partner, guide, and assistant. You will guide me through the project piece by piece and I will write the code manually by hand so I can learn. You will explain the code and give me a high level overview of each piece. Keep in mind the topics I'm describing for the project. Here's the first project:

Distributed Task Scheduler
- Topics: Distributed systems, multi-tiered systems, algorithms, complexity analysis.
- Project: Design a system that distributes tasks across worker nodes (simulate with Docker containers or threads). 
  - Implement scheduling algorithms (e.g., round-robin, priority queues).
  - Track task status in a relational database.
  - Handle failures and load balancing.
  - Analyze time/space complexity of scheduling strategies.
```

Usually with this prompt the LLM will first discuss the high level architecture of the project and ask you for the technologies you would like to use before getting started.

Happy hacking.