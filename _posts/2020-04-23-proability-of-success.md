---
title: "Probability of Success: 0.999"
date: 2020-04-23 00:00:00
featured_image: '/images/cover2.png'
excerpt: Data science has infiltrated many fields, helping to increase revenue, scale out business practices, improve recommender systems, predict outcomes, drive business decisions and make causal inferences...
---

<!-- ![](/images/equity.png) -->

Data science has infiltrated many fields, helping to increase revenue, scale out business practices, improve recommender systems, predict outcomes, drive business decisions and make causal inferences. Data science, and more specifically machine learning, is at the forefront of many business practices at companies like Netflix, Amazon, Zillow, Facebook, Airbnb and Google, to name a few. It has changed the way companies understand their consumers and drive business decisions. 

However, we often do not know why a given model works. Take neural networks: a machine learning model that contains various nodes and edges, automatically and iteratively adjusting the weights at each layer to achieve the most accurate classification. Essentially, there is no way to know how the model is making a given prediction, making neural networks “black box” models. Yet, neural networks achieve some of the highest prediction accuracies in machine learning. 

This kind of model works when there is a low-stakes decision on the line. The worst that could happen in the Netflix recommender system is that a user gets a movie recommendation that they do not want to watch. Oh no! I guess you’ll have to choose another movie. 

In fields like education, there is a history of bias, systemic racism, and educational inequity that is at stake. On the other end of the model is a child’s future, well-being, and financial security. On the other end of the model are real students and real families with real needs. 

Imagine you work in the college admission office at YaySchool. Your task is to identify whether a given applicant will “succeed” at your school or not. Based on this prediction, you will either admit or reject the student. You have a lot of information on each applicant including their race, family income, zip code, GPA, high school ranking, SAT scores, etc. First step, you must define “success.” You decide that “success” means graduating YaySchool with a 3.0 or higher and earning >60k within 3 months of graduation. Next, you choose your classifier. You choose a decision tree, a model that learns various decision rules inferred from your training data, which consists of all the information about current YaySchool graduates labeled with their class: “successful” or “unsuccessful.” Your model learns that when students come from a certain zip code, they tend to be “unsuccessful” graduates. Therefore, all applicants from that zipcode will have a higher probability of being “unsuccessful” graduates and will not be admitted. Since zip code is largely linked to race, income level, and school quality, YaySchool will systematically exclude students from a certain economic and racial profile, presumably low-income students of color from underfunded schools. And systemic racism is continued and exacerbated. 

Of course, school admissions do not actually employ machine learning models to make their admissions decisions because it is blatantly unethical and will perpetuate already biased systems. In education, data science simply cannot be employed in the same way as it has been in other fields. We cannot have models decide the most important factors in a classification, and sometimes, we cannot classify a human being at all. Data science will play a different role in education and needs to take on a certain awareness it has not needed in other fields. This awareness can look like: 

* **Never using** a “black box” model or blended model in which you cannot track the model’s decision making process.
* **Questioning** whether your defined objective for the model is really your objective (e.g. How can we define “success” differently? What else is important in an applicant aside from their future “success?”). 
* **Asking** whether the model perpetuates the biased system in place or works in opposition.
* Qualitatively **analyzing** who will be most positively and negatively affected by the decisions of this model. 
* **Asking** what problems we could run into if we deploy this model on a larger scale (e.g. outside of the school, town, state, etc). Have we overfit the “training” population? 

Of course, many of these questions and analyses are done on models outside of the education space. However, the potential implications and risks of unawareness in the model building process and greater context are so much greater in the education and related fields. While data science is gaining more and more traction in the education space, we will not see large scale benefits of its application without an accompanying hyper-awareness of the potential implications.  

> "The potential implications and risks of unawareness in the model building process and greater context are so much greater in the education and related fields."

