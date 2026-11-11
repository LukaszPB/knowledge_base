
# Explainable Artificial Intelligence (XAI): Concepts, taxonomies, opportunities and challenges toward responsible AI 

**Data:** 01.06.2020

**Autorzy:** Alejandro Barredo Arrieta, Natalia Díaz-Rodríguez, Javier Del Ser, Adrien Bennetot, Siham Tabik, Alberto Barbado, Salvador Garcia, Sergio Gil-Lopez, Daniel Molina, Richard Benjamins, Raja Chatila, Francisco Herrera

## Definitions
## Important

> <span style="color: #FFD400;">“Interpretability: It is defined as the ability to explain or to provide the meaning in understandable terms to a human.” ([PDF](zotero://open-pdf/library/items/H9ZYSN5I?page=4&annotation=YKAK5T9S)) (Alejandro Barredo Arrieta, Natalia Díaz-Rodríguez, Javier Del Ser, Adrien Bennetot, Siham Tabik, Alberto Barbado, Salvador Garcia, Sergio Gil-Lopez, Daniel Molina, Richard Benjamins, Raja Chatila, Francisco Herrera, 1590962400000, p. 4)</span>

focus on human understanding, so models with to much features for example should also count


> <span style="color: #FFD400;">“First, the details or the reasons used to explain, are completely dependent of the audience to which they are presented. Second, whether the explanation has left the concept clear or easy to understand also depends completely on the audience.” ([PDF](zotero://open-pdf/library/items/H9ZYSN5I?page=4&annotation=Z7NJNLP9)) (Alejandro Barredo Arrieta, Natalia Díaz-Rodríguez, Javier Del Ser, Adrien Bennetot, Siham Tabik, Alberto Barbado, Salvador Garcia, Sergio Gil-Lopez, Daniel Molina, Richard Benjamins, Raja Chatila, Francisco Herrera, 1590962400000, p. 4)</span>

Explanation tools should be customised to the audience


> <span style="color: #FFD400;">“Any means to reduce the complexity of the model or to simplify its outputs should be considered as an XAI approach.” ([PDF](zotero://open-pdf/library/items/H9ZYSN5I?page=4&annotation=DZY89RCG)) (Alejandro Barredo Arrieta, Natalia Díaz-Rodríguez, Javier Del Ser, Adrien Bennetot, Siham Tabik, Alberto Barbado, Salvador Garcia, Sergio Gil-Lopez, Daniel Molina, Richard Benjamins, Raja Chatila, Francisco Herrera, 1590962400000, p. 4)</span>

Extremely broad definition


> <span style="color: #FFD400;">“Accessibility: A minor subset of the reviewed contributions argues for explainability as the property that allows end users to get more involved in the process of improving and developing a certain ML model [37,86]. It seems clear that explainable models will ease the burden felt by non-technical or non-expert users when having to deal with algorithms that seem incomprehensible at first sight. This concept is expressed as the third most considered goal among the surveyed literature.” ([PDF](zotero://open-pdf/library/items/H9ZYSN5I?page=6&annotation=X9BESJNC)) (Alejandro Barredo Arrieta, Natalia Díaz-Rodríguez, Javier Del Ser, Adrien Bennetot, Siham Tabik, Alberto Barbado, Salvador Garcia, Sergio Gil-Lopez, Daniel Molina, Richard Benjamins, Raja Chatila, Francisco Herrera, 1590962400000, p. 6)</span>

Most notable goal of explainability for me


> <span style="color: #FFD400;">“In general, XAI measurements should evaluate the goodness, usefulness and satisfaction of explanations, the improvement of the mental model of the audience induced by model explanations” ([PDF](zotero://open-pdf/library/items/H9ZYSN5I?page=19&annotation=KTTT2WUE)) (Alejandro Barredo Arrieta, Natalia Díaz-Rodríguez, Javier Del Ser, Adrien Bennetot, Siham Tabik, Alberto Barbado, Salvador Garcia, Sergio Gil-Lopez, Daniel Molina, Richard Benjamins, Raja Chatila, Francisco Herrera, 1590962400000, p. 19)</span>

Subjective


> <span style="color: #FFD400;">“This is one of the reasons why, as mentioned above, a challenge in XAI is establishing objective metrics on what constitutes a good explanation. A possibility to reduce this subjectivity is taking inspiration from experiments on human psychology, sociology or cognitive sciences to create objectively convincing explanations. Relevant findings to be considered when creating an explainable AI model are highlighted in” ([PDF](zotero://open-pdf/library/items/H9ZYSN5I?page=20&annotation=8FU3CIGM)) (Alejandro Barredo Arrieta, Natalia Díaz-Rodríguez, Javier Del Ser, Adrien Bennetot, Siham Tabik, Alberto Barbado, Salvador Garcia, Sergio Gil-Lopez, Daniel Molina, Richard Benjamins, Raja Chatila, Francisco Herrera, 1590962400000, p. 20)</span>

Measuring explainability will be difficult

## Interesting points

> <span style="color: #5FB236;">“However, an improvement in the understanding of a system can lead to the correction of its deficiencies.” ([PDF](zotero://open-pdf/library/items/H9ZYSN5I?page=2&annotation=EBFAEPMH)) (Alejandro Barredo Arrieta, Natalia Díaz-Rodríguez, Javier Del Ser, Adrien Bennetot, Siham Tabik, Alberto Barbado, Salvador Garcia, Sergio Gil-Lopez, Daniel Molina, Richard Benjamins, Raja Chatila, Francisco Herrera, 1590962400000, p. 2)</span>



> <span style="color: #5FB236;">“LIME builds locally linear models around the predictions of an opaque model to explain it.” ([PDF](zotero://open-pdf/library/items/H9ZYSN5I?page=11&annotation=H98Z3953)) (Alejandro Barredo Arrieta, Natalia Díaz-Rodríguez, Javier Del Ser, Adrien Bennetot, Siham Tabik, Alberto Barbado, Salvador Garcia, Sergio Gil-Lopez, Daniel Molina, Richard Benjamins, Raja Chatila, Francisco Herrera, 1590962400000, p. 11)</span>



> <span style="color: #5FB236;">“human cognitive skills favors the understanding of visual data” ([PDF](zotero://open-pdf/library/items/H9ZYSN5I?page=15&annotation=EW4JLNHD)) (Alejandro Barredo Arrieta, Natalia Díaz-Rodríguez, Javier Del Ser, Adrien Bennetot, Siham Tabik, Alberto Barbado, Salvador Garcia, Sergio Gil-Lopez, Daniel Molina, Richard Benjamins, Raja Chatila, Francisco Herrera, 1590962400000, p. 15)</span>

indeed


> <span style="color: #5FB236;">“It is also ex- plained that probabilities are not as important as causal links in order to provide a satisfying explanation.” ([PDF](zotero://open-pdf/library/items/H9ZYSN5I?page=20&annotation=454982NF)) (Alejandro Barredo Arrieta, Natalia Díaz-Rodríguez, Javier Del Ser, Adrien Bennetot, Siham Tabik, Alberto Barbado, Salvador Garcia, Sergio Gil-Lopez, Daniel Molina, Richard Benjamins, Raja Chatila, Francisco Herrera, 1590962400000, p. 20)</span>


## Doubts

> <span style="color: #FF6666;">“the authors formulate the rule extraction problem as a multi-constrained optimiza- tion” ([PDF](zotero://open-pdf/library/items/H9ZYSN5I?page=14&annotation=6B5SSGLF)) (Alejandro Barredo Arrieta, Natalia Díaz-Rodríguez, Javier Del Ser, Adrien Bennetot, Siham Tabik, Alberto Barbado, Salvador Garcia, Sergio Gil-Lopez, Daniel Molina, Richard Benjamins, Raja Chatila, Francisco Herrera, 1590962400000, p. 14)</span>



> <span style="color: #FF6666;">“In Big Data fusion (Fig. 13.d), local models are learned on a split of the original data sources, each submitted to a Worker node in charge of performing this learning process (Map task). Then, a Reduce node (or several Reduce nodes, depending on the application) combines the outputs produced by each Map task. Therefore, Big Data fusion can be conceived as a means to distribute the complexity of learning a ML model over a pool of Worker nodes, wherein the strategy to design how information/models are fused together between the Map and the Reduce tasks is what defines the quality of the finally generated outcome [413].” ([PDF](zotero://open-pdf/library/items/H9ZYSN5I?page=25&annotation=EMHEFZ8Z)) (Alejandro Barredo Arrieta, Natalia Díaz-Rodríguez, Javier Del Ser, Adrien Bennetot, Siham Tabik, Alberto Barbado, Salvador Garcia, Sergio Gil-Lopez, Daniel Molina, Richard Benjamins, Raja Chatila, Francisco Herrera, 1590962400000, p. 25)</span>

Slicing big data into smaller (essayer to impreter) chunks and then combining the results into a group of models responsible for different part of a whole problem. Maybe even few models on different sets of features

## Ideas

> <span style="color: #A28AE5;">“n general, humans are reticent to adopt techniques that are not directly interpretable, tractable and trustworthy” ([PDF](zotero://open-pdf/library/items/H9ZYSN5I?page=2&annotation=QFBLSXLE)) (Alejandro Barredo Arrieta, Natalia Díaz-Rodríguez, Javier Del Ser, Adrien Bennetot, Siham Tabik, Alberto Barbado, Salvador Garcia, Sergio Gil-Lopez, Daniel Molina, Richard Benjamins, Raja Chatila, Francisco Herrera, 1590962400000, p. 2)</span>

I think this has changed over the last 6 years, given the current level of public trust in LLMs. As people come to trust "black-box" algorithms more, does the need for XAI (Explainable AI) increase or decrease?


> <span style="color: #A28AE5;">“For instance, [56] presents a simple distillation method called Interpretable Mimic Learning to extract an interpretable model by means of gradient boosting trees.” ([PDF](zotero://open-pdf/library/items/H9ZYSN5I?page=15&annotation=V2CWDCFD)) (Alejandro Barredo Arrieta, Natalia Díaz-Rodríguez, Javier Del Ser, Adrien Bennetot, Siham Tabik, Alberto Barbado, Salvador Garcia, Sergio Gil-Lopez, Daniel Molina, Richard Benjamins, Raja Chatila, Francisco Herrera, 1590962400000, p. 15)</span>

Are gradient boosting trees interpretable?

## Articles

> <span style="color: #2EA8E5;">“[349,350].” ([PDF](zotero://open-pdf/library/items/H9ZYSN5I?page=19&annotation=BYT48M5G)) (Alejandro Barredo Arrieta, Natalia Díaz-Rodríguez, Javier Del Ser, Adrien Bennetot, Siham Tabik, Alberto Barbado, Salvador Garcia, Sergio Gil-Lopez, Daniel Molina, Richard Benjamins, Raja Chatila, Francisco Herrera, 1590962400000, p. 19)</span>

it seems like a good source of information on explainability metrics


> <span style="color: #2EA8E5;">“[12]” ([PDF](zotero://open-pdf/library/items/H9ZYSN5I?page=20&annotation=4HQL7WUI)) (Alejandro Barredo Arrieta, Natalia Díaz-Rodríguez, Javier Del Ser, Adrien Bennetot, Siham Tabik, Alberto Barbado, Salvador Garcia, Sergio Gil-Lopez, Daniel Molina, Richard Benjamins, Raja Chatila, Francisco Herrera, 1590962400000, p. 20)</span>

Interesting article about objectively convincing explanations

## I don't understand