# NLP 4 Mental Health

The use of datasets in the Mental Health field is often challenging as most of them are unavailable due to the private nature of the data. This can be a significant obstacle for early-stage researchers studying the linguistic characteristics of different behavioral disorders.

The purpose of this repository is to create a collection of resources that can help navigate the various sources that provide, both publicly and privately, datasets usable for research in Mental Health.

We divide the contents based on publicly available content (aka available in the **WWWW** - Wild World Wide Web) and datasets available upon request (by signing a data agreement or contacting the authors).

## Mental Health datasets available in the wild

### DAIS-C corpus (2023)

The DAIS-C stands out as an exceptional open source resource due to its methodologically rigorous construction combining best practices in corpus linguistics with careful documentation of design decisions for clinical language data - probably one of the best resource you could ask for. The corpus uniquely captures both schizophrenia and non-clinical participants discussing creative language use, with multiple file formats and annotation layers that support various types of analysis from computational to qualitative research. 

- paper: https://www.sciencedirect.com/science/article/pii/S2666799123000291
- dataset: https://beta.ukdataservice.ac.uk/datacatalogue/studies/study?id=855021#!/access-data

### MENTALCHAT16K (2024)

MentalChat16K is a new English benchmark dataset for mental health counseling that combines two key components: (1) synthetic mental health counseling conversations generated using GPT-3.5 Turbo (10K conversations) and (2) anonymized transcripts from real interventions between Behavioral Health Coaches and Caregivers of patients in palliative/hospice care (6K conversations). The dataset is designed to facilitate the development and evaluation of large language models for mental health support, covering topics like depression, anxiety, grief and other mental health conditions. 

- paper: https://openreview.net/pdf?id=ISBmUNKPST (*anonymous*)
- dataset link: https://huggingface.co/datasets/ShenLab/MentalChat16K

### Reddit Posts - Covid Pandemic (2024)

A comprehensive dataset containing over 1 million Reddit posts from five mental health-related subreddits spanning pre-pandemic, during-pandemic, and post-pandemic periods (January 2019 to August 2022), along with a carefully annotated subset of 800 posts labeled with root causes including personality factors, drug/alcohol abuse, early life environment, and trauma/stress.

- paper: https://www.mdpi.com/2076-3417/14/4/1547
- dataset: https://www.kaggle.com/datasets/entenam/reddit-mental-health-dataset


### Suicidality on Reddit (2021)

A datasets of users experiencing suicide-related ideations, suicide-related behaviors or suicide attempt (https://zenodo.org/record/2667859#.YCwdTR1OlQI) manifested through their communication on r/SuicideWatch and associated mental health subreddits. Through a widely recognized questionnaire to assess suicide risk severity, The Columbia Suicide Severity Rating Scale, the domain experts in the study annotated 448 users with following labels: Supportive (new add to C-SSRS and specific to social media), Suicide Ideation, Suicide Behavior, Suicide Attempt.

- dataset: https://zenodo.org/records/4543776#.Y7FJJ9JBwUE

### MentalHelp (2024)

The researchers created MentalHelp, a large-scale semi-supervised mental health dataset containing 14 million posts collected from Reddit. The dataset was labeled using an ensemble of three models (flan-T5, Disor-BERT, and Mental-BERT) and includes confidence scores from multiple models to enable filtering subsets with high-quality labels.

- paper: https://aclanthology.org/2024.lrec-main.977.pdf
- dataset: https://github.com/mraihan-gmu/MentalHelp


 ### Mental Health Conversations
 
This dataset exemplifies how to train an AI model to provide empathetic and supportive responses to users seeking help or expressing emotional distress. The data structure shows various ways to respond to requests for help and expressions of sadness, with outputs that consistently demonstrate empathy, offer support, and encourage users to share more about their situation through follow-up questions, making it particularly valuable for developing mental health support chatbots.

- dataset: https://huggingface.co/datasets/CalebE/new_mental_health_conversations_all


### HelaDepDet

The researchers created a dataset of over 40,000 annotated statements from various social networks to detect depression severity levels, making it the largest and most balanced dataset for depression severity classification at the time of publication. The statements were used to evaluate a novel confidence vector method for detecting depression severity, which achieved better performance than existing models.

- paper: https://link.springer.com/chapter/10.1007/978-3-031-42141-9_1
- dataset: https://github.com/KUAS-ubicomp-lab/Depression_Severity_Levels_Dataset


## Datasets Available Upon Request

### eRisk (2017-)

eRisk is a workshop focused on exploring evaluation methodologies, effectiveness metrics, and practical applications of early risk detection on the Internet, with particular emphasis on health and safety-related issues.
The workshop is organized annually as part of CLEF (Conference and Labs of the Evaluation Forum) and features various challenges for participants to solve. These tasks range from the early detection of mental health disorders to measuring their severity. The workshop has been providing datasets since 2017, with new tasks introduced each year. 

- website: https://erisk.irlab.org



### MBTIK9k (2018) & PANDORA (2021)

MBTIK9k is a dataset created by leveraging Reddit flairs - short descriptive tags that users employ to identify themselves in subreddits. In MBTI-related subreddits, users commonly include their MBTI personality type in their flairs, which the authors utilized to extract personality labels for the dataset.

PANDORA represents an advancement in this field, as it moves beyond the MBTI model, which has limited recognition in academic personality psychology, by incorporating Big Five personality labels. The dataset is further enhanced with demographic features, making it more comprehensive for research purposes.

Both datasets share the primary objective of inferring different aspects of personality based on users' Reddit posts.

- paper MBTIK9k: https://aclanthology.org/W18-1112.pdf
- paper PANDORA: https://aclanthology.org/2021.socialnlp-1.12.pdf
- agreement: https://psy.takelab.fer.hr/datasets/all/#dataset-request-form

### SMHD (2018) & RSSD (2017)

The SMHD dataset comprises Reddit posts from over 9,000 users with self-reported diagnoses across 9 mental health conditions (depression, ADHD, anxiety, bipolar, PTSD, autism, OCD, schizophrenia, and eating disorders) matched with 107,274 control users, created using high-precision patterns and careful control user matching. The RSDD dataset is similar in scale but focuses specifically on depression diagnoses from Reddit users, with an additional manual annotation step requiring three annotators to verify each self-reported diagnosis claim. 

- paper SMHD: https://arxiv.org/pdf/1806.05258
- paper RSSD: https://arxiv.org/pdf/1709.01848
- instructions: https://ir.cs.georgetown.edu/resources/

### CLPsych

CLPsych (Computational Linguistics and Clinical Psychology) is a pioneering workshop series that began in 2014 to bridge computational linguistics and mental health research. It has become a significant venue for advancing the application of natural language processing techniques to mental health challenges through its annual shared tasks.

- website: https://clpsych.org


### Panic and Anxiety Dataset (2024)

The researchers collected 1,930 social media posts from Quora (1,502 posts) and Reddit (428 posts) specifically focused on panic and anxiety, with 713 posts labeled as panic and 1,217 as anxiety based on rule-based annotation driven by question formulation. The dataset is composed of first-reply answers to questions about anxiety and panic experiences.

- paper: https://aclanthology.org/2024.clpsych-1.12.pdf

### Depression Twitter Dataset (2024)

This dataset consists of Twitter data from 76 Filipino users (61 with depression and 15 without depression) who were clinically assessed by psychologists, resulting in 86,163 tweets that were manually annotated with 13 depression symptom categories.

- paper: https://data.jmir.org/2024/1/e53365

### HOPE
 Speaker and Time-aware Joint Contextual Learning for Dialogue-act Classification in Counselling Conversations


### MEMO Dataset

### DAIC-WoZ Dataset


### ALONE Dataset


### Counsel-Chat Dataset


### PAIR Dataset

> https://www.nature.com/articles/s41597-022-01211-x non trovo il link funzionante

> https://as3eem.medium.com/5-must-know-mental-health-counseling-datasets-for-ai-research-dd1a1b9f30b4

### PRIMATE (2022)

This paper introduces PRIMATE (PRocess knowledge Integrated Mental heAlth daTasEt), a dataset designed to help train conversational AI systems to generate appropriate follow-up questions when triaging depression cases. The researchers created PRIMATE by annotating Reddit posts against the PHQ-9 (Patient Health Questionnaire-9) depression screening tool, with expert annotators marking whether each PHQ-9 question was already answered in the post content. 

- paper: https://arxiv.org/pdf/2205.13884
- agreement: https://github.com/primate-mh/Primate2022

### MetaHate

MetaHate is a unified collection of 1.2 million social media comments compiled from 36 different hate speech datasets across platforms like Twitter, Facebook, Reddit, and YouTube, with approximately 20% of the content labeled as hate speech. The dataset includes a diverse range of content types and annotation approaches, making it a comprehensive resource for studying and detecting online hate speech.

- paper: https://stackoverflow.com  
- agreement: https://irlab.org/metahate.html

### DepreSym

DepreSym is a comprehensive dataset of 21,580 sentences from Reddit labeled according to their relevance to 21 depression symptoms specified in the Beck Depression Inventory-II (BDI-II), a standardized clinical questionnaire. The dataset was created by having three expert assessors (including a psychologist) annotate candidate sentences that were selected through a pooling approach from 37 different ranking methods submitted by research teams.

- paper: https://arxiv.org/pdf/2308.10758
- agreement: https://erisk.irlab.org/depresym_dataset.html

### BDI-Sen

BDI-Sen is a dataset of 4,973 annotated sentences from Reddit covering all 21 depression symptoms specified in the Beck Depression Inventory-II (BDI-II), along with 41,200 control sentences. The sentences were manually labeled by three expert annotators (including a psychologist) to indicate whether they provide information about specific depression symptoms. Additionally, each sentence has a severity level (0-3) derived from the original users' responses to the BDI-II questionnaire. 

- paper: https://dl.acm.org/doi/pdf/10.1145/3539618.3591905
- agreement: https://erisk.irlab.org/BDISen.html

### Depression on Social Media (2020)

A dataset for studying depression in social media that uses a weak-supervision framework to automatically collect labeled samples of depression and non-depression posts. The dataset was created by applying two heuristics - sentiment polarity scoring and topical similarity with a depression taxonomy - to gather posts from Reddit users who had self-declared being diagnosed with depression, along with control posts from users without depression. 

- paper: https://dl.acm.org/doi/pdf/10.1145/3340631.3394879
- To contact the author to get access


paper: https://arxiv.org/pdf/2408.12142
