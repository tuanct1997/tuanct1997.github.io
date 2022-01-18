# KDI-Project : Facilities in Lockdown Period
For more information please refer to the references section
## Acknowledgement
We would like to express my gratitude to all those who gave me possibility to complete this thesis in specific as well as academic supporting in general that we received during the time of my studying at the Trento University.
we wish to express my sincere thanks to **Professor Fausto Giunchiglia** for providing us with all the necessary facilities for the research. Foremost, we would like to send our honest thanks to **Mr. Simone Bocca** and **Mr.Matteo Busso** for sharing expertise, and sincere and valuable guidance and encouragement extended to us during the project.
## Abstract
Our project goal is to study and analyze students’ behavior, the main focus is on the location and movement of students in order to generate a heatmap and to create an average person profile for specific Points of Interest. This project is strictly follow the iTelos methods - [iTelos](https://arxiv.org/abs/2105.09418) in order to secure the reusability of the dataset for any future project.
This project is belong to the course *Knowledge and Data Itergration* of *Trento University*. All the project material is provided and teached by our **Professor Fausto Giunchiglia** and his team - **DISI Group**

## Dataset-Description
**WeNet Diversity pre-pilot data** : This project is part of a WeNet European big study. So the dataset has been provided by the Knowdive research group in Trento university. The dataset was collected last year thanks to the participation of 254 students in Trento University. They answered the necessary question and shared anonymized information about their general location to the Knowdive group. Also, the dataset provides the Point of Interest based on the OpenStreetMap dataset. All the detailed information will be described in the report which is provided inside the repo github below.

## Schema-Description
To fulfill the purpose of the project, we need to find and decide the knowledge resource where we get the ontology information.We decided to pick [schema.org](https://schema.org) as our knowledge resource. The reason is that schema.org is a big collaborative, community activity that is easy to find on the internet with a mission to create , maintain and promote schemas for structured data. It also provides a website that contains all the vocabularies ( ontologies term ) in a hierarchical form.

## ETG-Description
From ER model and by the help of *KOS Application* created by the course's group responsible, we managed to create an ETG model with Protégé. For more detail, please refer to our repo in the *Reference section*

## KG-Description
From the ETG and final data, after perform Semantic Heterogeneity , we can generate the EG out of ETG and data we have. That is the KG that we need. Our KG can be used to answer all the Competancy Question of the project by apply simple SPASQL query. 

## References
More detail and important file can be found at : [github](https://github.com/tuanct1997/KDI_2021_Facilities-activity-in-lockdown)