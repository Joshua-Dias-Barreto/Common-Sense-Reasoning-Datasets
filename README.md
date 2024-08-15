# Popular Common Sense Reasoning Datasets

### CREAK
**Link**: [https://www.cs.utexas.edu/~yasumasa/creak/](https://www.cs.utexas.edu/~yasumasa/creak/)  
**Description**: Commonsense reasoning about entity knowledge, bridging fact-checking about entities.  
**Answer Type**: True/False  
**Size**: 13k

<details>
  <summary>Example ⬇️</summary>
  
![](https://production-media.paperswithcode.com/datasets/Screenshot_2021-09-09_at_11.35.30.png)

</details>

### MCScript
**Link**: [https://arxiv.org/abs/1803.05223v1](https://arxiv.org/abs/1803.05223v1)  
**Description**: Given a passage, answer questions.  
**Answer Type**: MCQ (2)  
**Size**: 13k

<details>
  <summary>Example ⬇️</summary>
  
![](https://production-media.paperswithcode.com/datasets/MCScript-0000003556-0a6f41ae.jpg)

</details>

### Winograde
**Link**: [https://winogrande.allenai.org/](https://winogrande.allenai.org/)  
**Description**: Twin sentence problems, inspired by the original WSC design, twin sentences.  
**Answer Type**: MCQ (2)  
**Size**: 44k

<details>
  <summary>Example ⬇️</summary>
  
![](https://production-media.paperswithcode.com/datasets/Screen_Shot_2021-02-01_at_5.05.39_PM.png)

</details>

### CommonsenseQA
**Link**: [https://www.tau-nlp.org/commonsenseqa](https://www.tau-nlp.org/commonsenseqa)  
**Description**: Set of questions regarding everyday commonsense knowledge.  
**Answer Type**: MCQ (5)  
**Size**: 12k

<details>
  <summary>Example ⬇️</summary>
  
```
Q) Where would I not want a fox?
a)hen house b)england c)mountains d)english hunt e)california

Answer: a) hen house
```

</details>

### VisDial
**Link**: [https://visualdialog.org/](https://visualdialog.org/)  
**Description**: Given an image, context and a set of question answers, answer a question.  
**Answer Type**: Descriptive  
**Size**: 120k * 10 = 1.2M

<details>
  <summary>Example ⬇️</summary>
  
![](https://production-media.paperswithcode.com/datasets/VisDial-0000003368-deeb9b6d.jpg)

</details>

### SWAG
**Link**: [https://rowanzellers.com/swag/](https://rowanzellers.com/swag/)  
**Description**: Each question is a video caption from LSMDC or ActivityNet Captions, with four answer choices about what might happen next in the scene. The correct answer is the (real) video caption for the next event in the video; the three incorrect answers are adversarially generated and human verified.  
**Answer Type**: MCQ (4)  
**Size**: 113k

<details>
  <summary>Example ⬇️</summary>
  
![](https://production-media.paperswithcode.com/datasets/Screenshot_2021-01-07_at_17.36.30.png)

</details>

### ReCoRD
**Link**: [https://sheng-z.github.io/ReCoRD-explorer/](https://sheng-z.github.io/ReCoRD-explorer/)  
**Description**: Reading Comprehension with Commonsense Reasoning Dataset (ReCoRD) is a large-scale reading comprehension dataset which requires commonsense reasoning.  
**Answer Type**: Fixed (in passage)  
**Size**: 120k

<details>
  <summary>Example ⬇️</summary>
  
![](https://production-media.paperswithcode.com/datasets/Screen_Shot_2021-01-27_at_1.38.05_PM.png)

</details>

### RiddleSense
**Link**: [https://inklab.usc.edu/RiddleSense/](https://inklab.usc.edu/RiddleSense/)  
**Description**: Set of riddles.  
**Answer Type**: MCQ (5)  
**Size**: 5.7k

<details>
  <summary>Example ⬇️</summary>
  
```
If you take off my skin, I will not cry, but you will. What am I?
a)grape b)onion c)package d)plant e)body

Answer: b)onion
```

</details>

### X-CSQA
**Link**: [https://inklab.usc.edu/XCSR/xcsr_datasets#x-csqa](https://inklab.usc.edu/XCSR/xcsr_datasets#x-csqa)  
**Description**: Multi-lingual commonsense (16 languages).  
**Answer Type**: MCQ (5)  
**Size**: 11k

<details>
  <summary>Example ⬇️</summary>
  
```
{
  "id": "be1920f7ba5454ad",  # an id shared by all languages
  "lang": "en", # one of the 16 language codes.
  "question": { 
    "stem": "What will happen to your knowledge with more learning?",   # question text
    "choices": [
      {"label": "A",  "text": "headaches" },
      {"label": "B",  "text": "bigger brain" },
      {"label": "C",  "text": "education" },
      {"label": "D",  "text": "growth" },
      {"label": "E",  "text": "knowing more" }
    ] },
  "answerKey": "D"    # hidden for test data.
}
```

</details>

### Com2Sense
**Link**: [https://github.com/PlusLabNLP/Com2Sense](https://github.com/PlusLabNLP/Com2Sense)  
**Description**: Set of complementary sentence pairs.  
**Answer Type**: True/False  
**Size**: 8k

<details>
  <summary>Example ⬇️</summary>
  
![](https://production-media.paperswithcode.com/datasets/Screenshot_2021-06-03_at_09.24.08.png)

</details>

### WHOOPS!
**Link**: [https://whoops-benchmark.github.io/](https://whoops-benchmark.github.io/)  
**Description**: Commonsense defying images, reasoning for weirdness, captioning, generating correct images, etc.  
**Answer Type**: -  
**Size**: -

<details>
  <summary>Example ⬇️</summary>
  
![](https://production-media.paperswithcode.com/datasets/34cbc9d9-3bee-4885-9ce6-0225a70897fa.jpg)

</details>

### NumerSense
**Link**: [https://inklab.usc.edu/NumerSense/](https://inklab.usc.edu/NumerSense/)  
**Description**: Set of masked sentences with numerical answers.  
**Answer Type**: Any Number (0 to 10)
**Size**: 14k

<details>
  <summary>Example ⬇️</summary>
  
```
A bicycle has [MASK] tires.
Answer: 2
```

</details>

### Sarcasm Corpus V2
**Link**: [https://nlds.soe.ucsc.edu/sarcasm2](https://nlds.soe.ucsc.edu/sarcasm2)  
**Description**: Set of sarcastic and non-sarcastic sentences.  
**Answer Type**: True/False  
**Size**: 9k

<details>
  <summary>Example ⬇️</summary>
  
![](https://production-media.paperswithcode.com/datasets/sarcasm.jpg)

</details>

### PACS
**Link**: [https://github.com/samuelyu2002/PACS](https://github.com/samuelyu2002/PACS)  
**Description**: Physical commonsense with images, audio.  
**Answer Type**: Fixed answer  
**Size**: -

<details>
  <summary>Example ⬇️</summary>
  
![](https://production-media.paperswithcode.com/datasets/c6af9fc8-9bc6-4385-9391-6689d6a65f04.png)

</details>

### This is Not a Dataset
**Link**: [https://github.com/hitz-zentroa/This-is-not-a-Dataset](https://github.com/hitz-zentroa/This-is-not-a-Dataset)  
**Description**: Commonsense with negation.  
**Answer Type**: True/False  
**Size**: 380k

<details>
  <summary>Example ⬇️</summary>
  
```
Q) Bills are commonly part of birds
A) True

Q) Bills are never part of birds
A) False
```

</details>



### StrategyQA
**Link**: [https://arxiv.org/abs/2101.02235](https://arxiv.org/abs/2101.02235)  
**Description**: Commonsense with decomposition (strategy questions).  
**Answer Type**: True/False  
**Size**: 2.5k

<details>
  <summary>Example ⬇️</summary>
  
![](https://production-media.paperswithcode.com/datasets/strategyqa.png)

</details>

### BoolQ
**Link**: [https://github.com/google-research-datasets/boolean-questions](https://github.com/google-research-datasets/boolean-questions)  
**Description**: Answer a question from a passage.  
**Answer Type**: True/False  
**Size**: 16k

<details>
  <summary>Example ⬇️</summary>
  
![](https://production-media.paperswithcode.com/datasets/BoolQ-0000001329-5f81a5d7_CwfNA8f.jpg)

</details>

### OpenBookQA
**Link**: [https://huggingface.co/datasets/allenai/openbookqa](https://huggingface.co/datasets/allenai/openbookqa)  
**Description**: Given a fact, answer questions which revolve around that fact.  
**Answer Type**: MCQ (4)  
**Size**: 6k

<details>
  <summary>Example ⬇️</summary>
  
![](https://production-media.paperswithcode.com/datasets/OpenBookQA-0000002426-0fb76b92_C0D71QL.jpg)

</details>

### VCR
**Link**: [https://visualcommonsense.com/](https://visualcommonsense.com/)  
**Description**: Given an image, answer a question and explain the rationale behind it.  
**Answer Type**: MCQ (4) + Descriptive  
**Size**: 260k

<details>
  <summary>Example ⬇️</summary>
  
![](https://production-media.paperswithcode.com/datasets/VCR-0000000216-581da9d9_ccHlrxk.jpg)

</details>

### PIQA
**Link**: [https://arxiv.org/abs/1911.11641](https://arxiv.org/abs/1911.11641)  
**Description**: Physical commonsense reasoning.  
**Answer Type**: MCQ (2)  
**Size**: 21k

<details>
  <summary>Example ⬇️</summary>
  
![](https://production-media.paperswithcode.com/datasets/Screen_Shot_2021-03-16_at_2.10.51_PM.png)

</details>

### ARC
**Link**: [https://arxiv.org/abs/1803.05457](https://arxiv.org/abs/1803.05457)  
**Description**: Science grade-school level questions.  
**Answer Type**: MCQ (4)  
**Size**: 8k

<details>
  <summary>Example ⬇️</summary>
  
```
Q) Which property of a mineral can be determined just by looking at it?
A) luster  B) mass  C) weight  D) hardness
Correct Choice: A) luster
```

</details>

### COPA
**Link**: [https://www.researchgate.net/publication/221251392_Choice_of_Plausible_Alternatives_An_Evaluation_of_Commonsense_Causal_Reasoning](https://www.researchgate.net/publication/221251392_Choice_of_Plausible_Alternatives_An_Evaluation_of_Commonsense_Causal_Reasoning)  
**Description**: Open-domain commonsense causal reasoning of everyday activities.  
**Answer Type**: MCQ (2)  
**Size**: 1k

<details>
  <summary>Example ⬇️</summary>
  
![](https://production-media.paperswithcode.com/datasets/COPA-0000001331-20d6c9a0_dcaRFto.jpg)

</details>

### XCOPA
**Link**: [https://github.com/cambridgeltl/xcopa](https://github.com/cambridgeltl/xcopa)  
**Description**: COPA dataset in 11 languages.  
**Answer Type**: MCQ (2)  
**Size**: 11k

<details>
  <summary>Example ⬇️</summary>
  
```
Premise: L'uomo aprì il rubinetto.
Alternative 1: Il gabinetto si riempì d'acqua.
Alternative 2: Dell'acqua fluì dal beccuccio.
Correct Choice: Alternative 1
```

</details>

### CODAH
**Link**: [https://github.com/Websail-NU/CODAH](https://github.com/Websail-NU/CODAH)  
**Description**: Grounded situations in everyday activities.  
**Answer Type**: MCQ (4)  
**Size**: 3k

<details>
  <summary>Example ⬇️</summary>
  
![](https://production-media.paperswithcode.com/datasets/CODAH-0000001011-be7eead2_6drVi2P.jpg)

</details>

### MC-TACO
**Link**: [https://github.com/CogComp/MCTACO](https://github.com/CogComp/MCTACO)  
**Description**: Temporal Commonsense. Focusing on event ordering, duration, stationarity, frequency and time.  
**Answer Type**: MCQ (5)  
**Size**: 13k

<details>
  <summary>Example ⬇️</summary>
  
```
Paragraph: Growing up on a farm near St. Paul, L. Mark Bailey didn't dream of becoming a judge.
Q) How many years did it take for Mark to become a judge?
A) 63 years  B) 7 weeks  C) 7 years  D) 7 seconds  E) 7 hours
Correct Choice: C) 7 years
```

</details>

### aNLI
**Link**: [https://arxiv.org/abs/1908.05739](https://arxiv.org/abs/1908.05739)  
**Description**: Observations of objects or events in daily life.  
**Answer Type**: MCQ (2)  
**Size**: 18k

<details>
  <summary>Example ⬇️</summary>
  
```  
Obs1: It was a gorgeous day outside.
Obs2: She asked her neighbor for a jump-start.
Hyp1: Mary decided to drive to the beach, but her car would not start due to a dead battery.
Hyp2: It made a weird sound upon starting.
Correct Choice: Hyp1
```

</details>

### QASC
**Link**: [https://arxiv.org/abs/1910.11473](https://arxiv.org/abs/1910.11473)  
**Description**: Elementary and middle school level science, with a focus on fact composition.  
**Answer Type**: MCQ (8)  
**Size**: 10k

<details>
  <summary>Example ⬇️</summary>
  
![](https://production-media.paperswithcode.com/datasets/Screenshot_2021-01-11_at_16.06.20.png)

</details>

### Cosmos QA
**Link**: [https://arxiv.org/abs/1909.00277](https://arxiv.org/abs/1909.00277)  
**Description**: Reading comprehension with a focus on people’s everyday narratives, asking questions concerning the likely causes or effects of events that require reasoning beyond the exact text spans in the context.  
**Answer Type**: MCQ (4)  
**Size**: 36k

<details>
  <summary>Example ⬇️</summary>
  
![](https://production-media.paperswithcode.com/datasets/CosmosQA-0000003567-0f1f39e5.jpg)

</details>

### DREAM
**Link**: [https://arxiv.org/abs/1902.00164](https://arxiv.org/abs/1902.00164)  
**Description**: Multi-turn multi-party dialogues covering a variety of topics and scenarios in daily life. 34% of questions involve commonsense reasoning.  
**Answer Type**: MCQ (3)  
**Size**: 10k

<details>
  <summary>Example ⬇️</summary>
  
![](https://production-media.paperswithcode.com/datasets/Screenshot_2021-01-27_at_14.20.54.png)

</details>

### SIQA
**Link**: [https://arxiv.org/abs/1904.09728](https://arxiv.org/abs/1904.09728)  
**Description**: Social Interactions. It focuses on reasoning about people’s actions and their social implications.  
**Answer Type**: MCQ (3)  
**Size**: 38k

<details>
  <summary>Example ⬇️</summary>
  
![](https://production-media.paperswithcode.com/datasets/Social_IQA-0000003563-28fd0127.jpg)

</details>
