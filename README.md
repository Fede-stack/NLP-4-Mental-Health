# NLP-4-Mental-Health

## Mental Health datasets available in the wild

### DAIS-C corpus

The DAIS-C stands out as an exceptional open source resource due to its methodologically rigorous construction combining best practices in corpus linguistics with careful documentation of design decisions for clinical language data - probably one of the best resource you could ask for. The corpus uniquely captures both schizophrenia and non-clinical participants discussing creative language use, with multiple file formats and annotation layers that support various types of analysis from computational to qualitative research. 

- paper: https://www.sciencedirect.com/science/article/pii/S2666799123000291
- dataset: https://beta.ukdataservice.ac.uk/datacatalogue/studies/study?id=855021#!/access-data

### MENTALCHAT16K

MentalChat16K is a new English benchmark dataset for mental health counseling that combines two key components: (1) synthetic mental health counseling conversations generated using GPT-3.5 Turbo (10K conversations) and (2) anonymized transcripts from real interventions between Behavioral Health Coaches and Caregivers of patients in palliative/hospice care (6K conversations). The dataset is designed to facilitate the development and evaluation of large language models for mental health support, covering topics like depression, anxiety, grief and other mental health conditions. 

- paper: https://openreview.net/pdf?id=ISBmUNKPST
- dataset link: https://huggingface.co/datasets/ShenLab/MentalChat16K

### SMHD & RSSD 

The SMHD dataset comprises Reddit posts from over 9,000 users with self-reported diagnoses across 9 mental health conditions (depression, ADHD, anxiety, bipolar, PTSD, autism, OCD, schizophrenia, and eating disorders) matched with 107,274 control users, created using high-precision patterns and careful control user matching. The RSDD dataset is similar in scale but focuses specifically on depression diagnoses from Reddit users, with an additional manual annotation step requiring three annotators to verify each self-reported diagnosis claim.

- paper SMHD: https://arxiv.org/pdf/1806.05258
- paper RSSD: https://arxiv.org/pdf/1709.01848
- instructions: https://ir.cs.georgetown.edu/resources/


 ### Mental Health Conversations
 
This dataset exemplifies how to train an AI model to provide empathetic and supportive responses to users seeking help or expressing emotional distress. The data structure shows various ways to respond to requests for help and expressions of sadness, with outputs that consistently demonstrate empathy, offer support, and encourage users to share more about their situation through follow-up questions, making it particularly valuable for developing mental health support chatbots.

- dataset: https://huggingface.co/datasets/CalebE/new_mental_health_conversations_all

### Reddit Posts - Covid Pandemic

A comprehensive dataset containing over 1 million Reddit posts from five mental health-related subreddits spanning pre-pandemic, during-pandemic, and post-pandemic periods (January 2019 to August 2022), along with a carefully annotated subset of 800 posts labeled with root causes including personality factors, drug/alcohol abuse, early life environment, and trauma/stress.

- paper: https://www.mdpi.com/2076-3417/14/4/1547
- dataset: https://www.kaggle.com/datasets/entenam/reddit-mental-health-dataset


### Suicidality on Reddit

A datasets of users experiencing suicide-related ideations, suicide-related behaviors or suicide attempt (https://zenodo.org/record/2667859#.YCwdTR1OlQI) manifested through their communication on r/SuicideWatch and associated mental health subreddits. Through a widely recognized questionnaire to assess suicide risk severity, The Columbia Suicide Severity Rating Scale, the domain experts in the study annotated 448 users with following labels: Supportive (new add to C-SSRS and specific to social media), Suicide Ideation, Suicide Behavior, Suicide Attempt.

- dataset: https://zenodo.org/records/4543776#.Y7FJJ9JBwUE

### MentalHelp

The researchers created MentalHelp, a large-scale semi-supervised mental health dataset containing 14 million posts collected from Reddit. The dataset was labeled using an ensemble of three models (flan-T5, Disor-BERT, and Mental-BERT) and includes confidence scores from multiple models to enable filtering subsets with high-quality labels.

- paper: https://aclanthology.org/2024.lrec-main.977.pdf
- dataset: https://github.com/mraihan-gmu/MentalHelp




## Data under Signed Agreement

> eRisk



> Pandora



> CLPsych


> HOPE
 Speaker and Time-aware Joint Contextual Learning for Dialogue-act Classification in Counselling Conversations


> MEMO Dataset

> DAIC-WoZ Dataset


> ALONE Dataset


> Counsel-Chat Dataset


> PAIR Dataset

> https://www.nature.com/articles/s41597-022-01211-x non trovo il link funzionante

> https://as3eem.medium.com/5-must-know-mental-health-counseling-datasets-for-ai-research-dd1a1b9f30b4

### PRIMATE

This paper introduces PRIMATE (PRocess knowledge Integrated Mental heAlth daTasEt), a dataset designed to help train conversational AI systems to generate appropriate follow-up questions when triaging depression cases. The researchers created PRIMATE by annotating Reddit posts against the PHQ-9 (Patient Health Questionnaire-9) depression screening tool, with expert annotators marking whether each PHQ-9 question was already answered in the post content. 

- paper: https://arxiv.org/pdf/2205.13884
- agreement: https://github.com/primate-mh/Primate2022

### MetaHate: A Dataset for Unifying Efforts on Hate Speech Detection

MetaHate is a unified collection of 1.2 million social media comments compiled from 36 different hate speech datasets across platforms like Twitter, Facebook, Reddit, and YouTube, with approximately 20% of the content labeled as hate speech. The dataset includes a diverse range of content types and annotation approaches, making it a comprehensive resource for studying and detecting online hate speech.

- paper: https://stackoverflow.com  
- agreement: https://irlab.org/metahate.html

### DepreSym: A Depression Symptom Annotated Corpus and the Role of LLMs as Assessors of Psychological Markers

DepreSym is a comprehensive dataset of 21,580 sentences from Reddit labeled according to their relevance to 21 depression symptoms specified in the Beck Depression Inventory-II (BDI-II), a standardized clinical questionnaire. The dataset was created by having three expert assessors (including a psychologist) annotate candidate sentences that were selected through a pooling approach from 37 different ranking methods submitted by research teams.

- paper: https://arxiv.org/pdf/2308.10758
- agreement: https://erisk.irlab.org/depresym_dataset.html

### BDI-Sen: A Sentence Dataset for Clinical Symptoms of Depression

BDI-Sen is a dataset of 4,973 annotated sentences from Reddit covering all 21 depression symptoms specified in the Beck Depression Inventory-II (BDI-II), along with 41,200 control sentences. The sentences were manually labeled by three expert annotators (including a psychologist) to indicate whether they provide information about specific depression symptoms. Additionally, each sentence has a severity level (0-3) derived from the original users' responses to the BDI-II questionnaire. 

- paper: https://dl.acm.org/doi/pdf/10.1145/3539618.3591905
- agreement: https://erisk.irlab.org/BDISen.html




paper: https://arxiv.org/pdf/2408.12142
