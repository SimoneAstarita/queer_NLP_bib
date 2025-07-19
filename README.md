# Queer NLP Paper Repository
This repository collects papers that sit at the intersection between the queer community and natural language processing. It is sorted by tasks, and a single paper can appear in multiple sections. Tasks are presented in alphabetical order and papers are presented in chronological order. 

This repository does not contain:
- papers from outside of NLP (e.g. linguistics, sociology, gender studies, ...)
- papers that don't explicitly mention the queer community or subsets of the queer community

If you want a paper to be added to this repository, you can make a pull request or submit it via <a href="https://docs.google.com/forms/d/e/1FAIpQLScpZxc6V5OgS77hy08qt3iuA1vOdqkvCuQ74xRSGJ6Hjs7zAw/viewform?usp=header"><u>this google form</u></a> .

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

## Coreference Resolution
Yang Trista Cao and Hal Daumé III. 2020. <a href="https://aclanthology.org/2020.acl-main.418/"><u>Toward Gender-Inclusive Coreference Resolution.</u></a> In _Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics_, pages 4568–4595, Online. Association for Computational Linguistics.

Ankith Uppunda, Susan Cochran, Jacob Foster, Alina Arseniev-Koehler, Vickie Mays, and Kai-Wei Chang. 2021. <a href="https://aclanthology.org/2021.naacl-main.361/"><u>"Adapting Coreference Resolution for Processing Violent Death Narratives."</u></a> In _Proceedings of the 2021 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies_, pages 4553–4559, Online. Association for Computational Linguistics.

Connor Baumler and Rachel Rudinger. 2022. <a href="https://aclanthology.org/2022.naacl-main.250/"><u>Recognition of They/Them as Singular Personal Pronouns in Coreference Resolution.</u></a> In _Proceedings of the 2022 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies_, pages 3426–3432, Seattle, United States. Association for Computational Linguistics.

Leonor Veloso, Luisa Coheur, and Rui Ribeiro. 2023. <a href="https://aclanthology.org/2023.findings-emnlp.585/"><u>A rewriting approach for gender inclusivity in Portuguese.</u></a> In _Findings of the Association for Computational Linguistics: EMNLP 2023_, pages 8747–8759, Singapore. Association for Computational Linguistics.

Vagrant Gautam, Julius Steuer, Eileen Bingert, Ray Johns, Anne Lauscher, and Dietrich Klakow. 2024. <a href="https://aclanthology.org/2024.crac-1.6"><u>WinoPron: Revisiting English Winogender Schemas for Consistency, Coverage, and Grammatical Case.</u></a> In _Proceedings of the Seventh Workshop on Computational Models of Reference, Anaphora and Coreference_, pages 52–66, Miami, United States. Association for Computational Linguistics.

Vagrant Gautam, Eileen Bingert, Dawei Zhu, Anne Lauscher, and Dietrich Klakow. 2024. <a href="https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00719/125951/Robust-Pronoun-Fidelity-with-English-LLMs-Are-they"><u>Robust Pronoun Fidelity with English LLMs: Are they Reasoning, Repeating, or Just Biased?.</u></a> _Transactions of the Association for Computational Linguistics_ 12, pages 1755–1779.

## Data Collection

Amanda Hicks, Michael Rutherford, Christiane Fellbaum, and Jiang Bian. 2016. <a href="https://aclanthology.org/2016.gwc-1.19"><u>An analysis of wordnet’s coverage of gender identity using twitter and the national transgender discrimination survey.</u></a> In _Proceedings of the 8th Global WordNet Conference (GWC)_, pages 123–130, Bucharest, Romania. Global Wordnet Association.

Jesse Dodge, Maarten Sap, Ana Marasović, William Agnew, Gabriel Ilharco, Dirk Groeneveld, Margaret Mitchell, and Matt Gardner. 2021. <a href="https://aclanthology.org/2021.emnlp-main.98/"><u>Documenting Large Webtext Corpora: A Case Study on the Colossal Clean Crawled Corpus.</u></a> In _Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing_, pages 1286–1305, Online and Punta Cana, Dominican Republic. Association for Computational Linguistics.

## Evaluation and Benchmarks

Soumya Barikeri, Anne Lauscher, Ivan Vulić, and Goran Glavaš. 2021. <a href="https://aclanthology.org/2021.acl-long.151/"><u>RedditBias: A Real-World Resource for Bias Evaluation and Debiasing of Conversational Language Models.</u></a> In _Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing (Volume 1: Long Papers)_, pages 1941–1955, Online. Association for Computational Linguistics.

Juan Vásquez, Gemma Bel-Enguix, Scott Thomas Andersen, and Sergio-Luis Ojeda-Trueba. 2022. <a href="https://aclanthology.org/2022.gebnlp-1.23"><u>Heterocorpus: A Corpus for Heteronormative Language Detection.</u></a> In _Proceedings of the 4th Workshop on Gender Bias in Natural Language Processing (GeBNLP)_, pages 225–234, Seattle, Washington. Association for Computational Linguistics.

Alicia Parrish, Angelica Chen, Nikita Nangia, Vishakh Padmakumar, Jason Phang, Jana Thompson, Phu Mon Htut, and Samuel Bowman. 2022. <a href="https://aclanthology.org/2022.findings-acl.165/"><u>BBQ: A hand-built bias benchmark for question answering.</u></a> In _Findings of the Association for Computational Linguistics: ACL 2022_, pages 2086–2105, Dublin, Ireland. Association for Computational Linguistics.

Alex Tamkin, Amanda Askell, Liane Lovitt, Esin Durmus, Nicholas Joseph, Shauna Kravec, Karina Nguyen, Jared Kaplan, and Deep Ganguli. <a href="https://arxiv.org/abs/2312.03689"><u>Evaluating and mitigating discrimination in language model decisions.</u></a> arXiv preprint arXiv:2312.03689 (2023).

Juan Vásquez, Scott Andersen, Gemma Bel-enguix, Helena Gómez-adorno, and Sergio-luis Ojeda-trueba. 2023. <a href="https://aclanthology.org/2023.woah-1.20"><u>HOMO-MEX: A Mexican Spanish Annotated Corpus for LGBT+phobia Detection on Twitter.</u></a> In _The 7th Workshop on Online Abuse and Harms (WOAH)_, pages 202–214, Toronto, Canada. Association for Computational Linguistics.

Nathan Dennler, Anaelia Ovalle, Ashwin Singh, Luca Soldaini, Arjun Subramonian, Huy Tu, William Agnew, Avijit Ghosh, Kyra Yee, Irene Font Peradejordi, Zeerak Talat, Mayra Russo, and Jess De Jesus De Pinho Pinhal. 2023. <a href="https://dl.acm.org/doi/pdf/10.1145/3600211.3604682?casa_token=Ur4BPZa80YcAAAAA:TF4epkxXo7-Ey_-LyDPsCPQGoZ9HF6N19kFU9jXtoMs3CPH3x0zPN7IYITtKzOwyKnZIE-5FRbFJzg"><u>Bound by the Bounty: Collaboratively Shaping Evaluation Processes for Queer AI Harms.</u></a> In _Proceedings of the 2023 AAAI/ACM Conference on AI, Ethics, and Society (AIES '23)_, pages 375–386, Montréal, Canada. Association for Computing Machinery.

Andrea Piergentili, Beatrice Savoldi, Dennis Fucci, Matteo Negri, and Luisa Bentivogli. 2023. <a href="https://aclanthology.org/2023.emnlp-main.873"><u>Hi Guys or Hi Folks? Benchmarking Gender-Neutral Machine Translation with the GeNTE Corpus.</u></a> In _Proceedings of the 2023 Conference on Empirical Methods in Natural Language Processing_, pages 14124–14140, Singapore. Association for Computational Linguistics.

Felkner, Virginia, et al. <a href="https://aclanthology.org/2023.acl-long.507/"><u>WinoQueer: A Community-in-the-Loop Benchmark for Anti-LGBTQ+ Bias in Large Language Models.</u></a> Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers). 2023.

Bunzeck, Bastian, and Sina Zarrieß. <a href="https://aclanthology.org/2024.genbench-1.3.pdf"><u>The SlayQA benchmark of social reasoning: testing gender-inclusive generalization with neopronouns.</u></a> Proceedings of the 2nd GenBench Workshop on Generalisation (Benchmarking) in NLP. 2024.

Sosto, Mae, and Alberto Barrón-Cedeño. <a href="https://arxiv.org/abs/2406.12399"><u> "QueerBench: Quantifying Discrimination in Language Models Toward Queer Identities."</u></a> arXiv preprint arXiv:2406.12399 (2024).

Tang, Kunsheng  et al. <a href="https://dl.acm.org/doi/abs/10.1145/3658644.3670284"><u>GenderCARE: A Comprehensive Framework for Assessing and Reducing Gender Bias in Large Language Models.</u></a> In Proceedings of the 2024 on ACM SIGSAC Conference on Computer and Communications Security (CCS '24). 2024

Subramonian, Arjun et al.  <a href="https://arxiv.org/abs/2504.17075#"><u>Agree to Disagree? A Meta-Evaluation of LLM Misgendering</u></a> ArXiv 2025


## Gender Bias Including Nonbinary Genders

Rudinger, Rachel, et al. <a href="https://aclanthology.org/N18-2002/"><u>"Gender Bias in Coreference Resolution."</u></a> Proceedings of the 2018 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies, Volume 2 (Short Papers). 2018

Devinney, Hannah, et al. <a href="https://aclanthology.org/2020.gebnlp-1.8/"><u>"Semi-supervised topic modeling for gender bias discovery in English and Swedish."</u></a> GeBNLP2020, COLING'2020–The 28th International Conference on Computational Linguistics, December 8-13, 2020, Online. Association for Computational Linguistics, 2020.

Hansson, Saga, et al. <a href="https://aclanthology.org/2021.nodalida-main.52/"><u>"The Swedish Winogender Dataset."</u></a> Proceedings of the 23rd Nordic Conference on Computational Linguistics (NoDaLiDa). 2021.

Havens, Lucy, et al. <a href="https://aclanthology.org/2022.gebnlp-1.4/"><u>"Uncertainty and inclusivity in gender bias annotation: An annotation taxonomy and annotated datasets of British English text."</u></a> 4th Workshop on Gender Bias in Natural Language Processing at NAACL. ACL Anthology, 2022.

Nasim Sobhani, Kinshuk Sengupta, and Sarah Jane Delany. <a href="https://aclanthology.org/2023.ranlp-1.119/"><u>" Measuring Gender Bias in Natural Language Processing: Incorporating Gender-Neutral Linguistic Forms for Non-Binary Gender Identities in Abusive Speech Detection."</u></a> In Proceedings of the 14th International Conference on Recent Advances in Natural Language Processing, pages 1121–1131, Varna, Bulgaria. INCOMA Ltd., Shoumen, Bulgaria. 2023. 

Tang, Kunsheng  et al. <a href="https://dl.acm.org/doi/abs/10.1145/3658644.3670284"><u>GenderCARE: A Comprehensive Framework for Assessing and Reducing Gender Bias in Large Language Models.</u></a> In Proceedings of the 2024 on ACM SIGSAC Conference on Computer and Communications Security (CCS '24). 2024

## LLMs
Sheng, Emily, et al. <a href="https://aclanthology.org/D19-1339.pdf"><u>"The Woman Worked as a Babysitter: On Biases in Language Generation."</u></a> Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing and the 9th International Joint Conference on Natural Language Processing

Nozza, Debora, et al. <a href="https://aclanthology.org/2022.ltedi-1.4/"><u>"Measuring Harmful Sentence Completion in Language Models for LGBTQIA+ Individuals."</u></a> LTEDI 2022 (2022): 26.

Ovalle, Anaelia et al. <a href="https://dl.acm.org/doi/10.1145/3593013.3594078"><u>“I’m fully who I am”: Towards Centering Transgender and Non-Binary Voices to Measure Biases in Open Language Generation.</u></a> In Proceedings of the 2023 ACM Conference on Fairness, Accountability, and Transparency (FAccT '23). 

Felkner, Virginia, et al. <a href="https://aclanthology.org/2023.acl-long.507/"><u>"WinoQueer: A Community-in-the-Loop Benchmark for Anti-LGBTQ+ Bias in Large Language Models."</u></a> Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers). 2023.

Tamkin, Alex, et al. <a href="https://arxiv.org/pdf/2312.03689"><u>"Evaluating and mitigating discrimination in language model decisions."</u></a> arXiv preprint arXiv:2312.03689 (2023).

Hossain, Tamanna, et al. <a href="https://aclanthology.org/2023.acl-long.293/"><u>"MISGENDERED: Limits of Large Language Models in Understanding Pronouns."</u></a> Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers). 2023.

​​Dhingra, Harnoor, et al. <a href="https://arxiv.org/abs/2307.00101"><u>"Queer People are People First: Deconstructing Sexual Identity Stereotypes in Large Language Models."</u>,</a> arXiv e-prints (2023): arXiv-2307.

Ovalle, Anaelia, et al. <a href="https://arxiv.org/abs/2411.03700"><u>"The Root Shapes the Fruit: On the Persistence of Gender-Exclusive Harms in Aligned Language Models."</u></a> arXiv preprint arXiv:2411.03700 (2024).

Selma Bergstrand and Björn Gambäck. <a href="https://aclanthology.org/2024.gebnlp-1.22/"><u>Detecting and Mitigating LGBTQIA+ Bias in Large Norwegian Language Models.</u></a> In Proceedings of the 5th Workshop on Gender Bias in Natural Language Processing (GeBNLP), pages 351–364, Bangkok, Thailand. Association for Computational Linguistics. 2024

Lissak, Shir, et al. <a href="https://aclanthology.org/2024.naacl-long.113.pdf"><u>The Colorful Future of LLMs: Evaluating and Improving LLMs as Emotional Supporters for Queer Youth.</u></a> In Proceedings of the 2024 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies 2024.

Marion Bartl and Susan Leavy. <a href="https://aclanthology.org/2024.gebnlp-1.18/"><u>From ‘Showgirls’ to ‘Performers’: Fine-tuning with Gender-inclusive Language for Bias Reduction in LLMs.</u></a> In Proceedings of the 5th Workshop on Gender Bias in Natural Language Processing (GeBNLP), pages 280–294, Bangkok, Thailand. Association for Computational Linguistics. 2024. 

Xie, Sean et al. <a href="https://aclanthology.org/2024.findings-naacl.278/"><u>"Addressing Healthcare-related Racial and LGBTQ+ Biases in Pretrained Language Models."</u></a> Findings of the Association for Computational Linguistics: NAACL 2024. 

Knupleš, Urban et al. <a href="https://aclanthology.org/2024.findings-emnlp.680/"><u> "Gender Identity in Pretrained Language Models: An Inclusive Approach to Data Creation and Probing." </u></a> Findings of the Association for Computational Linguistics: EMNLP 2024. 2024.

Devinney, Hannah, et al. <a href="https://aclanthology.org/2024.gebnlp-1.3/"><u>"We don’t talk about that: case studies on intersectional analysis of social bias in large language models."</u></a> Workshop on Gender Bias in Natural Language Processing (GeBNLP), Bangkok, Thailand, 16th August, 2024. Association for Computational Linguistics, 2024.

Sosto, Mae, and Alberto Barrón-Cedeño. <a href="https://arxiv.org/abs/2406.12399"><u> "QueerBench: Quantifying Discrimination in Language Models Toward Queer Identities."</u></a> arXiv preprint arXiv:2406.12399 (2024).

Tang, Kunsheng  et al. <a href="https://dl.acm.org/doi/abs/10.1145/3658644.3670284"><u>GenderCARE: A Comprehensive Framework for Assessing and Reducing Gender Bias in Large Language Models.</u></a> In Proceedings of the 2024 on ACM SIGSAC Conference on Computer and Communications Security (CCS '24). 2024

Ovalle, Anaelia, et al. <a href="https://aclanthology.org/2024.findings-naacl.113/"><u>"Tokenization matters: Navigating data-scarce tokenization for gender inclusive language technologies."</u></a> Findings of the Association for Computational Linguistics: NAACL 2024. 2024.

## Media Analysis using NLP 

Hicks, Amanda, et al. <a href="https://aclanthology.org/2016.gwc-1.19.pdf">"<u>An analysis of wordnet’s coverage of gender identity using twitter and the national transgender discrimination survey."</u></a> Proceedings of the 8th global wordnet conference (gwc). 2016.

Hung, Han-Tang, and Shu-Kai Hsieh. <a href="https://aclanthology.org/2020.paclic-1.47.pdf">"<u>Exploring Discourse on Same-sex Marriage in Taiwan: A Case Study of Near-Synonym of HOMOSEXUAL in Opposing Stances."</u></a>  Proceedings of the 34th Pacific Asia Conference on Language, Information and Computation. 2020.

Sky CH-Wang and David Jurgens. <a href="https://aclanthology.org/2021.emnlp-main.782/">"<u>Using Sociolinguistic Variables to Reveal Changing Attitudes Towards Sexuality and Gender."</u></a> In Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing, pages 9918–9938, Online and Punta Cana, Dominican Republic. Association for Computational Linguistics. 2021.

Lin, Yu-Hsuan. <a href="https://aclanthology.org/2023.nlp4dh-1.30.pdf"><u>"Comparison on Heterosexual and Homosexual Woman’s Lonely Heart Ads in Taiwan: Taking AllTogether and Lesbian Board on PTT Web Forum as Examples."</u></a> Proceedings of the Joint 3rd International Conference on Natural Language Processing for Digital Humanities and 8th International Workshop on Computational Linguistics for Uralic Languages. 2023.

Locatelli, Davide, Greta Damo, and Debora Nozza. <a href="https://aclanthology.org/2023.c3nlp-1.3.pdf"><u>"A cross-lingual study of homotransphobia on twitter."</u></a> Proceedings of the First Workshop on Cross-Cultural Considerations in NLP (C3NLP). 2023.

Chakravarthi, Bharathi Raja, et al. <a href="https://aclanthology.org/2024.ltedi-1.10.pdf"><u>"A Diachronic Analysis of Gender-Neutral Language on wikiHow"</u></a> Proceedings of the Fourth Workshop on Language Technology for Equality, Diversity, Inclusion. 2024.

Andersen, Scott, et al. <a href="https://aclanthology.org/2024.woah-1.14.pdf"><u>"The Mexican Gayze: A Computational Analysis of the Attitudes towards the LGBT+ Population in Mexico on Social Media Across a Decade."</u></a> Proceedings of the 8th Workshop on Online Abuse and Harms (WOAH 2024). 2024.

Farhan Samir, Chan Young Park, Anjalie Field, Vered Shwartz, and Yulia Tsvetkov. <a href="https://aclanthology.org/2024.emnlp-main.384.pdf"><u> Locating Information Gaps and Narrative Inconsistencies Across Languages: A Case Study of LGBT People Portrayals on Wikipedia.</u></a> In Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing, pages 6747–6762, Miami, Florida, USA. Association for Computational Linguistics. 2024.

## POS Tagging

Björklund, Henrik, and Hannah Devinney. <a href="https://aclanthology.org/2023.ltedi-1.8.pdf"><u>"Computer, enhence: POS-tagging improvements for nonbinary pronoun use in Swedish."</u></a> Proceedings of the Third Workshop on Language Technology for Equality, Diversity and Inclusion. 2023.

## Question Answering
Brixey, Jacqueline, et al. <a href="https://aclanthology.org/W17-5544.pdf"><u>"Shihbot: A facebook chatbot for sexual health information on hiv/aids."</u></a> Proceedings of the 18th annual SIGdial meeting on discourse and dialogue. 2017.

Bunzeck, Bastian, and Sina Zarrieß. <a href="https://aclanthology.org/2024.genbench-1.3.pdf"><u>"The SlayQA benchmark of social reasoning: testing gender-inclusive generalization with neopronouns."</u></a> Proceedings of the 2nd GenBench Workshop on Generalisation (Benchmarking) in NLP. 2024.

## Sentiment Analysis
Ungless, Eddie L., Bjorn Ross, and Vaishak Belle. <a href="https://journals.sagepub.com/doi/epub/10.1177/08944393231152946"><u>"Potential Pitfalls With Automatic Sentiment Analysis: The Example of Queerphobic Bias."</u></a> (2023).

Ljubešić, Nikola, et al. <a href="https://aclanthology.org/2020.peoples-1.15.pdf"><u>"The LiLaH Emotion Lexicon of Croatian, Dutch and Slovene."</u></a> Proceedings of the Third Workshop on Computational Modeling of People's Opinions, Personality, and Emotion's in Social Media. 2020.

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

Krithika Ramesh, Sumeet Kumar, and Ashiqur Khudabukhsh. 2022. Revisiting Queer Minorities in Lexicons. In Proceedings of the Sixth Workshop on Online Abuse and Harms (WOAH), pages 245–251, Seattle, Washington (Hybrid). Association for Computational Linguistics.

Mun, Jimin, et al. "Beyond denouncing hate: Strategies for countering implied biases and stereotypes in language." Findings of the Association for Computational Linguistics: EMNLP 2023. 2023.

Juan Vásquez, Scott Andersen, Gemma Bel-enguix, Helena Gómez-adorno, and Sergio-luis Ojeda-trueba. 2023. HOMO-MEX: A Mexican Spanish Annotated Corpus for LGBT+phobia Detection on Twitter. In The 7th Workshop on Online Abuse and Harms (WOAH), pages 202–214, Toronto, Canada. Association for Computational Linguistics.

Locatelli, Davide, Greta Damo, and Debora Nozza. "A cross-lingual study of homotransphobia on twitter." Proceedings of the First Workshop on Cross-Cultural Considerations in NLP (C3NLP). 2023.

Ahani, Z., et al. "Zavira@ DravidianLangTech 2024: Telugu hate speech detection using LSTM." Proceedings of the Fourth Workshop on Speech, Vision, and Language Technologies for Dravidian Languages. 2024.

Wiegand, Michael, and Josef Ruppenhofer. "Oddballs and Misfits: Detecting Implicit Abuse in Which Identity Groups are Depicted as Deviating from the Norm." Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing. 2024.

Dacon, Jamell, et al. "Detecting Harmful Online Conversational Content towards LGBTQIA+ Individuals." arXiv e-prints (2022): arXiv-2207.

Engelmann, Paul, Peter Brunsgaard Trolle, and Christian Hardmeier. <a href="https://aclanthology.org/2024.ltedi-1.2.pdf"><u> "A Dataset for the Detection of Dehumanizing Language."</u></a> LT-EDI 2024 (2024): 14.

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


## Position Papers

Larson, Brian N. "Gender as a Variable in Natural-Language Processing: Ethical Considerations." EACL 2017 (2017): 1.

Devinney, Hannah, Jenny Björklund, and Henrik Björklund. "Theories of “gender” in nlp bias research." Proceedings of the 2022 ACM conference on fairness, accountability, and transparency. 2022.

Factoring the Matrix of Domination: A Critical Review and Reimagination of Intersectionality in AI Fairness A. Ovalle, A. Subramonian, V. Gautam, G. Gee, and K-W Chang. AIES, 2023.

Zhou, Azure. <a href="https://ojs.stanford.edu/ojs/index.php/grace/article/download/3221/1620"><u> "Queer Bias in Natural Language Processing: Towards More Expansive Frameworks of Gender and Sexuality in NLP Bias Research."</u></a> 2023

Razvan Amironesei and Mark Diaz. 2023. Relationality and Offensive Speech: A Research Agenda. In The 7th Workshop on Online Abuse and Harms (WOAH), pages 85–95, Toronto, Canada. Association for Computational Linguistics.

Understanding "Democratization" in NLP and ML Research {A. Subramonian, V. Gautam}, D. Klakow, Z. Talat. EMNLP, 2024.

Stop! In the Name of Flaws: Disentangling Personal Names and Sociodemographic Attributes in NLP V. Gautam, A. Subramonian, A. Lauscher, O. Keyes. Workshop on Gender Bias in Natural Language Processing, 2024.

McAra-Hunter, Dawn. "How AI hype impacts the LGBTQ+ community." AI and Ethics (2024): 1-20.

Dev, Sunipa, et al. "Harms of Gender Exclusivity and Challenges in Non-Binary Representation in Language Technologies."

 








