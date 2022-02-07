# Papers
- [Mutation Testing](#Mutation-Testing)
- [Coverage-Guided Testing](#Coverage-Guided-Testing)
- [Model Based Testing](#Model-Based-Testing)
## Mutation Testing
### [**ICSE 2021**] [RobOT: Robustness-Oriented Testing for Deep Learning Systems.](https://arxiv.org/pdf/2102.05913.pdf)
> DL (re)training is integrated with testing and two robustness testing metrics, FOL and ZOL, are proposed.

### [**ISSTA 2021**] [DeepCrime: mutation testing of deep learning systems based on real faults.](https://dl.acm.org/doi/10.1145/3460319.3464825)
> The first source-level pre-training mutation tool based on real DL faults.

### [**ASE 2021**] [DeepMetis: Augmenting a Deep Learning Test Set to Increase its Mutation Score.](https://arxiv.org/abs/2109.07514)
>An approach to automatically generate new test inputs that can be used to augment the existing test set so that its capability to detect DL mutations increases.

### [**ASE 2019**] [DeepMutation++: A Mutation Testing Framework for Deep Learning Systems. ](https://dl.acm.org/doi/pdf/10.1109/ASE.2019.00126)
>A mutation testing-based tool for DNNs, DeepMutation++, which facilitates the DNN quality evaluation, supporting both feed-forward neural networks (FNNs) and stateful recurrent neural networks (RNNs).

### [**ISSRE 2018**] [DeepMutation: Mutation Testing of Deep Learning Systems.](https://arxiv.org/pdf/1805.05206.pdf)
>The paper designs eight source-level mutation operators to introduce faults into the DL programming elements and propose two DL-specific mutation testing metrics.

## Coverage-Guided Testing
### [**SANER 2021**] [DeepCon: Contribution Coverage Testing for Deep Learning Systems.](https://www.researchgate.net/publication351501735_DeepCon_Contribution_Coverage_Testing_for_Deep_Learning_Systems)
>First explicitly combines the output of a neuron and the connection weight it connects to the nextlevel neuron.

### [**ICSE 2020**] [Importance-Driven Deep Learning System Testing](https://arxiv.org/pdf/2002.03433.pdf)
>The first systematic and automated testing methodology that employs the semantics of neuron influence to the DL system as a means of developing a laywer-wise functional understanding of its internal behaviour and assessing the semantic adequacy of a test set.

### [**ISSTA 2020**] [Effective white-box testing of deep neural networks with adaptive neuron-selection strategy.](https://dl.acm.org/doi/pdf/10.1145/3395363.3397346?casa_token=RZ5-zSG7tOsAAAAA:gG0PhgfkLMTCAAf1AEDQVgELqNZXCNMYPZ-bKWu61fLCVxFUsGUWMyDEAEONYAENzNhnXQmbYeeQyJ4)
>This paper presents a new white-box testing technique for deep neural networks and shows that using a fixed neuron-selection strategy is a major limitation of the existing white-box approaches.

### [**ICSE 2020**] [Uncertainty-guided testing and robustness enhancement for deep learning systems. ](https://dl.acm.org/doi/pdf/10.1145/3377812.3382160?casa_token=aZMrhNOESSgAAAAA:-Ns-ulCiF_e8SCENNcvXRySgafCemKlX87A0_zbwEN7ag8UoFJ0OoyKTL5T3_47Lqw2J6CW17bE7_hw)
>The paper conducts an empirical study to uncover the characteristics of adversarial examples(AEs) from the perspective of uncertainty. 

### [**ICSE 2019**] [Guiding deep learning system testing using surprise adequacy. ](https://arxiv.org/pdf/1808.08444.pdf)
>The paper proposes SADL, a fine grained test adequacy metric that measures the surprise of an input, i.e., the difference in the behaviour of a DL system between a given input and the training data. 

### [**ISSTA 2019**] [DeepHunter: a coverage-guided fuzz testing framework for deep neural networks. ](https://experts.illinois.edu/en/publications/deephunter-a-coverage-guided-fuzz-testing-framework-for-deep-neur)
>The paper first proposes a metamorphic mutation strategy to generate new semantically preserved tests, and leverage multiple extensible coverage criteria as feedback to guide the test generation.

### [**ICML 2019**] [TensorFuzz: Debugging Neural Networks with Coverage-Guided Fuzzing. ](http://proceedings.mlr.press/v97/odena19a/odena19a.pdf)
>The paper develops coverage-guided fuzzing (CGF) methods for neural network.

### [**SANER 2019**] [DeepCT: Tomographic Combinatorial Testing for Deep Learning Systems.](http://stap.ait.kyushu-u.ac.jp/~zhao/pub/pdf/saner2019.pdf)
>The paper performs an exploratory study of combinatorial testing (CT) on DL systems.

### [**FSE 2019**] [DeepStellar: model-based quantitative analysis of stateful deep learning systems.](https://dl.acm.org/doi/10.1145/3338906.3338954)
>The very first step towards the quantitative analysis of RNN-based DL systems

### [**ASE 2018**] [DeepGauge: multi-granularity testing criteria for deep learning systems.](https://arxiv.org/pdf/1803.07519.pdf)
>This is among the earliest studies to propose multi-granularity testing criteria for DL systems. 

### [**ASE 2018**] [Concolic testing for deep neural networks.](https://dl.acm.org/doi/pdf/10.1145/3238147.3238172?casa_token=cr27tkWst80AAAAA:elNXdvTosrndr_2reBIBLhHUEQKM38i9m5kz1cvHJ_3GxPvBLnccmv_WNKhFiJBsaVtlX3jW4QpjtFc)
>This paper presents the first concolic testing approach for Deep Neural Networks (DNNs).

### [**ICSE 2018**] [DeepTest: automated testing of deep-neural-network-driven autonomous cars.](https://dl.acm.org/doi/pdf/10.1145/3180155.3180220)
>A systematic testing tool for automatically detecting erroneous behaviors of DNN-driven vehicles that can potentially lead to fatal crashes. 

### [**FSE 2018**] [DLFuzz: Differential Fuzzing Testing of Deep Learning Systems.](https://arxiv.org/pdf/1808.09413.pdf)
>The first differential fuzzing testing framework aiming to maximize the neuron coverage and generate more adversarial inputs for a given DL system, without cross-referencing other similar DL systems or manual labeling.

### [**SOSP 2017**] [DeepXplore: Automated Whitebox Testing of Deep Learning Systems.](https://arxiv.org/pdf/1705.06640.pdf)
([*Open Source*](https://github.com/peikexin9/deepxplore))
> The first whitebox framework for systematically testing real-world DL systems. 


## Model Based Testing
###  [**FSE 2020**] [Model-based exploration of the frontier of behaviours for deep learning system testing.](https://dl.acm.org/doi/pdf/10.1145/3368089.3409730?casa_token=WXdcH1L2TTcAAAAA:cV_o25QtKW01Q85_U7ZGnlDjvhOzZwdVcL06rz9TfQ-dmZ4LAC7_x6YDR8A8sGf6IEQ3CdyDLHf7x5A))
> The paper introduces the notion of frontier of behaviours and developed DeepJanus, a search-based tool that generates frontier inputs for DL systems.
