## Generative Hyperelasticity with Physics-Informed Probabilistic Diffusion Fields
## Vahid Tac, Purdue University, 2024
#### USACM Student Chapter Seminar Series - Brief Tutorial
---

This (very small) repository was created to share the tutorial code for Vahid Tac's talk in USACM Student Chapter Seminar Series. 

The tutorial consists of a single jupyter notebook, [NODE_monotonic.ipynb](https://github.com/tajtac/USACM_tutorial/tree/master/NODE_monotonic.ipynb), aims to demonstrate
1. The differences between a feed-forward neural network (FFNN) and a neural ordinary differential equation (NODE)
2. That NODEs are always monotonic
3. That, further, NODEs can be made to pass through the origin (0,0)

For further info about my work on NODEs, and examples of the use of NODEs in physics, see my publications where I use NODEs to construct physics-informed, data-driven models of [Hyperelasticity](https://www.sciencedirect.com/science/article/pii/S0045782522003838), [Viscoelasticity](https://www.sciencedirect.com/science/article/pii/S0045782523001706), and, recently, [Damage](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4791814). 

---

Cite this work as:

    @article{tacDatadrivenTissueMechanics2022,
        title = {Data-Driven Tissue Mechanics with Polyconvex Neural Ordinary Differential Equations},
        author = {Tac, Vahidullah and Costabal, Francisco Sahli and Tepole, Adrian B},
        year = {2022},
        journal = {Computer Methods in Applied Mechanics and Engineering},
        volume = {398},
        pages = {18},
        doi = {10.1016/j.cma.2022.115248}
    }
