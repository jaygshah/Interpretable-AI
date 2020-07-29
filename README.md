# Interpretable-AI readings and resources
-- In Progress --

I will be updatting this more often as I read more papers and related readings along my research

# Readings and Articles

* [Feature Visualization](https://distill.pub/2017/feature-visualization/)
* [The Building Blocks of Interpretability](https://distill.pub/2018/building-blocks/)
* [Using Artiﬁcial Intelligence to Augment Human Intelligence](https://distill.pub/2017/aia/)
* [Visualizing Representations: Deep Learning and Human Beings](http://colah.github.io/posts/2015-01-Visualizing-Representations/)
* [Differentiable Image Parameterizations](https://distill.pub/2018/differentiable-parameterizations/)
* [Activation Atlas](https://distill.pub/2019/activation-atlas/)
* [Why we should rigorously measure and forecast AI progress?](https://www.lesswrong.com/posts/axzPYvcmWr2TwvnLi/an-101-why-we-should-rigorously-measure-and-forecast-ai)
	1. [How can Interpretability help Alignment?](https://www.lesswrong.com/posts/uRnprGSiLGXv35foX/how-can-interpretability-help-alignment)
* [On Model Explainability From LIME, SHAP, to Explainable Boosting](https://everdark.github.io/k9/notebooks/ml/model_explain/model_explain.nb.html)
* [Feature wise transformations - in case of multi-modality and integrating models](https://distill.pub/2018/feature-wise-transformations/)
* [Explaining Deep Neural Networks using Unsupervised Clustering](https://arxiv.org/pdf/2007.07477v1.pdf)
* [Summaries on various AI topics - Alignment Newsletter](https://docs.google.com/spreadsheets/d/1PwWbWZ6FPqAgZWOoOcXM8N_tUCuxpEyMbN1NYYC02aM/edit#gid=0)
* [Podcast: Making Intelligence Intelligible - Dr Rich Caruana](https://www.microsoft.com/en-us/research/podcast/making-intelligence-intelligible-dr-rich-caruana/?OCID=msr_podcast_rcaruana_tw)
* [A concept in psychology is helping AI to better navigate our world](https://www.technologyreview.com/2020/07/17/1005415/a-concept-in-psychology-is-helping-ai-to-better-navigate-our-world)
* [Better priors as an approach for Intepretable AI !?](https://mailchi.mp/ee62c1c9e331/an-109teaching-neural-nets-to-generalize-the-way-humans-would?e=ec0c4c2b61)

# Research Papers
* [Explaining Neural Networks by Decoding Layer Activations](https://arxiv.org/pdf/2005.13630v1.pdf)
* [InterpNET: Neural Introspection for Interpretable Deep Learning](https://arxiv.org/pdf/1710.09511v2.pdf)
	* And it's publicly available [code](https://github.com/sbarratt/interpnet)
* [What do Deep Networks Like to See?](https://arxiv.org/pdf/1803.08337v1.pdf)
* [Towards A Rigorous Science of Interpretable Machine Learning](https://arxiv.org/abs/1702.08608)
	* (Finale Doshi-Velez et al) discusses the field of interpretability research, and how it can be made more rigorous and well-defined. The authors first highlight the problem of defining interpretability in the first place - they don't have a resolution to this problem, but suggest that we can think of interpretability in terms of what it's used for. They claim that interpretability is used for confirming other important desiderata in ML systems, which stem from an incompleteness in the problem formalization. For example, if we want a system to be unbiased but aren't able to formally specify this in the reward function, or the reward we're optimising for is only a proxy of the true reward, then we could use interpretability to inspect our model and see whether it's reasoning how we want it to.

	* The authors next move on to discussing how we can evaluate interpretability methods, providing a taxonomy of different evaluation methods: Application-grounded is when the method is evaluated in the context it will actually be used in, by real humans (i.e. doctors getting explanations for AI diagnoses); Human-grounded is about conducting simpler human-subject experiments (who are perhaps not domain experts) using possibly simpler tasks than what the intended purpose of the method is; Functionally-grounded is where no humans are involved in the experiments, and instead some formal notion of interpretability is measured for the method to evaluate its quality. Each of these evaluation methods can be used in different circumstances, depending on the method and the context it will be used in.

	* Finally, the authors propose a data-driven approach to understanding the factors which are important in interpretability. They propose to try and create a dataset of applications of machine learning models to tasks, and then analyse this dataset to find important factors. They list some possible task- and method- related factors, and then conclude with recommendations to researchers doing interpretability.

* [Visualizing and Understanding Convolutional Networks - Also, in Cousera CNN > Week-4](https://arxiv.org/pdf/1311.2901.pdf)

# Books

* [Interpretable ML-A Guide for Making Black Box Models Explainable-Christoph Molnar](https://christophm.github.io/interpretable-ml-book/)

# Projects

* [IBM AI Explainability 360 (v0.2.0)](https://github.com/IBM/AIX360/)
* [Lime](https://github.com/marcotcr/lime)
* [SHAP](https://github.com/slundberg/shap)
* [InterpretML](https://github.com/interpretml/interpret)

---

# Cool Tools
* [Play with a Neural Network](https://github.com/jaygshah/Interpretable-AI.git)