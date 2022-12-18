
# Skill Barriers and Social Barriers to a “Just Transition” of U.S. Fossil Fuel Workers to Emerging Green Jobs - 2022
{Skill Barriers and Social Barriers to a “Just Transition” of U.S. Fossil Fuel Workers to Emerging Green Jobs}

* Team (members): Xizhi Wu (email) xiw183@pitt.edu
* Project presentation: click [here](Just_Transition.pdf) to visit presentation slides
* Project paper: click [here](Final_Project_Report_Network_Science.docx.pdf) to visit final report

## Dataset
* For O*NET dataset, please see the O*NET website [here](https://www.onetonline.org/find/descriptor/browse/2.A/2.A.1)
* For Resume dataset, please see the Resume Dataset on Kaggle [here](https://www.kaggle.com/datasets/gauravduttakiit/resume-dataset) or contact the author for his dataset.(xiw@183pitt.edu)

## Description
{Nowadays, we are witnessing a “Just Transition” of fossil fuel workers into emerging green jobs. However, job polarization is widely observed to become a major concern in many societies. Occupations are differentiating into high wage occupations and low wage occupations, requiring distinct skill sets. As a result, mobility for workers between high wage occupations and low wage occupations is constrained. In our “Just Transitions”, this type of difficulties could also be encountered by workers in fossil fuel jobs when adapting to green jobs. We examine this as skill barriers and try to analyze the barriers using the correlation between our derived occupations’ similarity scores and the number of job transitions in a resume dataset. We present this as a novel way to study the skill barriers between jobs requiring distinct skill sets. 
}
* {Just_Transition.pdf: A presentation slide for this project}
* {skills_jobs_transitions.ipynb: Code}
* {skills_jobs_transitions.pdf: A pdf of the colab notebook}
* {Final_Project_Report_Network_Science.docx.pdf: Project report}
* {License: License}
* {Readme: Readme}

## Conclusions
* Fossil fuel occupations heavily rely on sensory-physical skills, while green jobs are more relying on social-cognitive skills. Therefore, the barrier stem from the different skill set required by the two types of jobs. 
* RCA(Revealed Comparative Advantage) emphasize on the relative advantage of a skill to an occupation among all its skills, so this is not the most suitable index to measure job transition. The skills shared by two different occupations can decide job transition, in the future research, we need something that can represent this feature to be an index to replace RCA.
* Required skills of an occupation wouldn’t be the only perspective to examine the barriers, other factors such as market sizes could also be playing vital roles in the transitions.
* Future works should be re-examined the correlation between number of transitions and similarities of skill set under a bigger picture, and considering all the occupations while picking only fossil fuel and green jobs as subjects. Normalizing factors such as market sizes of certain industries should also be investigated.

## Prerequisites
{This project if being run on Google Colab.
If you are using Colab, you will install: !pip install stellargraph
else on a personal notebook, make sure you install any version of the following library: 
matplotlib
gensim
sklearn
networkx
numpy
pandas
stellargraph
collections
multiprocessing}

## Authors
{Xizhi Wu, xiw183@pitt.edu}

## Acknowledgments
{I would like to thank Dr. Frank for giving me guidance implementing my ideas. 
I would like to thank Alireza for helping me on the dataset!}

## License
{click [here](License) to see License}
[MIT](https://choosealicense.com/licenses/mit/)
