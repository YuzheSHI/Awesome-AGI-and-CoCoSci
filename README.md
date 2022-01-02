<div align="center">
	<img width="400" height="253" src="assets/abd_map.png" alt="Roadmap of studying Abduction">
</div>

# Awesome Artificial General Intelligence and Computational Cognitive Sciences [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

An **awesome & curated** list for **Artificial General Intelligence**, an emerging inter-discipline field that combines artificial intelligence and computational cognitive sciences as majority, alone with probability and mathematical statistics, formal logic, cognitive and developmental psychology, computational philosophy, cognitive neuroscience, and computational sociology. We are promoting high-level machine intelligence by getting inspirations from the way that human learns and thinks, while obtaining a deeper understanding of human cognition simultaneously. We believe that this kind of reciprocative research is a potential way towards our big picture: building human-level intelligent agents with capabilities such as abstracting, explaining, learning, planning, and making decisions.

The author of this repo has been struggling to taxonomize related topics, since there are so many perspectives to follow, such as task-oriented, technique-oriented, and metaphysics-oriented. Finally he decided to focus on the perspective of ***The Sciences of Intelligence***---each topic describes a phenomenon of intelligence, or an intelligent behavior---they show the objectives of reverse-engineering human intelligence for computational methods. These topics are never restricted to specific technical methods or tasks, but are trying to organize the nature of intelligence---from both *the software perspective* and *the hardware perspective*.

Obviously this reading list is far from covering the every aspect of AGI and CoCoSci. Since the list is a by-product of literature reviews when the author is working on Abduction, other non-Abduction topics are also collected with biases, more or less. Abduction is the way humans explain the world with the known, and discover the unknown, requiring much more investigations into its computational basis, cognitive underpinnings and applications to AI. Please feel free to contact the author if you are interested in Abduction.


<span id = "c"></span>
## Contents
* [Academic Tools](#academic-tools)
* [Papers](#papers)
    * [Abduction](#abduction)
      * [Computational Explanation](#compexp)
      * [Computational Scientific Discovery](#compscidsc)
      * [Applications in AI](#abdappai)
    * [Bayesian Modeling & Learning](#bayesian-modeling--learning)
      * [Bayesian Induction](#bayesian-induction)
      * [Generative Model](#generative-model)
      * [Nonparametric Model](#nonparametric-model)
      * [Bayesian Optimization](#bayesian-optimization)
    * [Learning with Cognitive Plausibility](#learning-with-cognitive-plausibility)
    * [Communications & Pragmatics](#communications--pragmatics)
      * [Non-Verbal Communication](#nvcomm)
      * [Rational Speech Act](#rsa)
      * [Language Compositionality](#lcps)
    * [Problem Solving](#problem-solving)
      * [Human-Level Problem Solving](#hmprobsol)
      * [Model-Based Planning](#mbplan)
      * [Model-Free Reinforcement Learning](#mfrl)
      * [Inverse Reinforcement Learning](#irl)
    * [Hybrid System 1 & 2](#hybrid-system-1--2)
    * [Explainability](#explainability)
    * [Embodied Intelligence](#embodied-intelligence)
    * [Human Intelligence Experiments](#human-intelligence-experiments)
    * [Metacognition](#metacognition)
      * [Gestalt](#gestalt)
      * [Rationality & Rationalization](#r&r)
      * [Cognitive Architecture](#cogarch)
    * [Theory of Mind](#theory-of-mind)
    * [Analogy](#analogy)
    * [Causality](#causality)
    * [Commonsense](#commonsense)
    * [Inductive Logic & Program Synthesis](#inductive-logic--program-synthesis)
    * [Knowledge Representation](#knowledge-representation)
    * [Cognitive Development](#cognitive-development)
    * [Learning in the Open World](#learning-in-the-open-world)
    <!--* [Tasks & Environments](#te)-->
* [Institute & Researcher](#institute--researcher)
    * [MIT](#mit)
    * [Stanford](#stanford)
    * [Princeton](#princeton)
    * [Harvard](#harvard)
    * [UCLA](#ucla)
    * [UC Berkeley](#uc-berkeley)
    * [UCSD](#ucsd)
    * [NYU](#nyu)
    * [BIGAI](#bigai)
* [People & Book](#people--book)
    * [Ulf Grenander](#ulf-grenander)
    * [Michael Tomasello](#michael-tomasello)
    * [Judea Pearl](#judea-pearl)
    * [Susan Carey](#susan-carey)
    * [Daniel Kahneman](#daniel-kahneman)
    * [Karl Popper](#karl-popper)


## Academic Tools

* [BibTex Template](BibTex/template.bib) - ***BibTex Template for including abbreviations of journals and conferences references***.

* [Computational Cognitive Science Courses](https://cbmm.mit.edu/education/courses/computational-cognitive-science) - ***Courses on CoCoSci from MIT, Harvard, Stanford, and JHU***.

* [Probabilistic Models of Cognition](https://probmods.org/) - ***The probabilistic approach to cognitive science, which models learning and reasoning as inference in complex probabilistic models***.

*[Back to Top](#c)

<span id = "p"></span>
## Papers
<span id = "abd"></span>
### Abduction

<span id = "compexp"></span>
#### Computational Explanation

* [Abduction](https://plato.stanford.edu/entries/abduction/index.html) - ***Plato Stanford***. 

* [Scientific Explanation](https://plato.stanford.edu/entries/scientific-explanation/) - ***Plato Stanford***. 

* [Non-monotonic Logic](https://plato.stanford.edu/entries/logic-nonmonotonic/) - ***Plato Stanford***.

* [Philosophical Writings of Peirce](https://4lib.org/book/702071/e8ffe8) - ***Courier Corporation***, 1955. [[All Versions](https://scholar.google.com/scholar?cluster=3917019015464129592&hl=en&as_sdt=0,5)].

* [The Inference to the Best Explanation](https://www.jstor.org/stable/2183532) - ***Philosophical Review***, 1965. [[All Versions](https://scholar.google.com/scholar?cluster=1416627814151433560&hl=en&as_sdt=0,5)].

* [Inference to the Best Explanation](https://hk1lib.org/book/3594789/f39e15?id=3594789&secret=f39e15) - ***Routledge***, 1991. [[All Versions](https://scholar.google.com/scholar?cluster=6494546505729177895&hl=en&as_sdt=0,5)].

* [A Study of Thinking](https://www.taylorfrancis.com/books/mono/10.4324/9781315083223/study-thinking-jerome-bruner-jacqueline-goodnow-george-austin) - ***Routledge***, 1956. [[All Versions](https://scholar.google.com/scholar?cluster=17466297915128086930&hl=en&as_sdt=0,5)].

* [Abductive Reasoning and Learning](https://link.springer.com/book/10.1007/978-94-017-1733-5) - ***Springer***, 2000. [[All Versions](https://scholar.google.com/scholar?cluster=12074269365138058159&hl=en&as_sdt=0,5)].

* [Abductive Reasoning: Logical Investigations into Discovery and Explanation](https://link.springer.com/book/10.1007%2F1-4020-3907-7#authorsandaffiliationsbook) - ***Springer***, 2006. [[All Versions](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Abductive+Reasoning%3A+Logical+Investigations+into+Discovery+and+Explanation&btnG=)].

* [Abductive Cognition: The Epistemological and Eco-Cognitive Dimensions of Hypothetical Reasoning](https://link.springer.com/book/10.1007%2F978-3-642-03631-6) - ***Springer***, 2009. [[All Versions](https://scholar.google.com/scholar?cluster=8707351442527595188&hl=en&as_sdt=0,5)].

* [Explanation and Abductive Inference](https://cognition.princeton.edu/sites/default/files/cognition/files/explanation_abductive_inference.pdf) - ***The Oxford Handbook of Thinking and Reasoning***, 2012. [[All Versions](https://scholar.google.com/scholar?cluster=16126850654692681562&hl=en&as_sdt=0,5)].

* [The structure and function of explanations](https://cognition.princeton.edu/sites/default/files/cognition/files/tics_explanation.pdf) - ***Trends in Cognitive Sciences***, 2006. [[All Versions](https://scholar.google.com/scholar?cluster=2849189270394400667&hl=en&as_sdt=0,5)].

* [Explanatory Preferences Shape Learning and Inference](https://scholar.princeton.edu/sites/default/files/cognition/files/explanatory_prefs_tics.pdf) - ***Trends in Cognitive Sciences***, 2016. [[All Versions](https://scholar.google.com/scholar?cluster=2040551538203889465&hl=en&as_sdt=0,5)].

* [The Role of Explanatory Considerations in Updating](https://www.sciencedirect.com/science/article/pii/S0010027715000955) - ***Cognition***, 2015. [[All Versions](https://scholar.google.com/scholar?cluster=3089358487428261042&hl=en&as_sdt=0,5)].

* [Explanation, updating, and accuracy](https://www.tandfonline.com/doi/full/10.1080/20445911.2016.1230122) - ***Journal of Cognitive Psychology***, 2016. [[All Versions](https://scholar.google.com/scholar?cluster=967127146748155733&hl=en&as_sdt=0,5)].

* [Best, second-best, and good-enough explanations: How they matter to reasoning](https://psycnet.apa.org/record/2018-03972-001) - ***Journal of Experimental Psychology***, 2018. [[All Versions](https://scholar.google.com/scholar?start=0&hl=en&as_sdt=0,5&cluster=3067550385175104201)].

* [How explanation guides belief change](https://www.sciencedirect.com/science/article/pii/S1364661321001790) - ***Trends in Cognitive Sciences***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=15240531165875981526&hl=en&as_sdt=2005&sciodt=2005)].

* [Use of current explanations in multicausal abductive reasoning](https://onlinelibrary.wiley.com/doi/abs/10.1207/s15516709cog2506_2) - ***Cognitive Science***, 2001. [[All Versions](https://scholar.google.com/scholar?cluster=7816050625957759346&hl=en&as_sdt=2005&sciodt=0,5)].

* [Kinematic mental simulations in abduction and deduction](https://www.pnas.org/content/110/42/16766.short) - ***Proceedings of National Academy of Sciences***, 2013. [[All Versions](https://scholar.google.com/scholar?cluster=11864820390497230588&hl=en&as_sdt=0,5)].

* [Patterns of abduction](https://link.springer.com/article/10.1007/s11229-007-9223-4) - ***Synthese***, 2007. [[All Versions](https://scholar.google.com/scholar?cluster=15230540023076470385&hl=en&as_sdt=0,5)].

* [Abduction: A categorical characterization](https://www.sciencedirect.com/science/article/pii/S1570868314000895) - ***Journal of Applied Logic***, 2015. [[All Versions](https://scholar.google.com/scholar?cluster=17834260152484836885&hl=en&as_sdt=2005&sciodt=0,5)].

* [Defending Abduction](https://www.journals.uchicago.edu/doi/abs/10.1086/392744) - ***Philosophy of Science***, 1999. [[All Versions](https://scholar.google.com/scholar?cluster=13895790050138832555&hl=en&as_sdt=0,5)].

* [On the distinction between Peirce's abduction and Lipton's Inference to the best explanation](https://link.springer.com/article/10.1007/s11229-009-9709-3) - ***Synthese***, 2011. [[All Versions](https://scholar.google.com/scholar?cluster=7865291004729010145&hl=en&as_sdt=0,5)].

* [Abduction − the context of discovery + underdetermination = inference to the best explanation](https://link.springer.com/article/10.1007/s11229-019-02337-z) - ***Synthese***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=4261649938116694095&hl=en&as_sdt=0,5)].

* [Towards an Architecture for Cognitive Vision Using Qualitative Spatio-temporal Representations and Abduction](https://link.springer.com/chapter/10.1007%2F3-540-45004-1_14) - ***Spatial Cognition***, 2002. [[All Versions](https://scholar.google.com/scholar?cluster=8072265283930278310&hl=en&as_sdt=0,5)].

* [Abductive inference within a pragmatic framework](https://link.springer.com/article/10.1007/s11229-018-1824-6) - ***Synthese***, 2018. [[All Versions](https://scholar.google.com/scholar?cluster=10285954503043361393&hl=en&as_sdt=0,5)].

* [Disjunctive Abduction](https://link.springer.com/article/10.1007/s00354-019-00059-x) - ***New Generation Computing***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=6664745483675209831&hl=en&as_sdt=0,5)].

* [Probabilistic alternatives to Bayesianism: the case of explanationism](https://www.frontiersin.org/articles/10.3389/fpsyg.2015.00459/full) - ***Frontiers in Psychology***, 2015. [[All Versions](https://scholar.google.com/scholar?cluster=9016714668469830914&hl=en&as_sdt=0,5)].

* [A Probabilistic Theory of Abductive Reasoning](https://www.scitepress.org/Link.aspx?doi=10.5220/0010195405620571) - ***ICAART***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=450937566244876051&hl=en&as_sdt=0,5)].

* [The order effect in human abductive reasoning: an empirical and computational study](https://www.tandfonline.com/doi/full/10.1080/09528130600558141?scroll=top&needAccess=true) - ***Journal of Experimental & Theoretical Artificial Intelligence***, 2006. [[All Versions](https://scholar.google.com/scholar?cluster=3803536062463585043&hl=en&as_sdt=0,5)].

* [Abduction, Induction, and Analogy](https://link.springer.com/chapter/10.1007%2F978-3-642-15223-8_5) - ***Model-Based Reasoning in Science and Technology***, 2010. [[All Versions](https://scholar.google.com/scholar?cluster=14979764682921693390&hl=en&as_sdt=0,5)].

* [Remembrance of inferences past: Amortization in human hypothesis generation](https://www.sciencedirect.com/science/article/abs/pii/S0010027718301094) - ***Cognition***, 2018. [[All Versions](https://scholar.google.com/scholar?cluster=190340622765037472&hl=en&as_sdt=2005&sciodt=0,5)].

* [The AHA! Experience: Creativity Through Emergent Binding in Neural Networks](https://onlinelibrary.wiley.com/doi/full/10.1111/j.1551-6709.2010.01142.x) - ***Cognitive Science***, 2012. [[All Versions](https://scholar.google.com/scholar?cluster=10006889101167052798&hl=en&as_sdt=0,5)].

* [Explanation-seeking curiosity in childhood](https://www.sciencedirect.com/science/article/pii/S2352154620300851) - ***Current Opinion in Behavioral Sciences***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=4167956555501133663&hl=en&as_sdt=2005)].

* [Why Imaginary Worlds? The psychological foundations and cultural evolution of fictions with imaginary worlds](https://www.cambridge.org/core/journals/behavioral-and-brain-sciences/article/abs/why-imaginary-worlds/CA2AB4B1E1EDD8FE965E6DDB4A047B35) - ***Behavioral and Brain Sciences***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=11677245106477509648&hl=en&as_sdt=2005&sciodt=2005)].

*[Back to Top](#c)

<span id = "compscidsc"></span>
#### Computational Scientific Discovery

* [Scientific Discovery](https://plato.stanford.edu/entries/scientific-discovery/) - ***Plato Stanford***.

* [Models of Discovery: And Other Topics in the Methods of Science](https://hk1lib.org/book/2241843/c5d7b3?id=2241843&secret=c5d7b3) - ***Springer***, 1977. [[All Versions](https://scholar.google.com/scholar?cluster=9932701864897299105&hl=en&as_sdt=0,5)].

* [Scientific discovery: Computational explorations of the creative processes](https://hk1lib.org/book/970300/6b0ff7?id=970300&secret=6b0ff7) - ***MIT Press***, 1987. [[All Versions](https://scholar.google.com/scholar?cluster=11327000316248254911&hl=en&as_sdt=0,5)].

* [Induction: Processes of Inference, Learning, and Discovery](https://hk1lib.org/book/701605/02b32a?id=701605&secret=02b32a) - ***MIT Press***, 1989. [[All Versions](https://scholar.google.com/scholar?cluster=12402938838725132707&hl=en&as_sdt=0,5)].

* [Exploring science: The cognition and development of discovery processes](https://psycnet.apa.org/record/2000-03968-000) - ***MIT Press***, 2000. [[All Versions](https://scholar.google.com/scholar?cluster=13091264356550286420&hl=en&as_sdt=2005&sciodt=0,5)].

* [Dual Space Search During Scientific Reasoning](https://onlinelibrary.wiley.com/doi/abs/10.1207/s15516709cog1201_1) - ***Cognitive Science***, 1988. [[All Versions](https://scholar.google.com/scholar?cluster=17542852673494089523&hl=en&as_sdt=2005&sciodt=0,5)].

* [Complexity Management in a Discovery Task](https://www.cmu.edu/dietrich/psychology/pdf/klahr/PDFs/schunn-klahr.pdf) - ***CogSci'92***, 1992. [[All Versions](https://scholar.google.com/scholar?cluster=18138712608977258974&hl=en&as_sdt=2005&sciodt=0,5)].

* [A dual-space model of iteratively deepening exploratory learning](https://www.sciencedirect.com/science/article/pii/S1071581996900324) - ***International Journal of Human-Computer Studies***, 1996. [[All Versions](https://scholar.google.com/scholar?cluster=17337189265334825678&hl=en&as_sdt=2005&sciodt=0,5)].

* [Heuristics for Scientific Experimentation: A Developmental Study](https://www.sciencedirect.com/science/article/abs/pii/S0010028583710030) - ***Cognitive Psychology***, 1993. [[All Versions](https://scholar.google.com/scholar?cluster=2469515962071844494&hl=en&as_sdt=2005&sciodt=0,5)].

* [A 4-Space Model of Scientific Discovery](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.645.248&rep=rep1&type=pdf) - ***CogSci'95***, 1995. [[All Versions](https://scholar.google.com/scholar?cluster=1063157789682040473&hl=en&as_sdt=2005&sciodt=0,5)].

* [When to trust the data: Further investigations of system error in a scientific reasoning task](https://link.springer.com/article/10.3758/BF03201090) - ***Memory & Cognition***, 1996. [[All Versions](https://scholar.google.com/scholar?cluster=3131191372086488656&hl=en&as_sdt=2005&sciodt=0,5)].

* [Confirmation, disconfirmation, and information in hypothesis testing](https://psycnet.apa.org/record/1987-20689-001) - ***Psychological Review***, 1987. [[All Versions](https://scholar.google.com/scholar?cluster=1954141597807453515&hl=en&as_sdt=0,5)].

* [Hypothesis generation, sparse categories, and the positive test strategy](https://psycnet.apa.org/record/2010-22980-001) - ***Psychological Review***, 2011. [[All Versions](https://scholar.google.com/scholar?cluster=4329636480235863472&hl=en&as_sdt=2005&sciodt=0,5)].

* [Children and adults as intuitive scientists](https://psycnet.apa.org/record/1990-03504-001) - ***Psychological Review***, 1989. [[All Versions](https://scholar.google.com/scholar?cluster=9577945454476127070&hl=en&as_sdt=2005&sciodt=0,5)].

* [Abduction and styles of scientifc thinking](https://link.springer.com/content/pdf/10.1007/s11229-019-02127-7.pdf) - ***Synthese***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=9336871656706514469&hl=en&as_sdt=0,5)].

*[Back to Top](#c)

<span id = "abdappai"></span>
#### Applications in AI

* [Functional genomic hypothesis generation and experimentation by a robot scientist](https://www.nature.com/articles/nature02236) - ***Nature***, 2004. [[All Versions](https://scholar.google.com/scholar?cluster=17461972625475533182&hl=en&as_sdt=0,5)].

* [Highly accurate protein structure prediction with AlphaFold](https://www.nature.com/articles/s41586-021-03819-2) - ***Nature***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=6286436358625670901&hl=en&as_sdt=0,5)].

* [Interpretation as abduction](https://www.sciencedirect.com/science/article/abs/pii/0004370293900154?via%3Dihub) - ***Artificial Intelligence***, 1993. [[All Versions](https://scholar.google.com/scholar?cluster=12658433318211361322&hl=en&as_sdt=0,5)].

* [Probabilistic Horn abduction and Bayesian networks](https://www.sciencedirect.com/science/article/abs/pii/000437029390061F?via%3Dihub) - ***Artificial Intelligence***, 1993. [[All Versions](https://scholar.google.com/scholar?cluster=7728248035489349629&hl=en&as_sdt=0,5)].

* [Abductive Inference in Bayesian Networks: A Review](https://link.springer.com/chapter/10.1007/978-3-540-39879-0_6) - ***Advances in Bayesian Networks***, 2004. [[All Versions](https://scholar.google.com/scholar?cluster=8502276402734843212&hl=en&as_sdt=0,5)].

* [Abductive Logic Programming](https://academic.oup.com/logcom/article-abstract/2/6/719/942121?redirectedFrom=fulltext) - ***Journal of Logic Computation***, 1992. [[All Versions](https://scholar.google.com/scholar?cluster=18119357517656745518&hl=en&as_sdt=0,5)].

* [ACLP: Abductive Constraint Logic Programming](https://www.sciencedirect.com/science/article/pii/S0743106699000758) - ***The Journal of Logic Programming***, 1999. [[All Versions](https://scholar.google.com/scholar?cluster=14319574550421192429&hl=en&as_sdt=0,5)].

* [Abduction in Logic Programming](https://web.stanford.edu/class/cs227/Readings/Abudction%20in%20LP.pdf) - ***Computational Logic***, 2002. [[All Versions](https://scholar.google.com/scholar?cluster=902643678163312237&hl=en&as_sdt=0,5)].

* [Bayesian Abductive Logic Programs: A Probabilistic Logic for Abductive Reasoning](https://www.cs.utexas.edu/~ml/papers/raghavan.starai10.pdf) - ***IJCAI'11***, 2011. [[All Versions](https://scholar.google.com/scholar?cluster=4453424083730209198&hl=en&as_sdt=0,5)].

* [Abductive Plan Recognition by Extending Bayesian Logic Programs](https://www.cs.utexas.edu/~ml/papers/raghavan.ecml11.pdf) - ***ECML'11***, 2011. [[All Versions](https://scholar.google.com/scholar?cluster=7276511797197017483&hl=en&as_sdt=0,5)].

* [An Approach to Abductive Reasoning in Equational Logic](https://www.aaai.org/ocs/index.php/IJCAI/IJCAI13/paper/view/6624/6619) - ***IJCAI'13***, 2013. [[All Versions](https://scholar.google.com/scholar?cluster=686895264429811190&hl=en&as_sdt=0,5)].

* [Abduction-Based Explanations for Machine Learning Models](https://ojs.aaai.org//index.php/AAAI/article/view/3964) - ***AAAI'19***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=7355960657107994022&hl=en&as_sdt=0,5)].

* [Probabilistic Sufficient Explanations](https://arxiv.org/pdf/2105.10118.pdf) - 2021. [[All Versions](https://scholar.google.com/scholar?cluster=1874102360688341104&hl=en&as_sdt=0,5)].

* [Machine Translation Using Abductive Inference](https://www.aclweb.org/anthology/H91-1024.pdf) - ***COLING***, 1990. [[All Versions](https://scholar.google.com/scholar?cluster=15275163177548183539&hl=en&as_sdt=0,5)].

* [Anomaly detection through explanations](https://dspace.mit.edu/handle/1721.1/129250) - ***Ph.D Dissertation MIT***, 2018. [[All Versions](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Anomaly+detection+through+explanations&btnG=)].

* [Discovering a symbolic planning language from continuous experience](https://joaoloula.github.io/Discovering_a_Symbolic_Planning_Language_From_Continuous_Experience.pdf) - ***CogSci'19***, 2019. [[All Versions](https://scholar.google.com/scholar?hl=en&as_sdt=2005&sciodt=0%2C5&cites=14400178089019636923&scipsc=&q=Discovering+a+symbolic+planning+language+from+continuous+experience&btnG=)].

*[Back to Top](#c)

<span id = "bml"></span>
### Bayesian Modeling & Learning

<span id = "bayesian-induction"></span>
#### Bayesian Induction

* [Bayesian Epistemology](https://plato.stanford.edu/entries/epistemology-bayesian/) - ***Plato Stanford***. 

* [Probabilistic machine learning and artificial intelligence](https://www.nature.com/articles/nature14541.pdf) - ***Nature***, 2015. [[All Versions](https://scholar.google.com/scholar?cluster=1783282361269717744&hl=en&as_sdt=0,5)].

* [Generalization, similarity, and Bayesian inference](http://web.mit.edu/cocosci/archive/Papers/tenenbaum_griffiths01.pdf) - ***Behavioral and Brain Sciences***, 2001. [[All Versions](https://scholar.google.com/scholar?cluster=14074987155133342565&hl=en&as_sdt=0,5)].

* [Bayesian modeling of human concept learning](http://web.mit.edu/cocosci/archive/Papers/bayes.pdf) - ***NIPS'99***, 1999. [[All Versions](https://scholar.google.com/scholar?cluster=12185543141957001794&hl=en&as_sdt=0,5&as_vis=1)].

* [Theory-based Bayesian models of inductive learning and reasoning](https://www.sciencedirect.com/science/article/pii/S1364661306001343) - ***Trends in Cognitive Sciences***, 2006. [[All Versions](https://scholar.google.com/scholar?cluster=6741344960992898446&hl=en&as_sdt=0,5)].

* [Word learning as Bayesian inference](https://psycnet.apa.org/doiLanding?doi=10.1037%2F0033-295X.114.2.245) - ***Psychological Review***, 2007. [[All Versions](https://scholar.google.com/scholar?oi=bibs&hl=en&cluster=5476233692839102256)].

* [How to Grow a Mind: Statistics, Structure, and Abstraction](https://science.sciencemag.org/content/331/6022/1279) - ***Science***, 2011. [[All Versions](https://scholar.google.com/scholar?cluster=2667398573353002097&hl=en&as_sdt=0,5)].

* [Human-level concept learning through probabilistic program induction.](https://science.sciencemag.org/content/sci/350/6266/1332.full.pdf) - ***Science***, 2015. [[All Versions](https://scholar.google.com/scholar?cluster=11844685101409624506&hl=en&as_sdt=0,5)]. [[Supplementary Material](https://cims.nyu.edu/~brenden/LakeEtAl2015Science_supp.pdf)].

* [Building Machines That Learn and Think Like People](https://arxiv.org/abs/1604.00289) - ***Behavioral and Brain Sciences***, 2017. [[All Versions](https://scholar.google.com/scholar?cluster=8504723689348856287&hl=en&as_sdt=0,5)].

*[Back to Top](#c)

<span id = "generative-modeling"></span>
#### Generative Model

* [A tale of three probabilistic families: Discriminative, descriptive, and generative models](http://www.stat.ucla.edu/~ywu/QAM2018.pdf) - ***Quarterly of Applied Mathematics***, 2018. [[All Versions](https://scholar.google.com/scholar?oi=bibs&hl=en&cluster=6129609629126793774)].

*[Back to Top](#c)

<span id = "nonparametric-model"></span>
#### Nonparametric Model

* [Mixtures of Dirichlet Process with Applications to Bayesian Nonparametric Problems](https://people.eecs.berkeley.edu/~jordan/courses/281B-spring04/readings/antoniak.pdf) - ***The Annals of Statistics***, 1974. [[All Versions](https://scholar.google.com/scholar?cluster=17937202534282344046&hl=en&as_sdt=0,5)].

* [Nonparametric Bayesian Data Analysis](https://projecteuclid.org/journals/statistical-science/volume-19/issue-1/Nonparametric-Bayesian-Data-Analysis/10.1214/088342304000000017.full) - ***Statistical Science***, 2004. [[All Versions](https://scholar.google.com/scholar?cluster=13476170780072319995&hl=en&as_sdt=0,5)].

* [Hierarchical topic models and the nested Chinese restaurant process](https://proceedings.neurips.cc/paper/2003/file/7b41bfa5085806dfa24b8c9de0ce567f-Paper.pdf) - ***NIPS'03***, 2003. [[All Versions](https://scholar.google.com/scholar?cluster=15040818675282958700&hl=en&as_sdt=0,5)].

* [Learning Systems of Concepts with an Infinite Relational Model](https://www.aaai.org/Papers/AAAI/2006/AAAI06-061.pdf) - ***AAAI'06***, 2006. [[All Versions](https://scholar.google.com/scholar?cluster=3207350432755252565&hl=en&as_sdt=0,5)].

* [The nested chinese restaurant process and bayesian nonparametric inference of topic hierarchies](https://dl.acm.org/doi/abs/10.1145/1667053.1667056) - ***Journal of the ACM***, 2010. [[All Versions](https://scholar.google.com/scholar?cluster=8216933258869737505&hl=en&as_sdt=0,5)].

* [Infinite Latent Feature Models and the Indian Buffet Process](http://mlg.eng.cam.ac.uk/zoubin/papers/ibptr.pdf) - ***Gatsby Computational Neuroscience Unit Technical Report 2005-001***, 2005. [[All Versions](https://scholar.google.com/scholar?cluster=13180738480564152907&hl=en&as_sdt=0,5)].

* [The Indian Buffet Process: An Introduction and Review](https://jmlr.org/papers/v12/griffiths11a.html) - ***Journal of Machine Learning Research***, 2011. [[All Versions](https://scholar.google.com/scholar?cluster=6301314251995890943&hl=en&as_sdt=0,5)].

* [Nonparametric Bayesian Logic](https://www.cs.ubc.ca/~nando/papers/npblog.pdf) - ***UAI'05***, 2005. [[All Versions](https://scholar.google.com/scholar?cluster=18267211625980322095&hl=en&as_sdt=0,5)].

* [Infinite Hidden Relational Models](https://www.dbs.ifi.lmu.de/~yu_k/uai06_relation.pdf) - ***UAI'06***, 2006. [[All Versions](https://scholar.google.com/scholar?cluster=2143172296528388141&hl=en&as_sdt=2005&sciodt=0,5)].

* [Statistical Predicate Invention](https://alchemy.cs.washington.edu/papers/kok07/kok07.pdf) - ***ICML'07***, 2007. [[All Versions](https://scholar.google.com/scholar?cluster=17009312281859401704&hl=en&as_sdt=2005&sciodt=0,5)].

*[Back to Top](#c)

<span id = "bayesian-optimization"></span>
#### Bayesian Optimization

* [Practical Bayesian Optimization of Machine Learning Algorithms](https://proceedings.neurips.cc/paper/2012/file/05311655a15b75fab86956663e1819cd-Paper.pdf) - ***NIPS'12***, 2012. [[All Versions](https://scholar.google.com/scholar?cluster=14442949298925775705&hl=en&as_sdt=0,5)].

* [Taking the Human Out of the Loop: A Review of Bayesian Optimization](https://www.cs.princeton.edu/~rpa/pubs/shahriari2016loop.pdf) - ***Proceedings of the IEEE***, 2015. [[All Versions](https://scholar.google.com/scholar?cluster=2039456143890648437&hl=en&as_sdt=0,5)].

*[Back to Top](#c)

<span id = "lcp"></span>
### Learning with Cognitive Plausibility

* [Accuracy and Precision](https://en.wikipedia.org/wiki/Accuracy_and_precision) - ***Wikipedia***.

* [Cognitive Science: Definition, Status, and Questions](https://www.annualreviews.org/doi/abs/10.1146/annurev.ps.40.020189.003131) - ***Annual Review of Psychology***, 1989. [[All Versions](https://scholar.google.com/scholar?cluster=8549671583307260475&hl=en&as_sdt=0,5)].

* [Recognition-by-Components: A Theory of Human Image Understanding](http://people.csail.mit.edu/torralba/courses/6.870/papers/Biederman_RBC_1987.pdf) - ***Psychological Review***, 1987. [[All Versions](https://scholar.google.com/scholar?cluster=16522931798979362446&hl=en&as_sdt=0,5)].

* [A global geometric framework for nonlinear dimensionality reduction](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.1084.4695&rep=rep1&type=pdf) - ***Science***, 2000. [[All Versions](https://scholar.google.com/scholar?oi=bibs&hl=en&cluster=14602426245887619907)].

* [A tale of three probabilistic families: Discriminative, descriptive, and generative models](http://www.stat.ucla.edu/~ywu/QAM2018.pdf) - ***Quarterly of Applied Mathematics***, 2018. [[All Versions](https://scholar.google.com/scholar?cluster=6129609629126793774&hl=en&as_sdt=0,5)].

* [Machine Behaviour](https://www.nature.com/articles/s41586-019-1138-y) - ***Nature***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=7881171273277686092&hl=en&as_sdt=0,5)].

* [Dark, Beyond Deep: A Paradigm Shift to Cognitive AI with Humanlike Common Sense](https://yzhu.io/publication/dark2020engineering/paper.pdf) - ***Engineering***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=12292747257300299161&hl=en&as_sdt=0,5)].

* [Self-supervised Learning Through the eyes of a Child](https://cims.nyu.edu/~brenden/papers/OrhanEtAl2020NeurIPS.pdf) - ***NIPS'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=5608715260418451299&hl=en&as_sdt=0,5)].

* [CLEVRER: CoLlision Events for Video REpresentation and Reasoning](https://arxiv.org/abs/1910.01442) - ***ICLR'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=4352064462350202338&hl=en&as_sdt=0,5)].

* [BONGARD-LOGO: A New Benchmark for Human-Level Concept Learning and Reasoning](https://proceedings.neurips.cc/paper/2020/file/bf15e9bbff22c7查看719020f9df4badc20a-Paper.pdf) - ***NIPS'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=9164011458889391917&hl=en&as_sdt=0,5)].

* [Grounded Language Learning Fast and Slow](https://arxiv.org/pdf/2009.01719.pdf) - ***ICLR'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=17735027444431750346&hl=en&as_sdt=0,5)]. [[Project](https://github.com/deepmind/dm_fast_mapping?s=05)].

* [The relationship between Precision-Recall and ROC curves](https://dl.acm.org/doi/10.1145/1143844.1143874) - ***ICML'06***, 2006. [[All Versions](https://scholar.google.com/scholar?cluster=10708180947310062390&hl=en&as_sdt=0,5)].

* [Distributional Generalization: A New Kind of Generalization](http://export.arxiv.org/pdf/2009.08092) - 2020. [[All Versions](https://scholar.google.com/scholar?cluster=6190621467796247477&hl=en&as_sdt=0,5)].

* [Learning and development in networks: The importance of starting small.](https://www.sciencedirect.com/science/article/abs/pii/0010027793900584) - ***Cognition***, 1993. [[All Versions](https://scholar.google.com/scholar?cluster=5133345254007462915&hl=en&as_sdt=0,5)].

* [Language acquisition in the absence of explicit negative evidence: how important is starting small?](https://www.sciencedirect.com/science/article/pii/S0010027799000311) - ***Cognition***, 1999. [[All Versions](https://scholar.google.com/scholar?cluster=11813578367725362166&hl=en&as_sdt=0,5)].

* [Curriculum Learning](https://dl.acm.org/doi/pdf/10.1145/1553374.1553380) - ***ICML'09***, 2009. [[All Versions](https://scholar.google.com/scholar?cluster=8740915934335425405&hl=en&as_sdt=0,5)].

* [Parsing video events with goal inference and intent prediction](https://ieeexplore.ieee.org/document/6126279) - ***ICCV'11***, 2011. [[All Versions](https://scholar.google.com/scholar?cluster=5979196784405021658&hl=en&as_sdt=0,5)].

* [Inferring "Dark Matter" and "Dark Energy" from Videos](https://ieeexplore.ieee.org/document/6751387) - ***ICCV'13***, 2013. [[All Versions](https://scholar.google.com/scholar?cluster=3467068307444498624&hl=en&as_sdt=0,5)].

* [Explainable and Explicit Visual Reasoning over Scene Graphs](https://openaccess.thecvf.com/content_CVPR_2019/papers/Shi_Explainable_and_Explicit_Visual_Reasoning_Over_Scene_Graphs_CVPR_2019_paper.pdf) - ***CVPR'19***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=8517395712319798436&hl=en&as_sdt=0,5)].

* [Distributed Representations of Words and Phrases and their Compositionality](https://papers.nips.cc/paper/2013/file/9aa42b31882ec039965f3c4923ce901b-Paper.pdf) - ***NIPS'13***, 2013. [[All Versions](https://scholar.google.com/scholar?cluster=2410615501856807729&hl=en&as_sdt=0,5)].

* [Motion Reasoning for Goal-Based Imitation Learning](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9197172) - ***ICRA'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=7519230802512388210&hl=en&as_sdt=0,5)].

* [Action Genome: Actions as Compositions of Spatio-temporal Scene Graphs](https://openaccess.thecvf.com/content_CVPR_2020/papers/Ji_Action_Genome_Actions_As_Compositions_of_Spatio-Temporal_Scene_Graphs_CVPR_2020_paper.pdf) - ***CVPR'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=388714326304810525&hl=en&as_sdt=0,5)].

* [Refactoring Policy for Compositional Generalizability using Self-Supervised Object Proposals](https://proceedings.neurips.cc/paper/2020/file/64dcf3c521a00dbb4d2a10a27a95a9d8-Paper.pdf) - ***NIPS'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=2255457416066730255&hl=en&as_sdt=0,5)].

* [Something-Else: Compositional Action Recognition with Spatial-Temporal Interaction Networks](https://openaccess.thecvf.com/content_CVPR_2020/papers/Materzynska_Something-Else_Compositional_Action_Recognition_With_Spatial-Temporal_Interaction_Networks_CVPR_2020_paper.pdf) - ***CVPR'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=17469863154797360929&hl=en&as_sdt=0,5)].

* [Putting visual object recognition in context](https://openaccess.thecvf.com/content_CVPR_2020/papers/Zhang_Putting_Visual_Object_Recognition_in_Context_CVPR_2020_paper.pdf) - ***CVPR'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=6207193649298787857&hl=en&as_sdt=0,5)].

* [Multimodal Few-Shot Learning with Frozen Language Models](https://arxiv.org/abs/2106.13884) - 2021. [[All Versions](https://scholar.google.com/scholar?cluster=16154696122208258147&hl=en&as_sdt=0,5)].

* [Describing Objects by their Attributes](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=5206772) - ***CVPR'09***, 2009. [[All Versions](https://scholar.google.com/scholar?cluster=6853730684095116174&hl=en&as_sdt=0,5)].

* [Panoramic Learning with A Standardized Machine Learning Formalism](https://arxiv.org/abs/2108.07783) - 2021. [[All Versions](https://scholar.google.com/scholar?cluster=14222434793711614257&hl=en&as_sdt=0,5)].

* [A generative vision model that trains with high data efficiency and breaks text-based CAPTCHAs](https://www.cs.jhu.edu/~ayuille/JHUcourses/ProbabilisticModelsOfVisualCognition2020/Lec22/GeorgeCAPCHAS.pdf) - ***Science***, 2017. [[All Versions](https://scholar.google.com/scholar?cluster=1478382321633671444&hl=en&as_sdt=0,5)].

* [Graininess of judgment under uncertainty: An accuracy-informativeness trade-off](https://psycnet.apa.org/record/1996-10319-001), ***Journal of Experimental Psychology***, 1995. [[All Versions](https://scholar.google.com/scholar?cluster=15366302654259490472&hl=en&as_sdt=0,5)].

*[Back to Top](#c)

<span id = "prgmcomm"></span>
### Communications & Pragmatics

<span id = "nvcomm"></span>
#### Non-Verbal Communication

* [The Interactive Evolution of Human Communication Systems](https://onlinelibrary.wiley.com/doi/epdf/10.1111/j.1551-6709.2009.01090.x) - ***Cognitive Science***, 2010. [[All Versions](https://scholar.google.com/scholar?cluster=6689941517686043970&hl=en&as_sdt=0,5)].

* [Iconicity: From sign to system in human communication and language](https://benjamins.com/catalog/pc.22.2.05fay) - ***Pragmatics & Cognition***, 2014. [[All Versions](https://scholar.google.com/scholar?cluster=8525760321117094567&hl=en&as_sdt=0,5)].

* [The Picture Exchange Communication System](https://journals.sagepub.com/doi/abs/10.1177/108835769400900301) - ***Behavior Modification***, 1994. [[All Versions](https://scholar.google.com/scholar?cluster=18113491434570143349&hl=en&as_sdt=0,5)].

* [Graphical Language Games: Interactional Constraints on Representational Form](https://onlinelibrary.wiley.com/doi/full/10.1080/15326900701221363) - ***Cognitive Science***, 2007. [[All Versions](https://scholar.google.com/scholar?cluster=280214578402050136&hl=en&as_sdt=0,5)].

* [A multimodal discourse theory of visual narrative](https://www.sciencedirect.com/science/article/pii/S0378216614001830) - ***Journal of Pragmatics***, 2014. [[All Versions](https://scholar.google.com/scholar?cluster=912273653379961242&hl=en&as_sdt=0,5)].

* [Pixelor: A Competitive Sketching AI Agent. So you think you can beat me?](https://ayankumarbhunia.github.io/pixelor/image/pixelor.pdf) - ***SIG Graph***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=6676723059377806081&hl=en&as_sdt=0,5)]. [[Project](http://sketchx.ai/pixelor)].

* [Pragmatic Inference and Visual Abstraction Enable Contextual Flexibility During Visual Communication](https://link.springer.com/article/10.1007/s42113-019-00058-7) - ***Computational Brain & Behavior***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=17971107104483505071&hl=en&as_sdt=0,5)].

* [Emergent Graphical Conventions in a Visual Communication Game](https://arxiv.org/abs/2111.14210) - 2021. [[All Versions](https://scholar.google.com/scholar?cluster=6476453985812346727&hl=en&as_sdt=0,5)].

* [Communicating artificial neural networks develop efficient color-naming systems](https://www.pnas.org/content/118/12/e2016569118) - ***Proceedings of National Academy of Sciences***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=1640459156303560508&hl=en&as_sdt=0,5)].

*[Back to Top](#c)

<span id = "rsa"></span>
#### Rational Speech Act

* [Pragmatics](https://plato.stanford.edu/entries/pragmatics/) - ***Plato Stanford***.

* [Predicting Pragmatic Reasoning in Language Games](https://science.sciencemag.org/content/336/6084/998) - ***Science***, 2012. [[All Versions](https://scholar.google.com/scholar?cluster=15533081031935746054&hl=en&as_sdt=0,5)].

* [Pragmatic Language Interpretation as Probabilistic Inference](https://www.sciencedirect.com/science/article/pii/S136466131630122X) - ***Trends in Cognitive Sciences***, 2016. [[All Versions](https://scholar.google.com/scholar?cluster=11393505968563356130&hl=en&as_sdt=0,5)].

* [Social Pragmatics: Preschoolers Rely on Commonsense Psychology to Resolve Referential Underspecification](https://compdevlab.yale.edu/docs/2019/2019_ChildDev_Pragmatics.pdf) - ***Child Development***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=16352913537004112920&hl=en&as_sdt=0,5)].

* [Disentangling contributions of visual information and interaction history in the formation of graphical conventions](https://cogsci.mindmodeling.org/2019/papers/0091/0091.pdf) - ***CogSci'19***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=15046353579508199394&hl=en&as_sdt=0,5)].

* [How young children integrate information sources to infer the meaning of words](https://www.nature.com/articles/s41562-021-01145-1) - ***Nature***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=10144794357802769844&hl=en&as_sdt=0,5)].

* [Information Structure in Discourse: Towards an Integrated Formal Theory of Pragmatics](https://semprag.org/index.php/sp/article/view/sp.5.6/pdf) - ***Semantics and Pragmatics***, 1998. [[All Versions](https://scholar.google.com/scholar?cluster=9127222314768938599&hl=en&as_sdt=0,5)].

* [When Lingens meets Frege: communication without common ground](https://link.springer.com/article/10.1007/s11098-020-01490-3) - ***Philosophical Studies***, 2021.

* [Language as shaped by the environment: linguistic construal in a collaborative spatial task](https://www.nature.com/articles/s41599-020-0404-9.pdf) - ***Nature Humanities and Social Sciences Communications***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=7842508027049437987&hl=en&as_sdt=0,5)].

*[Back to Top](#c)

<span id = "lcps"></span>
#### Language Compositionality

* [Compositionality](https://plato.stanford.edu/entries/compositionality/) - ***Plato Stanford***.

* [The Principle of Semantic Compositionality](https://link.springer.com/content/pdf/10.1007/BF00763644.pdf) - ***Topoi***, 1994. [[All Versions](https://scholar.google.com/scholar?cluster=10899040818001759322&hl=en&as_sdt=0,5)].

* [On The Emergence Of Compositionality](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.60.3235) - ***Proceedings of the Evolution of Language Conference'06***, 2006. [[All Versions](https://scholar.google.com/scholar?cluster=16315741180717951222&hl=en&as_sdt=0,5)].

* [Multi-Agent Cooperation and the Emergence of (Natural) Language](https://arxiv.org/pdf/1612.07182.pdf) - ***ICLR'17***, 2017. [[All Versions](https://scholar.google.com/scholar?cluster=1931070702879918446&hl=en&as_sdt=0,5)].

* [Emergence of Language with Multi-agent Games: Learning to Communicate with Sequences of Symbols](https://proceedings.neurips.cc/paper/2017/hash/70222949cc0db89ab32c9969754d4758-Abstract.html) - ***NIPS'18***, 2018. [[All Versions](https://scholar.google.com/scholar?cluster=17308624474306270808&hl=en&as_sdt=0,5)].

* [Emergent communication through negotiation](https://arxiv.org/abs/1804.03980) - ***ICLR'18***, 2018. [[All Versions](https://scholar.google.com/scholar?cluster=8825869866742501521&hl=en&as_sdt=0,5)].

* [The language of generalization](https://psycnet.apa.org/record/2019-07481-001) - ***Psychological Review***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=7723877614160376324&hl=en&as_sdt=0,5)].

* [Compositionality and Generalization in Emergent Languages](https://arxiv.org/abs/2004.09124) - ***ACL'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=5792073344743965767&hl=en&as_sdt=0,5)].

*[Back to Top](#c)

<span id = "probsol"></span>
### Problem Solving

<span id = "hmprobsol"></span>
#### Human-Level Problem Solving

* [Elements of a theory of human problem solving](https://psycnet.apa.org/record/1959-07883-001) - ***Psychological Review***, 1958. [[All Versions](https://scholar.google.com/scholar?cluster=6226995019045187501&hl=en&as_sdt=0,5)].

* [Human Problem Solving](https://psycnet.apa.org/record/1973-10478-000) - ***Englewood Cliffs, NJ: Prentice-hall***, 1972. [[All Versions](https://scholar.google.com/scholar?cluster=3996229083126262536&hl=en&as_sdt=0,5)].

* [Learning to Solve Problems: A Handbook for Designing Problem-Solving Learning Environments](http://196.223.158.148/bitstream/handle/123456789/2978/596.pdf?sequence=1&isAllowed=y) - ***Taylorfrancis***, 2010. [[All Versions](https://scholar.google.com/scholar?cluster=13262690779319271809&hl=en&as_sdt=2005&sciodt=0,5)].

* [Judgment under Uncertainty: Heuristics and Biases: Biases in judgments reveal some heuristics of thinking under uncertainty](https://www.science.org/doi/abs/10.1126/science.185.4157.1124) - ***Science***, 1974. [[All Versions](https://scholar.google.com/scholar?cluster=17040257859216791312&hl=en&as_sdt=0,5)].

* [Human Performance on Insight Problem Solving: A Review](https://docs.lib.purdue.edu/cgi/viewcontent.cgi?article=1094&context=jps) - ***The Journal of Problem Solving***, 2011. [[All Versions](https://scholar.google.com/scholar?cluster=15913242870565808883&hl=en&as_sdt=0,5)].

* [Learning to perceive and act by trial and error](https://link.springer.com/article/10.1007/BF00058926) - ***Machine Learning***, 1991. [[All Versions](https://scholar.google.com/scholar?cluster=1987606770603964473&hl=en&as_sdt=0,5)].

* [Representations in distributed cognitive tasks](https://onlinelibrary.wiley.com/doi/abs/10.1207/s15516709cog1801_3) - ***Cognitive Science***, 1994. [[All Versions](https://scholar.google.com/scholar?oi=bibs&hl=en&cluster=14781266698447195483)].

* [The nature of external representations in problem solving](https://www.sciencedirect.com/science/article/abs/pii/S0364021399800226) - ***Cognitive Science***, 1997. [[All Versions](https://scholar.google.com/scholar?cluster=10698887231200401430&hl=en&as_sdt=0,5)].

* [Mind Games: Game Engines as an Architecture for Intuitive Physics](https://www.sciencedirect.com/science/article/pii/S1364661317301134) - ***Trends in Cognitive Sciences***, 2017. [[All Versions](https://scholar.google.com/scholar?cluster=14527964477161848029&hl=en&as_sdt=2005&sciodt=0,5)].

* [Learning physical parameters from dynamic scenes](https://www.sciencedirect.com/science/article/abs/pii/S0010028517301822) - ***Cognitive Psychology***, 2017. [[All Versions](https://scholar.google.com/scholar?cluster=5103729321433959736&hl=en&as_sdt=0,5)].

* [Exploration: from machines to humans](https://www.sciencedirect.com/science/article/pii/S2352154620301236) - ***Current Opinion in Behavioral Sciences***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=8015078432419172621&hl=en&as_sdt=0,5)].

* [Balancing exploration and exploitation with information and randomization](https://www.sciencedirect.com/science/article/pii/S2352154620301467) - ***Current Opinion in Behavioral Sciences***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=8164388137243077863&hl=en&as_sdt=2005&sciodt=0,5)].

* [Hippocampal neurons construct a map of an abstract value space](https://www.sciencedirect.com/science/article/pii/S0092867421008369) - ***Cell***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=12658820581876003172&hl=en&as_sdt=0,5)].

* [Insightful problem solving and creative tool modification by captive nontool-using rooks](https://www.pnas.org/content/106/25/10370.short) - ***Proceedings of National Academy of Sciences***, 2009. [[All Versions](https://scholar.google.com/scholar?cluster=6776471679661065229&hl=en&as_sdt=0,5)]. [[Supplementary Material](https://www.pnas.org/content/suppl/2009/05/28/0901008106.DCSupplemental)].

*[Back to Top](#c)

<span id = "mbplan"></span>
#### Model-Based Planning

* [From Skills to Symbols: Learning Symbolic Representations for Abstract High-Level Planning](https://jair.org/index.php/jair/article/view/11175) - ***Journal of Artificial Intelligence Research***, 2018. [[All Versions](https://scholar.google.com/scholar?cluster=17962480659445514879&hl=en&as_sdt=0,5)].

* [Simulation as an engine of physical scene understanding](https://www.pnas.org/content/pnas/110/45/18327.full.pdf) - ***Proceedings of National Academy of Sciences***, 2013. [[All Versions](https://scholar.google.com/scholar?cluster=5892822406285231676&hl=en&as_sdt=0,5)]. [[Appendix](https://www.pnas.org/content/pnas/suppl/2013/10/18/1306572110.DCSupplemental/pnas.201306572SI.pdf?targetid=nameddest%3DSTXT)].

* [Differentiable Physics and Stable Modes for Tool-Use and Manipulation Planning](https://dspace.mit.edu/handle/1721.1/126626) - ***Robotics: Science and Systems***, 2018. [[All Versions](https://scholar.google.com/scholar?cluster=10342169019935480143&hl=en&as_sdt=0,5)].

* [Integrated Task and Motion Planning](https://www.annualreviews.org/doi/abs/10.1146/annurev-control-091420-084139) - ***Annual Review of Control, Robotics, and Autonomous Systems***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=478421650694199529&hl=en&as_sdt=0,5)].

* [Learning to act by integrating mental simulations and physical experiments](https://gershmanlab.com/pubs/Dasgupta18_simulation.pdf) - ***CogSci'21***, 2018. [[All Versions](https://scholar.google.com/scholar?cluster=7342920174595829739&hl=en&as_sdt=0,5)].

* [What Is the Model in Model-Based Planning?](https://onlinelibrary.wiley.com/doi/ftr/10.1111/cogs.12928) - ***Cognitive Science***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=10598397017491369972&hl=en&scisbd=1&as_sdt=2005&sciodt=0,5)].

* [Discovering State and Action Abstractions for Generalized Task and Motion Planning](https://arxiv.org/pdf/2109.11082.pdf) - ***AAAI'22***, 2022. [[All Versions](https://scholar.google.com/scholar?oi=bibs&hl=en&cluster=1054368060554971920)].

*[Back to Top](#c)

<span id = "mfrl"></span>
#### Model-Free Reinforcement Learning

* [Between MDPs and semi-MDPs: A framework for temporal abstraction in reinforcement learning](https://www.sciencedirect.com/science/article/pii/S0004370299000521) - ***Artificial Intelligence***, 1999. [[All Versions](https://scholar.google.com/scholar?cluster=1471968208408231068&hl=en&as_sdt=0,5)].

* [Solving Compositional Reinforcement Learning Problems via Task Reduction](https://openreview.net/forum?id=9SS69KwomAM) - ***ICLR'21***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=15628616147808752058&hl=en&as_sdt=0,5)].

* [Neural Task Programming: Learning to Generalize Across Hierarchical Tasks](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8460689) - ***ICRA'18***, 2018. [[All Versions](https://scholar.google.com/scholar?cluster=7155333517647976638&hl=en&as_sdt=0,5)].

* [Causal Curiosity: RL Agents Discovering Self-supervised Experiments for Causal Representation Learning](https://arxiv.org/abs/2010.03110) - ***ICML'21***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=4880520597219138666&hl=en&as_sdt=0,5)].

* [Learning to act: qualitative learning of deterministic action models](https://academic.oup.com/logcom/article-abstract/28/2/337/4695480) - ***Journal of Logic and Computation***, 2017. [[All Versions](https://scholar.google.com/scholar?cluster=14570482854600886953&hl=en&as_sdt=0,5)].

* [Learning to Act and Observe in Partially Observable Domains](https://arxiv.org/abs/2109.06076) - 2021. [[All Versions](https://scholar.google.com/scholar?cluster=2258600434630687063&hl=en&as_sdt=0,5)].

* [Why Generalization in RL is Difficult: Epistemic POMDPs and Implicit Partial Observability](https://arxiv.org/abs/2107.06277) - 2021. [[All Versions](https://scholar.google.com/scholar?cluster=9640851185758072663&hl=en&as_sdt=0,5)].

* [Rapid trail-and-error learning with simulation supports flexible tool use and physical reasoning.](https://www.pnas.org/content/pnas/117/47/29302.full.pdf) - ***Proceedings of National Academy of Sciences***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=14400178089019636923&hl=en&as_sdt=0,5)]. [[Project](https://sites.google.com/view/virtualtoolsgame/home)]. [[Appendix](https://www.pnas.org/content/pnas/suppl/2020/11/20/1912341117.DCSupplemental/pnas.1912341117.sapp.pdf)].

* [Abstract strategy learning underlies flexible transfer in physical problem solving](https://cogsci.mindmodeling.org/2020/papers/0764/) - ***CogSci'20***, 2020. [[All Versions](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Abstract+strategy+learning+underlies+flexible+transfer+in+physical+problem+solving.&btnG=)].

* [Physion: Evaluating Physical Prediction from Vision in Humans and Machines](https://openreview.net/forum?id=CXyZrKPz4CU) - 2021. [[All Versions](https://scholar.google.com/scholar?cluster=8733318111076645893&hl=en&as_sdt=0,5)].

* [Data-Efficient Learning for Complex and Real-Time Physical Problem Solving Using Augmented Simulation](https://ieeexplore.ieee.org/abstract/document/9387127) - ***Robotics and Automation Letters***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=3140653562829320759&hl=en&as_sdt=0,5)].

* [A Survey of Preference-Based Reinforcement Learning Methods](https://www.jmlr.org/papers/volume18/16-634/16-634.pdf) - ***Journal of Machine Learning Research***, 2017. [[All Versions](https://scholar.google.com/scholar?cluster=13278778479251450967&hl=en&as_sdt=0,5)].

* [On the Expressivity of Markov Reward](https://papers.nips.cc/paper/2021/file/4079016d940210b4ae9ae7d41c4a2065-Paper.pdf) - ***NIPS'21***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=4524686816939437211&hl=en&as_sdt=0,5)].

*[Back to Top](#c)

<span id = "irl"></span>
#### Inverse Reinforcement Learning

* [Apprenticeship Learning via Inverse Reinforcement Learning](https://dl.acm.org/doi/pdf/10.1145/1015330.1015430) - ***ICML'04***, 2004. [[All Versions](https://scholar.google.com/scholar?cluster=10260011060619377707&hl=en&as_sdt=0,5)].

* [From Language to Goals: Inverse Reinforcement Learning for Vision-Based Instruction Following](https://arxiv.org/abs/1902.07742) - ***ICLR'19***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=9128320307925997063&hl=en&as_sdt=0,5)].

* [Few-shot Bayesian imitation learning with logical program policies.](https://arxiv.org/pdf/1904.06317.pdf) - ***AAAI'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=5103854692762145813&hl=en&as_sdt=0,5)].

* [Generalized Inverse Planning: Learning Lifted non-Markovian Utility for Generalizable Task Representation](http://export.arxiv.org/pdf/2011.09854) - 2020. [[All Versions](https://scholar.google.com/scholar?cluster=18369106870663956780&hl=en&as_sdt=0,5)].

*[Back to Top](#c)

<span id = "nsl"></span>
### Hybrid System 1 & 2

* [Dual coding of knowledge in the human brain](https://www.sciencedirect.com/science/article/pii/S1364661321001765) - ***Trends in Cognitive Sciences***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=11751507203561842501&hl=en&as_sdt=0,5)].

* [Learning Explanatory Rules from Noisy Data](https://www.jair.org/index.php/jair/article/view/11172) - ***Journal of Artificial Intelligence Research***, 2018. [[All Versions](https://scholar.google.com/scholar?cluster=2553893814364678772&hl=en&as_sdt=0,5)].

* [DeepProbLog: Neural Probabilistic Logic Programming](https://arxiv.org/abs/1805.10872) - ***NIPS'18***, 2018. [[All Versions](https://scholar.google.com/scholar?cluster=6079567413300944995&hl=en&as_sdt=0,5)].

* [Learning by Abstraction: The Neural State Machine](https://proceedings.neurips.cc/paper/2019/file/c20a7ce2a627ba838cfbff082db35197-Paper.pdf) - ***NIPS'19***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=7361406080192630148&hl=en&as_sdt=0,5)].

* [Combining Logical Abduction and Statistical Induction: Discovering Written Primitives with Human Knowledge.](https://cs.nju.edu.cn/zhouzh/zhouzh.files/publication/aaai17lasin.pdf) - ***AAAI'17***, 2017. [[All Versions](https://scholar.google.com/scholar?cluster=14477085725208589393&hl=en&as_sdt=0,5)].

* [Neural Logic Reinforcement Learning](https://arxiv.org/pdf/1904.10729.pdf) - ***ICML'19***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=18074632043038701502&hl=en&as_sdt=0,5)].

* [Bridging Machine Learning and Logical Reasoning by Abductive Learning.](http://papers.nips.cc/paper/8548-bridging-machine-learning-and-logical-reasoning-by-abductive-learning) - ***NIPS'19***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=1518342375288126288&hl=en&as_sdt=0,5)]. [[slides](https://daiwz.net/org/slides/ABL-meetup.html#/slide-title)]. [[code](https://github.com/AbductiveLearning/ABL-HED)].

* [Abductive learning: towards bridging machine learning and logical reasoning](https://link.springer.com/article/10.1007/s11432-018-9801-4) - ***Science China Information Sciences***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=8541635351775190855&hl=en&as_sdt=0,5)].

* [Abductive Knowledge Induction From Raw Data](https://arxiv.org/pdf/2010.03514.pdf) - ***IJCAI'21***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=7027142960863064076&hl=en&as_sdt=0,5)].

* [Making sense of sensory input](https://www.sciencedirect.com/science/article/pii/S0004370220301855) - ***Artificial Intelligence***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=11875529139573472578&hl=en&as_sdt=0,5)].

* [Abstract Spatial-Temporal Reasoning via Probabilistic Abduction and Execution](https://arxiv.org/pdf/2103.14230v1.pdf) - ***CVPR'21***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=4172146500538799638&hl=en&as_sdt=0,5)].

* [Learn to explain efﬁciently via neural logic inductive learning](https://openreview.net/pdf?id=SJlh8CEYDB) - ***ICLR'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=4550874980727321525&hl=en&as_sdt=0,5)]. [[Project](https://github.com/gblackout/NLIL)].

* [Closed Loop Neural-Symbolic Learning via Integrating Neural Perception, Grammar Parsing, and Symbolic Reasoning](https://arxiv.org/abs/2006.06649) - ***ICML'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=9257372000778020812&hl=en&as_sdt=0,5)].

* [Generating new concepts with hybrid neuro-symbolic models.](https://arxiv.org/abs/2003.08978) - ***CogSci'20***, 2020. [[All Versions](https://scholar.google.com/scholar?oi=bibs&hl=en&cluster=1912020791698331044)].

* [Learning Task-General Representations with Generative Neuro-Symbolic Modeling](https://arxiv.org/abs/2006.14448) - ***ICLR'21***, 2021. [[All Versions](https://scholar.google.com/scholar?oi=bibs&hl=en&cluster=1335404082385789329)].

* [AI Feynman: A physics-inspired method for symbolic regression](https://advances.sciencemag.org/content/6/16/eaay2631/tab-pdf) - ***Science***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=3655502646441210453&hl=en&as_sdt=0,5)].

* [Classification-by-Components: Probabilistic Modeling of Reasoning over a Set of Components](http://papers.nips.cc/paper/8546-classification-by-components-probabilistic-modeling-of-reasoning-over-a-set-of-components.pdf) - ***NIPS'19***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=12691103404451941071&hl=en&as_sdt=0,5)].

* [Neuro-Symbolic Visual Reasoning: Disentangling “Visual” from “Reasoning”](https://arxiv.org/pdf/2006.11524.pdf) - ***ICML'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=13160160974887139307&hl=en&as_sdt=0,5)].

* [Understanding Deep Architectures with Reasoning Layer](https://proceedings.neurips.cc/paper/2020/file/0d82627e10660af39ea7eb69c3568955-Paper.pdf) - ***NIPS'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=937882599430270789&hl=en&as_sdt=0,5)].

* [An Explicitly Relational Neural Network Architecture](https://arxiv.org/pdf/1905.10307.pdf) - ***ICML'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=37732747764322837&hl=en&as_sdt=0,5)].

* [Neural Production Systems](https://arxiv.org/pdf/2103.01937.pdf) - ***ICML'21***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=15299280949648915581&hl=en&as_sdt=0,5)].

* [Compositional Generalization via Neural-Symbolic Stack Machines](https://arxiv.org/pdf/2008.06662.pdf) - ***NIPS'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=15612498612943317331&hl=en&as_sdt=0,5)].

* [Stochastic Optimization of Sorting Networks via Continuous Relaxations](https://openreview.net/pdf?id=H1eSS3CcKX) - ***ICLR'19***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=10619362619006891050&hl=en&as_sdt=0,5)].

* [Program Guided Agent](https://openreview.net/pdf?id=BkxUvnEYDH) - ***ICLR'20***, 2020. [[All Versions](https://openreview.net/forum?id=BkxUvnEYDH)].

* [Learning Compositional Rules via Neural Program Synthesis](https://proceedings.neurips.cc/paper/2020/hash/7a685d9edd95508471a9d3d6fcace432-Abstract.html) - ***NIPS'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=3160670555314650508&hl=en&as_sdt=0,5)].

* [Discovering Symbolic Models from Deep Learning with Inductive Biases](https://arxiv.org/abs/2006.11287) - ***NIPS'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=9452091824686227240&hl=en&as_sdt=0,5)].

* [Neural Logic Machines](https://arxiv.org/pdf/1904.11694.pdf) - ***ICLR'19***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=4525183211642569463&hl=en&as_sdt=0,5)].

* [The Neuro-Symbolic Concept Learner: Interpreting Scenes, Words, and Sentences From Natural Supervision](https://arxiv.org/pdf/1904.12584.pdf) - ***ICLR'19***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=8837128214653317831&hl=en&as_sdt=0,5)].

* [Visual Concept-Metaconcept Learning](https://papers.nips.cc/paper/2019/file/98d8a23fd60826a2a474c5b4f5811707-Paper.pdf) - ***NIPS'19***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=1888051343232298875&hl=en&as_sdt=0,5)].

* [Grounding Physical Concepts of Objects and Events Through Dynamic Visual Reasoning](https://arxiv.org/abs/2103.16564) - ***ICLR'21***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=16735976343684307244&hl=en&as_sdt=0,5)].

* [Temporal and Object Quantification Networks](https://jiajunwu.com/papers/toqnet_ijcai.pdf) - ***IJCAI'21***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=17251222943638414124&hl=en&as_sdt=0,5)].

* [Regression Analysis for Interval-Valued Data](https://link.springer.com/chapter/10.1007/978-3-642-59789-3_58) - ***Data Analysis, Classification, and Related Methods***, 2000. [[All Versions](https://scholar.google.com/scholar?cluster=9407097855380377791&hl=en&as_sdt=0,5)].

* [Symbolic data analysis: what is it?](https://link.springer.com/chapter/10.1007/978-3-7908-1709-6_20) - ***Proceedings in Computational Statistics***, 2006. [[All Versions](https://scholar.google.com/scholar?cluster=3730437602749399283&hl=en&as_sdt=0,5)].

*[Back to Top](#c)

<span id = "xai"></span>
### Explainability

* [Ultra-Strong Machine Learning: comprehensibility of programs learned with ILP](https://link.springer.com/article/10.1007/s10994-018-5707-3) - ***Machine Learning***, 2018. [[All Versions](https://scholar.google.com/scholar?cluster=17551060457946144913&hl=en&as_sdt=0,5)].

* [Beneficial and harmful explanatory machine learning](https://link.springer.com/article/10.1007%2Fs10994-020-05941-0) - ***Machine Learning***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=16983722694047294963&hl=en&as_sdt=0,5)].

* [Network dissection: Quantifying interpretability of deep visual representations](https://ieeexplore.ieee.org/document/8099837) - ***CVPR'17***, 2017. [[All Versions](https://scholar.google.com/scholar?cluster=18069685615852396783&hl=en&as_sdt=0,5)]. [[Dataset: Places365](http://places2.csail.mit.edu/index.html)]. 

* [Understanding the role of Individual Units in a Deep Neural Network](https://www.pnas.org/content/pnas/early/2020/08/31/1907375117.full.pdf) - ***Proceedings of National Academy of Sciences***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=11996680970579301810&hl=en&as_sdt=0,5)].

* [Zoom In: An Introduction to Circuits](https://distill.pub/2020/circuits/zoom-in/) - ***Distill***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=9053581372570691569&hl=en&as_sdt=0,5)].

* [Compositional Explanations of Neurons](https://proceedings.neurips.cc/paper/2020/file/c74956ffb38ba48ed6ce977af6727275-Paper.pdf) - ***NIPS'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=15725346730266402738&hl=en&as_sdt=0,5)]. [[Project](https://github.com/jayelm/compexp)].

* [This Looks Like That: Deep Learning for Interpretable Image Recognition](http://papers.nips.cc/paper/9095-this-looks-like-that-deep-learning-for-interpretable-image-recognition.pdf) - ***NIPS'19***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=9461838581952136719&hl=en&as_sdt=0,5)].

* [Unsupervised learning by competing hidden units](https://www.pnas.org/content/pnas/116/16/7723.full.pdf) - ***Proceedings of National Academy of Sciences***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=1228003598355915526&hl=en&as_sdt=0,5)].

* [NBDT: Neural-Backed Decision Trees](https://arxiv.org/abs/2004.00221) - ***NIPS'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=1902399007162005819&hl=en&as_sdt=0,5)]. [[code](https://github.com/alvinwan/neural-backed-decision-trees)].

* [Noise or Signal: The Role of Backgrounds in Image Classification](https://arxiv.org/pdf/2006.09994.pdf) - ***ICLR'21***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=14729938011425134088&hl=en&as_sdt=0,5)]. [[Project](https://gradientscience.org/background/)].

* [Deep Forest: Towards An Alternative to Deep Neural Networks](https://www.ijcai.org/Proceedings/2017/497) - ***IJCAI'17***, 2017. [[All Versions](https://scholar.google.com/scholar?cluster=7391596872731517007&hl=en&as_sdt=0,5)]. [[Project](https://github.com/LAMDA-NJU/Deep-Forest)].

* [X-ToM: Explaining with Theory-of-Mind for Gaining Justified Human Trust](https://arxiv.org/pdf/1909.06907.pdf) - 2019. [[All Versions](https://scholar.google.com/scholar?cluster=7751326666821697923&hl=en&as_sdt=0,5)].

* [CoCoX: Generating Conceptual and Counterfactual Explanations via Fault-Lines](https://ojs.aaai.org/index.php/AAAI/article/view/5643) - ***AAAI'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=17443137068166403183&hl=en&as_sdt=0,5)].

*[Back to Top](#c)

<span id = "ei"></span>
### Embodied Intelligence

* [Embodied Cognition](https://plato.stanford.edu/entries/embodied-cognition/) - ***Plato Stanford***.

* [Externalism About the Mind](https://plato.stanford.edu/entries/content-externalism/) - ***Plato Stanford***.

* [Cognitive engineering: Human problem solving with tools](https://www.researchgate.net/profile/David-Woods-19/publication/242545872_Cognitive_Engineering_Human_Problem_Solving_with_Tools/links/542becf70cf29bbc126ac097/Cognitive-Engineering-Human-Problem-Solving-with-Tools.pdf) - ***Human Factors***, 1988. [[All Versions](https://scholar.google.com/scholar?cluster=14194840995416222723&hl=en&as_sdt=0,5)].

* [Tools, language and cognition in human evolution](https://psycnet.apa.org/record/1993-97340-000) - ***Cambridge University Press***, 1993. [[All Versions](https://scholar.google.com/scholar?cluster=6046350461147957220&hl=en&as_sdt=0,5)].

* [The Extended Mind](https://icds.uoregon.edu/wp-content/uploads/2014/06/Clark-and-Chalmers-The-Extended-Mind.pdf) - ***Analysis***, 1998. [[All Versions](https://scholar.google.com/scholar?cluster=9546561188261943866&hl=en&as_sdt=0,5)].

* [The neural bases of complex tool use in humans](https://www.sciencedirect.com/science/article/pii/S1364661303003231) - ***Trends in Cognitive Sciences***, 2004. [[All Versions](https://scholar.google.com/scholar?cluster=3612212926196611828&hl=en&as_sdt=0,5)].

* [Spontaneous Metatool Use by New Caledonian Crows](https://www.sciencedirect.com/science/article/pii/S0960982207017708) - ***Current Biology***, 2007. [[All Versions](https://scholar.google.com/scholar?cluster=9263531730425342443&hl=en&as_sdt=0,5)].

* [Rapid Assimilation of External Objects Into the Body Schema](https://journals.sagepub.com/doi/abs/10.1177/0956797610371962) - ***Psychological Science***, 2010. [[All Versions](https://scholar.google.com/scholar?cluster=854636910326733489&hl=en&as_sdt=0,5)].

* [The cognitive bases of human tool use](https://www.eva.mpg.de/documents/Cambridge/Tennie_Cultural_BehBrainSci_2012_1566208.pdf) - ***Behavioral and Brain Sciences***, 2012. [[All Versions](https://scholar.google.com/scholar?cluster=4648150119820414671&hl=en&as_sdt=0,5)].

* [The embodied mind extended: using words as social tools](https://www.frontiersin.org/articles/10.3389/fpsyg.2013.00214/full) - ***Frontiers in Psychology***, 2013. [[All Versions](https://scholar.google.com/scholar?cluster=14719988081062606352&hl=en&as_sdt=0,5)].

* [Tool use as adaptation](https://royalsocietypublishing.org/doi/10.1098/rstb.2012.0408) - ***Philosophical Transactions of the Royal Society B: Biological Sciences***, 2013. [[All Versions](https://scholar.google.com/scholar?cluster=8060841461200774807&hl=en&as_sdt=0,5)].

* [Intensive tool-practice and skillfulness facilitate the extension of body representations in humans](https://www.sciencedirect.com/science/article/pii/S0028393214000232) - ***Neuropsychologia***, 2014. [[All Versions](https://scholar.google.com/scholar?cluster=10578024091098127929&hl=en&as_sdt=0,5)].

* [Tool use and affordance: Manipulation-based versus reasoning-based approaches](https://psycnet.apa.org/doiLanding?doi=10.1037%2Frev0000027) - ***Psychological Review***, 2016. [[All Versions](https://scholar.google.com/scholar?cluster=3284942486402374505&hl=en&as_sdt=0,5)].

* [Meta-strategy learning in physical problem-solving: the effect of embodied experience](https://escholarship.org/uc/item/5gf0m7x3) - ***CogSci'21***, 2021. [[All Versions](https://scholar.google.com/scholar?oi=bibs&hl=en&cluster=9713842177532954702)].

* [Understanding Tools: Task-Oriented Object Modeling, Learning and Recognition](https://yzhu.io/publication/tool2015cvpr/paper.pdf) - ***CVPR'15***, 2015. [[All Versions](https://scholar.google.com/scholar?cluster=4609926671953500969&hl=en&as_sdt=0,5)]. [[Project](https://yzhu.io/publication/tool2015cvpr/)].

* [Robotic hand augmentation drives changes in neural body representation](https://robotics.sciencemag.org/content/6/54/eabd7935.abstract) - ***Science Robotics***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=1622125726197763917&hl=en&as_sdt=0,5)].

* [Expert Tool Users Show Increased Differentiation between Visual Representations of Hands and Tools](https://www.jneurosci.org/content/jneuro/41/13/2980.full.pdf) - ***Journal of Neuroscience***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=13454164767827515188&hl=en&as_sdt=0,5)].

* [Visual scoping operations for physical assembly](https://arxiv.org/pdf/2106.05654.pdf) - ***CogSci'21***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=7238090583833839&hl=en&as_sdt=0,5)].

* [Behavior-grounded representation of tool affordances](https://www.cc.gatech.edu/ai/robot-lab/online-publications/StoytchevICRA2005.pdf) - ***ICRA'05***, 2005. [[All Versions](https://scholar.google.com/scholar?cluster=6115815663915603675&hl=en&as_sdt=0,5)].

* [A Relational Approach to Tool-Use Learning in Robots](https://link.springer.com/chapter/10.1007/978-3-642-38812-5_1) - ***ILP'12***, 2012. [[All Versions](https://scholar.google.com/scholar?cluster=18374178227592386332&hl=en&as_sdt=0,5)].

* [Relational affordances for multiple-object manipulation](https://link.springer.com/article/10.1007/s10514-017-9637-x) - ***Autonomous Robots***, 2017. [[All Versions](https://scholar.google.com/scholar?cluster=6357646940615855682&hl=en&as_sdt=0,5)].

* [Improvisation through Physical Understanding: Using Novel Objects as Tools with Visual Foresight](http://m.roboticsproceedings.org/rss15/p01.pdf) - ***RSS'19***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=4316276917607326251&hl=en&as_sdt=0,5)].

* [Meta-strategy learning in physical problem-solving: the effect of embodied experience](https://www.biorxiv.org/content/10.1101/2021.07.08.451333v1) - 2021. [[All Versions](https://scholar.google.com/scholar?cluster=9713842177532954702&hl=en&as_sdt=0,5)].

*[Back to Top](#c)

<span id = "hie"></span>
### Human Intelligence Experiments

* [Elimination by aspects: A theory of choice](https://psycnet.apa.org/record/1973-00249-001) - ***Psychological Review***, 1972. [[All Versions](https://scholar.google.com/scholar?cluster=1633792484482810297&hl=en&as_sdt=0,5)].

* [Problem Solving and Rule Induction: A Unified View](https://stacks.stanford.edu/file/druid:qv796fc9687/qv796fc9687.pdf) - ***Knowledge and cognition***, 1974. [[All Versions](https://scholar.google.com/scholar?cluster=12943734683291006234&hl=en&as_sdt=0,5)].

* [Experiments with More Than One Random Factor: Designs, Analytic Models, and Statistical Power](https://www.annualreviews.org/doi/abs/10.1146/annurev-psych-122414-033702) - ***Annual Review of Psychology***, 2017.

* [Evidence integration in model-based tree search](https://www.pnas.org/content/112/37/11708.short) - ***Proceedings of National Academy of Sciences***, 2015. [[All Versions](https://scholar.google.com/scholar?cluster=11085043350027609187&hl=en&as_sdt=0,5)].

* [Searching large hypothesis spaces by asking questions](https://cogsci.mindmodeling.org/2016/papers/0122/paper0122.pdf) - ***CogSci'16***, 2016. [[All Versions](https://scholar.google.com/scholar?cluster=3398849603439166012&hl=en&as_sdt=0,5)].

* [Asking and evaluating natural language questions](https://gureckislab.org/papers/RotheLakeGureckis-2016cogsci.pdf) - ***CogSci'16***, 2016. [[All Versions](https://scholar.google.com/scholar?cluster=34641833161282231&hl=en&as_sdt=0,5)].

* [Do People Ask Good Questions?](https://link.springer.com/article/10.1007/s42113-018-0005-5) - ***Computational Brain & Behavior***, 2018. [[All Versions](https://scholar.google.com/scholar?cluster=14595996621617337270&hl=en&as_sdt=0,5)].

* [Asking goal-oriented questions and learning from answers](http://nyuccl.org/papers/Rothe-Lake-Gureckis-2019-Cogsci.pdf) - ***CogSci'19***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=14185546187726917682&hl=en&as_sdt=0,5)].

* [People Infer Recursive Visual Concepts from Just a Few Examples](https://link.springer.com/content/pdf/10.1007/s42113-019-00053-y.pdf) - ***Computational Brain & Behavior***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=3871396883970734141&hl=en&as_sdt=0,5)].

* [One-shot learning of generative speech concepts](https://escholarship.org/content/qt3xf2n3vc/qt3xf2n3vc.pdf) - ***CogSci'14***, 2014. [[All Versions](https://scholar.google.com/scholar?cluster=15482292457660075957&hl=en&as_sdt=0,5)].

* [Human few-shot learning of compositional instructions](https://arxiv.org/abs/1901.04587) - ***CogSci'19***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=12841163907815018136&hl=en&as_sdt=0,5)].

* [Fast and flexible: Human program induction in abstract reasoning tasks](https://arxiv.org/pdf/2103.05823.pdf) - ***CogSci'21***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=5294483826040237516&hl=en&as_sdt=0,5)].

* [Investigating Human Priors for Playing Video Games](http://proceedings.mlr.press/v80/dubey18a.html) - ***ICML'18***, 2018. [[All Versions](https://scholar.google.com/scholar?cluster=2202192690517876762&hl=en&as_sdt=0,5)].

* [Tasks for aligning human and machine planning](https://www.sciencedirect.com/science/article/pii/S2352154619300622) - ***Current Opinion in Behavioral Sciences***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=8308872468787875598&hl=en&as_sdt=0,5)].

*[Back to Top](#c)

<span id = "metacog"></span>
### Metacognition

<span id = "gestalt"></span>
#### Gestalt

* [Gestalt theory](https://psycnet.apa.org/record/2007-10344-001) - ***A source book of Gestalt psychology***, 1938. [[All Versions](https://scholar.google.com/scholar?cluster=18133275659218646817&hl=en&as_sdt=0,5)].

* [Gestalt Psychology](https://link.springer.com/article/10.1007/BF00422382) - ***Psychologische Forschung***, 1967. [[All Versions](https://scholar.google.com/scholar?cluster=16023098380090751616&hl=en&as_sdt=0,5)].

* [Restructuring revisited I. Summary and critique of the Gestalt theory of problem solving](https://onlinelibrary.wiley.com/doi/abs/10.1111/j.1467-9450.1984.tb01001.x) - ***Scandinavian Journal of Psychology***, 1984. [[All Versions](https://scholar.google.com/scholar?cluster=1540079499182933565&hl=en&as_sdt=0,5)].

* [Restructuring revisited II. An information processing theory of restructuring and insight](https://onlinelibrary.wiley.com/doi/abs/10.1111/j.1467-9450.1984.tb01005.x) - ***Scandinavian Journal of Psychology***, 1984. [[All Versions](https://scholar.google.com/scholar?cluster=1821980539002417470&hl=en&as_sdt=0,5)].

*[Back to Top](#c)

<span id = "r&r"></span>
#### Rationality & Rationalization 

* [Bounded Rationality](https://plato.stanford.edu/entries/bounded-rationality/) - ***Plato Stanford***.

* [Instrumental Rationality](https://plato.stanford.edu/entries/rationality-instrumental/) - ***Plato Stanford***.

* [Imagination and the generation of new ideas](https://www.sciencedirect.com/science/article/abs/pii/S0885201414000744) - ***Cognitive Development***, 2015. [[All Versions](https://scholar.google.com/scholar?cluster=16920774374067505248&hl=en&as_sdt=2005&sciodt=0,5)].

* [Coalescing the Vapors of Human Experience into a Viable and Meaningful Comprehension](http://web.mit.edu/maxs/www/papers/cogsci_2016_vapors.pdf) - ***CogSci'16***, 2016. [[All Versions](https://scholar.google.com/scholar?cluster=5460385008324352958&hl=en&as_sdt=2005&sciodt=0,5)].

* [How We Know What Not To Think](https://www.sciencedirect.com/science/article/pii/S1364661319302311) - ***Trends in Cognitive Sciences***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=13106919756521743226&hl=en&as_sdt=2005&sciodt=0,5)].

* [Rationalization is rational](https://www.cambridge.org/core/journals/behavioral-and-brain-sciences/article/abs/rationalization-is-rational/2A13B99ED09BD802C0924D3681FEC55B) - ***Behavioral and Brain Sciences***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=5165464589274056844&hl=en&as_sdt=2005&sciodt=0,5)].

* [Rationalizing constraints on the capacity for cognitive control](https://www.sciencedirect.com/science/article/pii/S1364661321001480) - ***Trends in Cognitive Sciences***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=13065113821339619145&hl=en&as_sdt=2005&sciodt=0,5)].

*[Back to Top](#c)

<span id = "cogarch"></span>
#### Cognitive Architecture

* [SOAR: An architecture for general intelligence](https://www.sciencedirect.com/science/article/abs/pii/0004370287900506) - ***Artificial Intelligence***, 1987. [[All Versions](https://scholar.google.com/scholar?cluster=10873259207109132615&hl=en&as_sdt=0,5)].

* [Is human cognition adaptive?](http://act-r.psy.cmu.edu/wordpress/wp-content/uploads/2013/09/Anderson91.pdf) - ***Behavioral and Brain Sciences***, 1991. [[All Versions](https://scholar.google.com/scholar?cluster=3639936076538071052&hl=en&as_sdt=0,5)].

* [Metacognition in computation: A selected research review](https://www.sciencedirect.com/science/article/pii/S0004370205001530) - ***Artificial Intelligence***, 2005. [[All Versions](https://scholar.google.com/scholar?cluster=4240334051245008914&hl=en&as_sdt=0,5)].

* [Basic functional trade-offs in cognition: An integrative framework](https://www.sciencedirect.com/science/article/pii/S0010027718301604) - ***Cognition***, 2018. [[All Versions](https://scholar.google.com/scholar?cluster=11475742130443069967&hl=en&as_sdt=0,5)].

* [What is consciousness, and could machines have it?](https://doi.org/10.1126/SCIENCE.AAN8871) - ***Science***, 2017. [[All Versions](https://scholar.google.com/scholar?cluster=6932714857132107942&hl=en&as_sdt=0,5)].

* [A Theoretical Computer Science Perspective on Consciousness](https://www.worldscientific.com/doi/abs/10.1142/S2705078521500028) - ***Journal of Artificial Intelligence and Consciousness***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=16430561748075101972&hl=en&as_sdt=0,5)].

*[Back to Top](#c)

<span id = "tom"></span>
### Theory of Mind

* [Theory of Mind](https://en.wikipedia.org/wiki/Theory_of_mind) - ***Wikipedia***.

* [Cognitive Science](https://plato.stanford.edu/entries/cognitive-science/) - ***Plato Stanford***.

* [Intentionality](https://plato.stanford.edu/entries/intentionality/) - ***Plato Stanford***.

* [Epistemology](https://plato.stanford.edu/entries/epistemology/) - ***Plato Stanford***.

* [The Mind/Brain Identity Theory](https://plato.stanford.edu/entries/mind-identity/) - ***Plato Stanford***.

* [Mental Representation](https://plato.stanford.edu/entries/mental-representation/) - ***Plato Stanford***.

* [Mental Imagery](https://plato.stanford.edu/entries/mental-imagery/) - ***Plato Stanford***.

* [Temporal Consciousness](https://plato.stanford.edu/entries/consciousness-temporal/) - ***Plato Stanford***.

* [The Experience and Perception of Time](https://plato.stanford.edu/entries/time-experience/) - ***Plato Stanford***.

* [Practical Reason](https://plato.stanford.edu/entries/practical-reason/) - ***Plato Stanford***.

* [Memory](https://plato.stanford.edu/entries/memory/) - ***Plato Stanford***.

* [The Computational Theory of Mind](https://plato.stanford.edu/entries/computational-mind/) - ***Plato Stanford***.

* [Action Understanding as Inverse Planning](https://www.sciencedirect.com/science/article/pii/S0010027709001607) - ***Cognition***, 2009. [[All Versions](https://scholar.google.com/scholar?cluster=11478704181983566675&hl=en&as_sdt=0,5)]. [[Appendix](https://ars.els-cdn.com/content/image/1-s2.0-S0010027709001607-mmc1.pdf)]. 

* [Bayesian Theory of Mind: Modeling Joint Belief-Desire Attribution](http://web.mit.edu/9.s915/www/classes/theoryOfMind.pdf) - ***CogSci'11***, 2011. [[All Versions](https://scholar.google.com/scholar?cluster=7454981153033683025&hl=en&as_sdt=0,5)].

* [Bayesian Theory of Mind : modeling human reasoning about beliefs, desires, goals, and social relations](https://dspace.mit.edu/handle/1721.1/73768) - ***Ph.D. Dissertation MIT***, 2012. [[All Versions](https://scholar.google.com/scholar?cluster=16053170661075048224&hl=en&as_sdt=0,5)].

* [The Signature of All Things: Children Infer Knowledge States from Static Images](https://psyarxiv.com/f692k/) - ***CogSci'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=12380982112592086477&hl=en&as_sdt=0,5&as_ylo=2017)].

* [Bayesian Brains without Probabilities](https://www.sciencedirect.com/science/article/pii/S1364661316301565?via%3Dihub) - ***Trends in Cognitive Sciences***, 2016. [[All Versions](https://scholar.google.com/scholar?cluster=13076510377612067772&hl=en&as_sdt=0,5)].

* [Rational quantitative attribution of beliefs, desires and percepts in human mentalizing](https://www.nature.com/articles/s41562-017-0064) - ***Nature Human Behavior***, 2017. [[All Versions](https://scholar.google.com/scholar?cluster=9377509910551057835&hl=en&as_sdt=0,5)].

* [The Bayesian Brain: An Introduction to Predictive Processing](https://www.mindcoolness.com/blog/bayesian-brain-predictive-processing/) - 2018. 

* [Machine theory of mind](http://proceedings.mlr.press/v80/rabinowitz18a/rabinowitz18a.pdf) - ***ICML'18***, 2018. [[All Versions](https://scholar.google.com/scholar?cluster=6267278380616425333&hl=en&as_sdt=0,5)].

* [Theory of mind as inverse reinforcement learning](https://www.sciencedirect.com/science/article/pii/S2352154618302055?via%3Dihub) - ***Current Opinion in Behavioral Sciences***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=14959443239271810913&hl=en&as_sdt=0,5)].

* [Computational Models of Emotion Inference in Theory of Mind: A Review and Roadmap](https://onlinelibrary.wiley.com/doi/full/10.1111/tops.12371) - ***Topics in Cognitive Science***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=15919410726494658168&hl=en&as_sdt=0,5)].

* [The Naïve Utility Calculus as a unified, quantitative framework for action understanding](https://www.sciencedirect.com/science/article/pii/S0010028520300633) - ***Cognitive Psychology***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=10366690800692546587&hl=en&as_sdt=0,5)]. [[Project](http://www.github.com/julianje/bishop)].

* [AGENT: A Benchmark for Core Psychological Reasoning](https://arxiv.org/pdf/2102.12321.pdf) - ***ICML'21***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=9729067071974484204&hl=en&as_sdt=0,5)].

* [Experimental Games and Social Decision Making](https://www.annualreviews.org/doi/pdf/10.1146/annurev-psych-081420-110718) - ***Annual Review of Psychology***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=4713510112126264116&hl=en&as_sdt=0,5)].

* [Theory of Minds: Understanding Behavior in Groups through Inverse Planning](https://www.aaai.org/ojs/index.php/AAAI/article/view/4574) - ***AAAI'19***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=6755247312077985817&hl=en&as_sdt=0,5)].

* [Leveraging Facial Expressions and Contextual Information to Investigate Opaque Representations of Emotion](https://psycnet.apa.org/fulltext/2019-58384-001.pdf?auth_token=0859666184839448b848053cd7bdceb2bdf2745a) - ***Emotion***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=9634378462684744548&hl=en&as_sdt=0,5)].

* [Waiting and weighting: Information sampling is a balance between efficiency and error-reduction](https://linkinghub.elsevier.com/retrieve/pii/S0010027712002235) - ***Cognition***, 2013. [[All Versions](https://scholar.google.com/scholar?cluster=12787722822882067638&hl=en&as_sdt=0,5)].

* [Natural scene statistics account for the representation of scene categories in human visual cortex](https://www.sciencedirect.com/science/article/pii/S0896627313005503?via%3Dihub) - ***Neuron***, 2013. [[All Versions](https://scholar.google.com/scholar?cluster=14030885492052338412&hl=en&as_sdt=0,5)].

* [Using human brain activity to guide machine learning](https://www.nature.com/articles/s41598-018-23618-6) - ***Nature: Scientific Report***, 2018. [[All Versions](https://scholar.google.com/scholar?cluster=12987955253653036948&hl=en&as_sdt=0,5)].

* [Unit of visual working memory: A Boolean map provides a better account than an object does](https://psycnet.apa.org/record/2019-27729-001) - ***Journal of Experimental Psychology***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=14909735035752892020&hl=en&as_sdt=0,5)].

* [The logic of universalization guides moral judgment](https://www.pnas.org/content/117/42/26158.short) - ***Proceedings of National Academy of Sciences***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=13482051983012049752&hl=en&as_sdt=0,5)].

* [Learning Triadic Belief Dynamics in Nonverbal Communication from Videos](https://arxiv.org/abs/2104.02841) - ***CVPR'21***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=15365483338824697316&hl=en&as_sdt=0,5)].

* [Ten-month-old infants infer the value of goals from the costs of actions](https://dspace.mit.edu/bitstream/handle/1721.1/112291/ivc_full_preprint.pdf?sequence=1&isAllowed=y) - ***Science***, 2017. [[All Versions](https://scholar.google.com/scholar?cluster=11862940312128630925&hl=en&as_sdt=0,5)].

* [Origins of the concepts cause, cost, and goal in prereaching infants](https://www.pnas.org/content/116/36/17747) - ***Proceedings of National Academy of Sciences***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=15973074852436355789&hl=en&as_sdt=0,5)].

*[Back to Top](#c)

<span id = "anl"></span>
### Analogy

* [Metaphor](https://plato.stanford.edu/entries/metaphor/) - ***Plato Stanford***.

* [Analogy and Analogical Reasoning](https://plato.stanford.edu/entries/reasoning-analogy/#:~:text=Analogical%20reasoning%20is%20any%20type%20of%20thinking%20that,support%20the%20conclusion%20that%20some%20further%20similarity%20exists.) - ***Plato Stanford***.

* [A Cognitive Theory of Metaphor](https://1lib.net/book/1165963/e9aa3d) - ***MIT Press***, 1985. [[All Versions](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=a+cognitive+theory+of+metaphor&btnG=)].

* [The structure-mapping engine: Algorithm and examples](https://www.sciencedirect.com/science/article/abs/pii/0004370289900775) - ***Artificial Intelligence***, 1989. [[All Versions](https://scholar.google.com/scholar?cluster=16104901325436513899&hl=en&as_sdt=0,5)].

* [Generalize and Blend: Concept Blending Based on Generalization, Analogy, and Amalgams](https://www.iiia.csic.es/~enric/papers/generalize_and_blend.pdf) - ***ICCC'15***, 2015. [[All Versions](https://scholar.google.com/scholar?cluster=11073359237116879862&hl=en&as_sdt=0,5)].

* [Analogy-preserving Semantic Embedding for Visual Object Categorization](http://proceedings.mlr.press/v28/juhwang13.pdf) - ***ICML'13***, 2013. [[All Versions](https://scholar.google.com/scholar?cluster=9332855910734484101&hl=en&as_sdt=0,5)].

* [VISALOGY: Answering Visual Analogy Questions](https://proceedings.neurips.cc/paper/2015/file/45f31d16b1058d586fc3be7207b58053-Paper.pdf) - ***NIPS'15***, 2015. [[All Versions](https://scholar.google.com/scholar?cluster=7665427758655324654&hl=en&as_sdt=0,5)].

* [Detecting Unseen Visual Relations Using Analogies](https://ieeexplore.ieee.org/document/9010418) - ***CVPR'19***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=16686853801653819556&hl=en&as_sdt=0,5)].

* [Analogy between concepts](https://www.sciencedirect.com/science/article/pii/S0004370218301863) - ***Artificial Intelligence***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=1397905953174123757&hl=en&as_sdt=0,5)].

* [Learning to Make Analogies by Contrasting Abstract Relational Structure](https://arxiv.org/abs/1902.00120) - ***ICLR'19***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=15521573039503233138&hl=en&as_sdt=0,5)].

* [Sky + Fire = Sunset. Exploring Parallels between Visually Grounded Metaphors and Image Classifiers](https://aclanthology.org/2020.figlang-1.pdf#page=140) - ***ACL'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=5747285277687442001&hl=en&as_sdt=0,5)].

* [Analogy as Nonparametric Bayesian Inference over Relational Systems](https://arxiv.org/pdf/2006.04156.pdf) - ***CogSci'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=1798148167130120057&hl=en&as_sdt=0,5)].

*[Back to Top](#c)

<span id = "caus"></span>
### Causality

* [Causality](https://en.wikipedia.org/wiki/Causality) - ***Wikipedia***.

* [Causal Models](https://plato.stanford.edu/entries/causal-models/) - ***Plato Stanford***.

* [Causal Theories of Mental Content](https://plato.stanford.edu/entries/content-causal/) - ***Plato Stanford***.

* [Causal Reasoning](https://www.oxfordhandbooks.com/view/10.1093/oxfordhb/9780195376746.001.0001/oxfordhb-9780195376746-e-46) - ***The Oxford Handbook of Cognitive Psychology***, 2013. [[All Versions](https://scholar.google.com/scholar?cluster=11361740093816709089&hl=en&as_sdt=0,5)].

* [The Seven Tools of Causal Inference, with Reflections on Machine Learning](https://dl.acm.org/doi/pdf/10.1145/3241036) - ***Communication of the ACM***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=13296019510897277617&hl=en&as_sdt=0,5)].

* [Theory-Based Causal Induction](https://cocosci.princeton.edu/tom/papers/tbci.pdf) - ***Psychological Review***, 2009. [[All Versions](https://scholar.google.com/scholar?cluster=13980129728092173387&hl=en&as_sdt=0,5)].

* [Theory-Based Causal Transfer: Integrating Instance-Level Induction and Abstract-Level Structure Learning](https://ojs.aaai.org//index.php/AAAI/article/view/5483) - ***AAAI'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=9411622427165139667&hl=en&as_sdt=0,5)].

* [Do New Caledonian crows solve physical problems through causal reasoning?](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.183.4674&rep=rep1&type=pdf) - ***Proceedings of the Royal Society B: Biological Sciences***, 2009. [[All Versions](https://scholar.google.com/scholar?cluster=18374985546068164189&hl=en&as_sdt=0,5)].

* [Inferring causal networks from observations and interventions](https://onlinelibrary.wiley.com/doi/abs/10.1207/s15516709cog2703_6) - ***Cognitive Science***, 2010. [[All Versions](https://scholar.google.com/scholar?cluster=12050301037347772984&hl=en&as_sdt=2005&sciodt=0,5)].

* [A Language for Counterfactual Generative Models](http://proceedings.mlr.press/v139/tavares21a.html) - ***ICML'21***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=11606362305211066214&hl=en&as_sdt=0,5)].

* [Constraints on Hypothesis Selection in Causal Learning](https://cogsci.mindmodeling.org/2015/papers/0418/paper0418.pdf) - ***CogSci'15***, 2015. [[All Versions](https://scholar.google.com/scholar?hl=en&as_sdt=2005&sciodt=0%2C5&cites=16920774374067505248&scipsc=&q=Constraints+on+hypothesis+selection+in+causal+learning&btnG=)].

* [What happened? Reconstructing the past through vision and sound](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=d0TfP8EAAAAJ&sortby=pubdate&citation_for_view=d0TfP8EAAAAJ:S16KYo8Pm5AC) - 2021. [[All Versions](https://scholar.google.com/scholar?oi=bibs&hl=en&cluster=12975579257004398798)].

* [How do people generalize causal relations over objects? A non-parametric Bayesian account](https://psyarxiv.com/x57hf/) - 2021. [[All Versions](https://scholar.google.com/scholar?cluster=9078127785707706032&hl=en&as_sdt=0,5)].

*[Back to Top](#c)

<span id = "cms"></span>
### Commonsense

* [Towards a theory of commonsense visual reasoning](https://link.springer.com/chapter/10.1007%2F3-540-53487-3_59) - ***FSTTCS***, 1990. [[All Versions](https://scholar.google.com/scholar?cluster=13178231862265713961&hl=en&as_sdt=0,5)].

* [From Recognition to Cognition: Visual Commonsense Reasoning](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8953217) - ***CVPR'19***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=15467433880059136365&hl=en&as_sdt=0,5)]. [[Project](http://visualcommonsense.com/)].

* [PIQA: Reasoning about Physical Commonsense in Natural Language](https://arxiv.org/pdf/1911.11641.pdf) - ***AAAI'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=10110424163152713144&hl=en&as_sdt=0,5)].

* [Visual Commonsense R-CNN](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9156347) - ***CVPR'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=6886229776034162585&hl=en&as_sdt=0,5)].

* [Abductive Commonsense Reasoning](https://openreview.net/pdf?id=Byg1v1HKDB) - ***ICLR'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=16544200144479839958&hl=en&as_sdt=0,5)].

* [VisualCOMET: Reasoning About the Dynamic Context of a Still Image](https://link.springer.com/chapter/10.1007%2F978-3-030-58558-7_30) - ***ECCV'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=7681600847940772451&hl=en&as_sdt=0,5)].

* [Intentonomy: a Dataset and Study towards Human Intent Understanding](https://arxiv.org/pdf/2011.05558.pdf) - ***CVPR'21***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=5268870345003195142&hl=en&as_sdt=0,5)].

* [Experience Grounds Language](https://aclanthology.org/2020.emnlp-main.703.pdf) - ***EMNLP'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=3734668471751920487&hl=en&as_sdt=0,5)].

*[Back to Top](#c)

<span id = "lp"></span>
### Inductive Logic & Program Synthesis

* [Inductive Logic](https://plato.stanford.edu/entries/logic-inductive/) - ***Plato Stanford***.

* [First-order Model Theory](https://plato.stanford.edu/entries/modeltheory-fo/) - ***Plato Stanford***.

* [Paraconsistent Logic](https://plato.stanford.edu/entries/logic-paraconsistent/) - ***Plato Stanford***.

* [Logical Consequence](https://plato.stanford.edu/entries/logical-consequence/) - ***Plato Stanford***.

* [Logic Pluralism](https://plato.stanford.edu/entries/logical-pluralism/) - ***Plato Stanford***.

* [The Emergence of First-Order Logic](https://plato.stanford.edu/entries/logic-firstorder-emergence/) - ***Plato Stanford***.

* [Second-order and Higher-order Logic](https://plato.stanford.edu/entries/logic-higher-order/) - ***Plato Stanford***.

* [Program Synthesis](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/10/program_synthesis_now.pdf) - ***Foundations and Trends in Programming Languages***, 2017. [[All Versions](https://scholar.google.com/scholar?cluster=5442933587668978421&hl=en&as_sdt=0,5)].

* [Towards combining inductive logic programming with Bayesian networks](https://link.springer.com/chapter/10.1007%2F3-540-44797-0_10) - ***ILP'01***, 2001. [[All Versions](https://scholar.google.com/scholar?cluster=2904180673047700407&hl=en&as_sdt=0,5)].

* [Meta-interpretive learning: application to grammatical inference](https://link.springer.com/article/10.1007/s10994-013-5358-3) - ***Machine Learning***, 2014. [[All Versions](https://scholar.google.com/scholar?cluster=17075313112718885592&hl=en&as_sdt=0,5)].

* [Learning Efficient Logical Robot Strategies Involving Composable Objects](http://andrewcropper.com/pubs/ijcai15-metagolo.pdf) - ***IJCAI'15***, 2015. [[All Versions](https://scholar.google.com/scholar?cluster=5109851972354087162&hl=en&as_sdt=0,5)].

* [Learning Higher-Order Logic Programs through Abstraction and Invention](http://andrewcropper.com/pubs/ijcai16-metafunc.pdf) - ***IJCAI'16***, 2016. [[All Versions](https://scholar.google.com/scholar?cluster=10945054943203858325&hl=en&as_sdt=0,5)].

* [How Much Can Experimental Cost Be Reduced in Active Learning of Agent Strategies?](https://link.springer.com/chapter/10.1007%2F978-3-319-99960-9_3) - ***ILP'18***, 2018. [[All Versions](https://scholar.google.com/scholar?cluster=8152380236842970357&hl=en&as_sdt=0,5)].

* [Meta-Interpretive Learning from noisy images](https://link.springer.com/article/10.1007/s10994-018-5710-8) - ***Machine Learning***, 2018. [[All Versions](https://scholar.google.com/scholar?cluster=5719375383968868329&hl=en&as_sdt=0,5)].

* [Learning efficient logic programs](http://andrewcropper.com/pubs/mlj18-metaopt.pdf) - ***Machine Learning***, 2018. [[All Versions](https://scholar.google.com/scholar?cluster=17955696870252443734&hl=en&as_sdt=0,5)].

* [Learning higher-order logic programs](http://andrewcropper.com/pubs/mlj19-metaho.pdf) - ***Machine Learning***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=6723896359456002413&hl=en&as_sdt=0,5)].

* [Logical reduction of metarules](http://andrewcropper.com/pubs/mlj19-reduce.pdf) - ***Machine Learning***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=4577603126537024540&hl=en&as_sdt=0,5)].

* [Playgol: Learning Programs Through Play](http://andrewcropper.com/pubs/ijcai19-playgol.pdf) - ***IJCAI'19***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=556522464212000763&hl=en&as_sdt=0,5)].

* [Machine Discovery of Comprehensible Strategies for Simple Games Using Meta-interpretive Learning](https://link.springer.com/article/10.1007%2Fs00354-019-00054-2) - ***New Generation Computing***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=11019349634035542991&hl=en&as_sdt=0,5)].

* [Forgetting to Learn Logic Programs](http://andrewcropper.com/pubs/aaai20-forgetgol.pdf) - ***AAAI'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=13676986733133377042&hl=en&as_sdt=0,5)].

* [Turning 30: New Ideas in Inductive Logic Programming](https://www.ijcai.org/proceedings/2020/673) - ***IJCAI'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=17980870844719684257&hl=en&as_sdt=0,5)].

* [Inductive logic programming at 30: a new introduction](https://arxiv.org/abs/2008.07912) - ***Journal of Artificial Intelligence Research***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=317114056670544302&hl=en&as_sdt=0,5)].

* [Learning programs by learning from failures](https://arxiv.org/pdf/2005.02259.pdf) - ***Machine Learning***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=6797200487935462023&hl=en&as_sdt=0,5)].

* [Complete Bottom-Up Predicate Invention in Meta-Interpretive Learning](https://www.ijcai.org/proceedings/2020/320) - ***IJCAI'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=6085183078630665234&hl=en&as_sdt=0,5)].

* [Meta-Interpretive Learning as Metarule Specialisation](https://arxiv.org/pdf/2106.07464.pdf) - ***Machine Learning***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=14684315775211086859&hl=en&as_sdt=0,5)].

* [Qualitative choice logic](https://www.sciencedirect.com/science/article/pii/S0004370204000591) - ***Artificial Intelligence***, 2004. [[All Versions](https://scholar.google.com/scholar?cluster=1586187056162326386&hl=en&as_sdt=0,5)]

* [Derivative-free optimization of high-dimensional non-convex functions by sequential random embeddings](https://www.ijcai.org/Proceedings/16/Papers/278.pdf) - ***IJCAI'16***, 2016. [[All Versions](https://scholar.google.com/scholar?cluster=15955040483290586781&hl=en&as_sdt=0,5)].

* [Finitely Generated Groups and First-Order Logic](https://londmathsoc.onlinelibrary.wiley.com/doi/abs/10.1112/S0024610704006106) - ***Journal of The London Mathematical Society-second Series***, 2005. [[All Versions](https://scholar.google.com/scholar?cluster=3457158221419711506&hl=en&as_sdt=0,5)].

* [DreamCoder: Growing generalizable, interpretable knowledge with wake-sleep Bayesian program learning](https://arxiv.org/abs/2006.08381) - 2020. [[All Versions](https://scholar.google.com/scholar?cluster=3288385399148303844&hl=en&as_sdt=0,5)].

* [Leveraging Language for Abstraction and Program Search](https://vigilworkshop.github.io/static/papers-2021/25.pdf) - ***ICML'20***, 2020. [[All Versions](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Leveraging+Language+for+Abstraction+and+Program+Search&btnG=)].

* [Program Synthesis Guided Reinforcement Learning](https://arxiv.org/abs/2102.11137) - 2021. [[All Versions](https://scholar.google.com/scholar?cluster=17353674428642875269&hl=en&as_sdt=0,5)].

* [Learning Part-Based Abstractions for Visual Object Concepts](https://cogtoolslab.github.io/pdf/wang_cogsci_2021a.pdf) - ***CogSci'21***, 2021. [[All Versions](https://scholar.google.com/scholar?lookup=0&q=Learning+Part-Based+Abstractions+for+Visual+Object+Concepts&hl=en&as_sdt=0,5)].

*[Back to Top](#c)

<span id = "kr"></span>
### Knowledge Representation

* [Handbook of Knowledge Representation](https://1lib.net/book/511192/9eab86) - ***Elsevier***, 2008. [[All Versions](https://scholar.google.com/scholar?cluster=14732064619564679879&hl=en&as_sdt=0,5)].

* [Logic and Ontology](https://plato.stanford.edu/entries/logic-ontology/) - ***Plato Stanford***.

* [The Language of Thought Hypothesis](https://plato.stanford.edu/entries/language-thought/) - ***Plato Stanford***.

* [The Analysis of Knowledge](https://plato.stanford.edu/entries/knowledge-analysis/) - ***Plato Stanford***.

* [Scientific Representation](https://plato.stanford.edu/entries/scientific-representation/) - ***Plato Stanford***.

* [Self-Knowledge](https://plato.stanford.edu/entries/self-knowledge/) - ***Plato Stanford***.

* [Common Knowledge](https://plato.stanford.edu/entries/common-knowledge/) - ***Plato Stanford***.

* [Sense-Data](https://plato.stanford.edu/entries/sense-data/) - ***Plato Stanford***.

* [Supervenience](https://plato.stanford.edu/entries/supervenience/) - ***Plato Stanford***.

* [Dialogical Logic](https://plato.stanford.edu/entries/logic-dialogical/) - ***Plato Stanford***.

* [Temporal Logic](https://plato.stanford.edu/entries/logic-temporal/) - ***Plato Stanford***.

* [Situation Calculus](https://en.wikipedia.org/wiki/Situation_calculus) - ***Wikipedia***.

* [Modal Logic](https://plato.stanford.edu/entries/logic-modal/) - ***Plato Stanford***.

* [Epistemic Logic](https://plato.stanford.edu/entries/logic-epistemic/) - ***Plato Stanford***.

* [Epistemic Modal Logic](https://en.wikipedia.org/wiki/Epistemic_modal_logic) - ***Wikipedia***.

* [Commonsense reasoning about causality: Deriving behavior from structure](https://www.sciencedirect.com/science/article/abs/pii/0004370284900390) - ***Artificial Intelligence***, 1984. [[All Versions](https://scholar.google.com/scholar?oi=bibs&hl=en&cluster=14940738362673077704)].

* [Qualitative Simulation](https://www.cs.utexas.edu/ftp/qsim/papers/Kuipers-aij-86.pdf) - ***Artificial Intelligence***, 1986. [[All Versions](https://scholar.google.com/scholar?cluster=4945009733425184345&hl=en&as_sdt=0,5)].

* [Qualitative Reasoning: Modeling and Simulation with Incomplete Knowledge](https://www.cs.utexas.edu/users/qr/QR-book.html) - ***MIT Press***, 1994. [[All Versions](https://scholar.google.com/scholar?oi=bibs&hl=en&cluster=6634684154722677465)].

* [Logics for Epistemic Programs](https://link.springer.com/article/10.1023/B:SYNT.0000024912.56773.5e) - ***Synthese***, 2004. [[All Versions](https://scholar.google.com/scholar?cluster=11403619699670839488&hl=en&as_sdt=0,5&as_vis=1)].

* [A Translation Approach to Portable Ontology Specifications](https://tomgruber.org/writing/ontolingua-kaj-1993.pdf) - ***Knowledge Acquisition***, 1993. [[All Versions](https://scholar.google.com/scholar?cluster=14668658395073605123&hl=en&as_sdt=0,5)].

* [Answer Set Programming](http://people.sabanciuniv.edu/~esraerdem/teaching/krr06/asp.pdf) - ***ICLPNR'99***, 1999. [[All Versions](https://scholar.google.com/scholar?cluster=15267370435063454675&hl=en&as_sdt=0,5)].

* [Action Languages, Answer Sets, and Planning](https://link.springer.com/chapter/10.1007%2F978-3-642-60085-2_16) - ***The Logic Programming Paradigms***, 1999. [[All Versions](https://scholar.google.com/scholar?cluster=2045126541850245645&hl=en&as_sdt=0,5)].

* [The Symbolic Grounding Problem](http://www.cs.ox.ac.uk/activities/ieg/e-library/sources/harnad90_sgproblem.pdf) - ***Physica D: Nonlinear Phenomena***, 1990. [[All Versions](https://scholar.google.com/scholar?cluster=6279614024681929496&hl=en&as_sdt=0,5)].

* [Learning overhypotheses with hierarchical Bayesian models](https://onlinelibrary.wiley.com/doi/abs/10.1111/j.1467-7687.2007.00585.x?__cf_chl_captcha_tk__=pmd_Q6xVT1AstoEUxA7xS3_10HyDVsk8W_DzWgOPho_Njnw-1635210931-0-gqNtZGzNA1CjcnBszQvl) - ***Developmental Science***, 2007. [[All Versions](https://scholar.google.com/scholar?cluster=18041836774924845900&hl=en&as_sdt=0,5)].

* [Learning Causal Schemata](https://escholarship.org/content/qt19v2r2ws/qt19v2r2ws.pdf) - ***CogSci'07***, 2007, [[All Versions](https://scholar.google.com/scholar?cluster=5008191267417189643&hl=en&as_sdt=0,5)].

* [The discovery of structural form](https://www.pnas.org/content/105/31/10687) - ***Proceedings of National Academy of Sciences***, 2008. [[All Versions](https://scholar.google.com/scholar?cluster=10433149156915110486&hl=en&as_sdt=0,5)].

* [A Rational Analysis of Rule-Based Concept Learning](https://onlinelibrary.wiley.com/doi/full/10.1080/03640210701802071) - ***Cognitive Science***, 2008. [[All Versions](https://scholar.google.com/scholar?cluster=7765061503727822620&hl=en&as_sdt=0,5)].

* [Modeling semantic cognition as logical dimensionality reduction](https://escholarship.org/content/qt50r1c7qh/qt50r1c7qh.pdf) - ***CogSci'08***, 2008. [[All Versions](https://scholar.google.com/scholar?cluster=17061801746839695691&hl=en&as_sdt=0,5)].

* [Theory Acquisition and the Language of Thought](http://www.charleskemp.com/papers/KempGT08.pdf) - ***CogSci'08***, 2008. [[All Versions](https://scholar.google.com/scholar?cluster=1839916602381147749&hl=en&as_sdt=0,5)].

* [Theory Acquisition as Stochastic Search](http://web.mit.edu/tomeru/www/papers/tlss2010.pdf) - ***CogSci'10***, 2010. [[All Versions](https://scholar.google.com/scholar?cluster=16324634056226561429&hl=en&as_sdt=0,5)].

* [A probabilistic model of theory formation](http://www.charleskemp.com/papers/kemptng09.pdf) - ***Cognition***, 2010. [[All Versions](https://scholar.google.com/scholar?cluster=7705799129887482041&hl=en&as_sdt=0,5)].

* [Bootstrapping in a language of thought: A formal model of numerical concept learning](https://core.ac.uk/display/78064072) - ***Cognition***, 2012. [[All Versions](https://scholar.google.com/scholar?cluster=13046606910781656302&hl=en&as_sdt=0,5)].

* [Exploring the Conceptual Universe](http://www.charleskemp.com/papers/kemp_exploringtheconceptualuniverse.pdf) - ***Psychological Review***, 2012. [[All Versions](https://scholar.google.com/scholar?cluster=17824067813343816306&hl=en&as_sdt=0,5)].

* [A taxonomy of inductive problems](http://www.charleskemp.com/papers/kempj_ataxonomyofinductiveproblems.pdf) - ***Psychonomic Bulletin & Review***, 2014. [[All Versions](https://scholar.google.com/scholar?cluster=2571009743105592927&hl=en&as_sdt=0,5)].

* [The Logical Primitives of Thought: Empirical Foundations for Compositional Cognitive Models](http://colala.berkeley.edu/papers/piantadosi2016logical.pdf) - ***Psychological Review***, 2016. [[All Versions](https://scholar.google.com/scholar?cluster=5316027496661813145&hl=en&as_sdt=0,5)].

* [The Emergence of Organizing Structure in Conceptual Representation](https://onlinelibrary.wiley.com/doi/full/10.1111/cogs.12580) - ***Cognitive Science***, 2018. [[All Versions](https://scholar.google.com/scholar?cluster=4986316323923233074&hl=en&as_sdt=0,5)].

* [Theory Acquisition as Constraint-Based Program Synthesis](https://cogtoolslab.github.io/pdf/wang_cogsci_2021b.pdf) - ***CogSci'21***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=525148607069840280&hl=en&as_sdt=0,5)].

* [Connecting perceptual and procedural abstractions in physical construction](https://escholarship.org/uc/item/9j00x928) - ***CogSci'21***, 2021. [[All Versions](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Connecting+perceptual+and+procedural+abstractions+in+physical+construction&btnG=)].

* [Invariant representation of physical stability in the human brain](https://www.biorxiv.org/content/10.1101/2021.03.19.385641v1.full.pdf) - 2021. [[All Versions](https://scholar.google.com/scholar?cluster=17431019238600295521&hl=en&as_sdt=0,5)].

* [Introduction to The Fluent Calculus](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.146.4086&rep=rep1&type=pdf) - ***Linkoeping University Electronic Press***, 1998. [[All Versions](https://scholar.google.com/scholar?cluster=12069059079023496731&hl=en&as_sdt=0,5)].

* [From situation calculus to fluent calculus: State update axioms as a solution to the inferential frame problem](https://www.sciencedirect.com/science/article/pii/S0004370299000338) - ***Artificial Intelligence***, 1999. [[All Versions](https://scholar.google.com/scholar?cluster=10854895617698839149&hl=en&as_sdt=0,5)].

* [Unsupervised Structure Learning of Stochastic And-Or Grammars](http://www.stat.ucla.edu/~sczhu/papers/Conf_2013/Learning_AoG_NIPS_2013.pdf) - ***NIPS'13***, 2013. [[All Versions](https://scholar.google.com/scholar?oi=bibs&hl=en&cluster=4354984630817844670)].

* [Algorithms of Adaptation in Inductive Inference](https://psyarxiv.com/ysndt) - 2021. [[All Versions](https://scholar.google.com/scholar?cluster=16222039361294164246&hl=en&as_sdt=0,5)].

* [A representational analysis of numeration systems](https://www.sciencedirect.com/science/article/pii/0010027795006743) - ***Cognition***, 1995. [[All Versions](https://scholar.google.com/scholar?oi=bibs&hl=en&cluster=8852566070856662412)].

*[Back to Top](#c)

<span id = "cogdev"></span>
### Cognitive Development

* [Machine Common Sense Concept Paper](https://arxiv.org/pdf/2109.11082.pdf) - ***DARPA***, 2018. [[All Versions](https://scholar.google.com/scholar?cluster=1603121108181262769&hl=en&as_sdt=0,5)].

* [Cognitive Development](https://en.wikipedia.org/wiki/Cognitive_development) - ***Wikipedia***.

* [Cognitive development: An information processing approach](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Cognitive+Development%3A+an+information+processing+approach&btnG=) - ***B.Blackwell***, 1991. [[All Versions](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Cognitive+development%3A+An+information+processing+approach&btnG=)].

* [Reconstructing constructivism: Causal models, Bayesian learning mechanisms, and the theory theory](https://psycnet.apa.org/record/2012-12791-001) - ***Psychological Bulletin***, 2012. [[All Versions](https://scholar.google.com/scholar?cluster=11218217347365817167&hl=en&as_sdt=0,5)].

* [Towards a rational constructivist theory of cognitive development](https://doi.apa.org/doiLanding?doi=10.1037/rev0000153) - ***Psychological Review***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=3294824172745724080&hl=en&as_sdt=0,5)].

* [From exploration to play: A cross-sectional study of infant free play behavior](https://psycnet.apa.org/record/1981-32566-001) - ***Developmental Psychology***, 1981. [[All Versions](https://scholar.google.com/scholar?cluster=15547331535034599545&hl=en&as_sdt=0,5)].

* [Detecting Blickets: How Young Children Use Information about Novel Causal Powers in Categorization and Induction](https://srcd.onlinelibrary.wiley.com/doi/abs/10.1111/1467-8624.00224) - ***Children Development***, 2003. [[All Versions](https://scholar.google.com/scholar?cluster=9049737233568227380&hl=en&as_sdt=0,5)].

* [Serious fun: Preschoolers engage in more exploratory play when evidence is confounded](http://eccl.scripts.mit.edu/papers/bonawitzandschulzseriousfun.pdf) - ***Developmental Psychology***, 2007. [[All Versions](https://scholar.google.com/scholar?cluster=3033619407322882147&hl=en&as_sdt=0,5)].

* [Word, thought, and deed: the role of object categories in children's inductive inferences and exploratory play](https://psycnet.apa.org/record/2008-12114-008) - ***Developmental Psychology***, 2009. [[All Versions](https://scholar.google.com/scholar?cluster=13947689064550390312&hl=en&as_sdt=0,5)].

* [Where science starts: Spontaneous experiments in preschoolers' exploratory play](https://www.sciencedirect.com/science/article/pii/S0010027711000916) - ***Cognition***, 2011. [[All Versions](https://scholar.google.com/scholar?oi=bibs&hl=en&cluster=16321989770180281706)].

* [Scientific thinking in young children: Theoretical advances, empirical research, and policy implications](http://alisongopnik.com/Papers_Alison/Scientific%20Thinking%20in%20young%20Children.pdf) - ***Science***, 2012. [[All Versions](https://scholar.google.com/scholar?cluster=9103846738385460508&hl=en&as_sdt=2005)].

* [The origins of inquiry: inductive inference and exploration in early childhood](https://www.sciencedirect.com/science/article/pii/S1364661312001301) - ***Trends in Cognitive Sciences***, 2012. [[All Versions](https://scholar.google.com/scholar?cluster=5189329081728071335&hl=en&as_sdt=0,5)].

* [Finding New Facts; Thinking New Thoughts](http://eccl.scripts.mit.edu/papers/Finding%20New%20Facts_%20Thinking%20New%20Thoughts.pdf) - ***Advances in Child Development and Behavior***, 2012. [[All Versions](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Finding+new+facts%3B+thinking+new+thoughts&btnG=)]. 

* [Theory learning as stochastic search in the language of thought](https://www.sciencedirect.com/science/article/pii/S0885201412000445) - ***Cognitive Development***, 2012. [[All Versions](https://scholar.google.com/scholar?cluster=8036476579458645432&hl=en&as_sdt=0,5)].

* [Infants make more attempts to achieve a goal when they see adults persist](https://www.science.org/doi/abs/10.1126/science.aan2317) - ***Science***, 2017. [[All Versions](https://scholar.google.com/scholar?cluster=2617011825272996810&hl=en&as_sdt=0,5)].

* [Knowing when to quit: Children consider access to solutions when deciding whether to persist](https://cognitivesciencesociety.org/cogsci20/papers/0716/0716.pdf) - ***CogSci'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=15997297570269958414&hl=en&as_sdt=2005&sciodt=0,5)].

* [Bayesian Models of Conceptual Development: Learning as Building Models of the World](https://psyarxiv.com/aq3rp/) - ***Annual Review of Developmental Psychology***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=646614032563248495&hl=en&as_sdt=2005&sciodt=0,5)].

* [Sticking to the Evidence? A Behavioral and Computational Case Study of Micro-Theory Change in the Domain of Magnetism](https://onlinelibrary.wiley.com/doi/full/10.1111/cogs.12765) - ***Cognitive Science***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=4409900195679222965&hl=en&as_sdt=2005&sciodt=0,5)].

* [Cognitive pragmatism: Children flexibly choose between facts and conjectures](https://junyichu.mit.edu/sites/default/files/documents/2018-05-14%20CogSci%20Final.pdf) - ***CogSci'18***, 2018. [[All Versions](https://scholar.google.com/scholar?cluster=6978944437676543728&hl=en&as_sdt=2005&sciodt=0,5)].

* [Exploratory play, rational action, and efficient search](https://psyarxiv.com/9yra2/) - ***CogSci'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=17529638197045429028&hl=en&as_sdt=0,5)].

* [Children selectively endorse speculative conjectures](https://srcd.onlinelibrary.wiley.com/doi/full/10.1111/cdev.13647?saml_referrer) - ***Child Development***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=5672344544260882286&hl=en&as_sdt=2005&sciodt=0,5)].

* [Play, Curiosity, and Cognition](https://www.annualreviews.org/doi/abs/10.1146/annurev-devpsych-070120-014806) - ***Annual Review of Developmental Psychology***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=10278208468154249192&hl=en&as_sdt=2005&sciodt=0,5)].

* [Explore, Exploit, Create: Inventing goals in play](https://escholarship.org/uc/item/3rt5512s) - ***CogSci'21***, 2021. [[All Versions](https://scholar.google.com/scholar?oi=bibs&hl=en&cluster=8024407177006571407)].

* [Learning higher-order generalizations through free play: Evidence from 2- and 3-year-old children](https://psycnet.apa.org/buy/2017-12497-003) - ***Developmental Psychology***, 2017. [[All Versions](https://scholar.google.com/scholar?cluster=4386474921214936914&hl=en&as_sdt=0,5)].

* [The Child as Hacker](https://www.sciencedirect.com/science/article/abs/pii/S1364661320301741) - ***Trends in Cognitive Sciences***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=13128656954836679743&hl=en&as_sdt=2005&sciodt=0,5&as_ylo=2017)].

* [Childhood as a solution to explore–exploit tensions](https://royalsocietypublishing.org/doi/10.1098/rstb.2019.0502) - ***Philosophical Transactions of the Royal Society B: Biological Sciences***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=11960188575664977017&hl=en&as_sdt=2005&sciodt=0,5)].

* [Children's exploratory play tracks the discriminability of hypotheses](https://www.nature.com/articles/s41467-021-23431-2) - ***Nature Communications***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=12389351553206792907&hl=en&as_sdt=0,5&as_ylo=2020)].

* [A Developmental Perspective on Executive Function](https://srcd.onlinelibrary.wiley.com/doi/full/10.1111/j.1467-8624.2010.01499.x?saml_referrer) - ***Child Development***, 2010. [[All Versions](https://scholar.google.com/scholar?cluster=11347590808138984649&hl=en&as_sdt=0,5)].

* [Rethinking Executive Function and Its Development](https://journals.sagepub.com/doi/pdf/10.1177/1745691620904771) - ***Psychological Science***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=16570230278367237499&hl=en&as_sdt=2005&sciodt=0,5)].

*[Back to Top](#c)

<span id = "ow"></span>
### Learning in the Open World

* [Online learning of symbolic concepts](https://www.sciencedirect.com/science/article/abs/pii/S002224961730010X) - ***Journal of Mathematical Psychology***, 2017. [[All Versions](https://scholar.google.com/scholar?start=20&hl=en&as_sdt=2005&sciodt=0,5&cites=8036476579458645432&scipsc=)].

* [Zero-Shot Learning—A Comprehensive Evaluation of the Good, the Bad and the Ugly](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8413121) - ***Trans. PAMI***, 2018. [[All Versions](https://scholar.google.com/scholar?cluster=11909080239486864961&hl=en&as_sdt=0,5)].

* [Towards Open World Recognition](https://ieeexplore.ieee.org/document/7298799) - ***CVPR'15***, 2015. [[All Versions](https://scholar.google.com/scholar?cluster=856704237994181529&hl=en&as_sdt=0,5)]. 

* [Towards Open Set Deep Networks](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7780542) - ***CVPR'16***, 2016. [[All Versions](https://scholar.google.com/scholar?cluster=3571743951915089896&hl=en&as_sdt=0,5)].

* [In the Wild: From ML Models to Pragmatic ML Systems](https://arxiv.org/pdf/2007.02519.pdf) - ***ICLR'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=15243890330014986346&hl=en&as_sdt=0,5)].

* [Adversarial Filters of Dataset Biases](https://arxiv.org/pdf/2002.04108.pdf) - ***ICML'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=11617966867048191189&hl=en&as_sdt=0,5)].

* [A Wholistic View of Continual Learning with Deep Neural Networks: Forgotten Lessons and the Bridge to Active and Open World Learning](https://arxiv.org/pdf/2009.01797.pdf) - 2020. [[All Versions](https://scholar.google.com/scholar?cluster=2640432662088551010&hl=en&as_sdt=0,5)].

* [Energy-Based Models for Continual Learning](https://arxiv.org/pdf/2011.12216.pdf) - ***NIPS'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=7094884707139778576&hl=en&as_sdt=0,5)]. [[Project](https://energy-based-model.github.io/Energy-Based-Models-for-Continual-Learning/)].

* [Learning to Learn Image Classifiers with Visual Analogy](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhou_Learning_to_Learn_Image_Classifiers_With_Visual_Analogy_CVPR_2019_paper.pdf) - ***CVPR'18***, 2018. [[All Versions](https://scholar.google.com/scholar?cluster=6285495755337309034&hl=en&as_sdt=0,5)].

* [Zero-Shot Object Detection](https://arxiv.org/pdf/1804.04340v2.pdf) - ***ECCV'18***, 2018. [[All Versions](https://scholar.google.com/scholar?cluster=2027060030559987993&hl=en&as_sdt=0,5)].

* [Towards Open World Object Detection](https://arxiv.org/pdf/2103.02603v1.pdf) - ***CVPR'21***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=9715328489246217151&hl=en&as_sdt=0,5)]. [[Project](https://github.com/JosephKJ/OWOD)].

* [Learning to Recognise Unseen Classes by A Few Similes](https://dl.acm.org/doi/pdf/10.1145/3123266.3123323) - ***MM'17***, 2017. [[All Versions](https://scholar.google.com/scholar?q=related:FZZr2BK0U6YJ:scholar.google.com/&scioq=Learning+to+Recognise+Unseen+Classes+by+A+Few+Similes&hl=en&as_sdt=0,5)].

* [Ontology-guided Semantic Composition for Zero-Shot Learning](https://proceedings.kr.org/2020/87/kr2020-0087-chen-et-al.pdf) - ***KR'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=1825132732653262003&hl=en&as_sdt=0,5&scioq=Learning+to+Recognise+Unseen+Classes+by+A+Few+Similes)].

* [OntoZSL: Ontology-enhanced Zero-shot Learning](https://arxiv.org/pdf/2102.07339.pdf) - ***WWW'21***, 2021. [[All Versions](https://scholar.google.com/scholar?cluster=1042573079110416209&hl=en&as_sdt=0,5&scioq=Learning+to+Recognise+Unseen+Classes+by+A+Few+Similes)].

* [Knowledge-aware Zero-Shot Learning: Survey and Perspective](https://arxiv.org/abs/2103.00070) - ***IJCAI'21*** 2021. [[All Versions](https://scholar.google.com/scholar?cluster=2596179801089642923&hl=en&as_sdt=0,5&scioq=Learning+to+Recognise+Unseen+Classes+by+A+Few+Similes)].

* [From Red Wine to Red Tomato: Composition with Context](https://ieeexplore.ieee.org/document/8099612) - ***CVPR'17***, 2017. [[All Versions](https://scholar.google.com/scholar?cluster=6959320578989247472&hl=en&as_sdt=0,5&scioq=Learning+to+Recognise+Unseen+Classes+by+A+Few+Similes)].

* [Attributes as Operators: Factorizing Unseen Attribute-Object Compositions](https://link.springer.com/chapter/10.1007%2F978-3-030-01246-5_11) - ***ECCV'18***, 2018. [[All Versions](https://scholar.google.com/scholar?cluster=11627198158637727139&hl=en&as_sdt=0,5&scioq=Learning+to+Recognise+Unseen+Classes+by+A+Few+Similes)].

* [Learning Compositional Representations for Few-Shot Recognition](https://ieeexplore.ieee.org/document/9010671) - ***CVPR'19***, 2019. [[All Versions](https://scholar.google.com/scholar?cluster=7363445845219257348&hl=en&as_sdt=0,5&scioq=Learning+to+Recognise+Unseen+Classes+by+A+Few+Similes)].

* [Symmetry and Group in Attribute-Object Compositions](https://ieeexplore.ieee.org/document/9156505) - ***CVPR'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=16870815556752021056&hl=en&as_sdt=0,5&scioq=Learning+to+Recognise+Unseen+Classes+by+A+Few+Similes)].

* [A causal view of compositional zero-shot recognition](https://proceedings.neurips.cc/paper/2020/file/1010cedf85f6a7e24b087e63235dc12e-Paper.pdf) - ***NIPS'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=2543173389101020482&hl=en&as_sdt=0,5&scioq=Learning+to+Recognise+Unseen+Classes+by+A+Few+Similes)].

* [Compositional Few-Shot Recognition with Primitive Discovery and Enhancing](https://dl.acm.org/doi/10.1145/3394171.3413849) - ***MM'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=15817839338790433509&hl=en&as_sdt=0,5&scioq=Learning+to+Recognise+Unseen+Classes+by+A+Few+Similes)].

* [Learning Unseen Concepts via Hierarchical Decomposition and Composition](https://ieeexplore.ieee.org/document/9156655) - ***CVPR'20***, 2020. [[All Versions](https://scholar.google.com/scholar?cluster=14161656227038242300&hl=en&as_sdt=0,5&scioq=Learning+to+Recognise+Unseen+Classes+by+A+Few+Similes)].

*[Back to Top](#c)

<!--<span id = "te"></span>
### Tasks & Environments

#### Dataset Aggregation
  * [A Dataset and Architecture for Visual Reasoning with a Working Memory](https://link.springer.com/chapter/10.1007%2F978-3-030-01249-6_44) - ***ECCV'18***, 2018. [[Project](https://github.com/google/cog)].
  * [PHYRE: A New Benchmark for Physical Reasoning](https://research.fb.com/wp-content/uploads/2019/08/PHYRE-A-New-Benchmark-for-Physical-Reasoning-v4.pdf) - ***NIPS'19***, 2019.
  * [CATER: A diagnostic dataset for Compositional Actions & TEmporal Reasoning](https://openreview.net/forum?id=HJgzt2VKPB) - ***ICLR'20***, 2020. [[Project](https://rohitgirdhar.github.io/CATER/)].
  * [CausalWorld: A Robotic Manipulation Benchmark for Causal Structure and Transfer Learning](https://arxiv.org/abs/2010.04296), 2020.

#### Embodied AI Environment
  * [ThreeDWorld](http://www.threedworld.org/) - ***MIT-IBM***. [[Paper](https://arxiv.org/abs/2007.04954)].
  * [Rearrangement: A Challenge for Embodied AI](https://arxiv.org/pdf/2011.01975.pdf), 2020.
  * [iGibson](http://svl.stanford.edu/igibson/) - ***Stanford***. [[Paper](https://ieeexplore.ieee.org/document/8954627)].
  * [AI2-THOR](https://ai2thor.allenai.org/ithor) - ***Allen Institute***. [[Paper](https://arxiv.org/abs/1712.05474)].
  * [Robo-THOR](https://ai2thor.allenai.org/robothor) - ***Allen Institute***. [[Paper](https://arxiv.org/abs/2004.06799)].
  * [Manipula-THOR](https://ai2thor.allenai.org/manipulathor) - ***Allen Institute***. [[Paper](https://arxiv.org/abs/2104.11213)].
  * [RLBench](https://sites.google.com/view/rlbench) - ***Imperial College***. [[Paper](https://ieeexplore.ieee.org/document/9001253)].

#### First-Person Vision
  * [First-Person Vision](https://ieeexplore.ieee.org/document/6232429) - ***Proceedings of the IEEE***, 2012.
  * [The Evolution of First Person Vision Methods: A Survey](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7055926) - ***Trans. CSVT***, 2015.
  * [Understanding the Nature of First-Person Videos: Characterization and Classification using Low-Level Features](http://vijaychan.github.io/Publications/2014%20CVPR%20Workshop%20-%20Understanding%20the%20Nature%20of%20First-Person%20Videos.pdf) - ***CVPR'14***, 2014.
  * [Pooled Motion Features for First-Person Videos](https://openaccess.thecvf.com/content_cvpr_2015/papers/Ryoo_Pooled_Motion_Features_2015_CVPR_paper.pdf) - ***CVPR'15***, 2015.
  * [Actor and Observer: Joint Modeling of First and Third-Person Videos](https://openaccess.thecvf.com/content_cvpr_2018/papers/Sigurdsson_Actor_and_Observer_CVPR_2018_paper.pdf) - ***CVPR'18***, 2018.
  * [Forecasting Human-Object Interaction: Joint Prediction of Motor Attention and Actions in First Person Video](https://link.springer.com/chapter/10.1007/978-3-030-58452-8_41) - ***ECCV'20***, 2020.
  * [Rolling-Unrolling LSTMs for Action Anticipation from First-Person Video](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9088213) - ***Trans. PAMI***, 2020.
  * [View-Action Representation Learning for Active First-Person Vision](https://ieeexplore.ieee.org/document/9064828) - ***Trans. CSVT***, 2021.
  * [Design and Use Paradigms for Gazebo, An Open-Source Multi-Robot Simulator](https://ieeexplore.ieee.org/abstract/document/1389727) - ***IROS'04***, 2004. [[Project](http://gazebosim.org/)].
  * [ViZDoom: A Doom-based AI Research Platform for Visual Reinforcement Learning](https://arxiv.org/pdf/1605.02097v2.pdf) - ***CIG'16***, 2016. [[Project](http://vizdoom.cs.put.edu.pl/)].
  * [Is First Person Vision Challenging for Object Tracking? The TREK-100 Benchmark Dataset](https://arxiv.org/abs/2011.12263), 2020.  
  * **Visual Experience Database** [[Project](http://visualexperiencedatabase.org/research.html)]. [[Publications](http://visualexperiencedatabase.org/publications.html)].

 
#### Abstract Reasoning Challenge
  * [On the Measure of Intelligence](https://arxiv.org/pdf/1911.01547.pdf) - ***Google Research***, 2019.
  * [Abstract Reasoning Challenge](https://www.kaggle.com/c/abstraction-and-reasoning-challenge/)


#### AI Birds Challenge
  * [AI-Birds](https://aibirds.org) - ***IJCAI***.
  * [Hi-Phy: A Benchmark for Hierarchical Physical Reasoning](https://openreview.net/forum?id=AcL1ORzw0Nf), 2021.


#### Minecraft
  * [Mining Learning and Crafting Scientific Experiments: A Literature Review on the Use of Minecraft in Education and Research](https://eric.ed.gov/?id=EJ1097278) - ***Journal on Eduction Technology & Society***, 2016.

##### Malmo Platform for Minecraft AI
  * [The Malmo Platform for Artificial Intelligence Experimentation](https://www.microsoft.com/en-us/research/publication/malmo-platform-artificial-intelligence-experimentation/) ***IJCAI'16***, 2016. 
  * [[Malmo](https://github.com/Microsoft/malmo#getting-started)]. 
  * [[Malmo-env](https://github.com/Microsoft/malmo/tree/master/MalmoEnv)]. 
  * [[Malmo-Tutorials](https://microsoft.github.io/malmo/0.17.0/Python_Examples/Tutorial.pdf)].
  * [[MineRL](https://minerl.io/)].
  * [[MarLo Challenge 2018](https://github.com/crowdAI/marLo)].
 
#####  **Artificial Intelligence**
  * [Multi-task curriculum learning in a complex, visual, hard-exploration domain: Minecraft](https://arxiv.org/abs/2106.14876), 2021.
  * [Learning to execute instructions in a Minecraft dialogue](https://www.aclweb.org/anthology/2020.acl-main.232/) - ***ACL'20***, 2020.
  * [Collaborative Dialogue in Minecraft](https://www.aclweb.org/anthology/P19-1537.pdf) - ***ACL'19***, 2019.
  * [Learning Skill Hierarchies from Predicate Descriptions and Self-Supervision](http://web.mit.edu/tslvr/www/papers/genplan20_camera_ready.pdf) - ***AAAI GenPlan Workshop***, 2020.
  * [AMRL: Aggregated Memory for Reinforcement Learning](https://openreview.net/pdf?id=Bkl7bREtDr) - ***ICLR'20***, 2020.
  * [MineRL: A Large-Scale Dataset of Minecraft Demonstrations](https://www.ijcai.org/Proceedings/2019/0339.pdf) ***IJCAI'19***, 2019. [[2020 Competition](https://arxiv.org/abs/2106.03748)].
  * [Design Mining for Minecraft Architecture](http://www.cs.cornell.edu/~eland/papers/aiide2018.pdf) - ***AAAI'18***, 2018.
  * [Adaptive Agents in Minecraft: A Hybrid Paradigm for Combining Domain Knowledge with Reinforcement Learning](https://link.springer.com/chapter/10.1007%2F978-3-319-71679-4_6) - ***AAMAS'17***, 2017.
  * [Asynchronous Data Aggregation for Training End to End Visual Control Networks](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/05/fp185-monfort-1.pdf) - ***AAMAS'17***, 2017.
  * [A Deep Hierarchical Approach to Lifelong Learning in Minecraft](https://aaai.org/ocs/index.php/AAAI/AAAI17/paper/view/14630/13950) - ***AAAI'17***, 2017.
  * [Modular Multitask Reinforcement Learning with Policy Sketches](http://proceedings.mlr.press/v70/andreas17a.html) - ***ICML'17***, 2017.
  * [Control of memory, active perception, and action in minecraft](http://proceedings.mlr.press/v48/oh16.pdf) - ***ICML'16***, 2016.
  * [Learning Behavior from Demonstration in Minecraft via Symbolic Similarity Measures](fdg2015.org/papers/fdg2015_paper_11.pdf) - ***FDG'15***, 2015.
  
#####  **Cognitive Science**
  * [How Players Speak to an Intelligent GameCharacter Using Natural Language Messages](http://todigra.org/index.php/todigra/article/view/88/139) - ***DiGRA***, 2018.
  * [Minecraft as a Generative Platform for Analyzing and Practicing Spatial Reasoning](https://link.springer.com/chapter/10.1007%2F978-3-030-57983-8_22) - ***Spatial Cognition'20***, 2020.
  * [Generative Design in Minecraft: Chronicle Challenge](http://computationalcreativity.net/iccc2019/papers/iccc19-lbp-7.pdf) - ***ICCC'20***, 2020.
  * [Minecraft as a Platform for Project-Based Learning in AI](https://aaai.org/ojs/index.php/AAAI/article/view/7070) - ***AAAI'20***, 2020.
  * [MC-Saar-Instruct: a Platform for Minecraft Instruction Giving Agents](https://www.aclweb.org/anthology/2020.sigdial-1.7.pdf) - ***SIGDial'20***, 2020.

<!--*[Back to Top](#c)-->


<span id = "r&l"></span>
## Institute & Researcher

<span id = "mit"></span>
### MIT

* [Center for Brains, Minds and Machines (CBMM)](https://cbmm.mit.edu/) - ***NSF***.

* [Josh Tenenbaum](https://cocosci.mit.edu/josh) - ***MIT***, [Computational Cognitive Science Group (CoCoSci Group)](https://cocosci.mit.edu/) - ***Department of Brain and Cognitive Sciences, MIT***.

* [Rebecca Saxe](https://saxelab.mit.edu/people/rebecca-saxe) - ***MIT***, [Social Cognitive Neuroscience Laboratory (SaxeLab)](https://saxelab.mit.edu/) - ***Department of Brain and Cognitive Sciences, MIT***.

* [Laura Schulz](https://cbmm.mit.edu/about/people/schulz) - ***MIT***, [Early Childhood Cognition Lab](https://eccl.mit.edu/) - ***Department of Brain and Cognitive Sciences, MIT***.

* [Leslie Kaelbling](https://people.csail.mit.edu/lpk/) - ***MIT***, [The Learning & Intelligent Systems Group](https://lis.csail.mit.edu/) - ***Department of Electrical Engineering and Computer Science, MIT***.

*[Back to Top](#c)

<span id = "stfd"></span>
### Stanford

* [Noah Goodman](https://cocolab.stanford.edu/ndg.html) - ***Stanford***, [Computation & Cognition Lab (CoCoLab)](https://cocolab.stanford.edu/) - ***Department of Psychology, Department of Computer Science, Stanford***.

* [Michael Frank](https://web.stanford.edu/~mcfrank/) - ***Stanford***, [The Stanford Language and Cognition Lab](http://langcog.stanford.edu/) - ***Department of Psychology, Stanford***.

* [Tobias Gerstenberg](https://cicl.stanford.edu/member/tobias_gerstenberg/) - ***Stanford***, [Causality in Cognition Lab (CICL)](https://cicl.stanford.edu/) - ***Department of Psychology, Stanford***.

* [Jiajun Wu](https://jiajunwu.com/) - ***Department of Computer Science, Stanford***.

*[Back to Top](#c)

<span id = "prct"></span>
### Princeton

* [Tania Lombrozo](https://psych.princeton.edu/person/tania-lombrozo) - ***Princeton***, [Concepts & Cognition Lab](https://cognition.princeton.edu/) - ***Department of Psychology, Princeton***.

* [Tom Griffiths](https://cocosci.princeton.edu/tom/index.php) - ***Princeton***, [Computational Cognitive Science Lab](https://cocosci.princeton.edu/index.php) - ***Department of Psychology, Department of Computer Science, Princeton***.

*[Back to Top](#c)

<span id = "harvard"></span>
### Harvard

* [Elizabeth Spelke](https://psychology.fas.harvard.edu/people/elizabeth-s-spelke) - ***Harvard***, [Harvard Laboratory for Developmental Studies](https://www.harvardlds.org/) - ***Department of Psychology, Harvard***.

* [Tomer Ullman](https://www.tomerullman.org/) - ***Harvard***, [Computation, Cognition, and Development Lab (CoCoDev)](https://cocodev.fas.harvard.edu/) - ***Department of Psychology, Harvard***.

* [Samuel Gershman](https://psychology.fas.harvard.edu/people/samuel-j-gershman) - ***Harvard***, [Computational Cognitive Neuroscience Lab (CCN Lab)](https://gershmanlab.com/) - ***Department of Psychology, Harvard***.

*[Back to Top](#c)

<span id = "ucla"></span>
### UCLA

* [Center for Vision, Cognition, Learning and Autonomy (VCLA)](http://vcla.stat.ucla.edu/) - ***Department of Statistics, UCLA***.

* [Ying Nian Wu](http://www.stat.ucla.edu/~ywu/) - ***Department of Statistics, UCLA***

* [Tao Gao](http://www.stat.ucla.edu/~taogao/Taogao.html) - ***UCLA***, [Visual Intelligence Lab](http://www.stat.ucla.edu/~taogao/index.html) - ***Department of Statistics, UCLA***.

* [Hongjing Lu](https://www.psych.ucla.edu/faculty/page/hongjing) - ***UCLA***, [Computational Vision and Learning Lab (CVL)](http://cvl.psych.ucla.edu/) - ***Department of Psychology, UCLA***.

*[Back to Top](#c)

<span id = "ucb"></span>
### UC Berkeley

* [Fei Xu](https://psychology.berkeley.edu/people/fei-xu) - ***UCB***, [Berkeley Early Learning Lab (Xu Lab)](https://babylab5.wixsite.com/bell) - ***Department of Psychology, UCB***.

* [Alison Gopnik](http://alisongopnik.com/) - ***UCB***, [Cognitive Development & Learning Lab (Gopnik Lab)](http://www.gopniklab.berkeley.edu/) - ***Department of Psychology, UCB***.

* [Steve Piantadosi](http://colala.berkeley.edu/people/piantadosi/) - ***UCB***, [The computation and language lab (colala)](http://colala.berkeley.edu/) - ***Department of Psychology, UCB***.

* [Celeste Kidd](http://www.celestekidd.com/) - ***UCB***, [Kidd Lab](https://www.kiddlab.com/) - ***Department of Psychology, UCB***.

*[Back to Top](#c)

<span id = "ucsd"></span>
### UCSD

* [Judith Fan](https://psychology.ucsd.edu/people/profiles/jefan.html) - ***UCSD***, [Cognitive Tools Lab](https://cogtoolslab.github.io/) - ***UCSD***.

* [Zhuowen Tu](https://pages.ucsd.edu/~ztu/) - ***UCSD***, [Machine Learning, Perception, and Cognition Lab (mlPC)](https://pages.ucsd.edu/~ztu/Group.htm) - ***UCSD***.

* [Ed Vul](https://psychology.ucsd.edu/people/profiles/evul.html) - ***UCSD***, [Computational Cognition Lab](http://www.evullab.org/index.html) - ***UCSD***.

*[Back to Top](#c)

<span id = "nyu"></span>
### NYU

* [Brenden Lake](https://cims.nyu.edu/~brenden/) - ***NYU***, [Human & Machine Learning Lab (Lake Lab)](https://lake-lab.github.io/) - ***NYU***.

* [Todd Gureckis](https://as.nyu.edu/faculty/todd-gureckis.html) - ***NYU***, [Computation & Cognition Lab](http://gureckislab.org/) - ***NYU***.

* [Wei Ji Ma](http://www.cns.nyu.edu/malab/people.html) - ***NYU***, [Wei Ji Ma Lab](http://www.cns.nyu.edu/malab/) - ***NYU***.

*[Back to Top](#c)

<span id = "bigai"></span>
### BIGAI

* [Beijing Institute for General Artificial Intelligence (BIGAI)](https://bigai.ai/) - ***Beijing***.

* [Yixin Zhu](https://yzhu.io/) - ***BIGAI***.

* [Song-Chun Zhu](http://www.stat.ucla.edu/~sczhu/) - ***BIGAI***.

*[Back to Top](#c)

<span id = "bk"></span>
## People & Book
<span id = "ug"></span>
### Ulf Grenander

* [A Calculus of Ideas: A Mathematical Study of Thinking](https://www.dam.brown.edu/ptg/REPORTS/calculustext.PDF) - ***World Scientific Publishing Company***, 2012. [[All Versions](https://scholar.google.com/scholar?cluster=12182416000849265255&hl=en&as_sdt=0,5)].

* [General Pattern Theory: A Mathematical Study of Regular Structures](https://global.oup.com/academic/product/general-pattern-theory-9780198536710?cc=lt&lang=de#) - ***Oxford University Press***, 1993. [[All Versions](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=General+Pattern+Theory&btnG=)].

*[Back to Top](#c)

<span id = "mt"></span>
### Michael Tomasello

* [Origins of human communication](https://1lib.net/book/541274/39859f) - ***MIT Press***, 2010. [[All Versions](https://scholar.google.com/scholar?oi=bibs&hl=en&cluster=2553369883266458474)].

* [The cultural origins of human cognition](https://hk1lib.org/book/541275/1452f8?id=541275&secret=1452f8) - ***Havard University Press***, 2000. [[All Versions](https://scholar.google.com/scholar?oi=bibs&hl=en&cluster=5000469061641945144)].

*[Back to Top](#c)

<span id = "jp"></span>
### Judea Pearl

* [The Book of Why: The New Science of Cause and Effect](http://bayes.cs.ucla.edu/WHY/) - ***Basic Books***, 2018. [[All Versions](https://scholar.google.com/scholar?cluster=2505901292485349932&hl=en&as_sdt=0,5)].

* [Causality: Models, Reasoning and Inference](https://hk1lib.org/book/2780725/2ec8f1?id=2780725&secret=2ec8f1) - ***Cambridge University Press***, 2009. [[All Versions](https://scholar.google.com/scholar?cluster=10996260119229499611&hl=en&as_sdt=0,5&as_vis=1)].

*[Back to Top](#c)

<span id = "sc"></span>
### Susan Carey

* [The Origin of Concepts](https://hk1lib.org/book/844457/42178f?id=844457&secret=42178f) - ***Oxford University Press***, 2009. [[All Versions](https://scholar.google.com/scholar?cluster=11493102398422813821&hl=en&as_sdt=0,5)].

* [Conceptual Change in Childhood](https://hk1lib.org/book/3659332/11fa44) - ***MIT Press***, 1985. [[All Versions](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=conceptual+change+in+childhood+susan+carey&btnG=)].

*[Back to Top](#c)

<span id = "dk"></span>
### Daniel Kahneman

* [Thinking, fast and slow](https://hk1lib.org/book/2181569/f5e85a?id=2181569&secret=f5e85a) - ***Farrar Straus Giroux***, 2011. [[All Versions](https://scholar.google.com/scholar?oi=bibs&hl=en&cluster=3255681708785115121)].

*[Back to Top](#c)

<span id = "kpp"></span>
### Karl Popper

* [The logic of scientific discovery](https://hk1lib.org/book/511214/299596) - ***Routledge***, 2005. [[All Versions](https://scholar.google.com/scholar?cluster=5836864564733788424&hl=en&as_sdt=0,5)].

* [All Life is Problem Solving](https://hk1lib.org/book/2773070/c48f60) - ***Routledge***, 2001. [[All Versions](https://scholar.google.com/scholar?cluster=9799073870888093350&hl=en&as_sdt=0,5)].

*[Back to Top](#c)

