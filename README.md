# Queer NLP Paper Repository
This repository collects papers that sit at the intersection between the queer community and natural language processing. It is sorted by tasks, and a single paper can appear in multiple sections. Tasks are presented in alphabetical order and papers are presented in chronological order.

This repository does not contain:
- papers from outside of NLP (e.g. linguistics, sociology, gender studies);
- papers that don't explicitly mention the queer community or subsets of the queer community.

If you want a paper to be added to this repository, you can make a pull request or submit it via <a href="https://docs.google.com/forms/d/e/1FAIpQLScpZxc6V5OgS77hy08qt3iuA1vOdqkvCuQ74xRSGJ6Hjs7zAw/viewform?usp=header"><u>this google form</u></a>.

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

Alicia Parrish, Angelica Chen, Nikita Nangia, Vishakh Padmakumar, Jason Phang, Jana Thompson, Phu Mon Htut, and Samuel Bowman. 2022. <a href="https://aclanthology.org/2022.findings-acl.165/"><u>BBQ: A hand-built bias benchmark for question answering.</u></a> In _Findings of the Association for Computational Linguistics: ACL 2022_, pages 2086–2105, Dublin, Ireland. Association for Computational Linguistics.

Juan Vásquez, Gemma Bel-Enguix, Scott Thomas Andersen, and Sergio-Luis Ojeda-Trueba. 2022. <a href="https://aclanthology.org/2022.gebnlp-1.23"><u>Heterocorpus: A Corpus for Heteronormative Language Detection.</u></a> In _Proceedings of the 4th Workshop on Gender Bias in Natural Language Processing (GeBNLP)_, pages 225–234, Seattle, Washington. Association for Computational Linguistics.

Juan Vásquez, Scott Andersen, Gemma Bel-enguix, Helena Gómez-adorno, and Sergio-luis Ojeda-trueba. 2023. <a href="https://aclanthology.org/2023.woah-1.20"><u>HOMO-MEX: A Mexican Spanish Annotated Corpus for LGBT+phobia Detection on Twitter.</u></a> In _The 7th Workshop on Online Abuse and Harms (WOAH)_, pages 202–214, Toronto, Canada. Association for Computational Linguistics.

Virginia Felkner, Ho-Chun Herbert Chang, Eugene Jang, and Jonathan May. 2023. <a href="https://aclanthology.org/2023.acl-long.507/"><u>WinoQueer: A Community-in-the-Loop Benchmark for Anti-LGBTQ+ Bias in Large Language Models.</u></a> In _Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)_, pages 9126–9140, Toronto, Canada. Association for Computational Linguistics.

Nathan Dennler, Anaelia Ovalle, Ashwin Singh, Luca Soldaini, Arjun Subramonian, Huy Tu, William Agnew, Avijit Ghosh, Kyra Yee, Irene Font Peradejordi, Zeerak Talat, Mayra Russo, and Jess De Jesus De Pinho Pinhal. 2023. <a href="https://dl.acm.org/doi/pdf/10.1145/3600211.3604682?casa_token=Ur4BPZa80YcAAAAA:TF4epkxXo7-Ey_-LyDPsCPQGoZ9HF6N19kFU9jXtoMs3CPH3x0zPN7IYITtKzOwyKnZIE-5FRbFJzg"><u>Bound by the Bounty: Collaboratively Shaping Evaluation Processes for Queer AI Harms.</u></a> In _Proceedings of the 2023 AAAI/ACM Conference on AI, Ethics, and Society (AIES '23)_, pages 375–386, Montréal, Canada. Association for Computing Machinery.

Andrea Piergentili, Beatrice Savoldi, Dennis Fucci, Matteo Negri, and Luisa Bentivogli. 2023. <a href="https://aclanthology.org/2023.emnlp-main.873"><u>Hi Guys or Hi Folks? Benchmarking Gender-Neutral Machine Translation with the GeNTE Corpus.</u></a> In _Proceedings of the 2023 Conference on Empirical Methods in Natural Language Processing_, pages 14124–14140, Singapore. Association for Computational Linguistics.

Alex Tamkin, Amanda Askell, Liane Lovitt, Esin Durmus, Nicholas Joseph, Shauna Kravec, Karina Nguyen, Jared Kaplan, and Deep Ganguli. 2023. <a href="https://arxiv.org/abs/2312.03689"><u>Evaluating and mitigating discrimination in language model decisions.</u></a> _Computing Research Repository_, arXiv:2312.03689.

Alessandra Teresa Cignarella, Manuela Sanguinetti, Simona Frenda, Andrea Marra, Cristina Bosco, and Valerio Basile. 2024. <a href="https://aclanthology.org/2024.lrec-main.1176/"><u>QUEEREOTYPES: A Multi-Source Italian Corpus of Stereotypes towards LGBTQIA+ Community Members.</u></a> In _Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024)_, pages 13429–13441, Torino, Italia. ELRA and ICCL.

Mae Sosto and Alberto Barrón-Cedeño. 2024. <a href="https://arxiv.org/abs/2406.12399"><u> "QueerBench: Quantifying Discrimination in Language Models Toward Queer Identities."</u></a> _Computing Research Repository_, arXiv:2406.12399.

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
Sheng, Emily, et al. <a href="https://aclanthology.org/D19-1339"><u>The Woman Worked as a Babysitter: On Biases in Language Generation.</u></a> Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing and the 9th International Joint Conference on Natural Language Processing

Debora Nozza, Federico Bianchi, Anne Lauscher, and Dirk Hovy. 2022. <a href="https://aclanthology.org/2022.ltedi-1.4/"><u>Measuring Harmful Sentence Completion in Language Models for LGBTQIA+ Individuals.</u></a> In _Proceedings of the Second Workshop on Language Technology for Equality, Diversity and Inclusion_, pages 26–34, Dublin, Ireland. Association for Computational Linguistics.

Ovalle, Anaelia et al. <a href="https://dl.acm.org/doi/10.1145/3593013.3594078"><u>“I’m fully who I am”: Towards Centering Transgender and Non-Binary Voices to Measure Biases in Open Language Generation.</u></a> In Proceedings of the 2023 ACM Conference on Fairness, Accountability, and Transparency (FAccT '23). 

Virginia Felkner, Ho-Chun Herbert Chang, Eugene Jang, and Jonathan May. 2023. <a href="https://aclanthology.org/2023.acl-long.507/"><u>WinoQueer: A Community-in-the-Loop Benchmark for Anti-LGBTQ+ Bias in Large Language Models.</u></a> In _Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)_, pages 9126–9140, Toronto, Canada. Association for Computational Linguistics.

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

Ovalle, Anaelia, et al. <a href="https://aclanthology.org/2024.findings-naacl.113/"><u>Tokenization matters: Navigating data-scarce tokenization for gender inclusive language technologies.</u></a> Findings of the Association for Computational Linguistics: NAACL 2024. 2024.

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

Henrik Björklund and Hannah Devinney. <a href="https://aclanthology.org/2023.ltedi-1.8"><u>Computer, enhence: POS-tagging improvements for nonbinary pronoun use in Swedish.</u></a> In _Proceedings of the Third Workshop on Language Technology for Equality, Diversity and Inclusion_, pages 54–61, Varna, Bulgaria. INCOMA Ltd., Shoumen, Bulgaria.

## Question Answering
Jacqueline Brixey, Rens Hoegen, Wei Lan, Joshua Rusow, Karan Singla, Xusen Yin, Ron Artstein, and Anton Leuski. 2017. <a href="https://aclanthology.org/W17-5544"><u>"Shihbot: A Facebook chatbot for Sexual Health Information on HIV/AIDS."</u></a> In _Proceedings of the 18th Annual SIGdial Meeting on Discourse and Dialogue_, pages 370–373, Saarbrücken, Germany. Association for Computational Linguistics.

Bastian Bunzeck and Sina Zarrieß. 2024. <a href="https://aclanthology.org/2024.genbench-1.3"><u>"The SlayQA benchmark of social reasoning: testing gender-inclusive generalization with neopronouns."</u></a> In _Proceedings of the 2nd GenBench Workshop on Generalisation (Benchmarking) in NLP_, pages 42–53, Miami, United States. Association for Computational Linguistics.

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

Jamell Dacon, Harry Shomer, Shaylynn Crum-Dacon, and Jiliang Tang. 2022. <a href="https://arxiv.org/abs/2207.10032"><u>Detecting Harmful Online Conversational Content towards LGBTQIA+ Individuals.</u></a> _Computing Research Repository_, arXiv:2207.10032. Presented at _Queer in AI Workshop at NAACL 2022_.

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
<a href=""><u> </u></a>
Brian Larson. 2017. <a href="https://aclanthology.org/W17-1601/"><u>Gender as a Variable in Natural-Language Processing: Ethical Considerations.</u></a> In _Proceedings of the First ACL Workshop on Ethics in Natural Language Processing_, pages 1–11, Valencia, Spain. Association for Computational Linguistics.

Sunipa Dev, Masoud Monajatipoor, Anaelia Ovalle, Arjun Subramonian, Jeff Phillips, and Kai-Wei Chang. 2021. <a href="https://aclanthology.org/2021.emnlp-main.150/"><u>Harms of Gender Exclusivity and Challenges in Non-Binary Representation in Language Technologies.</u></a> In _Proceedings of the 2021 Conference on Empirical Methods in Natural Language Processing_, pages 1968–1994, Online and Punta Cana, Dominican Republic. Association for Computational Linguistics.

Devinney, Hannah, Jenny Björklund, and Henrik Björklund. "Theories of “gender” in nlp bias research." Proceedings of the 2022 ACM conference on fairness, accountability, and transparency. 2022.

Factoring the Matrix of Domination: A Critical Review and Reimagination of Intersectionality in AI Fairness A. Ovalle, A. Subramonian, V. Gautam, G. Gee, and K-W Chang. AIES, 2023.

Zhou, Azure. <a href="https://ojs.stanford.edu/ojs/index.php/grace/article/download/3221/1620"><u>Queer Bias in Natural Language Processing: Towards More Expansive Frameworks of Gender and Sexuality in NLP Bias Research.</u></a> 2023

Razvan Amironesei and Mark Diaz. 2023. Relationality and Offensive Speech: A Research Agenda. In The 7th Workshop on Online Abuse and Harms (WOAH), pages 85–95, Toronto, Canada. Association for Computational Linguistics.

Vagrant Gautam, Arjun Subramonian, Anne Lauscher, and Os Keyes. 2024. <a href="https://aclanthology.org/2024.gebnlp-1.20/"><u>Stop! In the Name of Flaws: Disentangling Personal Names and Sociodemographic Attributes in NLP.</u></a> In _Proceedings of the 5th Workshop on Gender Bias in Natural Language Processing (GeBNLP)_, pages 323–337, Bangkok, Thailand. Association for Computational Linguistics.

McAra-Hunter, Dawn. "How AI hype impacts the LGBTQ+ community." AI and Ethics (2024): 1-20.

