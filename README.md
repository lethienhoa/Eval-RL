## Quality of syntactic implication of RL-based sentence summarization

Work on summarization has explored both reinforcement learning (RL) optimization using ROUGE as a reward and syntax-aware models, such as models those input is enriched with part-of-speech (POS)-tags and dependency information. However, it is not clear what is the respective impact of these approaches beyond the standard ROUGE evaluation metric. Especially, RL-based for summarization is becoming more and more popular. In this paper, we provide a detailed comparison of these two approaches and of their combination along several dimensions that relate to the perceived quality of the generated summaries: number of repeated words, distribution of part-of-speech tags, impact of sentence length, relevance and grammaticality. Using the standard Gigaword sentence summarization task, we compare an RL self-critical sequence training (SCST) method with syntax-aware models that leverage POS tags and Dependency information. We show that on all qualitative evaluations, the combined model gives the best results, but also that only training with RL and without any syntactic information already gives nearly as good results as syntax-aware models with less parameters and faster training convergence.

**Paper:**

Hoa T. Le, Christophe Cerisara, Claire Gardent. **Quality of syntactic implication of RL-based sentence summarization**. Association for the Advancement of Artificial Intelligence 2020 (**AAAI-20**) Workshop on Engineering Dependable and Secure Machine Learning Systems (EDSMLS 2020). (https://arxiv.org/abs/1912.05493)

    @article{HoaLe:2019,
           author = {{Le}, Hoa T. and {Cerisara}, Christophe and {Gardent}, Claire},
            title = "{Quality of syntactic implication of RL-based sentence summarization}",
          journal = {arXiv e-prints},
         keywords = {Computer Science - Computation and Language},
             year = "2019",
            month = "Dec",
              eid = {arXiv:1912.05493},
            pages = {arXiv:1912.05493},
    archivePrefix = {arXiv},
           eprint = {1912.05493},
     primaryClass = {cs.CL},
           adsurl = {https://ui.adsabs.harvard.edu/abs/2019arXiv191205493L},
          adsnote = {Provided by the SAO/NASA Astrophysics Data System}
    }

**Reference Source Codes:**
https://github.com/ChenRocks/fast_abs_rl

