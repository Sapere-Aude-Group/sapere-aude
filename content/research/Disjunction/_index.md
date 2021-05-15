---
title: "析取连接词理解的神经生理基础"
date: 2020-12-24
---

# 2021.5.15 更新

## Materials and Design:

Speech synthesizer: iFlytek . Speed of sentences is 30. Pause: No pause or Insert a 200ms pause between connective and "N3".

Stimuli number: 180 sentences x 2 pause condition（no pause vs 200ms）x 2 Sentential connectives(disjunction vs conjunction)=720 stimuli.

720 stimuli will be divided into 4 participant groups. Each participant will hear 180 stimuli and they can't listen both disjunctive version and conjunctive version with the same items.(i.e. if one have listened "张三吃掉了苹果和香蕉。"，then he/she can't listen to the disjunctive version of this sentence"张三吃掉了苹果或香蕉。").

The 180 stimuli will be divied into 4 blocks so that the trials from same condition will not repeat many times. Each block contains 45 trials (11 trials * 4 condition , plus 1 more trial which is different condition for different block.)

[Excel](../Supporting_Information/2021-05-15-trials.xlsx)

## 1. Project Introduction

Suppose two simple propositions _A_ and _B_:

- A：张三吃掉了苹果。
- B：张三吃掉了香蕉。

There exist two basic sentential connectives in logic and natural language, i.e., disjunctive connective "or" ("或" in Mandarin Chinese) and conjunctive connective "and" ("和" in Mandarin Chinese). The basic functions of the two connectives are to combine the two simple propositions A and B to a disjunctive statement, _A or B_ ("A 或 B" in Mandarin Chinese) and a conjunctive statement _A and B_ ("A 和 B" in Mandarin Chinese) respectively:

- 合取句：张三吃掉了苹果**和**香蕉。
- 析取句：张三吃掉了苹果**或**香蕉。

Importantly, when combined by different connectives, the mental status of the two simple propositions changes: When combined by the conjunctive connective "and", the propositions _A_ and _B_ describe something that is actually happened in the actual world. When combined by the disjunctive connective "or", however, the same propositions _A_ and _B_ are only descriptions of something that is possibly but not actually happened in the actual world.

The remaining questions is how the described difference is neurobiologically differed by the human brain, or in more broad sense how the so called fact and possibility are differed by the human brain. This project intends to explore these questions. Some possible neuromarkers are  _N400_, Neuroal oscillations mu, etc.

## 3. Current work to do

#### 3.1 Experimental materials

- Sentence format: _N1 + V + N2 + and/or (和/或) + N3_. There is no specific requirement for "N1" and "V". "N2" and "N3" however, should be all of __two syllables__, to keep the time course of our critical temporal periods the same.

- Sentence number: Test sentences will be about 180 in total (60 "and" + 60 "or" + 60 fillers = 180). If not possible, the number of fillers can be a litter smaller.

- Design: The design will be counterbalanced, i.e., the 180 test sentences will be divided into three versions.

- Audio generation software: Find the most appropriate software to synthesize auditory version of the test sentences, and convert the designed sentences into their auditory formats.

- Add some jittered pause (comment 7 of Dan) between the connective and _N3_. 'praat' is a possible option.

- Mark the onset of the sentential connective and _N3_ for each sentence. 'praat' is also a possible option.

The Previous will be charged by **Meng Wang**, planned to be completed before the Chinese New Year.

#### 3.2 Experiments conducting

- To participate the relevant trainings and some other projects conducted by the lab to familiarize with the procedure of the experiments.

All group members, especially Hui-Hui Fan, Xiu-Mei Xia, Jing Xu, Xiang Li are required to participate.

## 2. Comments from Dr. Dan Zhang

1. Remove all visual presentation and replace with a fixation cross throughout the audio presentation period.

2. Add a simple question (e.g., was ‘cow’ mentioned in the heard sentence) after each trial (i.e., sentence) for the attention control purpose.

3. Recommend to have >=60 trials per condition, each trial with a difference sentence. 

4. We could have matching ending words (like 公鸡) across conditions, in order to have comparable stimulus sets to later ERP analysis.

5. Use synthesized sentences for audio generation. Neospeech synthesizer (http://www.neospeech.com/) could be one option.

6. Skip the words of ‘一只’ to make the stimuli concise.

7. Introduce jittered intervals (e.g., 400-600 ms) between the conjunction / disjunction words and the ending words, for obtaining clean ERPs while having naturally paced speech.

8. Might be good to introduce control conditions for the possible confounding factor by the difference acoustic forms of 和 and 或.
