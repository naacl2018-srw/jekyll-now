---
layout: page
title: Accepted Papers
permalink: /accepted-papers/
---



### **Igbo Diacritic Restoration using Embedding Models**

#### _Ignatius Ezeani, Mark Hepple, Ikechukwu Onyenwe and Enemouh Chioma_
Igbo is a low-resource language spoken by approximately 30 million people worldwide. It is the native language of the Igbo people of south-eastern Nigeria. In Igbo language, diacritics - orthographic and tonal - play a huge role in the distinguishing the meaning and pronunciation of words. Omitting diacritics in texts often leads to lexical ambiguity. Diacritic restoration is a pre-processing task that replaces missing diacritics on words from which they have been removed. In this work, we applied embedding models to the diacritic restoration task and compared their performances to those of n-gram models. Although word embedding models have been successfully applied to various NLP tasks, it has not been used, to our knowledge, for diacritic restoration. Two classes of word embeddings models were used: those projected from the English embedding space; and those trained with Igbo bible corpus (≈ 1m). Our best result, 82.49%, is an improvement on the baseline n-gram models.


### **Generating Image Captions in Arabic using Root-Word Based Recurrent Neural Networks and Deep Neural Networks**

#### _Vasu Jindal_
Image caption generation has gathered widespread interest in the artificial intelligence community. Automatic generation of an image description requires both computer vision and natural language processing techniques.  While, there has been advanced research in the English caption generation,  research on generating Arabic descriptions of an image is extremely limited.  Semitic languages like Arabic are heavily influenced by root-words.  We leverage this critical dependency of Arabic to generate captions of an image directly in Arabic using  root-word based Recurrent Neural Network and Deep Neural Networks.  Experimental results on dataset from various Middle Eastern newspaper websites allow us to report the first BLEU score for direct Arabic caption generation.  We also compare the results of our approach with BLEU score captions generated in English and translated in Arabic. Experimental results confirm that generating image captions using root-words directly in Arabic significantly outperforms the English-Arabic translated captions using state-of-the-art methods.


### **Japanese Predicate Conjugation for Neural Machine Translation**

#### _Michiki Kurosawa, Yukio Matsumura, Hayahide Yamagishi and Mamoru Komachi_
Neural machine translation (NMT) has a drawback in that can generate only high-frequency words owing to the computational costs of the softmax function in the output layer.  In Japanese-English NMT, Japanese predicate conjugation causes an increase in vocabulary size. For example, one verb can have as many as 19 surface varieties. In this research, we focus on predicate conjugation for compressing the vocabulary size in Japanese. The vocabulary list is filled with the various forms of verbs. We propose methods using predicate conjugation information without discarding linguistic information. The proposed methods can generate low-frequency words and deal with unknown words. Two methods were considered to introduce conjugation information: the first considers it as a token (conjugation token) and the second considers it as an embedded vector (conjugation feature).  The results using these methods demonstrate that the vocabulary size can be compressed by approximately 86.1% (Tanaka corpus) and the NMT models can output the words not in the training data set. Furthermore, BLEU scores improved by 0.91 points in Japanese-to-English translation, and 0.32 points in English-to-Japanese translation with ASPEC.


### **Read and Comprehend by Gated-Attention Reader with More Belief**

#### _Haohui Deng and Yik-Cheung Tam_
Gated-Attention (GA) Reader has been effective for reading comprehension. GA Reader makes two assumptions: (1) a uni-directional attention that uses an input query to gate token encodings of a document; (2) encoding at the cloze position of an input query is considered for answer prediction. In this paper, we propose Collaborative Gating (CG) and Self-Belief Aggregation (SBA) to address the above assumptions respectively. In CG, we first use an input document to gate token encodings of an input query so that the influence of irrelevant query tokens may be reduced. Then the filtered query is used to gate token encodings of an document in a collaborative fashion. In SBA, we conjecture that query tokens other than the cloze token may be informative for answer prediction. We apply self-attention to link the cloze token with other tokens in a query so that the importance of query tokens with respect to the cloze position are weighted. Then their evidences are weighted, propagated and aggregated for better reading comprehension. Experiments show that our approaches advance the state-of-theart results in CNN, Daily Mail, and Who Did What public test sets.


### **Metric for Automatic Machine Translation Evaluation based on Universal Sentence Representations**

#### _Hiroki Shimanaka, Tomoyuki Kajiwara and Mamoru Komachi_
Sentence representations can capture a wide range of information that cannot be captured by local features based on character or word N-grams.  This paper examines the usefulness of universal sentence representations for eval- uating the quality of machine translation.  Al-though it is difficult to train sentence represen- tations using small-scale translation datasets with manual evaluation, sentence representa- tions trained from large-scale data in other tasks can improve the automatic evaluation of machine translation.  Experimental results of the WMT-2016 dataset show that the proposed method achieves state-of-the-art performance with sentence representation features only.


### **Combining Abstractness and Language-specific Theoretical Indicators for Detecting Non-Literal Usage of Estonian Particle Verbs**

#### _Eleri Aedmaa, Maximilian Köper and Sabine Schulte im Walde_
This paper presents two novel datasets and a random-forest classifier to automatically predict literal vs. non-literal language usage for a highly frequent type of multi-word expression in a low-resource language, i.e., Estonian. We demonstrate the value of language-specific indicators induced from theoretical linguistic research, which outperform a high majority baseline when combined with language-independent features of non-literal language (such as abstractness).


### **Corpus Creation and Emotion Prediction for Hindi-English Code-Mixed Social Media Text**

#### _Deepanshu Vijay, Aditya Bohra, Vinay Singh, Syed Sarfaraz Akhtar and Manish Shrivastava_
Emotion Prediction is a Natural Language Processing (NLP) task dealing with detection and classification of emotions in various monolingual and bilingual texts. While some work has been done on code-mixed social media text and in emotion prediction separately, our work is the first attempt which aims at identifying the emotion associated with Hindi-English code-mixed social media text. In this paper, we analyze the problem of emotion identification in code-mixed content and present a Hindi-English code-mixed corpus extracted from twitter and annotated with the associated emotion. For every tweet in the dataset, we annotate the source language of all the words present, and also the causal language of the expressed emotion. Finally, we propose a supervised classification system which uses various machine learning techniques for detecting the emotion associated with the text using a variety of character level, word level, and lexicon based features.


### **Verb Alternations and Their Impact on Frame Induction**

#### _Esther Seyffarth_
Frame induction is the automatic creation of frame-semantic resources similar to FrameNet or PropBank, which map lexical units of a language to frame representations of each lexical unit's semantics. For verbs, these representations usually include a specification of their argument slots and of the selectional restrictions that apply to each slot. Verbs that participate in diathesis alternations have different syntactic realizations whose semantics are closely related, but not identical. We discuss the influence that such alternations have on frame induction, compare several possible frame structures for verbs in the causative alternation, and propose a systematic analysis of alternating verbs that encodes their similarities as well as their differences.


### **A Generalized Knowledge Hunting Framework for the Winograd Schema Challenge**

#### _Ali Emami, Adam Trischler, Kaheer Suleman and Jackie Chi Kit Cheung_
We  introduce  an  automatic  system  that performs well on two common-sense rea- soning tasks, the Winograd Schema Challenge (WSC) and the Choice of Plausible Alternatives  (COPA).  Problem  instances from  these  tasks  require  diverse,   complex  forms  of  inference  and  knowledge to solve.  Our method uses a knowledge-hunting  module  to  gather  text  from  the web,  which  serves  as  evidence  for  candidate problem resolutions.  Given an input  problem,  our  system  generates  relevant  queries  to  send  to  a  search  engine. It extracts and classifies knowledge from the returned results and weighs it to make a  resolution.   Our  approach  improves  F1 performance on the WSC by 0.16 over the previous best and is competitive with the state-of-the-art  on  COPA,  demonstrating its general applicability.


### **Learning Word Embeddings for Data Sparse and Sentiment Rich Data Sets**

#### _Prathusha Kameswara Sarma_
This research proposal describes two algorithms that are aimed at learning word embeddings for data sparse and sentiment rich data sets. The goal is to use word embeddings adapted for domain specific data sets in downstream applications such as sentiment classification. The first approach learns word embeddings in a supervised fashion via SWESA (Supervised Word Embeddings for Sentiment Analysis), an algorithm for sentiment analysis on data sets that are of modest size. SWESA leverages document labels to jointly learn polarity-aware word embeddings and a classifier to classify unseen documents. In the second approach domain adapted (DA) word embeddings are learned by exploiting the specificity of domain specific data sets and the breadth of generic word embeddings. The new embeddings are formed by aligning corresponding word vectors using Canonical Correlation Analysis (CCA) or the related nonlinear Kernel CCA. Experimental results on binary sentiment classification tasks using both approaches for standard data sets are presented.


### **Sensing and Learning Human Annotators Engaged in Narrative Sensemaking**

#### _McKenna Tornblad, Luke Lapresi, Christopher Homan, Raymond Ptucha and Cecilia Ovesdotter Alm_
While labor issues and quality assurance in crowdwork are increasingly studied, how annotators make sense of texts and how they are personally impacted by doing so are not. We study these questions via a narrative-sorting annotation task, where carefully selected (by sequentiality, topic, emotional content, and length) collections of tweets serve as examples of everyday storytelling. As readers process these narratives, we measure their facial expressions, galvanic skin response, and self-reported reactions. From the perspective of annotator well-being, a reassuring outcome was that the sorting task did not cause a measurable stress response, however readers reacted to humor. In terms of sensemaking, readers were more confident when sorting sequential, target-topical, and highly emotional tweets. As crowdsourcing becomes more common, this research sheds light onto the perceptive capabilities and emotional impact of human readers.


### **Towards Qualitative Word Embeddings Evaluation: Measuring Neighbors Variation**

#### _Benedicte Pierrejean and Ludovic Tanguy_
We propose a method to study the variation lying between different word embeddings models trained with different parameters. We explore the variation between models trained with only one varying parameter by observing the distributional neighbors variation and show how changing only one parameter can have a massive impact on a given semantic space. We show that the variation is not affecting all words of the semantic space equally. Variation is influenced by parameters such as setting a parameter to its minimum or maximum value but it also depends on the corpus intrinsic features such as the frequency of a word. We identify semantic classes of words remaining stable across the models trained and specific words having high variation.


### **A Deeper Look into Dependency-Based Word Embeddings**

#### _Sean MacAvaney and Amir Zeldes_
We investigate the effect of various dependency-based word embeddings on distinguishing between functional and domain similarity, word similarity rankings, and two downstream tasks in English. Variations include word embeddings trained using context windows from Stanford and Universal dependencies at several levels of enhancement (ranging from unlabeled, to Enhanced++ dependencies). Results are compared to basic linear contexts and evaluated on several datasets. We found that embeddings trained with Universal and Stanford dependency contexts excel at different tasks, and that enhanced dependencies often improve performance.


### **Using Classifier Features to Determine Language Transfer on Morphemes**

#### _Alexandra Lavrentovich_
The aim of this thesis is to perform a Native Language Identification (NLI) task where we identify an English learner's native language background based only on the learner's English writing samples. We focus on the use of English grammatical morphemes across four proficiency levels. The outcome of the computational task is connected to a position in second language acquisition research that holds all learners acquire English grammatical morphemes in the same order, regardless of native language background. We use the NLI task as a tool to uncover cross-linguistic influence on the developmental trajectory of morphemes. We perform a cross-corpus evaluation across proficiency levels to increase the reliability and validity of the linguistic features that predict the native language background. We include native English data to determine the different morpheme patterns used by native versus non-native English speakers. Furthermore, we conduct a human NLI task to determine the type and magnitude of language transfer cues used by human raters versus the classifier.


### **Training a Ranking Function for Open-Domain Question Answering**

#### _Phu Mon Htut, Samuel Bowman and Kyunghyun Cho_
In recent years, there have been amazing advances in deep learning methods for machine reading. In machine reading, the machine reader has to extract the answer from the given ground truth paragraph. Recently, the state-of-the-art machine reading models achieve human level performance in SQuAD which is a reading comprehension-style question answering (QA) task. The success of machine reading has inspired researchers to combine Information Retrieval with machine reading to tackle open-domain QA. However, these systems perform poorly compared to reading comprehension-style QA because it is difficult to retrieve the pieces of paragraphs that contain the answer to the question. In this study, we propose two neural network rankers that assign scores to different passages based on their likelihood of containing the answer to a given question. Additionally, we analyze the relative importance of semantic similarity and word level relevance matching in open-domain QA.


### **Alignment, Acceptance, and Rejection of Group Identities in Online Political Discourse**

#### _Hagyeong Shin and Gabriel Doyle_
Conversation is a joint social process, with participants cooperating to exchange information. This process is helped along through linguistic alignment: participants' adoption of each other's word use. This alignment is robust, appearing many settings, and is nearly always positive. We create an alignment model for examining alignment in Twitter conversations across antagonistic groups. This model finds that some word categories, specifically pronouns used to establish group identity and common ground, are negatively aligned. This negative alignment is observed despite other categories, which are less related to the group dynamics, showing the standard positive alignment.  This suggests that alignment is strongly biased toward cooperative alignment, but that different linguistic features can show substantially different behaviors.


### **Neural Machine Translation for Low Resource Languages using Bilingual Lexicon Induced from Comparable Corpora**

#### _Sree Harsha Ramesh and Krishna Prasad Sankaranarayanan_
Resources for the non-English languages are scarce and this paper addresses this problem in the context of machine translation, by automatically extracting parallel sentence pairs from the multilingual articles available on the Internet. In this paper, we have used an end-to-end Siamese bidirectional recurrent neural


network to generate parallel sentences from comparable multilingual articles in Wikipedia. Subsequently, we have showed that using the harvested dataset improved BLEU scores on both NMT and phrase-based SMT systems for the low-resource language pairs: English–Hindi and English–Tamil, when compared to training exclusively on the limited bilingual corpora collected for these language pairs."
### **End-to-End Learning of Task-Oriented Dialogs**

#### _Bing Liu_
In this thesis proposal, we address the limitations of conventional pipeline design of task-oriented dialog systems and propose end-to-end learning solutions. We design neural network based dialog system that is able to robustly track dialog state, interface with knowledge bases, and incorporate structured query results into system responses to successfully complete task-oriented dialog. In learning such neural network based dialog systems, we propose hybrid offline training and online interactive learning methods. We introduce a multi-task learning method in pre-training the dialog agent in a supervised manner using task-oriented dialog corpora. The supervised training agent can further be improved via interacting with users and learning online from user demonstration and feedback with imitation and reinforcement learning. In addressing the sample efficiency issue with online policy learning, we further propose a method by combining the learning-from-user and learning-from-simulation approaches to improve the online interactive learning efficiency.


### **ListOps: A Diagnostic Dataset for Latent Tree Learning**

#### _Nikita Nangia and Samuel Bowman_
Latent tree learning models learn to parse a sentence without syntactic supervision, and use that parse to build the sentence representation. Existing work on such models has shown that, while they perform well on tasks like sentence classification, they do not learn grammars that conform to any plausible semantic or syntactic formalism (Williams et al., 2018a). Studying the parsing ability of such models in natural language can be challenging due to the inherent complexities of natural language, like having several valid parses for a single sentence. In this paper we introduce ListOps, a toy dataset created to study the parsing ability of latent tree models. ListOps sequences are in the style of prefix arithmetic. The dataset is designed to have a single correct parsing strategy that a system needs to learn to succeed at the task. We show that the current leading latent tree models are unable to learn to parse and succeed at ListOps. These models achieve accuracies worse than purely sequential RNNs.


### **Towards Generating Personalized Hospitalization Summaries**

#### _Sabita Acharya, Barbara Di Eugenio, Andrew Boyd, Richard Cameron, Karen Dunn Lopez, Pamela Martyn-Nemeth, Carolyn Dickens and Amer Ardati_
Most of the health documents, including patient education materials and discharge notes, are usually flooded with medical jargons and contain a lot of generic information about the health issue. In addition, patients are only provided with the doctor’s perspective of what happened to them in the hospital while the care procedure performed by nurses during their entire hospital stay is nowhere included. The main focus of this research is to generate personalized hospital-stay summaries for patients by combining information from physician discharge notes and nursing plan of care. It uses a metric to identify medical concepts that are Complex, extracts definitions for the concept from three external knowledge sources, and provides the simplest definition to the patient. It also takes various features of the patient into account, like their concerns and strengths, ability to understand basic health information, level of engagement in taking care of their health, and familiarity with the health issue and personalizes the content of the summaries accordingly. Our evaluation showed that the summaries contain 80% of the medical concepts that are considered as being important by both doctor and nurses. Three patient advisors (i.e. individuals who are trained in understanding patient experience extensively) verified the usability of our summaries and mentioned that they would like to get such summaries when they are discharged from hospital.


