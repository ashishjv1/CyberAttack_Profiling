# CyberAttack_Profiling
We use low-level attributes ("bash-history") to classify an attack behavior in a CPTC dataset. This repo is the implementation for the paper Cyber Attacker Profiling for Risk Analysis based on Machine Learning.


<ins>Number of Commands entered per team in the CPTC Competition:</ins>

![alt text](https://github.com/ashishjv1/CyberAttack_Profiling/blob/main/fig3.png?raw=true)



Please cite our work: 

@Article{s23042028,
AUTHOR = {Kotenko, Igor and Fedorchenko, Elena and Novikova, Evgenia and Jha, Ashish},
TITLE = {Cyber Attacker Profiling for Risk Analysis Based on Machine Learning},
JOURNAL = {Sensors},
VOLUME = {23},
YEAR = {2023},
NUMBER = {4},
ARTICLE-NUMBER = {2028},
URL = {https://www.mdpi.com/1424-8220/23/4/2028},
ISSN = {1424-8220},
ABSTRACT = {The notion of the attacker profile is often used in risk analysis tasks such as cyber attack forecasting, security incident investigations and security decision support. The attacker profile is a set of attributes characterising an attacker and their behaviour. This paper analyzes the research in the area of attacker modelling and presents the analysis results as a classification of attacker models, attributes and risk analysis techniques that are used to construct the attacker models. The authors introduce a formal two-level attacker model that consists of high-level attributes calculated using low-level attributes that are in turn calculated on the basis of the raw security data. To specify the low-level attributes, the authors performed a series of experiments with datasets of attacks. Firstly, the requirements of the datasets for the experiments were specified in order to select the appropriate datasets, and, afterwards, the applicability of the attributes formed on the basis of such nominal parameters as bash commands and event logs to calculate high-level attributes was evaluated. The results allow us to conclude that attack team profiles can be differentiated using nominal parameters such as bash history logs. At the same time, accurate attacker profiling requires the extension of the low-level attributes list.},
DOI = {10.3390/s23042028}
}
