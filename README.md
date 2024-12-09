# Queer NLP Paper Repository
This repository collects papers that sit at the intersection between the queer community and natural language processing. It is sorted by tasks, and a single paper can appear in multiple sections. Tasks are presented in alphabetical order and papers are presented in chronological order. 

This repository does not contain:
- papers from outside of NLP (e.g. linguistics, sociology, gender studies, ...)
- papers that don't explicitly mention the queer community or subsets of the queer community

## Table of Contents
- [Coreference Resolution](#coreference-resolution)
- [Data Collection](#data-collection)
- [Evaluation, Benchmarks](#evaluation-benchmarks)
- [Gender Bias Including Nonbinary Genders](#gender-bias-including-nonbinary-genders)
- [LLMs](#llms)
- [Media Analysis using NLP](#media-analysis-using-nlp)
- [POS Tagging](#pos-tagging)
- [Question Answering](#question-answering)
- [Sentiment Analysis](#sentiment-analysis)
- [Text Classification](#text-classification)
- [Text to Image](#text-to-image)
- [Toxicity and Hate Speech](#toxicity-and-hate-speech)
- [Translation](#translation)
- [Other](#other)
-[Position Papers](#position-papers)
-[Unsure what topic](#unsure-what-topic)


## Coreference Resolution

Ankith Uppunda, Susan Cochran, Jacob Foster, Alina Arseniev-Koehler, Vickie Mays, and Kai-Wei Chang. 2021. Adapting Coreference Resolution for Processing Violent Death Narratives. In Proceedings of the 2021 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies, pages 4553–4559, Online. Association for Computational Linguistics.

WinoPron: Revisiting English Winogender Schemas for Consistency, Coverage, and Grammatical Case V. Gautam, J. Steuer, E. Bingert, R. Johns, A. Lauscher, D. Klakow. Workshop on Computational Models of Reference, Anaphora and Coreference, 2024.

Robust Pronoun Fidelity with English LLMs: Are they Reasoning, Repeating, or Just Biased? V. Gautam, E. Bingert, D. Zhu, A. Lauscher, D. Klakow. Transactions of ACL, 2024 (to appear).

## Data Collection

Hicks, Amanda, et al. "An analysis of wordnet’s coverage of gender identity using twitter and the national transgender discrimination survey." Proceedings of the 8th global wordnet conference (gwc). 2016.

Jesse Dodge, Maarten Sap, Ana Marasović, William Agnew, Gabriel Ilharco, Dirk Groeneveld, Margaret Mitchell, and Matt Gardner. 2021. Documenting Large Webtext Corpora: A Case Study on the Colossal Clean Crawled Corpus. In Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing, pages 1286–1305, Online and Punta Cana, Dominican Republic. Association for Computational Linguistics.

## Evaluation, Benchmarks

Barikeri, Soumya, et al. "RedditBias: A Real-World Resource for Bias Evaluation and Debiasing of Conversational Language Models." Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing (Volume 1: Long Papers). 2021.

Juan Vásquez, Gemma Bel-Enguix, Scott Thomas Andersen, and Sergio-Luis Ojeda-Trueba. 2022. HeteroCorpus: A Corpus for Heteronormative Language Detection. In Proceedings of the 4th Workshop on Gender Bias in Natural Language Processing (GeBNLP), pages 225–234, Seattle, Washington. Association for Computational Linguistics.

Juan Vásquez, Scott Andersen, Gemma Bel-enguix, Helena Gómez-adorno, and Sergio-luis Ojeda-trueba. 2023. HOMO-MEX: A Mexican Spanish Annotated Corpus for LGBT+phobia Detection on Twitter. In The 7th Workshop on Online Abuse and Harms (WOAH), pages 202–214, Toronto, Canada. Association for Computational Linguistics.

Dennler, Nathan, et al. "Bound by the Bounty: Collaboratively Shaping Evaluation Processes for Queer AI Harms." Proceedings of the 2023 AAAI/ACM Conference on AI, Ethics, and Society. 2023.

Bunzeck, Bastian, and Sina Zarrieß. "The SlayQA benchmark of social reasoning: testing gender-inclusive generalization with neopronouns." Proceedings of the 2nd GenBench Workshop on Generalisation (Benchmarking) in NLP. 2024.

Piergentili, Andrea, et al. "Hi Guys or Hi Folks? Benchmarking Gender-Neutral Machine Translation with the GeNTE Corpus."

## Gender Bias Including Nonbinary Genders

Rudinger, Rachel, et al. "Gender Bias in Coreference Resolution." Proceedings of the 2018 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies, Volume 2 (Short Papers). 2018

Devinney, Hannah, Jenny Björklund, and Henrik Björklund. "Semi-supervised topic modeling for gender bias discovery in English and Swedish." GeBNLP2020, COLING'2020–The 28th International Conference on Computational Linguistics, December 8-13, 2020, Online. Association for Computational Linguistics, 2020.

Hansson, Saga, et al. "The Swedish Winogender Dataset." Proceedings of the 23rd Nordic Conference on Computational Linguistics (NoDaLiDa). 2021.

Havens, Lucy, et al. "Uncertainty and inclusivity in gender bias annotation: An annotation taxonomy and annotated datasets of British English text." 4th Workshop on Gender Bias in Natural Language Processing at NAACL. ACL Anthology, 2022.

## LLMs

Nozza, Debora, et al. "Measuring Harmful Sentence Completion in Language Models for LGBTQIA+ Individuals." LTEDI 2022 (2022): 26.

Anaelia Ovalle, Palash Goyal, Jwala Dhamala, Zachary Jaggers, Kai-Wei Chang, Aram Galstyan, Richard Zemel, and Rahul Gupta. 2023. “I’m fully who I am”: Towards Centering Transgender and Non-Binary Voices to Measure Biases in Open Language Generation. In Proceedings of the 2023 ACM Conference on Fairness, Accountability, and Transparency (FAccT '23). Association for Computing Machinery, New York, NY, USA, 1246–1266. https://doi.org/10.1145/3593013.3594078

Felkner, Virginia, et al. "WinoQueer: A Community-in-the-Loop Benchmark for Anti-LGBTQ+ Bias in Large Language Models." Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers). 2023.

Hossain, Tamanna, Sunipa Dev, and Sameer Singh. "MISGENDERED: Limits of Large Language Models in Understanding Pronouns." Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers). 2023.

​​Dhingra, Harnoor, et al. "Queer People are People First: Deconstructing Sexual Identity Stereotypes in Large Language Models." arXiv e-prints (2023): arXiv-2307.

Ovalle, Anaelia, et al. "The Root Shapes the Fruit: On the Persistence of Gender-Exclusive Harms in Aligned Language Models." arXiv preprint arXiv:2411.03700 (2024).

Selma Bergstrand and Björn Gambäck. 2024. Detecting and Mitigating LGBTQIA+ Bias in Large Norwegian Language Models. In Proceedings of the 5th Workshop on Gender Bias in Natural Language Processing (GeBNLP), pages 351–364, Bangkok, Thailand. Association for Computational Linguistics.

Shir Lissak, Nitay Calderon, Geva Shenkman, Yaakov Ophir, Eyal Fruchter, Anat Brunstein Klomek, and Roi Reichart. 2024. The Colorful Future of LLMs: Evaluating and Improving LLMs as Emotional Supporters for Queer Youth. In Proceedings of the 2024 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies (Volume 1: Long Papers), pages 2040–2079, Mexico City, Mexico. Association for Computational Linguistics.
Marion Bartl and Susan Leavy. 2024. From ‘Showgirls’ to ‘Performers’: Fine-tuning with Gender-inclusive Language for Bias Reduction in LLMs. In Proceedings of the 5th Workshop on Gender Bias in Natural Language Processing (GeBNLP), pages 280–294, Bangkok, Thailand. Association for Computational Linguistics.

Xie, Sean, Saeed Hassanpour, and Soroush Vosoughi. "Addressing Healthcare-related Racial and LGBTQ+ Biases in Pretrained Language Models." Findings of the Association for Computational Linguistics: NAACL 2024. 2024.

Knupleš, Urban, Agnieszka Falenska, and Filip Miletić. "Gender Identity in Pretrained Language Models: An Inclusive Approach to Data Creation and Probing." Findings of the Association for Computational Linguistics: EMNLP 2024. 2024.

Devinney, Hannah, Jenny Björklund, and Henrik Björklund. "We don’t talk about that: case studies on intersectional analysis of social bias in large language models." Workshop on Gender Bias in Natural Language Processing (GeBNLP), Bangkok, Thailand, 16th August, 2024.. Association for Computational Linguistics, 2024.

Sheng, Emily, et al. "The Woman Worked as a Babysitter: On Biases in Language Generation."


## Media Analysis using NLP 

Hicks, Amanda, et al. <a href="https://aclanthology.org/2016.gwc-1.19.pdf">"<u>An analysis of wordnet’s coverage of gender identity using twitter and the national transgender discrimination survey."</u></a> Proceedings of the 8th global wordnet conference (gwc). 2016.

Hung, Han-Tang, and Shu-Kai Hsieh. <a href="https://aclanthology.org/2020.paclic-1.47.pdf">"<u>Exploring Discourse on Same-sex Marriage in Taiwan: A Case Study of Near-Synonym of HOMOSEXUAL in Opposing Stances."</u></a>  Proceedings of the 34th Pacific Asia Conference on Language, Information and Computation. 2020.

Sky CH-Wang and David Jurgens. 2021. Using Sociolinguistic Variables to Reveal Changing Attitudes Towards Sexuality and Gender. In Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing, pages 9918–9938, Online and Punta Cana, Dominican Republic. Association for Computational Linguistics.

Lin, Yu-Hsuan. "Comparison on Heterosexual and Homosexual Woman’s Lonely Heart Ads in Taiwan: Taking AllTogether and Lesbian Board on PTT Web Forum as Examples." Proceedings of the Joint 3rd International Conference on Natural Language Processing for Digital Humanities and 8th International Workshop on Computational Linguistics for Uralic Languages. 2023.

Locatelli, Davide, Greta Damo, and Debora Nozza. "A cross-lingual study of homotransphobia on twitter." Proceedings of the First Workshop on Cross-Cultural Considerations in NLP (C3NLP). 2023.

Chakravarthi, Bharathi Raja, et al. "A Diachronic Analysis of Gender-Neutral Language on wikiHow" Proceedings of the Fourth Workshop on Language Technology for Equality, Diversity, Inclusion. 2024.

Andersen, Scott, et al. "The Mexican Gayze: A Computational Analysis of the Attitudes towards the LGBT+ Population in Mexico on Social Media Across a Decade." Proceedings of the 8th Workshop on Online Abuse and Harms (WOAH 2024). 2024.

Farhan Samir, Chan Young Park, Anjalie Field, Vered Shwartz, and Yulia Tsvetkov. 2024. Locating Information Gaps and Narrative Inconsistencies Across Languages: A Case Study of LGBT People Portrayals on Wikipedia. In Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing, pages 6747–6762, Miami, Florida, USA. Association for Computational Linguistics.

## POS Tagging

Björklund, Henrik, and Hannah Devinney. "Computer, enhence: POS-tagging improvements for nonbinary pronoun use in Swedish." Proceedings of the Third Workshop on Language Technology for Equality, Diversity and Inclusion. 2023.

## Question Answering

Bunzeck, Bastian, and Sina Zarrieß. "The SlayQA benchmark of social reasoning: testing gender-inclusive generalization with neopronouns." Proceedings of the 2nd GenBench Workshop on Generalisation (Benchmarking) in NLP. 2024.

## Sentiment Analysis
Ungless, Eddie L., Bjorn Ross, and Vaishak Belle. "Potential Pitfalls With Automatic Sentiment Analysis: The Example of Queerphobic Bias." (2023).

## Text Classification

Wu, Hsiao-Han, and Shu-Kai Hsieh. "Exploring Lavender Tongue from Social Media Texts [In Chinese]." Proceedings of the 29th Conference on Computational Linguistics and Speech Processing (ROCLING 2017). 2017.

Guanhua Zhang, Bing Bai, Junqi Zhang, Kun Bai, Conghui Zhu, and Tiejun Zhao. 2020. Demographics Should Not Be the Reason of Toxicity: Mitigating Discrimination in Text Classifications with Instance Weighting. In Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics, pages 4134–4145, Online. Association for Computational Linguistics.

Waldis, Andreas, et al. "The Lou Dataset-Exploring the Impact of Gender-Fair Language in German Text Classification." Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing. 2024.

## Text to Image

Ungless, Eddie, Björn Ross, and Anne Lauscher. "Stereotypes and Smut: The (Mis) representation of Non-cisgender Identities by Text-to-Image Models." 61st Annual Meeting of the Association for Computational Linguistics. Association for Computational Linguistics (ACL), 2023.

## Toxicity and Hate Speech

Zueva, Nadezhda, Madina Kabirova, and Pavel Kalaidin. "Reducing Unintended Identity Bias in Russian Hate Speech Detection." Proceedings of the Fourth Workshop on Online Abuse and Harms. 2020.

Díaz, Mark, et al. "Accounting for offensive speech as a practice of resistance." Proceedings of the sixth workshop on online abuse and harms (woah). 2022.

Elsafoury, Fatma, et al. "SOS: Systematic Offensive Stereotyping Bias in Word Embeddings." Proceedings of the 29th International Conference on Computational Linguistics. 2022.

Elsafoury, Fatma, Steven R. Wilson, and Naeem Ramzan. "A comparative study on word embeddings and social NLP tasks." Proceedings of the Tenth International Workshop on Natural Language Processing for Social Media. 2022.

Sahoo, Nihar, Himanshu Gupta, and Pushpak Bhattacharyya. "Detecting Unintended Social Bias in Toxic Language Datasets." Proceedings of the 26th Conference on Computational Natural Language Learning (CoNLL). 2022.

Lu, Christina, and David Jurgens. "The subtle language of exclusion: Identifying the Toxic Speech of Trans-exclusionary Radical Feminists." Proceedings of the sixth workshop on online abuse and harms (WOAH). 2022.

Mun, Jimin, et al. "Beyond denouncing hate: Strategies for countering implied biases and stereotypes in language." Findings of the Association for Computational Linguistics: EMNLP 2023. 2023.

Juan Vásquez, Scott Andersen, Gemma Bel-enguix, Helena Gómez-adorno, and Sergio-luis Ojeda-trueba. 2023. HOMO-MEX: A Mexican Spanish Annotated Corpus for LGBT+phobia Detection on Twitter. In The 7th Workshop on Online Abuse and Harms (WOAH), pages 202–214, Toronto, Canada. Association for Computational Linguistics.

Locatelli, Davide, Greta Damo, and Debora Nozza. "A cross-lingual study of homotransphobia on twitter." Proceedings of the First Workshop on Cross-Cultural Considerations in NLP (C3NLP). 2023.

Ahani, Z., et al. "Zavira@ DravidianLangTech 2024: Telugu hate speech detection using LSTM." Proceedings of the Fourth Workshop on Speech, Vision, and Language Technologies for Dravidian Languages. 2024.

Wiegand, Michael, and Josef Ruppenhofer. "Oddballs and Misfits: Detecting Implicit Abuse in Which Identity Groups are Depicted as Deviating from the Norm." Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing. 2024.

Dacon, Jamell, et al. "Detecting Harmful Online Conversational Content towards LGBTQIA+ Individuals." arXiv e-prints (2022): arXiv-2207.

### Shared Task LT-EDI-ACL22

Swaminathan, Krithika, et al. "Ssncse_nlp@ lt-edi-acl2022: Homophobia/transphobia detection in multiple languages using Svm classifiers and Bert-based Transformers." Proceedings of the Second Workshop on Language Technology for Equality, Diversity and Inclusion. 2022

​​Singh, Muskaan, and Petr Motlicek. "IDIAP Submission@ LT-EDI-ACL2022: Homophobia/Transphobia Detection in social media comments." Proceedings of the Second Workshop on Language Technology for Equality, Diversity and Inclusion. 2022.

Muti, Arianna, et al. "LeaningTower@ LT-EDI-ACL2022: when hope and hate collide." Proceedings of the second workshop on language technology for equality, diversity and inclusion. 2022.

### Shared Task LT-EDI-ACL23
Chakravarthi, Bharathi Raja, et al. "Overview of Second Shared Task on Homophobia and Transphobia Detection in Social Media Comments." Proceedings of the Third Workshop on Language Technology for Equality, Diversity and Inclusion. 2023.

Asha Hegde, Kavya G, Sharal Coelho, and Hosahalli Lakshmaiah Shashirekha. 2023. MUCS@LT-EDI2023: Homophobic/Transphobic Content Detection in Social Media Text using mBERT. In Proceedings of the Third Workshop on Language Technology for Equality, Diversity and Inclusion, pages 287–294, Varna, Bulgaria. INCOMA Ltd., Shoumen, Bulgaria.

### Shared Task LT-EDI-ACL24

Sonali Kulal, Nethravathi Gidnakanala, Raksha G, Kavya G, Asha Hegde, and H Shashirekha. 2024. MUCS@LT-EDI-2024: Learning Approaches to Empower Homophobic/Transphobic Comment Identification. In Proceedings of the Fourth Workshop on Language Technology for Equality, Diversity, Inclusion, pages 288–293, St. Julian's, Malta. Association for Computational Linguistics.

Yadav, Sargam, Abhishek Kaushik, and Kevin McDaid. "dkit@ LT-EDI-2024: Detecting Homophobia and Transphobia in English Social Media Comments." Proceedings of the Fourth Workshop on Language Technology for Equality, Diversity, Inclusion. 2024.


## Translation

Paolucci, Angela Balducci, Manuel Lardelli, and Dagmar Gromann. "Gender-Fair Language in Translation: A Case Study." 1st Workshop on Gender-Inclusive Translation Technologies. 2023.

Lauscher, Anne, et al. "What about “em”? How Commercial Machine Translation Fails to Handle (Neo-) Pronouns." Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers). 2023.

Robinson, Kevin, et al. "MiTTenS: A Dataset for Evaluating Gender Mistranslation." Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing. 2024.

Steinunn Rut Friidhriksdóttir. 2024. The GenderQueer Test Suite. In Proceedings of the Ninth Conference on Machine Translation, pages 327–340, Miami, Florida, USA. Association for Computational Linguistics.

Lardelli, Manuel, et al. "Sparks of Fairness: Preliminary Evidence of Commercial Machine Translation as English-to-German Gender-Fair Dictionaries." 2nd International Workshop on Gender-Inclusive Translation Technologies. 2024.

Lardelli, Manuel, Anne Lauscher, and Giuseppe Attanasio. "GeFMT: Gender-Fair Language in German Machine Translation." Association for Machine Translation (2024): 37.

Lardelli, Manuel, Giuseppe Attanasio, and Anne Lauscher. "Building Bridges: A Dataset for Evaluating Gender-Fair Machine Translation into German." arXiv e-prints (2024): arXiv-2406.

Piergentili, Andrea, et al. "Enhancing Gender-Inclusive Machine Translation with Neomorphemes and Large Language Models." arXiv preprint arXiv:2405.08477 (2024).

Stewart, Ian, and Rada Mihalcea. "Whose wife is it anyway? Assessing bias against same-gender relationships in machine translation." arXiv preprint arXiv:2401.04972 (2024).

## Other

### Position Papers

Larson, Brian N. "Gender as a Variable in Natural-Language Processing: Ethical Considerations." EACL 2017 (2017): 1.

Devinney, Hannah, Jenny Björklund, and Henrik Björklund. "Theories of “gender” in nlp bias research." Proceedings of the 2022 ACM conference on fairness, accountability, and transparency. 2022.

Factoring the Matrix of Domination: A Critical Review and Reimagination of Intersectionality in AI Fairness A. Ovalle, A. Subramonian, V. Gautam, G. Gee, and K-W Chang. AIES, 2023.

Razvan Amironesei and Mark Diaz. 2023. Relationality and Offensive Speech: A Research Agenda. In The 7th Workshop on Online Abuse and Harms (WOAH), pages 85–95, Toronto, Canada. Association for Computational Linguistics.

Understanding "Democratization" in NLP and ML Research {A. Subramonian, V. Gautam}, D. Klakow, Z. Talat. EMNLP, 2024.

Stop! In the Name of Flaws: Disentangling Personal Names and Sociodemographic Attributes in NLP V. Gautam, A. Subramonian, A. Lauscher, O. Keyes. Workshop on Gender Bias in Natural Language Processing, 2024.

McAra-Hunter, Dawn. "How AI hype impacts the LGBTQ+ community." AI and Ethics (2024): 1-20.

Dev, Sunipa, et al. "Harms of Gender Exclusivity and Challenges in Non-Binary Representation in Language Technologies."

### Unsure what topic 
Ovalle, Anaelia, et al. "Tokenization matters: Navigating data-scarce tokenization for gender inclusive language technologies." Findings of the Association for Computational Linguistics: NAACL 2024. 2024.

Dev, Sunipa, et al. "Harms of Gender Exclusivity and Challenges in Non-Binary Representation in Language Technologies." Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing. 2021.

Krithika Ramesh, Sumeet Kumar, and Ashiqur Khudabukhsh. 2022. Revisiting Queer Minorities in Lexicons. In Proceedings of the Sixth Workshop on Online Abuse and Harms (WOAH), pages 245–251, Seattle, Washington (Hybrid). Association for Computational Linguistics.

Veloso, Leonor, Luísa Coheur, and Rui Ribeiro. "A rewriting approach for gender inclusivity in Portuguese." Findings of the Association for Computational Linguistics: EMNLP 2023. 2023.

Ljubešić, Nikola, et al. "The LiLaH Emotion Lexicon of Croatian, Dutch and Slovene." Proceedings of the Third Workshop on Computational Modeling of People's Opinions, Personality, and Emotion's in Social Media. 2020.




