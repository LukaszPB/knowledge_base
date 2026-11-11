
# Survey on Explainable AI: Techniques, challenges and open issues 

**Data:** 01.12.2024

**Autorzy:** Adel Abusitta, Miles Q. Li, Benjamin C. M. Fung

## Definitions

> <span style="color: #F19837;">“Simulatability. Simulatability is the property that someone (i.e., a human) can go through the machine learning model’s steps and understand them (Lage et al., 2019; Peng et al., 2022). Therefore, a human can check whether each model’s step is reasonable to her/him or not.” ([PDF](zotero://open-pdf/library/items/IZHZQX4L?page=6&annotation=VT9KQHYI)) (Adel Abusitta, Miles Q. Li, Benjamin C. M. Fung, 1733007600000, p. 6)</span>

nice, easy to understand definition


> <span style="color: #F19837;">“Decomposability. Decomposability is testing interpretability with respect to a model’s sub-components (Lu, Lee, Kim, & Danks, 2019; Slack, Friedler, Scheidegger, & Roy, 2019). For example, consider a DT , whose nodes correspond to understood factors. The prediction of a DT can be easily explained in terms of what decisions are made at the tree’s various nodes.” ([PDF](zotero://open-pdf/library/items/IZHZQX4L?page=7&annotation=23H2RUMY)) (Adel Abusitta, Miles Q. Li, Benjamin C. M. Fung, 1733007600000, p. 7)</span>



> <span style="color: #F19837;">“Algorithmic Transparency. A machine learning algorithm is considered explainable if its decisions are explainable by humans (Ahmad, Eckert, & Teredesai, 2018; Peng et al., 2022). In other words, it consists of preferred properties that can be understood by a human. To this end, the algorithm should rely on mathematical techniques and tools to provide proof and to make the model easy to understand (Peng et al., 2022). Examples of algorithmic transparency are logistic/linear models and Bayesian models.” ([PDF](zotero://open-pdf/library/items/IZHZQX4L?page=7&annotation=VNR9S9ED)) (Adel Abusitta, Miles Q. Li, Benjamin C. M. Fung, 1733007600000, p. 7)</span>


## Important

> <span style="color: #FFD400;">“These techniques can be categorized into three types: model-agnostic, model-specific, and model-semi-agnostic techniques” ([PDF](zotero://open-pdf/library/items/IZHZQX4L?page=2&annotation=6IK989GI)) (Adel Abusitta, Miles Q. Li, Benjamin C. M. Fung, 1733007600000, p. 2)</span>

Previous article (2020) didn't mention semi-agnostic, New methods or just new categorysation?


> <span style="color: #FFD400;">“Arrieta et al. (2020” ([PDF](zotero://open-pdf/library/items/IZHZQX4L?page=2&annotation=KV77UVT8)) (Adel Abusitta, Miles Q. Li, Benjamin C. M. Fung, 1733007600000, p. 2)</span>



> <span style="color: #FFD400;">“The efficiency and scalability of XAI methods, as the size of data and number of features need to scale largely in some critical applications.” ([PDF](zotero://open-pdf/library/items/IZHZQX4L?page=2&annotation=NDYPQBM8)) (Adel Abusitta, Miles Q. Li, Benjamin C. M. Fung, 1733007600000, p. 2)</span>

our problem


> <span style="color: #FFD400;">“Table 1  Summary of papers conducting surveys on XAI.” ([PDF](zotero://open-pdf/library/items/IZHZQX4L?page=4&annotation=UI6H7ZGD)) (Adel Abusitta, Miles Q. Li, Benjamin C. M. Fung, 1733007600000, p. 4)</span>

<b>Great paper summarisation! </b>Unfortunately sounds quite generic and I don't fell like it captures where those papers shine

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

## I don't understand