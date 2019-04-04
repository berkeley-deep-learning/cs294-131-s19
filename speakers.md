## Nicolas Paprenot: A Marauder's Map of Security and Privacy in Machine Learning

### Abstract

There is growing recognition that machine learning (ML) exposes new security and privacy vulnerabilities in software systems, yet the technical community's understanding of the nature and extent of these vulnerabilities remains limited but expanding. In this talk, we explore the threat model space of ML algorithms through the lens of Saltzer and Schroeder's principles for the design of secure computer systems. This characterization of the threat space prompts an investigation of current and future research directions. We structure our discussion around three of these directions, which we believe are likely to lead to significant progress. The first encompasses a spectrum of approaches to verification and admission control, which is a prerequisite to enable fail-safe defaults in machine learning systems. The second seeks to design mechanisms for assembling reliable records of compromise that would help understand the degree to which vulnerabilities are exploited by adversaries, as well as favor psychological acceptability of machine learning applications. The third pursues formal frameworks for security and privacy in machine learning, which we argue should strive to align machine learning goals such as generalization with security and privacy desiderata like robustness or privacy. Key insights resulting from these three directions pursued both in the ML and security communities are identified and the effectiveness of approaches are related to structural elements of ML algorithms and the data used to train them. We conclude by systematizing best practices in our community.

### Bio

Nicolas Papernot is a research scientist at Google Brain working on the security and privacy of machine learning. He will join the University of Toronto and Vector Institute as an assistant professor and Canada CIFAR AI Chair in the Fall 2019. He earned his Ph.D. in Computer Science and Engineering at the Pennsylvania State University, working with Prof. Patrick McDaniel and supported by a Google PhD Fellowship in Security and Privacy. Nicolas received a best paper award at ICLR 2017. He is also the co-author of CleverHans, an open-source library widely adopted in the technical community to benchmark machine learning in adversarial settings, and tf.Privacy, an open-source library for training differentially private models with TensorFlow. In 2016, he received his M.S. in Computer Science and Engineering from the Pennsylvania State University and his M.S. in Engineering Sciences from the Ecole Centrale de Lyon.

## Justin Gilmer: Adversarial Examples Are a Natural Consequence of Test Error in Noise

### Abstract

 Over the last few years, the phenomenon of adversarial examples — maliciously constructed inputs that fool trained machine learning models — has captured the attention of the research community, especially when the adversary is restricted to small modifications of a correctly handled input. Less surprisingly, image classifiers also lack human-level performance on randomly corrupted images, such as images with additive Gaussian noise. In this paper we provide both empirical and theoretical evidence that these are two manifestations of the same underlying phenomenon, establishing close connections between the adversarial robustness and corruption robustness research programs. This suggests that improving adversarial robustness should go hand in hand with improving performance in the presence of more general and realistic image corruptions. Based on our results we recommend that future adversarial defenses consider evaluating the robustness of their methods to distributional shift with benchmarks such as Imagenet-C.

### Bio

Justin Gilmer attended the inaugural Brain Residency program and is now a research scientist at Google Brain. He’s interested in a number of topics in machine learning with recent focus on graph neural networks and model robustness. His received his PhD in theoretical mathematics from Rutgers University where he worked with Michael Saks.

## Stefan Wager: Deep Learning for Causal Inference?

### Abstract

Causal inference is about understanding how various interventions might affect a target of interest, e.g., should we expect surgery to help heal a given patient, or do we believe a minimum wage hike will influence employment in the service industry. There is considerable interest in using methods from deep learning for causal inference so that we might be able to bring new unstructured data to bear on ever more complex questions. In doing so, however, it is important to consider several challenges that are accentuated in a causal inference context: selection bias may make it difficult to distinguish causality from association; effect sizes are invariably weak and we need to be wary of hallucinating signals; and decision rules deployed in high-stakes environments must be well-enough understood by stakeholders so that they can assess whether they are fair. This talk will survey different takes on how deep learning could be used for causal inference, and discuss how any such approach can plug-in to decades of research on robust and credible causal inference from economics, epidemiology and statistics.

### Bio

Stefan Wager is an Assistant Professor of Operations, Information and Technology at Stanford Graduate School of Business, and an Assistant Professor of Statistics (by courtesy). He received his Ph.D. in Statistics from Stanford in 2016. Professor Wager’s research lies at the intersection of causal inference, optimization, and statistical learning. He is particularly interested in developing new solutions to classical problems in statistics, economics and decision making that leverage recent developments in machine learning.

## Guillaume Bouchard: Social Media Platform Safety - AI against Misinformation

### Abstract

False news is harmful to society, it makes the world less informed, and it erodes trust. It's not a new phenomenon, and many organizations — tech companies, media companies, newsrooms, schools — have a responsibility to do our part in addressing it. At Facebook, we're working to fight the spread of false news by building AI-centric products to curb the spread of false news. During this course, we will review state-of-the-art content understanding techniques that are used to reduce the spread of misinformation, and fight harmful behavior, such as hate speech or inadequate media content sharing.

### Bio

Guillaume Bouchard is Research Manager in the Integrity Solution group at Facebook, with the primary goal of reducing misinformation using AI techniques. He authored more than 60 publications and 50 patents in international venues. He received his PhD in Applied Statistics from INRIA in 2005, was senior research scientist for Xerox Research Centre, France and UCL, UK. He was Founder and CEO of Bloomsbury AI, a NLP startup developing question-answering systems that can “read” and “reason” on written documents automatically.

## Zachary Lipton: Deep Learning Under Distribution Shift

### Abstract

We might hope that when faced with unexpected inputs, well-designed software systems would fire off warnings. However, ML systems, which depend strongly on properties of their inputs (e.g. the i.i.d. assumption), tend to fail silently. Faced with distribution shift, we wish to detect and quantify the shift, and to correct our classifiers when possible, even without observing test set labels. This talk will describe several approaches for tackling distribution shift. In one case, motivated by medical diagnosis, where diseases (targets), cause symptoms (observations), we focus on label shift, where the label marginal p(y) changes but the conditional p(x\|y) does not. Our method exploits arbitrary black box predictors to reduce dimensionality, detecting and correcting shift without having to maneuver in the ambient dimension. In other work, we extend this research examining shift detection more broadly, and focusing on cases including structured output, noisy inputs.

### Bio

Zachary Chase Lipton is an assistant professor at Carnegie Mellon University. His research spans both core machine learning methods and their social impact. This work addresses diverse application areas, including medical diagnosis, dialogue systems, and product recommendation. He is the founding editor of the Approximately Correct blog and the lead author of Dive Into Deep Learning, an interactive open-source book teaching deep learning through Jupyter notebooks. Find on Twitter (@zacharylipton) or GitHub (@zackchase).

## Dustin Tran: The Probabilistic Approach to Deep Learning

### Abstract

Probabilistic methods have expanded the scope of deep learning, with applications ranging from perceptual tasks such as image generation, to scientific challenges such as understanding how genetic factors cause diseases. In this talk, I will give an overview of the probabilistic approach to machine learning---specifically, the idea of Box's loop which formulates the scientific method via building models, performing inference and predictions, validating the models, and repeating this loop by revising the models. I'll then go over two specific directions to assist in Box's loop: improved methods for variational inference; and improved software via probabilistic programming languages.

### Bio

Dustin Tran is a research scientist at Google Brain. His interests are broadly in probabilistic generative models, where he has made contributions in probabilistic programming, variational inference, and latent variable models.  Previously, he was a Ph.D. student in Computer Science at Columbia advised by David Blei and Andrew Gelman. Find him on Twitter (@dustinvtran); website: http://dustintran.com/.

## Alex Alemi and Ian Fischer: Information Theory, Learning Representations, and Robust Generalization

### Abstract

In this talk we will introduce core ideas in representation learning from an information theoretic perspective.  We will present unsupervised and supervised learning objectives and show their relationship to the well-known Information Bottleneck method.  By constraining the information present in a representation, gains have been demonstrated with respect to generalization, out of distribution detection, calibration and adversarial robustness.


### Bio

Alex Alemi is currently a Senior Research Scientist at Google interested in the intersection of information theory and deep learning with a particular focus on representational learning.  In a previous life he was a theoretical condensed matter physicist.  he received my PhD from Cornell working under Jim Sethna on a wide array of topics from nonlinear elasticity to zombies, and a BS in Physics from Caltech.

Ian Fischer is a researcher at Google working at the intersection of information theory and machine learning. His focus has been on understanding and developing information theoretic objective functions, motivated by a desire for robust generalization. Previous to joining Google, he started and sold two technology companies.

## Been Kim: Interpretability - the myth, questions, and some answers

### Abstract

In this talk, I will provide an overview of my work on interpretability from the past year. I will talk about 1) our studies on factors that influence how humans understand explanations from machine learning models, 2) building inherently interpretable models with and without human-in-the-loop, 3) improving interpretability when you already have a model (post-training interpretability) and 4) our work on ways to test and evaluate interpretability methods.

Among them, I will take a deeper dive in one of my recent work - testing with concept activation vectors (TCAV) - a post-training interpretability method for complex models, such as neural network. This method provides an interpretation of a neural net's internal state in terms of human-friendly, high-level concepts instead of low-level input features. The key idea is to view the high-dimensional internal state of a neural net as an aid, not an obstacle. We show how to use concept activation vectors (CAVs) as part of a technique, Testing with CAVs (TCAV), that uses directional derivatives to quantify the degree to which a user-defined concept is important to a classification result--for example, how sensitive a prediction of “zebra” is to the presence of stripes. Using the domain of image classification as a testing ground, we describe how CAVs may be used to explore hypotheses and generate insights for a standard image classification network as well as a medical application.


### Bio



