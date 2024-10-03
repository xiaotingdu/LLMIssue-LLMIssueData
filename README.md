# Towards Understanding the Characteristics of Issues Across the Lifecycle of Large Language Models
Large Language Models (LLMs) have demonstrated remarkable capabilities across a broad range of tasks. Despite significant progress in enhancing and evaluating the performance of LLMs, a critical question remains underexplored: 
What types of issues do LLM developers typically encounter and what issues do they concern most? To address this gap, we perform the first empirical study of real-world issues in the lifecycle of three of the most widely used open-source LLMs: LLaMA, Vicuna, and Alpaca. 
We collect and manually inspect 591 bug reports from the GitHub repositories of these LLMs, categorizing them into 11 distinct issue types of greatest concern to LLM developers. According to the results, access, compatibility, and performance are the three most reported issues. Additionally, we analyze the distribution of these issues across different phases of the LLM lifecycle (authorization, data preparation, model pre-training, fine-tuning, inference, and deployment), revealing the correlation between issue types and specific lifecycle phases. We also assess the difficulty of solving these issues by measuring the time required to solve them and the proportion of issues that obtain an accepted answer. This study ultimately yields eight major findings with corresponding practical implications, as shown in Table 1.

![image](https://github.com/user-attachments/assets/b73aaf9e-d8ba-4e3b-9412-6bb82adc91c7)

To facilitate replication of our study and prompt future research in this area, we have made our dataset publicly available. Please find the issue information in the following links.

https://docs.google.com/spreadsheets/d/1Ea1fNprz8ldt5tDnj4V91wKwRu0v0BxQ/edit?usp=drive_link&ouid=103721203812247967297&rtpof=true&sd=true
