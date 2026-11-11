
# Survey on Explainable AI: Techniques, challenges and open issues 

**Data:** 01.12.2024

**Autorzy:** Adel Abusitta, Miles Q. Li, Benjamin C. M. Fung

## Definitions

> <span style="color: #F19837;">“Simulatability. Simulatability is the property that someone (i.e., a human) can go through the machine learning model’s steps and understand them (Lage et al., 2019; Peng et al., 2022). Therefore, a human can check whether each model’s step is reasonable to her/him or not.” ([PDF](zotero://open-pdf/library/items/IZHZQX4L?page=6&annotation=VT9KQHYI)) (Adel Abusitta, Miles Q. Li, Benjamin C. M. Fung, 1733007600000, p. 6)</span>

nice, easy to understand definition


> <span style="color: #F19837;">“Decomposability. Decomposability is testing interpretability with respect to a model’s sub-components (Lu, Lee, Kim, & Danks, 2019; Slack, Friedler, Scheidegger, & Roy, 2019). For example, consider a DT , whose nodes correspond to understood factors. The prediction of a DT can be easily explained in terms of what decisions are made at the tree’s various nodes.” ([PDF](zotero://open-pdf/library/items/IZHZQX4L?page=7&annotation=23H2RUMY)) (Adel Abusitta, Miles Q. Li, Benjamin C. M. Fung, 1733007600000, p. 7)</span>



> <span style="color: #F19837;">“Algorithmic Transparency. A machine learning algorithm is considered explainable if its decisions are explainable by humans (Ahmad, Eckert, & Teredesai, 2018; Peng et al., 2022). In other words, it consists of preferred properties that can be understood by a human. To this end, the algorithm should rely on mathematical techniques and tools to provide proof and to make the model easy to understand (Peng et al., 2022). Examples of algorithmic transparency are logistic/linear models and Bayesian models.” ([PDF](zotero://open-pdf/library/items/IZHZQX4L?page=7&annotation=VNR9S9ED)) (Adel Abusitta, Miles Q. Li, Benjamin C. M. Fung, 1733007600000, p. 7)</span>



> <span style="color: #F19837;">“Fidelity:. Fidelity measures how accurately the explanation reflects the behavior of the model. An explanation with high fidelity accurately represents the decision-making process of the model (Ribeiro et al., 2016a). Fidelity can be quantified using metrics such as cosine similarity or mean squared error between the predictions of the original model and the simplified model.” ([PDF](zotero://open-pdf/library/items/IZHZQX4L?page=10&annotation=VMBPQP4V)) (Adel Abusitta, Miles Q. Li, Benjamin C. M. Fung, 1733007600000, p. 10)</span>



> <span style="color: #F19837;">“Completeness:. Completeness evaluates whether the explanation includes all the relevant information used by the model to make a decision (Ribeiro et al., 2016a).” ([PDF](zotero://open-pdf/library/items/IZHZQX4L?page=10&annotation=6TKDKJ3I)) (Adel Abusitta, Miles Q. Li, Benjamin C. M. Fung, 1733007600000, p. 10)</span>



> <span style="color: #F19837;">“Accuracy:. Explanation accuracy measures how correct the explanation is in describing the underlying model (Ribeiro et al., 2016a).” ([PDF](zotero://open-pdf/library/items/IZHZQX4L?page=10&annotation=6EPE58SU)) (Adel Abusitta, Miles Q. Li, Benjamin C. M. Fung, 1733007600000, p. 10)</span>



> <span style="color: #F19837;">“Interpretability:. Interpretability assesses how easily a human can understand the explanation (Lipton, 2016).” ([PDF](zotero://open-pdf/library/items/IZHZQX4L?page=10&annotation=IQJUHBKV)) (Adel Abusitta, Miles Q. Li, Benjamin C. M. Fung, 1733007600000, p. 10)</span>



> <span style="color: #F19837;">“Trust:. Trust measures the degree to which users believe and rely on the explanations provided by the model (Doshi-Velez & Kim, 2017).” ([PDF](zotero://open-pdf/library/items/IZHZQX4L?page=10&annotation=XH9E6LUM)) (Adel Abusitta, Miles Q. Li, Benjamin C. M. Fung, 1733007600000, p. 10)</span>



> <span style="color: #F19837;">“Usability:. Usability evaluates how practical and helpful the explanations are for users in making decisions or gaining insights (Doshi-Velez & Kim, 2017).” ([PDF](zotero://open-pdf/library/items/IZHZQX4L?page=10&annotation=5K9IK9QF)) (Adel Abusitta, Miles Q. Li, Benjamin C. M. Fung, 1733007600000, p. 10)</span>


## Important

> <span style="color: #FFD400;">“These techniques can be categorized into three types: model-agnostic, model-specific, and model-semi-agnostic techniques” ([PDF](zotero://open-pdf/library/items/IZHZQX4L?page=2&annotation=6IK989GI)) (Adel Abusitta, Miles Q. Li, Benjamin C. M. Fung, 1733007600000, p. 2)</span>

Previous article (2020) didn't mention semi-agnostic, New methods or just new categorysation?


> <span style="color: #FFD400;">“Arrieta et al. (2020” ([PDF](zotero://open-pdf/library/items/IZHZQX4L?page=2&annotation=KV77UVT8)) (Adel Abusitta, Miles Q. Li, Benjamin C. M. Fung, 1733007600000, p. 2)</span>



> <span style="color: #FFD400;">“The efficiency and scalability of XAI methods, as the size of data and number of features need to scale largely in some critical applications.” ([PDF](zotero://open-pdf/library/items/IZHZQX4L?page=2&annotation=NDYPQBM8)) (Adel Abusitta, Miles Q. Li, Benjamin C. M. Fung, 1733007600000, p. 2)</span>

our problem


> <span style="color: #FFD400;">“Table 1  Summary of papers conducting surveys on XAI.” ([PDF](zotero://open-pdf/library/items/IZHZQX4L?page=4&annotation=UI6H7ZGD)) (Adel Abusitta, Miles Q. Li, Benjamin C. M. Fung, 1733007600000, p. 4)</span>

<b>Great paper summarisation! </b>Unfortunately sounds quite generic and I don't fell like it captures where those papers shine


> <span style="color: #FFD400;">“Another disadvantage of this approach is that in most cases, features are mathematically correlated, which makes the permutation feature importance biased by unrealistic data instances (Molnar, 2020; Rudin, 2019). In addition, it is a time-consuming process to permute the whole set of features and run the model many times.” ([PDF](zotero://open-pdf/library/items/IZHZQX4L?page=8&annotation=JBZYG9UD)) (Adel Abusitta, Miles Q. Li, Benjamin C. M. Fung, 1733007600000, p. 8)</span>



> <span style="color: #FFD400;">“However, the main limitation of this approach is that it requires a lot of computation time. This is due to the fact that calculating the Shapley values is intractable if we have a huge number of features” ([PDF](zotero://open-pdf/library/items/IZHZQX4L?page=8&annotation=XWA34ZDZ)) (Adel Abusitta, Miles Q. Li, Benjamin C. M. Fung, 1733007600000, p. 8)</span>

SHAP may strugle with big data


> <span style="color: #FFD400;">“To achieve scalable model-agnostic XAI, we suggest that heuristic algorithms are used (e.g., linear approximation (Fatima, Wooldridge, & Jennings, 2008)) instead of using the original expensive algorithms. For example, in game theory-based explainable AI, the main challenge in adopting the Shapley value to real-world XAI systems is its computational time which increases exponentially with the number of features (van Campen, Hamers, Husslage, & Lindelauf, 2018). The approximation method can approximate the value of the Shapley value and produce a value that is very close to it (Fatima et al., 2008; van Campen et al., 2018).” ([PDF](zotero://open-pdf/library/items/IZHZQX4L?page=13&annotation=9549LNYF)) (Adel Abusitta, Miles Q. Li, Benjamin C. M. Fung, 1733007600000, p. 13)</span>


## Interesting points

> <span style="color: #5FB236;">“Scopus, Web of Science, IEEE Xplore, and PubMed” ([PDF](zotero://open-pdf/library/items/IZHZQX4L?page=3&annotation=BBKM8MG4)) (Adel Abusitta, Miles Q. Li, Benjamin C. M. Fung, 1733007600000, p. 3)</span>

seems like most relevant publication databases


> <span style="color: #5FB236;">“One should note that if the machine learning model is not simulatable, it would be very difficult to understand, even if it is simple. For example, a huge number of simple rules would not allow a human to guess its predictions” ([PDF](zotero://open-pdf/library/items/IZHZQX4L?page=7&annotation=3Z48YT2E)) (Adel Abusitta, Miles Q. Li, Benjamin C. M. Fung, 1733007600000, p. 7)</span>

important for big data

## Doubts

> <span style="color: #FF6666;">“However, a limitation of the review is its broad classifica- tion, which may overlook nuanced distinctions and context-specific challenges” ([PDF](zotero://open-pdf/library/items/IZHZQX4L?page=3&annotation=ZJSRU9XC)) (Adel Abusitta, Miles Q. Li, Benjamin C. M. Fung, 1733007600000, p. 3)</span>

The same reason for last few, seems a little bit forced


> <span style="color: #FF6666;">“XAI also aids in bias detection, ensuring fairer predictions by identifying and mitigating biases in training data. Scenario analysis becomes feasible through XAI’s capability to generate counterfactual explanations, allowing analysts to explore the impact of variable changes on price forecasts. Furthermore, human-in-the-loop systems benefit from XAI’s interpretability, fostering collaboration between analysts and models for continuous refinement.” ([PDF](zotero://open-pdf/library/items/IZHZQX4L?page=5&annotation=SVKRABCT)) (Adel Abusitta, Miles Q. Li, Benjamin C. M. Fung, 1733007600000, p. 5)</span>

Teeling the same thing over and over again, but for diffrent XAI aplication without any insights in this specific domain. <b>REMEMBER, DON'T DO THAT IN MY PAPERS</b>

## Ideas
## Articles

> <span style="color: #2EA8E5;">“Vilone and Longo (2021) introduced the limitation of XAI formats (formats of explanations). The provided some recommendations on how to create applicable and realistic XAI techniques.” ([PDF](zotero://open-pdf/library/items/IZHZQX4L?page=3&annotation=F4ENAKWB)) (Adel Abusitta, Miles Q. Li, Benjamin C. M. Fung, 1733007600000, p. 3)</span>

guaidline on XAI limitations and his to create resonyble XAI methods


> <span style="color: #2EA8E5;">“Schwalbe and Finzel (2023) present a unified taxonomy of XAI methods, integrating terminologies, concepts, and approaches from over 50 prominent surveys. Their aim is to assist researchers and practitioners in understanding, comparing, and select- ing appropriate XAI methods based on specific use-case requirements. While providing a comprehensive reference, the paper’s limitation lies in its potential oversimplification of complex, nuanced distinctions between methods due to the broad unification of diverse terminologies and concepts.” ([PDF](zotero://open-pdf/library/items/IZHZQX4L?page=3&annotation=65I866Q2)) (Adel Abusitta, Miles Q. Li, Benjamin C. M. Fung, 1733007600000, p. 3)</span>

explanation when to use different XAI methods and mabe more deatel explanation how they work. <b>This work may be oversymplifying!</b>


> <span style="color: #2EA8E5;">“Linardatos et al. (2021)” ([PDF](zotero://open-pdf/library/items/IZHZQX4L?page=4&annotation=BBDUDEMK)) (Adel Abusitta, Miles Q. Li, Benjamin C. M. Fung, 1733007600000, p. 4)</span>

seems very technical, focus on interpretable models like in our base plan


> <span style="color: #2EA8E5;">“Doshi-Velez and Kim (2017) propose a framework that includes both human-grounded evaluation and application-grounded evaluation, merging quantitative and qualitative aspects to assess explanations (Doshi-Velez & Kim, 2017).” ([PDF](zotero://open-pdf/library/items/IZHZQX4L?page=10&annotation=Y7DR4YA8)) (Adel Abusitta, Miles Q. Li, Benjamin C. M. Fung, 1733007600000, p. 10)</span>


## I don't understand

> <span style="color: #E56EEE;">“First, select a dataset D, which has been adopted for training the black box. Secondly, obtain the prediction of the model (i.e., blackbox model) using the selected data D. Thirdly, choose any type of interpretable models (e.g., DT). Fourthly, train the interpretable model on the same data D and find its prediction. Finally, the interpretable model becomes the surrogater that can be used to explain the original model” ([PDF](zotero://open-pdf/library/items/IZHZQX4L?page=8&annotation=EYE8ATQ3)) (Adel Abusitta, Miles Q. Li, Benjamin C. M. Fung, 1733007600000, p. 8)</span>

How?
