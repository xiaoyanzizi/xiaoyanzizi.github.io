---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* *Ph.D in Artificial Intelligence, North ChinaElectric Power University, China, 2023.09 - Present*
* *M.Sc. in Electronic and Information Engineering, Jiangsu University of Science and Technology, China, 2020.09 - 2023.06*
* *B.Eng. in Software Engineering, Nanjing Institute of Technology, China, 2016.09 - 2020.06*

Awards and honors
======
1. Outstanding Ph.D. Scholarship, Academic Year 2023-2024.
2. Outstanding Master’s Student Award, Academic Year 2020-2021.
3. Second Prize, Jiangsu Province “LSCAT” Cup Translation Competition (English to Chinese).
4. Third Prize, China Undergraduate Mathematical Contest in Modeling (CUMCM).

Grants
======
1. *National Natural Science Foundation of China (NSFC), General Program, No. 62176107*: “Research on Class Imbalance Learning Theory and Algorithms Integrating Prior Distribution Information of Samples,” Duration: Jan. 2022– Dec. 2025, Funding: 570,000 CNY, Participant.
2. *Jiangsu Provincial Natural Science Foundation, General Program, No. BK20191457*: “Research on Imbalance Learning Theory, Methods, and Applications Incorporating Prior Distribution Information of Samples,” Duration: Jul. 2019– Jun. 2022, Funding: 100,000 CNY, Participant.
3. *Jiangsu Provincial Research and Practice Innovation Program*: “Research on Active Learning Methods Based on Extreme Learning Machine,” Duration: Mar. 2022– May. 2023, Funding: 15,000 CNY, Principal Investigator.

Patents filed
======
1. “A Cloud Manufacturing Scheduling Method Based on Quantum Multi-Agent Reinforcement Learning” (in Chinese), Application No. 2024104863776, 2025.

Research topic
======
* *WorkflowScheduling Based on Deep Reinforcement Learning*
  Workflow scheduling in cloud computing refers to the intricate process of allocating interdependent tasks within workflows to suitable cloud resources. This allocation must fulfill user-specified quality of service (QoS) requirements and performance metrics set by cloud providers while adhering to existing constraints. The problem is recognized as an NP-complete problem. My research focuses on the following three topics:
  1. *Integration of Simulated Annealing with Deep Q-Network (DQN).* This study integrates the simulated annealing algorithm with DQN to enhance workflow scheduling efficiency in the cloud environment. Specifically, simulated annealing is employed to determine the optimal execution order of subtasks, which is then used as a key characteristic of the task so that the DRL agent can learn and optimize the scheduling strategy effectively.
  2. *Workflow Scheduling in Privacy-Constrained Hybrid Cloud Using Multi-Agent Deep Reinforcement Learning (MADRL).* To address workflow scheduling in hybrid cloud environments with privacy constraints, my research employs MADRL to enable virtual machines to collaboratively determine task allocation strategies, optimizing the mapping of workflows to virtual machines.
  3. *Hierarchical GNN-Based Workflow Scheduling in Hybrid Cloud Environments.* To capture the complex dependencies among tasks within a workflow, my research employs a hierarchical graph neural network (GNN) to generate high-quality state embeddings. These embeddings are seamlessly integrated into the decision-making process, where MADRL is leveraged to optimize workflow scheduling in hybrid cloud environments. This approach enables agents to collaboratively make intelligent decisions, effectively reducing workflow makespan and rental costs while ensuring strict compliance with privacy and security requirements.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
