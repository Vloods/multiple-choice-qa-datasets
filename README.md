# Multiple-choice QA datasets
A collection of large datasets containing multiple-choice questions and their answers for use in Natural Language Processing tasks like question answering (QA).

## MMLU (Measuring Massive Multitask Language Understanding)
🎓: https://arxiv.org/pdf/2009.03300.pdf
💻: https://huggingface.co/datasets/cais/mmlu
>This is a massive multitask test consisting of multiple-choice questions from various branches of knowledge. The test spans subjects in the humanities, social sciences, hard sciences, and other areas that are important for some people to learn. This covers 57 tasks including elementary mathematics, US history, computer science, law, and more. To attain high accuracy on this test, models must possess extensive world knowledge and problem solving ability.

| Train | Dev | Val | Test |
| ------ | ------ | ------ | ------ |
| 99842 | 285 | 1531 | 14042 |

## PIQA (Physical Interaction: Question Answering)
🎓: https://arxiv.org/pdf/1911.11641.pdf
💻: https://huggingface.co/datasets/piqa
> To apply eyeshadow without a brush, should I use a cotton swab or a toothpick? Questions requiring this kind of physical commonsense pose a challenge to state-of-the-art natural language understanding systems. The PIQA dataset introduces the task of physical commonsense reasoning and a corresponding benchmark dataset Physical Interaction: Question Answering or PIQA.
> Physical commonsense knowledge is a major challenge on the road to true AI-completeness, including robots that interact with the world and understand natural language.
> PIQA focuses on everyday situations with a preference for atypical solutions. The dataset is inspired by instructables.com, which provides users with instructions on how to build, craft, bake, or manipulate objects using everyday materials.

| Train | Val | Test |
| ------ | ------ | ------ |
| 16100 | 1840 | 3080 |

## ARC (AI2’s Reasoning Challenge)
🎓: https://arxiv.org/pdf/1803.05457v1.pdf
💻: https://huggingface.co/datasets/ai2_arc
> The AI2’s Reasoning Challenge (ARC) dataset is a multiple-choice question-answering dataset, containing questions from science exams from grade 3 to grade 9. The dataset is split in two partitions: Easy and Challenge, where the latter partition contains the more difficult questions that require reasoning. Most of the questions have 4 answer choices, with <1% of all the questions having either 3 or 5 answer choices. ARC includes a supporting KB of 14.3M unstructured text passages.

### Challenge
| Train | Val | Test |
| ------ | ------ | ------ |
| 1119 | 299 | 1172 |

### Easy
| Train | Val | Test |
| ------ | ------ | ------ |
| 2251 | 570 | 2376 |

## CosmosQA 
🎓: https://arxiv.org/pdf/1909.00277.pdf
💻: https://huggingface.co/datasets/cosmos_qa
> Cosmos QA is a large-scale dataset of 35.6K problems that require commonsense-based reading comprehension, formulated as multiple-choice questions. It focuses on reading between the lines over a diverse collection of people's everyday narratives, asking questions concerning on the likely causes or effects of events that require reasoning beyond the exact text spans in the context

| Train | Val | Test |
| ------ | ------ | ------ |
| 25262 | 2985 | 6963 |

## RACE (Large-scale ReAding Comprehension Dataset From Examinations)
🎓: https://aclanthology.org/D17-1082.pdf
💻: https://huggingface.co/datasets/race
> RACE is a large-scale reading comprehension dataset with more than 28,000 passages and nearly 100,000 questions. The dataset is collected from English examinations in China, which are designed for middle school and high school students. The dataset can be served as the training and test sets for machine comprehension.

### All
| Train | Val | Test |
| ------ | ------ | ------ |
| 87866 | 4887 | 4934 |

### High
| Train | Val | Test |
| ------ | ------ | ------ |
| 62445 | 3451 | 3498 |

### Middle
| Train | Val | Test |
| ------ | ------ | ------ |
| 25421 | 1436 | 1436 |

## QASC (Question Answering via Sentence Composition)
🎓: https://arxiv.org/pdf/1910.11473.pdf
💻: https://huggingface.co/datasets/qasc
> QASC is a question-answering dataset with a focus on sentence composition. It consists of 9,980 8-way multiple-choice questions about grade school science (8,134 train, 926 dev, 920 test), and comes with a corpus of 17M sentences.

| Train | Val | Test |
| ------ | ------ | ------ |
| 8134 | 926 | 920 |

## MedMCQA (Multiple-Choice Question Answering)
🎓: https://arxiv.org/pdf/2203.14371.pdf
💻: https://huggingface.co/datasets/medmcqa
> MedMCQA is a large-scale, Multiple-Choice Question Answering (MCQA) dataset designed to address real-world medical entrance exam questions.
> MedMCQA has more than 194k high-quality AIIMS & NEET PG entrance exam MCQs covering 2.4k healthcare topics and 21 medical subjects are collected with an average token length of 12.77 and high topical diversity.
> Each sample contains a question, correct answer(s), and other options which require a deeper language understanding as it tests the 10+ reasoning abilities of a model across a wide range of medical subjects & topics. A detailed explanation of the solution, along with the above information, is provided in this study.

| Train | Val | Test |
| ------ | ------ | ------ |
| 183k | 4180 | 6150 |

## CommonsenseQA
🎓: https://arxiv.org/pdf/1811.00937v2.pdf
💻: https://huggingface.co/datasets/commonsense_qa
> The CommonsenseQA is a dataset for commonsense question answering task. The dataset consists of 12,247 questions with 5 choices each. The dataset was generated by Amazon Mechanical Turk workers in the following process (an example is provided in parentheses):
    1. a crowd worker observes a source concept from ConceptNet (“River”) and three target concepts (“Waterfall”, “Bridge”, “Valley”) that are all related by the same ConceptNet relation (“AtLocation”),
    2. the worker authors three questions, one per target concept, such that only that particular target concept is the answer, while the other two distractor concepts are not, (“Where on a river can you hold a cup upright to catch water on a sunny day?”, “Where can > I stand on a river to see water falling without getting wet?”, “I’m crossing the river, my feet are wet but my body is dry, where am I?”)
    3. for each question, another worker chooses one additional distractor from Concept Net (“pebble”, “stream”, “bank”), and the author another distractor (“mountain”, “bottom”, “island”) manually.

| Train | Val | Test |
| ------ | ------ | ------ |
| 9741 | 1221 | 1140 |

## OpenBookQA
🎓: https://aclanthology.org/D18-1260.pdf
💻: https://huggingface.co/datasets/openbookqa
> OpenBookQA aims to promote research in advanced question-answering, probing a deeper understanding of both the topic (with salient facts summarized as an open book, also provided with the dataset) and the language it is expressed in. In particular, it contains questions that require multi-step reasoning, use of additional common and commonsense knowledge, and rich text comprehension. OpenBookQA is a new kind of question-answering dataset modeled after open book exams for assessing human understanding of a subject.

### Main
| Train | Val | Test |
| ------ | ------ | ------ |
| 4957 | 500 | 500 |

### Additional
| Train | Val | Test |
| ------ | ------ | ------ |
| 4957 | 500 | 500 |

## RiddleSense
🎓: https://arxiv.org/abs/2101.00376
💻: https://huggingface.co/datasets/riddle_sense
> Answering such a riddle-style question is a challenging cognitive process, in that it requires complex commonsense reasoning abilities, an understanding of figurative language, and counterfactual reasoning skills, which are all important abilities for advanced natural language understanding (NLU). However, there is currently no dedicated datasets aiming to test these abilities. Herein, we present RiddleSense, a new multiple-choice question answering task, which comes with the first large dataset (5.7k examples) for answering riddle-style commonsense questions. We systematically evaluate a wide range of models over the challenge, and point out that there is a large gap between the best-supervised model and human performance  suggesting intriguing future research in the direction of higher-order commonsense reasoning and linguistic creativity towards building advanced NLU systems.

| Train | Val | Test |
| ------ | ------ | ------ |
| 3510 | 1021 | 1184 |

## LogiQA
🎓: https://arxiv.org/abs/2007.08124
💻: https://huggingface.co/datasets/lucasmccabe/logiqa
> LogiQA is constructed from the logical comprehension problems from publically available questions of the National Civil Servants Examination of China, which are designed to test the civil servant candidates’ critical thinking and problem solving. This dataset includes the English versions only; the Chinese versions are available via the homepage/original source.

| Train | Val | Test |
| ------ | ------ | ------ |
| 7376 | 651 | 651 |

## HellaSwag
🎓: https://arxiv.org/pdf/1905.07830.pdf
💻: https://huggingface.co/datasets/hellaswag
> HellaSwag is a challenge dataset for evaluating commonsense NLI that is specially hard for state-of-the-art models, though its questions are trivial for humans (>95% accuracy).

| Train | Val | Test |
| ------ | ------ | ------ |
| 39905 | 10042 | 10003 |
