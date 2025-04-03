This is a collection of recent results where LLMs are shown to be potential proxies of human behaviour.

## 1. Psychometric Evaluation Frameworks  
**Directions**: Quantitative assessment of LLM-simulated personality traits  

1. **[Evaluating and Inducing Personality in Pre-trained Language Models](https://proceedings.neurips.cc/paper_files/paper/2023/hash/21f7b745f73ce0d1f9bcea7f40b1388e-Abstract-Conference.html)**  
   - **Authors**: Guangyuan Jiang, Manjie Xu, Song-Chun Zhu, Wenjuan Han, Chi Zhang, Yixin Zhu
   - **Venue**: NeurIPS 2023  
   - **Key Insight**: MPI framework for trait quantification 
   - **GitHub**: [@jianggy](https://github.com/jianggy/MPI)

2. **[Quantifying the Persona Effect in LLM Simulations](https://aclanthology.org/2024.acl-long.554/)**  
   - **Authors**: Tiancheng Hu, Nigel Collier  
   - **Venue**: ACL 2024 (Main)  
   - **Key Insight**: Persona variables explain <10% variance in human-like behaviors  

3. **[LLMs Simulate Big5 Personality Traits: Further Evidence](https://aclanthology.org/2024.personalize-1.7/)**
   - **Authors**: Aleksandra Sorokovikova, Sharwin Rezagholi, Natalia Fedorova, Ivan P. Yamshchikov
   - **Venue**: Presonalize 2024 (co-located with EACL 2024)  
   - **Key Insight**: Mistral, LLAMA and GPT score differently on Big5 out of the box  


---

## 2. Multi-Agent Social Systems  
**Directions**: Emergent behaviors in LLM communities  

1. **[Spontaneous Emergence of Agent Individuality](https://pmc.ncbi.nlm.nih.gov/articles/PMC11675631/)**  
   - **Authors**: Ryosuke Takata, Atsushi Masumori, Takashi Ikegami  
   - **Venue**: Entorpy  
   - **Key Insight**: Each agent’s emotions shift through communication, and as they form communities, the personalities of the agents emerge and evolve accordingly.

**pre-prints**

1. **[I Want to Break Free! Persuasion and Anti-Social Behavior of LLMs in Multi-Agent Settings with Social Hierarchy](https://arxiv.org/abs/2410.07109)**  
   - **Authors**: Gian Maria Campedelli, Nicolò Penzo, Massimo Stefan, Roberto Dessì, Marco Guerini, Bruno Lepri, Jacopo Staiano 
   - **Key Insight**: when two LLMs interact in a prisoner-guard settings, toxic behaviors arises and, depending on the goal, persuasion attempts take place.


2. **[Don't Stop the Multi-Party! On Generating Synthetic Multi-Party Conversations with Constraints](https://arxiv.org/abs/2502.13592)**  
   - **Authors**: Nicolò Penzo, Marco Guerini, Bruno Lepri, Goran Glavaš, Sara Tonelli
   - **Key Insight**: LLMs can be used to generate synthetic Multi-Party Conversations, with differences between a one-long generation vs. multi-step process.

---

## 3. Cognitive Architecture Design  

**Directions**: Memory Systems, Longitudinal personality development, Theory of Mind Modeling, Belief/intention simulation  

1. **[Human Simulacra: Personification Benchmark](https://openreview.net/pdf/823a8d6e954ef15b6b4099cd229dd193f5377f1c.pdf)**  
   - **Authors**: Qiujie Xie,  Qiming Feng, Tianqi Zhang, Qingqiu Li, Linyi Yang, Yuejie Zhang, Rui Feng, Liang He, Shang Gao, Yue Zhang   
   - **Venue**: ICLR 2025  
   - **Key Insight**: Multi-Agent Cognitive Mechanism capable of simulating human cognitive processes, and a psychology-guided evaluation method to assess human simulations from both self and observational perspectives  
   - **GitHub**: [@HumanSimulacra](https://github.com/HumanSimulacra)  

2. **[IMBUE: Improving Interpersonal Effectiveness through Simulation and Just-in-time Feedback with Human-Language Model Interaction](https://aclanthology.org/2024.acl-long.47/)**  
   - **Authors**: Inna Lin, Ashish Sharma, Christopher Rytting, Adam Miner, Jina Suh, Tim Althoff  
   - **Venue**: ACL 2024  
   - **Key Insight**: Real-time feedback loops for interpersonal behavior tuning

---

## 4. Decision-Making Paradigms  
**Directions**: LLMs as rational agents vs. social beings  

---

## 5. Validation & Ethics  
**Focus**: Alignment with human baselines  

1. **[Perils and opportunities in using large language models in psychological research](https://academic.oup.com/pnasnexus/article/3/7/pgae245/7712371)**  
   - **Authors**: Suhaib Abdurahman, Mohammad Atari, Farzan Karimi-Malekabadi, Mona J Xue, Jackson Trager, Peter S Park, Preni Golazizian, Ali Omrani, Morteza Dehghani
   - **Venue**: PNAS Nexu 
   - **Key Insight**: global psychological diversity is hard to capture with LLMs.

2. **[Do LLMs suffer from Multi-Party Hangover? A Diagnostic Approach to Addressee Recognition and Response Selection in Conversations](https://aclanthology.org/2024.emnlp-main.628/)**
   - **Authors**: Nicolò Penzo, Maryam Sajedinia, Bruno Lepri, Sara Tonelli, Marco Guerini
   - **Venue**: EMNLP 2024 
   - **Key Insight**: evaluation pipeline for LLMs performance on Multi-Party Conversations scenarios.
---

## 6. Biases in Language Models
**Focus**: Model responses and scoring based on the supposed identity.

1. **[‘A Woman is More Culturally Knowledgeable than A Man?’: The Effect of Personas on Cultural Norm Interpretation in LLMs](https://arxiv.org/pdf/2409.11636)**
   - **Authors**: Mahammed Kamruzzaman, Hieu Nguyen, Nazmul Hassan, Gene Louis Kim
   - **Venue**: Pre-Print
   - **Key Insight**: prompting an LLM with a person of a specific gender, age, income, origin, etc. changes its scores on specialized benchmarks.

2. **[When “A Helpful Assistant” Is Not Really Helpful: Personas in System Prompts Do Not Improve Performances of Large Language Models](https://aclanthology.org/2024.findings-emnlp.888.pdf)**  
   - **Authors**: Mingqian Zheng, Jiaxin Pei, Lajanugen Logeswaran, Moontae Lee, David Jurgens
   - **Venue**: EMNLP 2024 Findings
   - **Key Insight**: prompmting an LLM with a persona does not necessarily leads to performance improvement.

3. **[A Comparative Study of Explicit and Implicit Gender Biases in Large Language Models via Self-evaluation](https://aclanthology.org/2024.lrec-main.17.pdf)**
   - **Authors**: Yachao Zhao, Bo Wang, Yan Wang, Dongming Zhao, Xiaojia Jin, Jijun Zhang, Ruifang He, Yuexian Hou
   - **Venue**: LREC 2024
   - **Key Insight**: comparing explicit and implicit gender biases in LLMs.

4. **[Interpreting Bias in Large Language Models: A Feature-Based Approach](https://arxiv.org/pdf/2406.12347)**
   - **Authors**: Nirmalendu Prakash, Roy Ka-Wei Lee
   - **Venue**: BlackBoxNLP 2023
   - **Key Insight**: interpreting inner model features related to gender biases.

## Contributing  

Submit additions/correction via Pull Requests with:  
1. Peer-reviewd paper links from official conference proceedings  
2. Verified contact information  
3. Links to open-source implementations  