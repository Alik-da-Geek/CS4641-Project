# CS 4641 Project
## Introduction and Background
Our goal is to examine a variety of factors related to students' lives, ranging from academic paths to socio-economic backgrounds, in order to identify which students are at risk of dropping out. Through our research, we aim to pinpoint the key factors that contribute to students dropping out and use this information to keep them in school. <br>
There has been a wealth of literature and studies on this topic. For example, an IJCRT study found that health and attendance were strongly indicative factors of students' propensity to drop out. [1] Our dataset is unique in that it has a very international basis of participants and has a very wide range of features, and will hopefully yield interesting results.

## Problem Defintion
The goal of the project is to contribute to the reduction of students dropping out of higher education, by using machine learning techniques to identify students at risk of failure at an early stage of their academic path. We will use the dataset mentioned in this document and classification models to predict a student's likelihood of dropping out.

## Methods
A dataset with 37 different attributes from the Polytechnic Institute Of Portalegre in Portugal will be used to train different models[2]. A neural network can be utilized with multiple inputs concerning the background and information about the student to determine the output layer: dropping out of school. With this model, the frequency and density of each node can be stored within the binary classification to which we can output a multiclass classification in evaluating the student’s risk factors in dropping their education. We may also utilize a Gaussian Mixture Model in order to use a given subsample to determine the overall population of students. This revolves around the normal distribution and the realization that not all samples or populations may fall within the normal distribution of multiple subsamples of varying data throughout schools or various students. In addition, we plan on leveraging several libraries such as scikit-learn and numpy to quickly and accurately train our model. 

## Potential Results and Discussion
A potential result of this project is a model that can accurately estimate a student’s risk of dropping out of their education and how varying factors may influence their chances of remaining in school. Education is crucial and degree holders are better off than those with some or no college [3]. This project ideally should result in more students mitigating any risk factors or understanding the factors which put them in a position where they may have to face the potential of dropping out, especially for the international demographic within the dataset. Better knowing the presented circumstances and obstacles of one’s situation can lead one to do all in their power and ability to make the most of what they have and determine appropriate steps or decisions that will lead them to achieve a desired result. School administrators can also create programs tailored to these most at-risk students.

## Contribution Table
| Team Member | Contribution |
| --- | --- |
| Tyler Reasoner | Meeting Coordination, Dataset Research, Contribution Table, Video Slides |
| Alik Emelianov | Dataset Research, Intro & Background, GitHub Creation, Submission |
| Arjun Ramani | Problem Definition, Proposed Timeline, Gantt Chart |
| Roy Harrison | Methods, Potential Results & Discussion |
| Dashiel Heidt | Video Script, Video Narration, Video Editing |

## Additional Materials
Presentation Slides:
[Link to Slides](https://docs.google.com/presentation/d/1xrt0yRC76JdiU6q66skm9aSLTgcXUeyH2F0t7HeteMs/edit?usp=sharing)
<br>
Gantt Chart:
[Link to Gantt Chart](https://docs.google.com/spreadsheets/d/1ffgaEJgp1C5RCP0d-mwu_piYM0wTb66OEJxfO0703rY/edit?usp=sharing)
<br>
Dataset:
[Link to Dataset](https://archive-beta.ics.uci.edu/dataset/697/predict+students+dropout+and+academic+success)

## Work Cited
[1] Lavanya, V, and K. Santhi Sree. “Factors Influencing Students Dropout: A Machine Learning Based Study.” IJCRT.org, International Journal of Creative Research Thoughts, 6 June 2021, https://ijcrt.org/papers/IJCRT2106341.pdf.
<br>
[2] Realinho,Valentim, Vieira Martins,Mónica, Machado,Jorge & Baptista,Luís. (2021). Predict students' dropout and academic success. UCI Machine Learning Repository. https://doi.org/1.
<br>
[3] Vuolo, Mike et al. “The value of educational degrees in turbulent economic times: Evidence from the Youth Development Study.” Social science research vol. 57 (2016): 233-52. doi:10.1016/j.ssresearch.2015.12.014
