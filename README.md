# Queer NLP Paper Repository
This repository collects papers that sit at the intersection between the queer community and natural language processing. It is sorted by tasks, and a single paper can appear in multiple sections. Tasks are presented in alphabetical order and papers are presented in chronological order.

This repository does not contain:
- papers from outside of NLP (e.g. linguistics, sociology, gender studies);
- papers that don't explicitly mention the queer community or subsets of the queer community.

If you want a paper to be added to this repository, you can make a pull request or submit it via <a href="https://docs.google.com/forms/d/e/1FAIpQLScpZxc6V5OgS77hy08qt3iuA1vOdqkvCuQ74xRSGJ6Hjs7zAw/viewform?usp=header"><u>this google form</u></a>.

## Table of Contents
- [Coreference Resolution](#coreference-resolution)
- [Data Collection](#data-collection)
- [Evaluation and Benchmarks](#evaluation-and-benchmarks)
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
- [Shared Tasks](#shared-tasks)

## Coreference Resolution
Yang Trista Cao and Hal Daumé III. 2020. <a href="https://aclanthology.org/2020.acl-main.418/"><u>Toward Gender-Inclusive Coreference Resolution.</u></a> In _Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics_, pages 4568–4595, Online. Association for Computational Linguistics.

Ankith Uppunda, Susan Cochran, Jacob Foster, Alina Arseniev-Koehler, Vickie Mays, and Kai-Wei Chang. 2021. <a href="https://aclanthology.org/2021.naacl-main.361/"><u>Adapting Coreference Resolution for Processing Violent Death Narratives.</u></a> In _Proceedings of the 2021 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies_, pages 4553–4559, Online. Association for Computational Linguistics.

Connor Baumler and Rachel Rudinger. 2022. <a href="https://aclanthology.org/2022.naacl-main.250/"><u>Recognition of They/Them as Singular Personal Pronouns in Coreference Resolution.</u></a> In _Proceedings of the 2022 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies_, pages 3426–3432, Seattle, United States. Association for Computational Linguistics.

Leonor Veloso, Luisa Coheur, and Rui Ribeiro. 2023. <a href="https://aclanthology.org/2023.findings-emnlp.585/"><u>A rewriting approach for gender inclusivity in Portuguese.</u></a> In _Findings of the Association for Computational Linguistics: EMNLP 2023_, pages 8747–8759, Singapore. Association for Computational Linguistics.

Vagrant Gautam, Julius Steuer, Eileen Bingert, Ray Johns, Anne Lauscher, and Dietrich Klakow. 2024. <a href="https://aclanthology.org/2024.crac-1.6"><u>WinoPron: Revisiting English Winogender Schemas for Consistency, Coverage, and Grammatical Case.</u></a> In _Proceedings of the Seventh Workshop on Computational Models of Reference, Anaphora and Coreference_, pages 52–66, Miami, United States. Association for Computational Linguistics.

Vagrant Gautam, Eileen Bingert, Dawei Zhu, Anne Lauscher, and Dietrich Klakow. 2024. <a href="https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00719/125951/Robust-Pronoun-Fidelity-with-English-LLMs-Are-they"><u>Robust Pronoun Fidelity with English LLMs: Are they Reasoning, Repeating, or Just Biased?.</u></a> _Transactions of the Association for Computational Linguistics_ 12, pages 1755–1779.

## Data Collection
Amanda Hicks, Michael Rutherford, Christiane Fellbaum, and Jiang Bian. 2016. <a href="https://aclanthology.org/2016.gwc-1.19"><u>An analysis of wordnet’s coverage of gender identity using twitter and the national transgender discrimination survey.</u></a> In _Proceedings of the 8th Global WordNet Conference (GWC)_, pages 123–130, Bucharest, Romania. Global Wordnet Association.

Jesse Dodge, Maarten Sap, Ana Marasović, William Agnew, Gabriel Ilharco, Dirk Groeneveld, Margaret Mitchell, and Matt Gardner. 2021. <a href="https://aclanthology.org/2021.emnlp-main.98/"><u>Documenting Large Webtext Corpora: A Case Study on the Colossal Clean Crawled Corpus.</u></a> In _Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing_, pages 1286–1305, Online and Punta Cana, Dominican Republic. Association for Computational Linguistics.

## Evaluation and Benchmarks
Soumya Barikeri, Anne Lauscher, Ivan Vulić, and Goran Glavaš. 2021. <a href="https://aclanthology.org/2021.acl-long.151/"><u>RedditBias: A Real-World Resource for Bias Evaluation and Debiasing of Conversational Language Models.</u></a> In _Proceedings of the 59th Annual Meeting of the Association for Computational Linguistics and the 11th International Joint Conference on Natural Language Processing (Volume 1: Long Papers)_, pages 1941–1955, Online. Association for Computational Linguistics.

Alicia Parrish, Angelica Chen, Nikita Nangia, Vishakh Padmakumar, Jason Phang, Jana Thompson, Phu Mon Htut, and Samuel Bowman. 2022. <a href="https://aclanthology.org/2022.findings-acl.165/"><u>BBQ: A hand-built bias benchmark for question answering.</u></a> In _Findings of the Association for Computational Linguistics: ACL 2022_, pages 2086–2105, Dublin, Ireland. Association for Computational Linguistics.

Juan Vásquez, Gemma Bel-Enguix, Scott Thomas Andersen, and Sergio-Luis Ojeda-Trueba. 2022. <a href="https://aclanthology.org/2022.gebnlp-1.23"><u>Heterocorpus: A Corpus for Heteronormative Language Detection.</u></a> In _Proceedings of the 4th Workshop on Gender Bias in Natural Language Processing (GeBNLP)_, pages 225–234, Seattle, Washington. Association for Computational Linguistics.

Juan Vásquez, Scott Andersen, Gemma Bel-enguix, Helena Gómez-adorno, and Sergio-luis Ojeda-trueba. 2023. <a href="https://aclanthology.org/2023.woah-1.20"><u>HOMO-MEX: A Mexican Spanish Annotated Corpus for LGBT+phobia Detection on Twitter.</u></a> In _The 7th Workshop on Online Abuse and Harms (WOAH)_, pages 202–214, Toronto, Canada. Association for Computational Linguistics.

Virginia Felkner, Ho-Chun Herbert Chang, Eugene Jang, and Jonathan May. 2023. <a href="https://aclanthology.org/2023.acl-long.507/"><u>WinoQueer: A Community-in-the-Loop Benchmark for Anti-LGBTQ+ Bias in Large Language Models.</u></a> In _Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)_, pages 9126–9140, Toronto, Canada. Association for Computational Linguistics.

Nathan Dennler, Anaelia Ovalle, Ashwin Singh, Luca Soldaini, Arjun Subramonian, Huy Tu, William Agnew, Avijit Ghosh, Kyra Yee, Irene Font Peradejordi, Zeerak Talat, Mayra Russo, and Jess De Jesus De Pinho Pinhal. 2023. <a href="https://dl.acm.org/doi/pdf/10.1145/3600211.3604682?casa_token=Ur4BPZa80YcAAAAA:TF4epkxXo7-Ey_-LyDPsCPQGoZ9HF6N19kFU9jXtoMs3CPH3x0zPN7IYITtKzOwyKnZIE-5FRbFJzg"><u>Bound by the Bounty: Collaboratively Shaping Evaluation Processes for Queer AI Harms.</u></a> In _Proceedings of the 2023 AAAI/ACM Conference on AI, Ethics, and Society (AIES '23)_, pages 375–386, Montréal, Canada. Association for Computing Machinery.

Andrea Piergentili, Beatrice Savoldi, Dennis Fucci, Matteo Negri, and Luisa Bentivogli. 2023. <a href="https://aclanthology.org/2023.emnlp-main.873"><u>Hi Guys or Hi Folks? Benchmarking Gender-Neutral Machine Translation with the GeNTE Corpus.</u></a> In _Proceedings of the 2023 Conference on Empirical Methods in Natural Language Processing_, pages 14124–14140, Singapore. Association for Computational Linguistics.

Alex Tamkin, Amanda Askell, Liane Lovitt, Esin Durmus, Nicholas Joseph, Shauna Kravec, Karina Nguyen, Jared Kaplan, and Deep Ganguli. 2023. <a href="https://arxiv.org/abs/2312.03689"><u>Evaluating and mitigating discrimination in language model decisions.</u></a> _Computing Research Repository_, arXiv:2312.03689.

Alessandra Teresa Cignarella, Manuela Sanguinetti, Simona Frenda, Andrea Marra, Cristina Bosco, and Valerio Basile. 2024. <a href="https://aclanthology.org/2024.lrec-main.1176/"><u>QUEEREOTYPES: A Multi-Source Italian Corpus of Stereotypes towards LGBTQIA+ Community Members.</u></a> In _Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024)_, pages 13429–13441, Torino, Italia. ELRA and ICCL.

Mae Sosto and Alberto Barrón-Cedeño. 2024. <a href="https://arxiv.org/abs/2406.12399"><u>QueerBench: Quantifying Discrimination in Language Models Toward Queer Identities.</u></a> _Computing Research Repository_, arXiv:2406.12399.

Bastian Bunzeck and Sina Zarrieß. 2024. <a href="https://aclanthology.org/2024.genbench-1.3"><u>The SlayQA benchmark of social reasoning: testing gender-inclusive generalization with neopronouns.</u></a> In _Proceedings of the 2nd GenBench Workshop on Generalisation (Benchmarking) in NLP_, pages 42–53, Miami, Florida, USA. Association for Computational Linguistics.

Kunsheng Tang, Wenbo Zhou, Jie Zhang, Aishan Liu, Gelei Deng, Shuai Li, Peigui Qi, Weiming Zhang, Tianwei Zhang, and NengHai Yu. 2024. <a href="https://dl.acm.org/doi/abs/10.1145/3658644.3670284"><u>GenderCARE: A Comprehensive Framework for Assessing and Reducing Gender Bias in Large Language Models.</u></a> In _Proceedings of the 2024 on ACM SIGSAC Conference on Computer and Communications Security (CCS '24)_, pages 1196–1210, Salt Lake City, UT, USA. Association for Computing Machinery.

Arjun Subramonian, Vagrant Gautam, Preethi Seshadri, Dietrich Klakow, Kai-Wei Chang and Yizhou Sun. 2025. <a href="https://arxiv.org/abs/2504.17075#"><u>Agree to Disagree? A Meta-Evaluation of LLM Misgendering</u></a> _Computing Research Repository_, arXiv:2504.17075. Work in progress.

## Gender Bias Including Nonbinary Genders
Rachel Rudinger, Jason Naradowsky, Brian Leonard, and Benjamin Van Durme. 2018. <a href="https://aclanthology.org/N18-2002/"><u>Gender Bias in Coreference Resolution.</u></a> In _Proceedings of the 2018 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies, Volume 2 (Short Papers)_, pages 8–14, New Orleans, Louisiana. Association for Computational Linguistics.

Hannah Devinney, Jenny Björklund, and Henrik Björklund. 2020. <a href="https://aclanthology.org/2020.gebnlp-1.8/"><u>Semi-supervised topic modeling for gender bias discovery in English and Swedish.</u></a> In _Proceedings of the Second Workshop on Gender Bias in Natural Language Processing_, pages 79–92, Barcelona, Spain (Online). Association for Computational Linguistics.

Saga Hansson, Konstantinos Mavromatakis, Yvonne Adesam, Gerlof Bouma, and Dana Dannélls. 2021. <a href="https://aclanthology.org/2021.nodalida-main.52/"><u>The Swedish Winogender Dataset.</u></a> In _Proceedings of the 23rd Nordic Conference on Computational Linguistics (NoDaLiDa)_, pages 452–459, Reykjavik, Iceland (Online). Linköping University Electronic Press.

Lucy Havens, Melissa Terras, Benjamin Bach, and Beatrice Alex. 2022. <a href="https://aclanthology.org/2022.gebnlp-1.4/"><u>Uncertainty and inclusivity in gender bias annotation: An annotation taxonomy and annotated datasets of British English text.</u></a> In _Proceedings of the 4th Workshop on Gender Bias in Natural Language Processing (GeBNLP)_, pages 30–57, Seattle, Washington. Association for Computational Linguistics.

Sandra Martinková, Karolina Stanczak, and Isabelle Augenstein. 2023. <a href="https://aclanthology.org/2023.bsnlp-1.17/"><u>Measuring Gender Bias in West Slavic Language Models.</u></a> In _Proceedings of the 9th Workshop on Slavic Natural Language Processing 2023 (SlavicNLP 2023)_, pages 146–154, Dubrovnik, Croatia. Association for Computational Linguistics.

Nasim Sobhani, Kinshuk Sengupta, and Sarah Jane Delany. 2023. <a href="https://aclanthology.org/2023.ranlp-1.119/"><u>Measuring Gender Bias in Natural Language Processing: Incorporating Gender-Neutral Linguistic Forms for Non-Binary Gender Identities in Abusive Speech Detection.</u></a> In _Proceedings of the 14th International Conference on Recent Advances in Natural Language Processing_, pages 1121–1131, Varna, Bulgaria. INCOMA Ltd., Shoumen, Bulgaria. 

Kunsheng Tang, Wenbo Zhou, Jie Zhang, Aishan Liu, Gelei Deng, Shuai Li, Peigui Qi, Weiming Zhang, Tianwei Zhang, and NengHai Yu. 2024. <a href="https://dl.acm.org/doi/abs/10.1145/3658644.3670284"><u>GenderCARE: A Comprehensive Framework for Assessing and Reducing Gender Bias in Large Language Models.</u></a> In _Proceedings of the 2024 on ACM SIGSAC Conference on Computer and Communications Security (CCS '24)_, pages 1196–1210, Salt Lake City, UT, United States. Association for Computing Machinery.

## LLMs
Emily Sheng, Kai-Wei Chang, Premkumar Natarajan, and Nanyun Peng. 2019. <a href="https://aclanthology.org/D19-1339"><u>The Woman Worked as a Babysitter: On Biases in Language Generation.</u></a> In _Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing and the 9th International Joint Conference on Natural Language Processing (EMNLP-IJCNLP)_, pages 3407–3412, Hong Kong, China. Association for Computational Linguistics.

Debora Nozza, Federico Bianchi, Anne Lauscher, and Dirk Hovy. 2022. <a href="https://aclanthology.org/2022.ltedi-1.4/"><u>Measuring Harmful Sentence Completion in Language Models for LGBTQIA+ Individuals.</u></a> In _Proceedings of the Second Workshop on Language Technology for Equality, Diversity and Inclusion_, pages 26–34, Dublin, Ireland. Association for Computational Linguistics.

Anaelia Ovalle, Palash Goyal, Jwala Dhamala, Zachary Jaggers, Kai-Wei Chang, Aram Galstyan, Richard Zemel, and Rahul Gupta. 2023. <a href="https://dl.acm.org/doi/10.1145/3593013.3594078"><u>“I’m fully who I am”: Towards Centering Transgender and Non-Binary Voices to Measure Biases in Open Language Generation.</u></a> In _Proceedings of the 2023 ACM Conference on Fairness, Accountability, and Transparency (FAccT '23)_, pages 1246–1266, Chicago, IL, USA. Association for Computing Machinery.

​​Harnoor Dhingra, Preetiha Jayashanker, Sayali Moghe, and Emma Strubell. 2023. <a href="https://arxiv.org/abs/2307.00101"><u>Queer People are People First: Deconstructing Sexual Identity Stereotypes in Large Language Models.</u>,</a> _Computing Research Repository_, arXiv:2307.00101.

Tamanna Hossain, Sunipa Dev, and Sameer Singh. 2023. <a href="https://aclanthology.org/2023.acl-long.293/"><u>MISGENDERED: Limits of Large Language Models in Understanding Pronouns.</u></a> In _Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)_, pages 5352–5367, Toronto, Canada. Association for Computational Linguistics.

Virginia Felkner, Ho-Chun Herbert Chang, Eugene Jang, and Jonathan May. 2023. <a href="https://aclanthology.org/2023.acl-long.507/"><u>WinoQueer: A Community-in-the-Loop Benchmark for Anti-LGBTQ+ Bias in Large Language Models.</u></a> In _Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)_, pages 9126–9140, Toronto, Canada. Association for Computational Linguistics.

Alex Tamkin, Amanda Askell, Liane Lovitt, Esin Durmus, Nicholas Joseph, Shauna Kravec, Karina Nguyen, Jared Kaplan, and Deep Ganguli. 2023. <a href="https://arxiv.org/abs/2312.03689"><u>Evaluating and mitigating discrimination in language model decisions.</u></a> _Computing Research Repository_, arXiv:2312.03689.

Shir Lissak, Nitay Calderon, Geva Shenkman, Yaakov Ophir, Eyal Fruchter, Anat Brunstein Klomek, and Roi Reichart. 2024. <a href="https://aclanthology.org/2024.naacl-long.113"><u>The Colorful Future of LLMs: Evaluating and Improving LLMs as Emotional Supporters for Queer Youth.</u></a> In _Proceedings of the 2024 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies (Volume 1: Long Papers)_, pages 2040–2079, Mexico City, Mexico. Association for Computational Linguistics.

Sean Xie, Saeed Hassanpour, and Soroush Vosoughi. 2024. <a href="https://aclanthology.org/2024.findings-naacl.278/"><u>Addressing Healthcare-related Racial and LGBTQ+ Biases in Pretrained Language Models.</u></a> In _Findings of the Association for Computational Linguistics: NAACL 2024_, pages 4451–4464, Mexico City, Mexico. Association for Computational Linguistics.

Anaelia Ovalle, Ninareh Mehrabi, Palash Goyal, Jwala Dhamala, Kai-Wei Chang, Richard Zemel, Aram Galstyan, Yuval Pinter, and Rahul Gupta. 2024. <a href="https://aclanthology.org/2024.findings-naacl.113/"><u>Tokenization matters: Navigating data-scarce tokenization for gender inclusive language technologies.</u></a> In _Findings of the Association for Computational Linguistics: NAACL 2024_, pages 1739–1756, Mexico City, Mexico. Association for Computational Linguistics.

Mae Sosto and Alberto Barrón-Cedeño. 2024. <a href="https://arxiv.org/abs/2406.12399"><u>QueerBench: Quantifying Discrimination in Language Models Toward Queer Identities.</u></a> _Computing Research Repository_, arXiv:2406.12399.

Selma Bergstrand and Björn Gambäck. 2024. <a href="https://aclanthology.org/2024.gebnlp-1.22/"><u>Detecting and Mitigating LGBTQIA+ Bias in Large Norwegian Language Models.</u></a> In _Proceedings of the 5th Workshop on Gender Bias in Natural Language Processing (GeBNLP)_, pages 351–364, Bangkok, Thailand. Association for Computational Linguistics.

Marion Bartl and Susan Leavy. 2024. <a href="https://aclanthology.org/2024.gebnlp-1.18/"><u>From ‘Showgirls’ to ‘Performers’: Fine-tuning with Gender-inclusive Language for Bias Reduction in LLMs.</u></a> In _Proceedings of the 5th Workshop on Gender Bias in Natural Language Processing (GeBNLP)_, pages 280–294, Bangkok, Thailand. Association for Computational Linguistics.

Hannah Devinney, Jenny Björklund, and Henrik Björklund. 2024. <a href="https://aclanthology.org/2024.gebnlp-1.3/"><u>We don’t talk about that: case studies on intersectional analysis of social bias in large language models.</u></a> In _Proceedings of the 5th Workshop on Gender Bias in Natural Language Processing (GeBNLP)_, pages 33–44, Bangkok, Thailand. Association for Computational Linguistics.

Urban Knupleš, Agnieszka Falenska, and Filip Miletić. 2024. <a href="https://aclanthology.org/2024.findings-emnlp.680/"><u>Gender Identity in Pretrained Language Models: An Inclusive Approach to Data Creation and Probing.</u></a> In _Findings of the Association for Computational Linguistics: EMNLP 2024_, pages 11612–11631, Miami, Florida, USA. Association for Computational Linguistics.

Kunsheng Tang, Wenbo Zhou, Jie Zhang, Aishan Liu, Gelei Deng, Shuai Li, Peigui Qi, Weiming Zhang, Tianwei Zhang, and NengHai Yu. 2024. <a href="https://dl.acm.org/doi/abs/10.1145/3658644.3670284"><u>GenderCARE: A Comprehensive Framework for Assessing and Reducing Gender Bias in Large Language Models.</u></a> In _Proceedings of the 2024 on ACM SIGSAC Conference on Computer and Communications Security (CCS '24)_, pages 1196–1210, Salt Lake City, UT, USA. Association for Computing Machinery.

Anaelia Ovalle, Krunoslav Lehman Pavasovic, Louis Martin, Luke Zettlemoyer, Eric Michael Smith, Adina Williams, and Levent Sagun. 2024. <a href="https://arxiv.org/abs/2411.03700"><u>The Root Shapes the Fruit: On the Persistence of Gender-Exclusive Harms in Aligned Language Models.</u></a> _Computing Research Repository_, arXiv:2411.03700. Presented at the Queer in AI Workshop at NeurIPS 2024.

## Media Analysis using NLP 
Amanda Hicks, Michael Rutherford, Christiane Fellbaum, and Jiang Bian. 2016. <a href="https://aclanthology.org/2016.gwc-1.19"><u>An analysis of wordnet’s coverage of gender identity using twitter and the national transgender discrimination survey.</u></a> In _Proceedings of the 8th Global WordNet Conference (GWC)_, pages 123–130, Bucharest, Romania. Global Wordnet Association.

Han-Tang Hung and Shu-Kai Hsieh. 2020. <a href="https://aclanthology.org/2020.paclic-1.47"><u>Exploring Discourse on Same-sex Marriage in Taiwan: A Case Study of Near-Synonym of HOMOSEXUAL in Opposing Stances.</u></a> In _Proceedings of the 34th Pacific Asia Conference on Language, Information and Computation_, pages 411–419, Hanoi, Vietnam. Association for Computational Linguistics.

Sky CH-Wang and David Jurgens. 2021. <a href="https://aclanthology.org/2021.emnlp-main.782/"><u>Using Sociolinguistic Variables to Reveal Changing Attitudes Towards Sexuality and Gender.</u></a> In _Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing_, pages 9918–9938, Online and Punta Cana, Dominican Republic. Association for Computational Linguistics.

Davide Locatelli, Greta Damo, and Debora Nozza. 2023. <a href="https://aclanthology.org/2023.c3nlp-1.3"><u>A cross-lingual study of homotransphobia on twitter.</u></a> In _Proceedings of the First Workshop on Cross-Cultural Considerations in NLP (C3NLP)_, pages 16–24, Dubrovnik, Croatia. Association for Computational Linguistics.

Yu-Hsuan Lin. 2023. <a href="https://aclanthology.org/2023.nlp4dh-1.30"><u>Comparison on Heterosexual and Homosexual Woman’s Lonely Heart Ads in Taiwan: Taking AllTogether and Lesbian Board on PTT Web Forum as Examples.</u></a> In _Proceedings of the Joint 3rd International Conference on Natural Language Processing for Digital Humanities and 8th International Workshop on Computational Linguistics for Uralic Languages_, pages 278–287, Tokyo, Japan. Association for Computational Linguistics.

Katharina Suhr and Michael Roth. 2024. <a href="https://aclanthology.org/2024.ltedi-1.10"><u>A Diachronic Analysis of Gender-Neutral Language on wikiHow</u></a> In _Proceedings of the Fourth Workshop on Language Technology for Equality, Diversity, Inclusion_, pages 118–123, St. Julian's, Malta. Association for Computational Linguistics.

Scott Andersen, Segio-Luis Ojeda-Trueba, Juan Vásquez, and Gemma Bel-Enguix. 2024. <a href="https://aclanthology.org/2024.woah-1.14"><u>The Mexican Gayze: A Computational Analysis of the Attitudes towards the LGBT+ Population in Mexico on Social Media Across a Decade.</u></a> In _Proceedings of the 8th Workshop on Online Abuse and Harms (WOAH 2024)_, pages 178–200, Mexico City, Mexico. Association for Computational Linguistics.

Farhan Samir, Chan Young Park, Anjalie Field, Vered Shwartz, and Yulia Tsvetkov. 2024. <a href="https://aclanthology.org/2024.emnlp-main.384"><u>Locating Information Gaps and Narrative Inconsistencies Across Languages: A Case Study of LGBT People Portrayals on Wikipedia.</u></a> In _Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing_, pages 6747–6762, Miami, Florida, USA. Association for Computational Linguistics.

## POS Tagging
Henrik Björklund and Hannah Devinney. <a href="https://aclanthology.org/2023.ltedi-1.8"><u>Computer, enhence: POS-tagging improvements for nonbinary pronoun use in Swedish.</u></a> In _Proceedings of the Third Workshop on Language Technology for Equality, Diversity and Inclusion_, pages 54–61, Varna, Bulgaria. INCOMA Ltd., Shoumen, Bulgaria.

## Question Answering
Jacqueline Brixey, Rens Hoegen, Wei Lan, Joshua Rusow, Karan Singla, Xusen Yin, Ron Artstein, and Anton Leuski. 2017. <a href="https://aclanthology.org/W17-5544"><u>Shihbot: A Facebook chatbot for Sexual Health Information on HIV/AIDS.</u></a> In _Proceedings of the 18th Annual SIGdial Meeting on Discourse and Dialogue_, pages 370–373, Saarbrücken, Germany. Association for Computational Linguistics.

Alicia Parrish, Angelica Chen, Nikita Nangia, Vishakh Padmakumar, Jason Phang, Jana Thompson, Phu Mon Htut, and Samuel Bowman. 2022. <a href="https://aclanthology.org/2022.findings-acl.165/"><u>BBQ: A hand-built bias benchmark for question answering.</u></a> In _Findings of the Association for Computational Linguistics: ACL 2022_, pages 2086–2105, Dublin, Ireland. Association for Computational Linguistics.

Bastian Bunzeck and Sina Zarrieß. 2024. <a href="https://aclanthology.org/2024.genbench-1.3"><u>The SlayQA benchmark of social reasoning: testing gender-inclusive generalization with neopronouns.</u></a> In _Proceedings of the 2nd GenBench Workshop on Generalisation (Benchmarking) in NLP_, pages 42–53, Miami, United States. Association for Computational Linguistics.

## Sentiment Analysis
Nikola Ljubešić, Ilia Markov, Darja Fišer, and Walter Daelemans. 2020. <a href="https://aclanthology.org/2020.peoples-1.15"><u>The LiLaH Emotion Lexicon of Croatian, Dutch and Slovene.</u></a> In _Proceedings of the Third Workshop on Computational Modeling of People's Opinions, Personality, and Emotion's in Social Media_, pages 153–157, Barcelona, Spain (Online). Association for Computational Linguistics.

Eddie L. Ungless, Bjorn Ross, and Vaishak Belle. 2023. <a href="https://journals.sagepub.com/doi/epub/10.1177/08944393231152946"><u>Potential Pitfalls With Automatic Sentiment Analysis: The Example of Queerphobic Bias.</u></a> _Social Science Computer Review_, 41(6), pages 2211-2229.

Mayk Brendon Almeida Antunes, Matheus de Freitas Issa and Raphael Magalhães Hoed. 2023. <a href="https://ojs.focopublicacoes.com.br/foco/article/view/853"><u>Técnicas de Machine Learning Aplicada a Mineração de Dados e Análise de Sentimentos para Predição de Homofobia no Twitter.</u></a> _Revista Foco_, 16(1):e853, Curitiba.

## Text Classification
Hsiao-Han Wu and Shu-Kai Hsieh. 2017. <a href="https://aclanthology.org/O17-1007/"><u>Exploring Lavender Tongue from Social Media Texts\[In Chinese\].</u></a> In _Proceedings of the 29th Conference on Computational Linguistics and Speech Processing (ROCLING 2017)_, pages 68–80, Taipei, Taiwan. The Association for Computational Linguistics and Chinese Language Processing (ACLCLP).

Guanhua Zhang, Bing Bai, Junqi Zhang, Kun Bai, Conghui Zhu, and Tiejun Zhao. 2020. <a href="https://aclanthology.org/2020.acl-main.380/"><u>Demographics Should Not Be the Reason of Toxicity: Mitigating Discrimination in Text Classifications with Instance Weighting.</u></a> In _Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics_, pages 4134–4145, Online. Association for Computational Linguistics.

Andreas Waldis, Joel Birrer, Anne Lauscher, and Iryna Gurevych. 2024. <a href="https://aclanthology.org/2024.emnlp-main.592/"><u>The Lou Dataset-Exploring the Impact of Gender-Fair Language in German Text Classification.</u></a> In _Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing_, pages 10604–10624, Miami, United States. Association for Computational Linguistics.

## Text to Image
Eddie Ungless, Bjorn Ross, and Anne Lauscher. 2023. <a href="https://aclanthology.org/2023.findings-acl.502/"><u>Stereotypes and Smut: The (Mis)representation of Non-cisgender Identities by Text-to-Image Models.</u></a> In _Findings of the Association for Computational Linguistics: ACL 2023_, pages 7919–7942, Toronto, Canada. Association for Computational Linguistics.

## Toxicity and Hate Speech
Zueva, Nadezhda, Madina Kabirova, and Pavel Kalaidin. 2020. <a href="https://aclanthology.org/2020.alw-1.8/"><u>Reducing Unintended Identity Bias in Russian Hate Speech Detection.</u></a> In _Proceedings of the Fourth Workshop on Online Abuse and Harms_, pages 65–69, Online. Association for Computational Linguistics.

Jamell Dacon, Harry Shomer, Shaylynn Crum-Dacon, and Jiliang Tang. 2022. <a href="https://arxiv.org/abs/2207.10032"><u>Detecting Harmful Online Conversational Content towards LGBTQIA+ Individuals.</u></a> _Computing Research Repository_, arXiv:2207.10032. Presented at the Queer in AI Workshop at NAACL 2022.

Mark Diaz, Razvan Amironesei, Laura Weidinger, and Iason Gabriel. 2022. <a href="https://aclanthology.org/2022.woah-1.18/"><u>Accounting for offensive speech as a practice of resistance.</u></a> In _Proceedings of the Sixth Workshop on Online Abuse and Harms (WOAH)_, pages 192–202, Seattle, Washington (Hybrid). Association for Computational Linguistics.

Fatma Elsafoury, Steven R. Wilson, and Naeem Ramzan. 2022. <a href="https://aclanthology.org/2022.socialnlp-1.5/"><u>A Comparative Study on Word Embeddings and Social NLP Tasks.</u></a> In _Proceedings of the Tenth International Workshop on Natural Language Processing for Social Media_, pages 55–64, Seattle, Washington, United States. Association for Computational Linguistics.

Christina Lu and David Jurgens. 2022. <a href="https://aclanthology.org/2022.woah-1.8/"><u>The subtle language of exclusion: Identifying the Toxic Speech of Trans-exclusionary Radical Feminists.</u></a> In _Proceedings of the Sixth Workshop on Online Abuse and Harms (WOAH)_, pages 79–91, Seattle, Washington (Hybrid). Association for Computational Linguistics.

Krithika Ramesh, Sumeet Kumar, and Ashiqur Khudabukhsh. 2022. <a href="https://aclanthology.org/2022.woah-1.23/"><u>Revisiting Queer Minorities in Lexicons.</u></a> In _Proceedings of the Sixth Workshop on Online Abuse and Harms (WOAH)_, pages 245–251, Seattle, Washington (Hybrid). Association for Computational Linguistics.

Andrey O. Souza, Eduardo F. Nakamura, and Fabíola G. Nakamura. 2022. <a href="https://sol.sbc.org.br/index.php/bresci/article/view/20477"><u>Detecção de Discurso de Ódio: Homofobia.</u></a> In _Anais do XVI Brazilian e-Science Workshop_, pages 73–80, Niterói, Brazil. Sociedade Brasileira de Computação (SBC).

Vinícius S. dos Santos, Felipe da R. Henriques, and Gustavo Guedes. 2022. <a href=""><u>O Discurso de Ódio Homofóbico no Twitter a partir da Análise de Dados.</u></a> In _Anais do XI Brazilian Workshop on Social Network Analysis and Mining (BRASNAM)_, pages 109–120, Rio de Janeiro. Sociedade Brasileira de Computação (SBC).

Fatma Elsafoury, Steve R. Wilson, Stamos Katsigiannis, and Naeem Ramzan. 2022. <a href="https://aclanthology.org/2022.coling-1.108/"><u>SOS: Systematic Offensive Stereotyping Bias in Word Embeddings.</u></a> In _Proceedings of the 29th International Conference on Computational Linguistics_, pages 1263–1274, Gyeongju, Republic of Korea. International Committee on Computational Linguistics.

Nihar Sahoo, Himanshu Gupta, and Pushpak Bhattacharyya. 2022. <a href="https://aclanthology.org/2022.conll-1.10/"><u>Detecting Unintended Social Bias in Toxic Language Datasets.</u></a> In _Proceedings of the 26th Conference on Computational Natural Language Learning (CoNLL)_, pages 132–143, Abu Dhabi, United Arab Emirates (Hybrid). Association for Computational Linguistics.

Mayk Brendon Almeida Antunes, Matheus de Freitas Issa and Raphael Magalhães Hoed. 2023. <a href="https://ojs.focopublicacoes.com.br/foco/article/view/853"><u>Técnicas de Machine Learning Aplicada a Mineração de Dados e Análise de Sentimentos para Predição de Homofobia no Twitter.</u></a> _Revista Foco_, 16(1):e853, Curitiba.

Daniel García-Baena, Miguel Á. García-Cumbreras, Sara M. Jiménez-Zafra, José A. García-Díaz, and Raúl Valencia-García. 2023. <a href="https://link.springer.com/article/10.1007/s10579-023-09638-3"><u>Hope Speech Detection in Spanish: The LGBT Case.</u></a> _Language Resources and Evaluation_, 57:1487–1514.

Juan Vásquez, Scott Andersen, Gemma Bel-enguix, Helena Gómez-adorno, and Sergio-luis Ojeda-trueba. 2023. <a href="https://aclanthology.org/2023.woah-1.20/"><u>HOMO-MEX: A Mexican Spanish Annotated Corpus for LGBT+phobia Detection on Twitter.</u></a> In The _7th Workshop on Online Abuse and Harms (WOAH)_, pages 202–214, Toronto, Canada. Association for Computational Linguistics.

Jimin Mun, Emily Allaway, Akhila Yerukola, Laura Vianna, Sarah-Jane Leslie, and Maarten Sap. 2023. <a href="https://aclanthology.org/2023.findings-emnlp.653/"><u>Beyond Denouncing Hate: Strategies for Countering Implied Biases and Stereotypes in Language.</u></a> In _Findings of the Association for Computational Linguistics: EMNLP 2023_, pages 9759–9777, Singapore. Association for Computational Linguistics.

Paul Engelmann, Peter Trolle, and Christian Hardmeier. 2024. <a href="https://aclanthology.org/2024.ltedi-1.2"><u>A Dataset for the Detection of Dehumanizing Language.</u></a> In _Proceedings of the Fourth Workshop on Language Technology for Equality, Diversity, Inclusion_, pages 14–20, St. Julian's, Malta. Association for Computational Linguistics.

Rebecca Dorn, Lee Kezar, Fred Morstatter, and Kristina Lerman. 2024. <a href="https://dl.acm.org/doi/10.1145/3689904.3694704"><u>Harmful Speech Detection by Language Models Exhibits Gender-Queer Dialect Bias.</u></a> In _Proceedings of the 4th ACM Conference on Equity and Access in Algorithms, Mechanisms, and Optimization (EAAMO '24)_, article 6, pages 1-12, San Luis Potosi, Mexico. Association for Computing Machinery.

Michael Wiegand and Josef Ruppenhofer. 2024. <a href="https://aclanthology.org/2024.emnlp-main.132/"><u>Oddballs and Misfits: Detecting Implicit Abuse in Which Identity Groups are Depicted as Deviating from the Norm.</u></a> In _Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing_, pages 2200–2218, Miami, Florida, USA. Association for Computational Linguistics.

Lia Draetta, Chiara Ferrando, Marco Cuccarini, Liam James, and Viviana Patti. 2024. <a href="https://aclanthology.org/2024.clicit-1.40/"><u>ReCLAIM Project: Exploring Italian Slurs Reappropriation with Large Language Models.</u></a> In _Proceedings of the 10th Italian Conference on Computational Linguistics (CLiC-it 2024)_, pages 335–342, Pisa, Italy. CEUR Workshop Proceedings.

Marcos Barbosa, Carlos Arcila, and Patricia Sánchez-Holgado. 2025. <a href="https://revistas.uned.es/index.php/empiria/article/view/45201"><u>LGTBfobia en redes sociales: Revisión sistemática de la detección y clasificación de discurso de odio a gran escala.</u></a> _EMPIRIA. Revista de Metodología de Ciencias Sociales_, 64:51–79.

## Translation
Angela Balducci Paolucci, Manuel Lardelli, and Dagmar Gromann. 2023. <a href="https://aclanthology.org/2023.gitt-1.2/"><u>Gender-Fair Language in Translation: A Case Study.</u></a> In _Proceedings of the First Workshop on Gender-Inclusive Translation Technologies_, pages 13–23, Tampere, Finland. European Association for Machine Translation.

Anne Lauscher, Debora Nozza, Ehm Miltersen, Archie Crowley, and Dirk Hovy. 2023. <a href="https://aclanthology.org/2023.acl-long.23/"><u> What about “em”? How Commercial Machine Translation Fails to Handle (Neo-)Pronouns.</u></a> In _Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)_, pages 377–392, Toronto, Canada. Association for Computational Linguistics.

Andrea Piergentili, Beatrice Savoldi, Matteo Negri, and Luisa Bentivogli. 2024. <a href="https://aclanthology.org/2024.eamt-1.25/"><u>Enhancing Gender-Inclusive Machine Translation with Neomorphemes and Large Language Models.</u></a> In _Proceedings of the 25th Annual Conference of the European Association for Machine Translation (Volume 1)_, pages 300–314, Sheffield, UK. European Association for Machine Translation (EAMT).

Manuel Lardelli, Timm Dill, Giuseppe Attanasio, and Anne Lauscher. 2024. <a href="https://aclanthology.org/2024.gitt-1.2/"><u>Sparks of Fairness: Preliminary Evidence of Commercial Machine Translation as English-to-German Gender-Fair Dictionaries.</u></a> In _Proceedings of the 2nd International Workshop on Gender-Inclusive Translation Technologies_, pages 12–21, Sheffield, United Kingdom. European Association for Machine Translation (EAMT).

Manuel Lardelli, Anne Lauscher, and Giuseppe Attanasio. 2024. <a href="https://aclanthology.org/2024.eamt-2.19/"><u>GeFMT: Gender-Fair Language in German Machine Translation.</u></a> In _Proceedings of the 25th Annual Conference of the European Association for Machine Translation (Volume 2)_, pages 37–38, Sheffield, UK. European Association for Machine Translation (EAMT).

Manuel Lardelli, Giuseppe Attanasio, and Anne Lauscher. 2024. <a href="https://aclanthology.org/2024.findings-acl.448/"><u>Building Bridges: A Dataset for Evaluating Gender-Fair Machine Translation into German.</u></a> In _Findings of the Association for Computational Linguistics: ACL 2024_, pages 7542–7550, Bangkok, Thailand. Association for Computational Linguistics.

Ian Stewart and Rada Mihalcea. 2024. <a href="https://aclanthology.org/2024.gebnlp-1.23/"><u>Whose wife is it anyway? Assessing bias against same-gender relationships in machine translation.</u></a> In _Proceedings of the 5th Workshop on Gender Bias in Natural Language Processing (GeBNLP)_, pages 365–375, Bangkok, Thailand. Association for Computational Linguistics.

Kevin Robinson, Sneha Kudugunta, Romina Stella, Sunipa Dev, and Jasmijn Bastings. 2024. <a href="https://aclanthology.org/2024.emnlp-main.238/"><u>MiTTenS: A Dataset for Evaluating Gender Mistranslation.</u></a> In _Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing_, pages 4115–4124, Miami, Florida, USA. Association for Computational Linguistics.

Steinunn Rut Friðriksdóttir. 2024. <a href="https://aclanthology.org/2024.wmt-1.26/"><u>The GenderQueer Test Suite.</u></a> In _Proceedings of the Ninth Conference on Machine Translation_, pages 327–340, Miami, Florida, USA. Association for Computational Linguistics.

Fanny Jourdan, Yannick Chevalier, and Cécile Favre. 2025. <a href="https://dl.acm.org/doi/10.1145/3715275.3732013"><u>FairTranslate: an English-French Dataset for Gender Bias Evaluation in Machine Translation by Overcoming Gender Binarity.</u></a> In _Proceedings of the 2025 ACM Conference on Fairness, Accountability, and Transparency (FAccT '25)_, pages 150–166, Athens, Greece. Association for Computing Machinery.

## Position Papers
Brian Larson. 2017. <a href="https://aclanthology.org/W17-1601/"><u>Gender as a Variable in Natural-Language Processing: Ethical Considerations.</u></a> In _Proceedings of the First ACL Workshop on Ethics in Natural Language Processing_, pages 1–11, Valencia, Spain. Association for Computational Linguistics.

Sunipa Dev, Masoud Monajatipoor, Anaelia Ovalle, Arjun Subramonian, Jeff Phillips, and Kai-Wei Chang. 2021. <a href="https://aclanthology.org/2021.emnlp-main.150/"><u>Harms of Gender Exclusivity and Challenges in Non-Binary Representation in Language Technologies.</u></a> In _Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing_, pages 1968–1994, Online and Punta Cana, Dominican Republic. Association for Computational Linguistics.

Hannah Devinney, Jenny Björklund, and Henrik Björklund. 2022. <a href="https://dl.acm.org/doi/10.1145/3531146.3534627"><u>Theories of “Gender” in NLP Bias Research.</u></a> In _Proceedings of the 2022 ACM Conference on Fairness, Accountability, and Transparency (FAccT '22)_, pages 2083–2102, Seoul, Republic of Korea. Association for Computing Machinery.

Razvan Amironesei and Mark Diaz. 2023. <a href="https://aclanthology.org/2023.woah-1.8/"><u>Relationality and Offensive Speech: A Research Agenda.</u></a> In _The 7th Workshop on Online Abuse and Harms (WOAH)_, pages 85–95, Toronto, Canada. Association for Computational Linguistics.

Anaelia Ovalle, Arjun Subramonian, Vagrant Gautam, Gilbert Gee, and Kai-Wei Chang. 2023. <a href="https://dl.acm.org/doi/10.1145/3600211.3604705"><u>Factoring the Matrix of Domination: A Critical Review and Reimagination of Intersectionality in AI Fairness.</u></a> In _Proceedings of the 2023 AAAI/ACM Conference on AI, Ethics, and Society (AIES '23)_, pages 496–511, Montreal, Canada. Association for Computing Machinery.

Azure Zhou. 2024. <a href="https://ojs.stanford.edu/ojs/index.php/grace/article/download/3221/1620"><u>Queer Bias in Natural Language Processing: Towards More Expansive Frameworks of Gender and Sexuality in NLP Bias Research.</u></a> _GRACE: Global Review of AI Community Ethics_, 2(1):1-9.

Dawn McAra-Hunter. 2024. <a href="https://link.springer.com/article/10.1007/s43681-024-00423-8#citeas"><u>How AI hype impacts the LGBTQ + community.</u></a> _AI Ethics_, 4:771–790.

Vagrant Gautam, Arjun Subramonian, Anne Lauscher, and Os Keyes. 2024. <a href="https://aclanthology.org/2024.gebnlp-1.20/"><u>Stop! In the Name of Flaws: Disentangling Personal Names and Sociodemographic Attributes in NLP.</u></a> In _Proceedings of the 5th Workshop on Gender Bias in Natural Language Processing (GeBNLP)_, pages 323–337, Bangkok, Thailand. Association for Computational Linguistics.

## Shared Tasks Papers

## LTEDI: The Workshop on Language Technology for Equality, Diversity, Inclusion

### LTEDI 2022 – Homophobia/Transphobia Detection in Social Media Comments

`Overview paper`
Bharathi Raja Chakravarthi, Ruba Priyadharshini, Thenmozhi Durairaj, John McCrae, Paul Buitelaar, Prasanna Kumaresan, and Rahul Ponnusamy. 2022. <a href="https://aclanthology.org/2022.ltedi-1.57/"><u>Overview of The Shared Task on Homophobia and Transphobia Detection in Social Media Comments.</u></a> In _Proceedings of the Second Workshop on Language Technology for Equality, Diversity and Inclusion_, pages 369–377, Dublin, Ireland. Association for Computational Linguistics.

José García-Díaz, Camilo Caparros-Laiz, and Rafael Valencia-García. 2022. <a href="https://aclanthology.org/2022.ltedi-1.16/"><u>UMUTeam@LT-EDI-ACL2022: Detecting homophobic and transphobic comments in Tamil.</u></a> In _Proceedings of the Second Workshop on Language Technology for Equality, Diversity and Inclusion_, pages 140–144, Dublin, Ireland. Association for Computational Linguistics.

Vitthal Bhandari and Poonam Goyal. 2022. <a href="https://aclanthology.org/2022.ltedi-1.18/"><u>bitsa_nlp@LT-EDI-ACL2022: Leveraging Pretrained Language Models for Detecting Homophobia and Transphobia in Social Media Comments.</u></a> In _Proceedings of the Second Workshop on Language Technology for Equality, Diversity and Inclusion_, pages 149–154, Dublin, Ireland. Association for Computational Linguistics.

Abulimiti Maimaitituoheti. 2022. <a href="https://aclanthology.org/2022.ltedi-1.19/"><u>ABLIMET @LT-EDI-ACL2022: A Roberta based Approach for Homophobia/Transphobia Detection in Social Media.</u></a> In _Proceedings of the Second Workshop on Language Technology for Equality, Diversity and Inclusion_, pages 155–160, Dublin, Ireland. Association for Computational Linguistics.

Krithika Swaminathan, Bharathi B, Gayathri G L, and Hrishik Sampath. 2022. <a href="https://aclanthology.org/2022.ltedi-1.34/"><u>SSNCSE_NLP@LT-EDI-ACL2022: Homophobia/Transphobia Detection in Multiple Languages using SVM Classifiers and BERT-based Transformers.</u></a> In _Proceedings of the Second Workshop on Language Technology for Equality, Diversity and Inclusion_, pages 239–244, Dublin, Ireland. Association for Computational Linguistics.

Debora Nozza. 2022. <a href="https://aclanthology.org/2022.ltedi-1.37/"><u>Nozza@LT-EDI-ACL2022: Ensemble Modeling for Homophobia and Transphobia Detection.</u></a> In _Proceedings of the Second Workshop on Language Technology for Equality, Diversity and Inclusion_, pages 258–264, Dublin, Ireland. Association for Computational Linguistics.

Ishan Sanjeev Upadhyay, Kv Aditya Srivatsa, and Radhika Mamidi. 2022. <a href="https://aclanthology.org/2022.ltedi-1.39/"><u>Sammaan@LT-EDI-ACL2022: Ensembled Transformers Against Homophobia and Transphobia.</u></a> In _Proceedings of the Second Workshop on Language Technology for Equality, Diversity and Inclusion_, pages 270–275, Dublin, Ireland. Association for Computational Linguistics.

Nsrin Ashraf, Mohamed Taha, Ahmed Abd Elfattah, and Hamada Nayel. 2022. <a href="https://aclanthology.org/2022.ltedi-1.42/"><u>NAYEL @LT-EDI-ACL2022: Homophobia/Transphobia Detection for Equality, Diversity, and Inclusion using SVM.</u></a> In _Proceedings of the Second Workshop on Language Technology for Equality_, Diversity and Inclusion, pages 287–290, Dublin, Ireland. Association for Computational Linguistics.

Arianna Muti, Marta Marchiori Manerba, Katerina Korre, and Alberto Barrón-Cedeño. 2022. <a href="https://aclanthology.org/2022.ltedi-1.46/"><u>LeaningTower@LT-EDI-ACL2022: When Hope and Hate Collide.</u></a> In _Proceedings of the Second Workshop on Language Technology for Equality, Diversity and Inclusion_, pages 306–311, Dublin, Ireland. Association for Computational Linguistics.

Muskaan Singh and Petr Motlicek. 2022. <a href="https://aclanthology.org/2022.ltedi-1.55/"><u>IDIAP Submission@LT-EDI-ACL2022: Homophobia/Transphobia Detection in social media comments.</u></a> In _Proceedings of the Second Workshop on Language Technology for Equality, Diversity and Inclusion_, pages 356–361, Dublin, Ireland. Association for Computational Linguistics.

### LTEDI 2023 – Homophobia/Transphobia Detection in Social Media Comments

`Overview paper`
Bharathi Raja Chakravarthi, Rahul Ponnusamy, Malliga S, Paul Buitelaar, Miguel Ángel García-Cumbreras, Salud María Jimenez-Zafra, Jose Antonio Garcia-Diaz, Rafael Valencia-Garcia, and Nitesh Jindal. 2023. <a href="https://aclanthology.org/2023.ltedi-1.6/"><u>Overview of Second Shared Task on Homophobia and Transphobia Detection in Social Media Comments.</u></a> In _Proceedings of the Third Workshop on Language Technology for Equality, Diversity and Inclusion_, pages 38–46, Varna, Bulgaria. INCOMA Ltd., Shoumen, Bulgaria.

Kaustubh Lande, Rahul Ponnusamy, Prasanna Kumar Kumaresan, and Bharathi Raja Chakravarthi. 2023. <a href="https://aclanthology.org/2023.ltedi-1.10/"><u>KaustubhSharedTask@LT-EDI 2023: Homophobia-Transphobia Detection in Social Media Comments with NLPAUG-driven Data Augmentation.</u></a> In _Proceedings of the Third Workshop on Language Technology for Equality, Diversity and Inclusion_, pages 71–77, Varna, Bulgaria. INCOMA Ltd., Shoumen, Bulgaria.

Judith Jeyafreeda Andrew. 2023. <a href="https://aclanthology.org/2023.ltedi-1.11/"><u>JudithJeyafreeda@LT-EDI-2023: Using GPT model for recognition of Homophobia/Transphobia detection from social media.</u></a> In _Proceedings of the Third Workshop on Language Technology for Equality, Diversity and Inclusion_, pages 78–82, Varna, Bulgaria. INCOMA Ltd., Shoumen, Bulgaria.

Sidney Wong, Matthew Durward, Benjamin Adams, and Jonathan Dunn. 2023. <a href="https://aclanthology.org/2023.ltedi-1.15/"><u>cantnlp@LT-EDI-2023: Homophobia/Transphobia Detection in Social Media Comments using Spatio-Temporally Retrained Language Models.</u></a> In _Proceedings of the Third Workshop on Language Technology for Equality, Diversity and Inclusion_, pages 103–108, Varna, Bulgaria. INCOMA Ltd., Shoumen, Bulgaria.

Vaidhegi D, Priya M, Rajalakshmi Sivanaiah, Angel Deborah S, and Mirnalinee ThankaNadar. 2023. <a href="https://aclanthology.org/2023.ltedi-1.25/"><u>SSNTech2@LT-EDI-2023: Homophobia/Transphobia Detection in Social Media Comments Using Linear Classification Techniques.</u></a> In _Proceedings of the Third Workshop on Language Technology for Equality, Diversity and Inclusion_, pages 166–171, Varna, Bulgaria. INCOMA Ltd., Shoumen, Bulgaria.

Dean Ninalga. 2023. <a href="https://aclanthology.org/2023.ltedi-1.28/"><u>Cordyceps@LT-EDI: Patching Language-Specific Homophobia/Transphobia Classifiers with a Multilingual Understanding.</u></a> In _Proceedings of the Third Workshop on Language Technology for Equality, Diversity and Inclusion_, pages 185–191, Varna, Bulgaria. INCOMA Ltd., Shoumen, Bulgaria.

Prasanna Kumar Kumaresan, Kishore Kumar Ponnusamy, Kogilavani S V, Subalalitha Cn, Ruba Priyadharshini, and Bharathi Raja Chakravarthi. 2023. <a href="https://aclanthology.org/2023.ltedi-1.35/"><u>VEL@LT-EDI: Detecting Homophobia and Transphobia in Code-Mixed Spanish Social Media Comments.</u></a> In _Proceedings of the Third Workshop on Language Technology for Equality, Diversity and Inclusion_, pages 233–238, Varna, Bulgaria. INCOMA Ltd., Shoumen, Bulgaria.

Shwetha Sureshnathan, Samyuktaa Sivakumar, Priyadharshini Thandavamurthi, Thenmozhi D., Bharathi B, and Kiruthika Chandrasekaran. 2023. <a href="https://aclanthology.org/2023.ltedi-1.41/"><u>Tercet@LT-EDI-2023: Homophobia/Transphobia Detection in social media comment.</u></a> In _Proceedings of the Third Workshop on Language Technology for Equality, Diversity and Inclusion_, pages 266–271, Varna, Bulgaria. INCOMA Ltd., Shoumen, Bulgaria.

Asha Hegde, Kavya G, Sharal Coelho, and Hosahalli Lakshmaiah Shashirekha. 2023. <a href="https://aclanthology.org/2023.ltedi-1.44/"><u>MUCS@LT-EDI2023: Homophobic/Transphobic Content Detection in Social Media Text using mBERT.</u></a> In _Proceedings of the Third Workshop on Language Technology for Equality, Diversity and Inclusion_, pages 287–294, Varna, Bulgaria. INCOMA Ltd., Shoumen, Bulgaria.

### LTEDI 2024 – Homophobia/Transphobia Detection in Social Media Comments

`Overview paper`
Bharathi Raja Chakravarthi, Prasanna Kumaresan, Ruba Priyadharshini, Paul Buitelaar, Asha Hegde, Hosahalli Shashirekha, Saranya Rajiakodi, Miguel Ángel García, Salud María Jiménez-Zafra, José García-Díaz, Rafael Valencia-García, Kishore Ponnusamy, Poorvi Shetty, and Daniel García-Baena. 2024. <a href="https://aclanthology.org/2024.ltedi-1.11/"><u>Overview of Third Shared Task on Homophobia and Transphobia Detection in Social Media Comments.</u></a> In _Proceedings of the Fourth Workshop on Language Technology for Equality, Diversity, Inclusion_, pages 124–132, St. Julian's, Malta. Association for Computational Linguistics.

Durga Prasad Manukonda and Rohith Gowtham Kodali. 2024. <a href="https://aclanthology.org/2024.ltedi-1.16/"><u>byteLLM@LT-EDI-2024: Homophobia/Transphobia Detection in Social Media Comments - Custom Subword Tokenization with Subword2Vec and BiLSTM.</u></a> In _Proceedings of the Fourth Workshop on Language Technology for Equality, Diversity, Inclusion_, pages 157–163, St. Julian's, Malta. Association for Computational Linguistics.

Dhiman Goswami, Sadiya Sayara Chowdhury Puspo, Md Nishat Raihan, and Al Nahian Bin Emran. 2024. <a href="https://aclanthology.org/2024.ltedi-1.17/"><u>MasonTigers@LT-EDI-2024: An Ensemble Approach Towards Detecting Homophobia and Transphobia in Social Media Comments.</u></a> In _Proceedings of the Fourth Workshop on Language Technology for Equality, Diversity, Inclusion_, pages 164–172, St. Julian's, Malta. Association for Computational Linguistics.

Kogilavani Shanmugavadivel, Malliga Subramanian, Shri R, Srigha S, Samyuktha K, and Nithika K. 2024. <a href="https://aclanthology.org/2024.ltedi-1.23/"><u>KEC-AI-NLP@LT-EDI-2024:Homophobia and Transphobia Detection in Social Media Comments using Machine Learning.</u></a> In _Proceedings of the Fourth Workshop on Language Technology for Equality, Diversity, Inclusion_, pages 200–205, St. Julian's, Malta. Association for Computational Linguistics.

Shaun H, Samyuktaa Sivakumar, Rohan R, Nikilesh Jayaguptha, and Durairaj Thenmozhi. 2024. <a href="https://aclanthology.org/2024.ltedi-1.28/"><u>Quartet@LT-EDI 2024: Support Vector Machine Based Approach For Homophobia/Transphobia Detection In Social Media Comments.</u></a> In _Proceedings of the Fourth Workshop on Language Technology for Equality, Diversity, Inclusion_, pages 227–232, St. Julian's, Malta. Association for Computational Linguistics.

Adwita Arora, Aaryan Mattoo, Divya Chaudhary, Ian Gorton, and Bijendra Kumar. 2024. <a href="https://aclanthology.org/2024.ltedi-1.34/"><u>MEnTr@LT-EDI-2024: Multilingual Ensemble of Transformer Models for Homophobia/Transphobia Detection.</u></a> In _Proceedings of the Fourth Workshop on Language Technology for Equality, Diversity, Inclusion_, pages 259–264, St. Julian's, Malta. Association for Computational Linguistics.

Sargam Yadav, Abhishek Kaushik, and Kevin McDaid. 2024. <a href="https://aclanthology.org/2024.ltedi-1.36/"><u>dkit@LT-EDI-2024: Detecting Homophobia and Transphobia in English Social Media Comments.</u></a> In _Proceedings of the Fourth Workshop on Language Technology for Equality, Diversity, Inclusion_, pages 271–276, St. Julian's, Malta. Association for Computational Linguistics.

Sonali Kulal, Nethravathi Gidnakanala, Raksha G, Kavya G, Asha Hegde, and H Shashirekha. 2024. <a href="https://aclanthology.org/2024.ltedi-1.39/"><u>MUCS@LT-EDI-2024: Learning Approaches to Empower Homophobic/Transphobic Comment Identification.</u></a> In _Proceedings of the Fourth Workshop on Language Technology for Equality, Diversity, Inclusion_, pages 288–293, St. Julian's, Malta. Association for Computational Linguistics.

### LTEDI 2025 – Homophobia/Transphobia Detection in Social Media Comments

Papers yet to be published.

## IberLEF: The Iberian Language Evaluation Forum

### IberLEF2023 – HOMO-MEX: Hate speech detection towards the Mexican Spanish speaking LGBT+ population

`Overview paper`
Gemma Bel-Enguix, Helena Gómez-Adorno, Scott T. Andersen, Juan Vásquez, and Sergio-Luis Ojeda-Trueba. 2023. <a href="http://journal.sepln.org/sepln/ojs/ojs/index.php/pln/article/view/6566"><u>Overview of HOMO-MEX at IberLEF 2023: Hate Speech Detection in Online Messages Directed towards the Mexican Spanish-Speaking LGBTQ+ Population.</u></a> _Procesamiento del Lenguaje Natural_ 71, pages 361–370, A Coruña. Sociedad Española para el PLN.

Moein Shahiki-Tash, Jesús Armenta-Segura, Zahra Ahani, Olga Kolesnikova, Grigori Sidorov, and Alexander Gelbukh. 2024. <a href="https://ceur-ws.org/Vol-3496/homomex-paper1.pdf"><u>LIDOMA at HOMO-MEX2023@IberLEF: Hate Speech Detection Towards the Mexican Spanish-Speaking LGBT+ Population. The Importance of Preprocessing Before Using BERT-Based Models.</u></a> In _Proceedings of the Iberian Languages Evaluation Forum (IberLEF 2023)_, Jaén, Spain. CEUR-WS.org.

Erika Rivadeneira-Pérez, María de Jesús García-Santiago, and Cipriano Callejas-Hernández. 2024. <a href="https://ceur-ws.org/Vol-3496/homomex-paper2.pdf"><u>CIMAT-NLP at HOMO-MEX2023@IBERLEF: Machine Learning Techniques For Fine-grained Speech Detection Task.</u></a> In _Proceedings of the Iberian Languages Evaluation Forum (IberLEF 2023)_, Jaén, Spain. CEUR-WS.org.

Antonio José Morano Moriña, Javier Román Pásaro, Jacinto Mata Vázquez, and Victoria Pachón Álvarez. 2024. <a href="https://ceur-ws.org/Vol-3496/homomex-paper3.pdf"><u>I2C-UHU at IberLEF-2023 HOMO-MEX task: Ensembling Transformers Models to Identify and Classify Hate Messages Towards the Community LGBTQ+.</u></a> In _Proceedings of the Iberian Languages Evaluation Forum (IberLEF 2023)_, Jaén, Spain. CEUR-WS.org.

Duván-Andrés Marrugo-Tobón, Juan-Carlos Martinez-Santos, and Edwin Puertas. 2024. <a href="https://ceur-ws.org/Vol-3496/homomex-paper4.pdf"><u>Natural Language Content Evaluation System For Multiclass Detection of Hate Speech in Tweets Using Transformers.</u></a> In _Proceedings of the Iberian Languages Evaluation Forum (IberLEF 2023)_, Jaén, Spain. CEUR-WS.org.

Mesay Gemeda Yigezu, Olga Kolesnikova, Grigori Sidorov, and Alexander Gelbukh. 2024. <a href="https://ceur-ws.org/Vol-3496/homomex-paper5.pdf"><u>Transformer-Based Hate Speech Detection for Multi-Class and Multi-Label Classification.</u></a> In _Proceedings of the Iberian Languages Evaluation Forum (IberLEF 2023)_, Jaén, Spain. CEUR-WS.org.

José Antonio García-Díaz, Salud María Jiménez-Zafra, and Rafael Valencia-García. 2024. <a href="https://ceur-ws.org/Vol-3496/homomex-paper6.pdf"><u>UMUTeam at HOMO-MEX 2023: Fine-tuning Large Language Models integration for solving hate-speech detection in Mexican Spanish.</u></a> In _Proceedings of the Iberian Languages Evaluation Forum (IberLEF 2023)_, Jaén, Spain. CEUR-WS.org.

Carlos Fernández Rosauro, and Montse Cuadros. 2024. <a href="https://ceur-ws.org/Vol-3496/homomex-paper7.pdf"><u>Hate Speech Detection Against the Mexican Spanish LGBTQ+ Community Using BERT-based Transformers.</u></a> In _Proceedings of the Iberian Languages Evaluation Forum (IberLEF 2023)_, Jaén, Spain. CEUR-WS.org.

Cesar Macias, Miguel Soto, Tania Alcántara, and Hiram Calvo. 2024. <a href="https://ceur-ws.org/Vol-3496/homomex-paper8.pdf"><u>Impact of Text Preprocessing and Feature Selection on Hate Speech Detection in Online Messages Towards the LGBTQ+ Community in Mexico.</u></a> In _Proceedings of the Iberian Languages Evaluation Forum (IberLEF 2023)_, Jaén, Spain. CEUR-WS.org.

### IberLEF2024 – HOMO-MEX: Hate speech detection towards the Mexican Spanish speaking LGBT+ population

`Overview paper`
Helena Gómez-Adorno, Gemma Bel-Enguix, Juan Vásquez, Scott T. Andersen, and Sergio-Luis Ojeda-Trueba. 2024. <a href="http://journal.sepln.org/sepln/ojs/ojs/index.php/pln/article/view/6626"><u>Overview of HOMO-MEX at IberLEF 2024: Hate Speech Detection towards the Mexican Spanish-Speaking LGBT+ Population.</u></a> _Procesamiento del Lenguaje Natural_ 73, pages 393-405. Sociedad Española para el PLN.

Anibal Hernández-González, Julio Madera-Quintana, and Alfredo Simón-Cuevas. 2024. <a href="https://ceur-ws.org/Vol-3756/HOMO-MEX2024_paper1.pdf"><u>UC-CUJAE at HOMO-MEX 2024: Detecting Hate Speech Against the LGTB+ Community using Transformers on Imbalanced Datasets.</u></a> In _Proceedings of the Iberian Languages Evaluation Forum (IberLEF 2024)_, Valladolid, Spain. CEUR-WS.org.

Devendra Deepak Kayande, Kishore Kumar Ponnusamy, Prasanna Kumar Kumaresan, Paul Buitelaar, and Bharathi Raja Chakravarthi. 2024. <a href="https://ceur-ws.org/Vol-3756/HOMO-MEX2024_paper2.pdf"><u>VEL at HOMO-MEX 2024: Detecting LGBT+phobia in Mexican Spanish Social Media.</u></a> In _Proceedings of the Iberian Languages Evaluation Forum (IberLEF 2024)_, Valladolid, Spain. CEUR-WS.org.

Daniel Yacob Espinosa, Grigori Sidorov, and Eusebio Ricárdez Vázquez. 2024. <a href="https://ceur-ws.org/Vol-3756/HOMO-MEX2024_paper3.pdf"><u>The LaboCIC at HOMO-MEX 2024: Using BERT to Classify Hate-LGTB Speech.</u></a> In _Proceedings of the Iberian Languages Evaluation Forum (IberLEF 2024)_, Valladolid, Spain. CEUR-WS.org.

Le Minh Quan, Bui Hong Son, and Dang Van Thin. 2024. <a href="https://ceur-ws.org/Vol-3756/HOMO-MEX2024_paper4.pdf"><u>CANTeam at HOMO-MEX 2024: Hate Speech Detection Towards the Mexican Spanish Speaking LGBT+ Population with Large Language Model.</u></a> In _Proceedings of the Iberian Languages Evaluation Forum (IberLEF 2024)_, Valladolid, Spain. CEUR-WS.org.

Omar Garcia Vazquez, Marco Cardoso-Moreno, José Alberto Torres-León, and Diana Jiménez. 2024. <a href="https://ceur-ws.org/Vol-3756/HOMO-MEX2024_paper5.pdf"><u>HomoCIC at HOMO-MEX 2024: Deep Learning Approaches for Classifying Homophobic Content in Tweets and Songs: Leveraging LLM and NL.</u></a> In _Proceedings of the Iberian Languages Evaluation Forum (IberLEF 2024)_, Valladolid, Spain. CEUR-WS.org.

Javier Román-Pásaro, Alvaro Carrillo-Casado, Jacinto Mata-Vázquez, and Victoria Pachón-Álvarez. 2024. <a href="https://ceur-ws.org/Vol-3756/HOMO-MEX2024_paper6.pdf"><u>I2C-UHU at HOMO-MEX 2024: Leveraging Large Language Models and Ensembling Transformers to Identify and Classify Hate Messages Towards the LGBTQ+ Community.</u></a> In _Proceedings of the Iberian Languages Evaluation Forum (IberLEF 2024)_, Valladolid, Spain. CEUR-WS.org.

Roger David Gonzalez-Henao, Duvan Andres Marrugo-Tobon, Juan Carlos Martinez-Santos, and Edwin Puertas. 2024. <a href="https://ceur-ws.org/Vol-3756/HOMO-MEX2024_paper7.pdf"><u>VerbaNexAI Lab at HOMO-MEX 2024: Multiclass and Multilabel Detection of LGBTQ+ Phobic Content Using Transformers.</u></a> In _Proceedings of the Iberian Languages Evaluation Forum (IberLEF 2024)_, Valladolid, Spain. CEUR-WS.org.

Metztli Ramírez-González, Delia Irazú Hernández-Farías, and Manuel Montes-y-Gómez. 2024. <a href="https://ceur-ws.org/Vol-3756/HOMO-MEX2024_paper8.pdf"><u>LabTL-INAOE at HOMO-MEX 2024: Distance-based Representations for LGBT+ Phobia Detection.</u></a> In _Proceedings of the Iberian Languages Evaluation Forum (IberLEF 2024)_, Valladolid, Spain. CEUR-WS.org.

Sergio Damián, David Vázquez, Edgardo Felipe-Riverón, and Cornelio Yáñez-Márquez. 2024. <a href="https://ceur-ws.org/Vol-3756/HOMO-MEX2024_paper9.pdf"><u>DSVS at HOMO-MEX24: Multi-Class and Multi-Label Hate Speech Detection using Transformer-Based Models.</u></a> In _Proceedings of the Iberian Languages Evaluation Forum (IberLEF 2024)_, Valladolid, Spain. CEUR-WS.org.

Luis Ramos, Carolina Palma-Preciado, Olga Kolesnikova, Magdalena Saldana-Perez, Grigori Sidorov, and Moein Shahiki-Tash. 2024. <a href="https://ceur-ws.org/Vol-3756/HOMO-MEX2024_paper10.pdf"><u>IntelliLeksika at HOMO-MEX 2024: Detection of Homophobic Content in Spanish Lyrics with Machine Learning.</u></a> In _Proceedings of the Iberian Languages Evaluation Forum (IberLEF 2024)_, Valladolid, Spain. CEUR-WS.org.

Daniel Ayala Niño, Manuel Montes y Gómez, and Ciro Velasco Cruz. 2024. <a href="https://ceur-ws.org/Vol-3756/HOMO-MEX2024_paper11.pdf"><u>ColPos at HOMO-MEX 2024: Weighted Naive Bayes for LGBTQ+Phobia Detection in Spanish Text.</u></a> In _Proceedings of the Iberian Languages Evaluation Forum (IberLEF 2024)_, Valladolid, Spain. CEUR-WS.org.

### IberLEF2025 – HOMO-LAT: Human-centric polarity detection in Online Messages Oriented to the Latin American-speaking LGBTQ+ population

Papers yet to be published.

## The Final Workshop for EVALITA, the evaluation campaign of Natural Language Processing (NLP) and speech tools for the Italian language

### EVALITA2023 – HODI: Homotransphobia Detection in Italian

`Overview paper`
Debora Nozza, Alessandra Teresa Cignarella, Greta Damo, Tommaso Caselli, and Viviana Patti. 2023. <a href="https://ceur-ws.org/Vol-3473/paper26.pdf"><u>HODI at EVALITA 2023: Overview of the first Shared Task on Homotransphobia Detection in Italian.</u></a> In _Proceedings of the Eighth Evaluation Campaign of Natural Language Processing and Speech Tools for Italian (EVALITA 2023)_, Parma, Italy. CEUR-WS.org.

Irene Siragusa and Roberto Pirrone. 2023. <a href="https://ceur-ws.org/Vol-3473/paper27.pdf"><u>CHILab at HODI: A minimalist approach.</u></a> In _Proceedings of the Eighth Evaluation Campaign of Natural Language Processing and Speech Tools for Italian (EVALITA 2023)_, Parma, Italy. CEUR-WS.org.

Rahul Ponnusamy, Prasanna Kumar Kumaresan, Kishore Kumar Ponnusamy, Charmathi Rajkumar, Ruba Priyadharshini, and Bharathi Raja Chakravarthi. 2023. <a href="https://ceur-ws.org/Vol-3473/paper28.pdf"><u>Team_Tamil at HODI: Few-Shot Learning for Detecting Homotransphobia in Italian Language.</u></a> In _Proceedings of the Eighth Evaluation Campaign of Natural Language Processing and Speech Tools for Italian (EVALITA 2023)_, Parma, Italy. CEUR-WS.org.

Chiara Di Bonaventura, Arianna Muti, and Marco Antonio Stranisci. 2023. <a href="https://ceur-ws.org/Vol-3473/paper29.pdf"><u>O-Dang at HODI and HaSpeeDe3: A Knowledge-Enhanced Approach to Homotransphobia and Hate Speech Detection in Italian.</u></a> In _Proceedings of the Eighth Evaluation Campaign of Natural Language Processing and Speech Tools for Italian (EVALITA 2023)_, Parma, Italy. CEUR-WS.org.

Davide Locatelli and Lorenzo Locatelli. 2023. <a href="https://ceur-ws.org/Vol-3473/paper30.pdf"><u>LCTs at HODI: Homotransphobic Speech Detection on Italian Tweets.</u></a> In _Proceedings of the Eighth Evaluation Campaign of Natural Language Processing and Speech Tools for Italian (EVALITA 2023)_, Parma, Italy. CEUR-WS.org.

Elisa Leonardelli and Camilla Casula. 2023. <a href="https://ceur-ws.org/Vol-3473/paper31.pdf"><u>DH-FBK at HODI: Multi-Task Learning with Classifier Ensemble Agreement, Oversampling and Synthetic Data.</u></a> In _Proceedings of the Eighth Evaluation Campaign of Natural Language Processing and Speech Tools for Italian (EVALITA 2023)_, Parma, Italy. CEUR-WS.org.
