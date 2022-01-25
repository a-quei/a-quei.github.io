---
layout: page
title: resume
permalink: /resume/
---



Here are some ideas of MSc/BSc projects I am keen to supervise. Besides, I am open to any ideas related to natural language processing, particularly natural language generation. Please don't hesitate to contact me. 

### **Chinese Language Processing**
 

#### **[MSc] Understanding and Modelling the use of "ba" construction**

"ba" construction is one of the major sentence constructions in Chinese. Using "ba" or not using "ba" places a referring expression in different syntactic positions. For example, the following two sentences have the same semantic: (1) wo ba zhe sanbenshu maile; and (2) wo maile zhe sanbenshu.

Nevertheless, it has been suggested that Chinese speakers would choose between them differently given different contexts. A corpus study by J. Chen et al. (2021) suggested that the "ba" construction is preferred if the referring expression is discourse-old (i.e., it has been mentioned in previous discourse) or animate or long (i.e., 3 syllables or more).

In this project, the student will first design an experiment in order to understand the use of "?" construction. If time allows, s/he will build a computational model accordingly.

Reference

1. Chen, J., Fu, G., Yang, S., & Narasimhan, B. (2021). Processing factors and syntactic choice in mandarin child and caregiver speech.

 

#### **[MSc/BSc] Zero Pronoun Production and Resolution**

Chinese is a typical example of "cool" languages (other examples include Japanese and Korean). A language is “cool” if understanding a sentence requires some work on the reader’s or the hearer’s part (Huang, 1984). This highly impacts the use of anaphora. Concretely, pronouns in Chinese are usually omittable and are often more naturally omitted. These omitted pronouns are called zero pronouns.

In the realm of natural language processing, much work has been done for not only zero pronouns resolution and recovery but also zero pronouns production given their contexts.

In this specific project, the student can: (1) extend/develop new zero pronoun resolution/production/recovery models; (2) do interpretability research to understand what have statistical zero pronoun resolution/production/recovery models learnt; (3) investigate the impacts of recovering zero pronouns on downstream tasks (i.e., machine translation, dialogue systems, etc.).

Reference

1. Huang, C. T. J. (1984). On the distribution and reference of empty pronouns. Linguistic inquiry, 531-574.

 

#### **[MSc] Definiteness and Plurality in Chinese**

It has been pointed out that definiteness and plurality in Chinese can be expressed implicitly. For instance, the noun phrase ? in Chinese can be translated to "a book", "the book", "books", and "the books" depending on its context. This project aims to investigate how definiteness and plurality are expressed through either a corpus study or a psycholinguistic study; and build computational models (which could be rule-based, statistical, or deep learning based) accordingly.

 

### **Dialogue Modelling**
 

#### **[MSc/BSc] Analysing the use of Reference in Dialogues**

The use of Referring Expressions (REs) in discourse contexts has been researched extensively. Thanks to the GREC open challenge (Belz et al. 2009), many computational models of RE use have been developed (see Same and van Deemter (2020) for a summary). In contrast, researches about the use of REs in dialogue contexts had entered a period of stasis after Gupta and Stent (2005).

This project is open-ended. Students can explore the use of REs in dialogues from any aspect they prefer. One option is to assess the models in Same and van Deemter (2020) for modelling REs in dialogues using corpora introduced in Gupta and Stent (2005). Another option is to do a corpus analysis for investigating what factors would influence the reference choices in dialogues.

Reference

1. Belz, A., Kow, E., Viethen, J., & Gatt, A. (2009). Generating referring expressions in context: The GREC task evaluation challenges. In Empirical methods in natural language generation (pp. 294-327). Springer, Berlin, Heidelberg.
2. Same, F., & van Deemter, K. (2020, December). A Linguistic Perspective on Reference: Choosing a Feature Set for Generating Referring Expressions in Context. In Proceedings of the 28th International Conference on Computational Linguistics (pp. 4575-4586).
3. Gupta, S., & Stent, A. (2005). Automatic evaluation of referring expression generation using corpora. In Proceedings of the Workshop on Using Corpora for Natural Language Generation (pp. 1-6).

 

### **Natural Language Generation**
 

#### **[MSc/BSc] When do rule-based NLG matter?**

The realm of natural language generation (NLG) has been dominated by Neural Natural Language Generation systems (NNLG, i.e., NLG systems built on deep neural network techniques). Interestingly, it has been pointed out that, for some NLG tasks (e.g., lexicalisation, aggregation, referring expression generation), rule-based systems are easier to be built and have at least on par performance with NNLG systems. Nevertheless, these easy-to-build rule-based systems were overlooked in most NLG evaluations. In other words, many previous studies claimed their NNLG systems are state-of-the-arts without even comparing them to rule-based systems.

This project aims to explore which NLG tasks do rule-based systems matter evaluation. Concretely, in this project, the students will pick one or two NLG tasks, build (simple) rule-based systems for these tasks, and compare their outputs with that of NNLG systems.

 

#### **[MSc] The Cause of Hallucination in NeuralNLG Systems**

Recently, neural methods have dominated the research of NLG. Nevertheless, some researchers pointed out that NeuralNLG systems often hallucinate (i.e., generating content that is not grounded on the inputs; see: https://ehudreiter.com/2019/09/26/generated-texts-must-be-accurate/). This project investigates such an issue in various NLG tasks and attempts to understand its origin.

 

#### **[MSc] Which NLG Evaluator can Capture the Gradations of Error Severity in Automatic Image Descriptions?**

Image description systems generate descriptions in accordance with the input images. They can make various mistakes. Recently, van Miltenburg et al. (2020) demonstrated that some mistakes are more severe than other mistakes. For example, for a description that describes an image where there is a woman who wears a blue shirt and holds a cake, an object error (e.g., generating "a woman wearing a blue shirt holds a rocket") is much more flagrant than an age error (e.g., generating "a girl wearing a blue shirt holds a cake"). van Miltenburg et al. (2020) assessed this idea by conducting experiments on automatic image descriptions in Chinese.

Building on this finding, it is plausible to assess whether the classic and state-of-the-art automatic evaluators (from BLEU to BERTScore) capture such gradations.

Reference
1. van Miltenburg, E., Lu, W. T., Krahmer, E., Gatt, A., Chen, G., Li, L., & van Deemter, K. (2020, December). Gradations of Error Severity in Automatic Image Descriptions. In Proceedings of the 13th International Conference on Natural Language Generation (pp. 398-411).