# Assessing Multimodal LLMs on Three National Undergraduate Computing Exams in Brazil: Accuracy, Stability, and Cross-Exam Generalization

This repository contains supplementary materials for the study reported in the paper “Assessing Multimodal LLMs on Three National Undergraduate Computing Exams in Brazil: Accuracy, Stability, and Cross-Exam Generalization”.
## ENADE Computer Science exam
The tables below provide an overview of the answers produced by the LLMs for the multiple-choice questions from the ENADE Computer Science exam. The questions were supplied to the LLMs as images.

## Performance of **ChatGPT o4-mini** over 10 rounds on the 25 image-based questions from the ENADE Computer Science exam  

| Question | Answer Key | Difficulty Level | Point-Biserial Correlation | Scored | Response 1 | Response 2 | Response 3 | Response 4 | Response 5 | Response 6 | Response 7 | Response 8 | Response 9 | Response 10 | Score |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| [9](questions/cc/q09.md) | E | Medium | 0.24 | Yes | E | X | E | X | X | E | E | E | E | E | 7 |
| [10](questions/cc/q10.md) | B | Hard | 0.40 | Yes | B | B | B | B | B | B | B | B | B | B | 10 |
| [11](questions/cc/q11.md) | D | Easy | 0.47 | Yes | D | D | D | D | D | D | D | D | D | D | 10 |
| [12](questions/cc/q12.md) | B | Very Hard | 0.04 | Yes | B | B | B | B | B | B | B | B | B | B | 10 |
| [13](questions/cc/q13.md) | E | Hard | -0.04 | Yes | D | D | D | D | D | D | D | D | D | D | 0 |
| [14](questions/cc/q14.md) | C | Hard | 0.26 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [15](questions/cc/q15.md) | C | Medium | 0.29 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [16](questions/cc/q16.md) | B | Easy | 0.37 | Yes | B | B | B | B | B | B | B | B | B | B | 10 |
| [17](questions/cc/q17.md) | C | Very Hard | -0.01 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [18](questions/cc/q18.md) | E | Medium | 0.31 | Yes | E | E | E | E | E | E | E | E | E | E | 10 |
| [19](questions/cc/q19.md) | D | Hard | 0.26 | Yes | D | D | D | D | D | D | D | D | D | D | 10 |
| [20](questions/cc/q20.md) | A | Hard | 0.53 | Yes | A | A | A | A | A | A | A | A | A | A | 10 |
| [21](questions/cc/q21.md) | E | Very Hard | -0.08 | Yes | E | D | D | D | E | D | D | D | E | X | 3 |
| [22](questions/cc/q22.md) | A | Medium | 0.38 | Yes | A | A | A | A | A | A | A | A | A | A | 10 |
| [23](questions/cc/q23.md) | C | Medium | 0.28 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [24](questions/cc/q24.md) | E | Hard | 0.33 | Yes | E | E | E | C | D | C | A | C | C | E | 4 |
| [25](questions/cc/q25.md) | B | Hard | -0.05 | Yes | D | D | D | D | D | D | D | D | D | D | 0 |
| [26](questions/cc/q26.md) | A | Very Hard | 0.23 | Yes | A | A | A | A | A | A | A | A | A | A | 10 |
| [27](questions/cc/q27.md) | D | Medium | 0.45 | Yes | D | D | D | D | D | D | D | D | D | D | 10 |
| [28](questions/cc/q28.md) | B | Hard | 0.34 | Yes | B | B | B | B | B | B | B | B | B | B | 10 |
| [30](questions/cc/q30.md) | E | Medium | 0.37 | Yes | E | E | E | E | E | E | E | E | E | E | 10 |
| [31](questions/cc/q31.md) | E | Hard | 0.37 | Yes | E | C | X | E | C | B | X | C | X | E | 3 |
| [32](questions/cc/q32.md) | A | Hard | 0.02 | Yes | A | A | A | A | A | A | X | A | A | A | 9 |
| [34](questions/cc/q34.md) | C | Hard | 0.20 | Yes | C | C | C | C | C | X | C | C | C | C | 9 |
| [35](questions/cc/q35.md) | D | Medium | 0.48 | Yes | D | D | D | D | D | D | D | D | D | D | 10 |
| **Correct Answers** |  |  |  |  | 23 | 20 | 21 | 20 | 20 | 19 | 19 | 20 | 21 | 22 | **20,5** |
| **Accuracy %** |  |  |  |  | 92,0% | 80,0% | 84,0% | 80,0% | 80,0% | 76,0% | 76,0% | 80,0% | 84,0% | 88,0% | **82,0%** |

## Performance of **ChatGPT o3** over 10 rounds on the 25 image-based questions from the ENADE Computer Science exam  

| Question | Answer Key | Difficulty Level | Point-Biserial Correlation | Scored | Response 1 | Response 2 | Response 3 | Response 4 | Response 5 | Response 6 | Response 7 | Response 8 | Response 9 | Response 10 | Score |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| [9](questions/cc/q09.md) | E | Medium | 0.24 | Yes | E | E | E | E | E | E | E | E | E | E | 10 |
| [10](questions/cc/q10.md) | B | Hard | 0.40 | Yes | B | B | B | B | B | B | B | B | B | B | 10 |
| [11](questions/cc/q11.md) | D | Easy | 0.47 | Yes | D | D | D | D | D | D | D | D | D | D | 10 |
| [12](questions/cc/q12.md) | B | Very Hard | 0.04 | Yes | B | B | B | B | B | B | B | B | B | B | 10 |
| [13](questions/cc/q13.md) | E | Hard | -0.04 | Yes | D | D | D | D | D | D | D | D | D | D | 0 |
| [14](questions/cc/q14.md) | C | Hard | 0.26 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [15](questions/cc/q15.md) | C | Medium | 0.29 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [16](questions/cc/q16.md) | B | Easy | 0.37 | Yes | B | C | B | C | C | B | B | B | B | B | 7 |
| [17](questions/cc/q17.md) | C | Very Hard | -0.01 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [18](questions/cc/q18.md) | E | Medium | 0.31 | Yes | E | E | E | E | E | E | E | E | E | E | 10 |
| [19](questions/cc/q19.md) | D | Hard | 0.26 | Yes | D | D | D | D | D | D | D | D | D | D | 10 |
| [20](questions/cc/q20.md) | A | Hard | 0.53 | Yes | A | A | A | A | A | A | A | A | A | A | 10 |
| [21](questions/cc/q21.md) | E | Very Hard | -0.08 | Yes | D | E | D | D | D | D | D | D | D | E | 2 |
| [22](questions/cc/q22.md) | A | Medium | 0.38 | Yes | A | A | C | A | A | A | C | A | A | A | 8 |
| [23](questions/cc/q23.md) | C | Medium | 0.28 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [24](questions/cc/q24.md) | E | Hard | 0.33 | Yes | E | A | A | A | A | A | A | A | A | A | 1 |
| [25](questions/cc/q25.md) | B | Hard | -0.05 | Yes | D | D | D | D | D | D | D | D | D | D | 0 |
| [26](questions/cc/q26.md) | A | Very Hard | 0.23 | Yes | A | A | A | A | A | A | A | A | A | A | 10 |
| [27](questions/cc/q27.md) | D | Medium | 0.45 | Yes | D | D | D | D | D | D | D | D | D | D | 10 |
| [28](questions/cc/q28.md) | B | Hard | 0.34 | Yes | B | B | B | B | B | B | B | B | B | B | 10 |
| [30](questions/cc/q30.md) | E | Medium | 0.37 | Yes | E | E | E | E | E | E | E | E | E | E | 10 |
| [31](questions/cc/q31.md) | E | Hard | 0.37 | Yes | E | E | E | E | E | E | E | E | E | E | 10 |
| [32](questions/cc/q32.md) | A | Hard | 0.02 | Yes | A | A | A | A | A | A | A | A | A | A | 10 |
| [34](questions/cc/q34.md) | C | Hard | 0.20 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [35](questions/cc/q35.md) | D | Medium | 0.48 | Yes | D | D | D | D | D | D | D | D | D | D | 10 |
| **Correct Answers** |  |  |  |  | 22 | 21 | 20 | 20 | 20 | 21 | 20 | 21 | 21 | 22 | **20,8** |
| **Accuracy %** |  |  |  |  | 88,0% | 84,0% | 80,0% | 80,0% | 80,0% | 84,0% | 80,0% | 84,0% | 84,0% | 88,0% | **83,2%** |

## Performance of **Deepseek - V3** over 10 rounds on the 25 image-based questions from the ENADE Computer Science exam  

| Question | Answer Key | Difficulty Level | Point-Biserial Correlation | Scored | Response 1 | Response 2 | Response 3 | Response 4 | Response 5 | Response 6 | Response 7 | Response 8 | Response 9 | Response 10 | Score |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| [9](questions/cc/q09.md) | E | Medium | 0.24 | Yes | D | D | C | D | D | E | C | E | C | D | 2 |
| [10](questions/cc/q10.md) | B | Hard | 0.40 | Yes | B | B | B | B | B | B | B | B | B | B | 10 |
| [11](questions/cc/q11.md) | D | Easy | 0.47 | Yes | E | X | X | X | X | X | A | X | E | X | 0 |
| [12](questions/cc/q12.md) | B | Very Hard | 0.04 | Yes | B | B | D | B | B | B | D | B | D | B | 7 |
| [13](questions/cc/q13.md) | E | Hard | -0.04 | Yes | D | D | D | D | D | D | D | D | D | D | 0 |
| [14](questions/cc/q14.md) | C | Hard | 0.26 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [15](questions/cc/q15.md) | C | Medium | 0.29 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [16](questions/cc/q16.md) | B | Easy | 0.37 | Yes | E | C | A | A | C | B | E | B | A | X | 2 |
| [17](questions/cc/q17.md) | C | Very Hard | -0.01 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [18](questions/cc/q18.md) | E | Medium | 0.31 | Yes | E | E | E | E | X | E | E | E | E | E | 9 |
| [19](questions/cc/q19.md) | D | Hard | 0.26 | Yes | D | D | D | D | D | D | D | D | D | D | 10 |
| [20](questions/cc/q20.md) | A | Hard | 0.53 | Yes | A | A | A | A | A | A | A | A | A | A | 10 |
| [21](questions/cc/q21.md) | E | Very Hard | -0.08 | Yes | E | E | E | E | X | E | E | D | D | E | 7 |
| [22](questions/cc/q22.md) | A | Medium | 0.38 | Yes | A | A | A | X | A | A | A | A | A | X | 8 |
| [23](questions/cc/q23.md) | C | Medium | 0.28 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [24](questions/cc/q24.md) | E | Hard | 0.33 | Yes | X | E | E | E | X | E | E | E | E | E | 8 |
| [25](questions/cc/q25.md) | B | Hard | -0.05 | Yes | D | D | D | D | D | D | D | D | D | D | 0 |
| [26](questions/cc/q26.md) | A | Very Hard | 0.23 | Yes | A | A | A | A | A | A | A | A | A | A | 10 |
| [27](questions/cc/q27.md) | D | Medium | 0.45 | Yes | D | X | D | D | X | D | D | X | X | D | 6 |
| [28](questions/cc/q28.md) | B | Hard | 0.34 | Yes | B | B | B | B | B | B | B | B | B | B | 10 |
| [30](questions/cc/q30.md) | E | Medium | 0.37 | Yes | E | E | E | E | E | E | E | E | E | E | 10 |
| [31](questions/cc/q31.md) | E | Hard | 0.37 | Yes | X | E | D | B | C | E | E | B | C | X | 3 |
| [32](questions/cc/q32.md) | A | Hard | 0.02 | Yes | A | A | A | A | A | A | A | A | A | A | 10 |
| [34](questions/cc/q34.md) | C | Hard | 0.20 | Yes | C | X | C | X | A | C | C | X | X | C | 5 |
| [35](questions/cc/q35.md) | D | Medium | 0.48 | Yes | D | D | D | D | D | D | D | D | D | D | 10 |
| **Correct Answers** |  |  |  |  | 18 | 18 | 18 | 17 | 14 | 22 | 19 | 18 | 15 | 18 | **17,7** |
| **Accuracy %** |  |  |  |  | 72,0% | 72,0% | 72,0% | 68,0% | 56,0% | 88,0% | 76,0% | 72,0% | 60,0% | 72,0% | **70,8%** |

## Performance of **Gemini 2.5 Pro** over 10 rounds on the 25 image-based questions from the ENADE Computer Science exam  

| Question | Answer Key | Difficulty Level | Point-Biserial Correlation | Scored | Response 1 | Response 2 | Response 3 | Response 4 | Response 5 | Response 6 | Response 7 | Response 8 | Response 9 | Response 10 | Score |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| [9](questions/cc/q09.md) | E | Medium | 0.24 | Yes | E | E | B | E | E | E | E | E | E | E | 9 |
| [10](questions/cc/q10.md) | B | Hard | 0.40 | Yes | B | B | B | B | B | B | B | B | B | B | 10 |
| [11](questions/cc/q11.md) | D | Easy | 0.47 | Yes | D | D | D | D | D | D | D | D | D | C | 9 |
| [12](questions/cc/q12.md) | B | Very Hard | 0.04 | Yes | B | B | B | B | B | B | B | B | D | B | 9 |
| [13](questions/cc/q13.md) | E | Hard | -0.04 | Yes | D | D | D | D | D | D | D | D | D | D | 0 |
| [14](questions/cc/q14.md) | C | Hard | 0.26 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [15](questions/cc/q15.md) | C | Medium | 0.29 | Yes | C | C | C | C | C | C | C | C | A | C | 9 |
| [16](questions/cc/q16.md) | B | Easy | 0.37 | Yes | A | C | C | C | C | C | C | C | X | A | 0 |
| [17](questions/cc/q17.md) | C | Very Hard | -0.01 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [18](questions/cc/q18.md) | E | Medium | 0.31 | Yes | E | E | E | E | E | E | E | E | E | E | 10 |
| [19](questions/cc/q19.md) | D | Hard | 0.26 | Yes | D | D | D | D | D | D | D | D | D | D | 10 |
| [20](questions/cc/q20.md) | A | Hard | 0.53 | Yes | A | A | A | A | A | A | A | A | A | A | 10 |
| [21](questions/cc/q21.md) | E | Very Hard | -0.08 | Yes | D | D | D | D | D | D | D | D | D | D | 0 |
| [22](questions/cc/q22.md) | A | Medium | 0.38 | Yes | A | A | A | A | A | A | A | A | A | A | 10 |
| [23](questions/cc/q23.md) | C | Medium | 0.28 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [24](questions/cc/q24.md) | E | Hard | 0.33 | Yes | A | A | A | A | A | A | A | A | A | A | 0 |
| [25](questions/cc/q25.md) | B | Hard | -0.05 | Yes | D | D | D | D | D | D | D | D | D | D | 0 |
| [26](questions/cc/q26.md) | A | Very Hard | 0.23 | Yes | A | A | A | A | A | A | A | A | A | A | 10 |
| [27](questions/cc/q27.md) | D | Medium | 0.45 | Yes | D | D | D | D | D | D | D | D | D | D | 10 |
| [28](questions/cc/q28.md) | B | Hard | 0.34 | Yes | B | B | B | B | B | B | B | B | B | B | 10 |
| [30](questions/cc/q30.md) | E | Medium | 0.37 | Yes | A | A | D | E | E | E | E | E | A | E | 6 |
| [31](questions/cc/q31.md) | E | Hard | 0.37 | Yes | E | E | C | E | E | E | E | E | E | E | 9 |
| [32](questions/cc/q32.md) | A | Hard | 0.02 | Yes | A | A | A | A | A | A | A | A | A | A | 10 |
| [34](questions/cc/q34.md) | C | Hard | 0.20 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [35](questions/cc/q35.md) | D | Medium | 0.48 | Yes | D | D | D | D | D | D | D | D | D | D | 10 |
| **Correct Answers** |  |  |  |  | 19 | 19 | 17 | 20 | 20 | 20 | 20 | 20 | 17 | 19 | **19,1** |
| **Accuracy %** |  |  |  |  | 76,0% | 76,0% | 68,0% | 80,0% | 80,0% | 80,0% | 80,0% | 80,0% | 68,0% | 76,0% | **76,4%** |

## Analysis and Systems Development exam
The tables below provide an overview of the answers produced by the LLMs for the multiple-choice questions from the ENADE Analysis and Systems Development exam. The questions were supplied to the LLMs as images.

## Performance of **Deepseek - V3 R1** over 10 rounds on the 27 image-based questions from the ENADE Analysis and Systems Development exam  

| Question | Answer Key | Difficulty Level | Point-Biserial Correlation | Scored | Response 1 | Response 2 | Response 3 | Response 4 | Response 5 | Response 6 | Response 7 | Response 8 | Response 9 | Response 10 | Score |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| [9](questions/asd/q09.md) | C | Hard | 0.40 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [10](questions/asd/q10.md) | D | Hard | -0.02 | Yes | A | D | D | D | X | A | A | A | A | X | 3 |
| [11](questions/asd/q11.md) | E | Hard | 0.29 | Yes | E | E | E | E | E | E | E | E | E | E | 10 |
| [12](questions/asd/q12.md) | C | Hard | -0.04 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [13](questions/asd/q13.md) | C | Hard | 0.31 | Yes | X | X | X | X | X | X | X | X | X | X | 0 |
| [14](questions/asd/q14.md) | E | Hard | 0.26 | Yes | E | E | E | E | E | E | E | C | E | E | 9 |
| [15](questions/asd/q15.md) | B | Hard | 0.21 | Yes | NTE | NTE | NTE | NTE | NTE | NTE | NTE | NTE | NTE | NTE | 0 |
| [16](questions/asd/q16.md) | E | Very Hard | -0.05 | Yes | E | D | E | C | X | E | D | B | E | E | 5 |
| [17](questions/asd/q17.md) | C | Hard | 0.26 | Yes | D | D | D | D | D | D | D | D | D | D | 0 |
| [18](questions/asd/q18.md) | A | Medium | 0.36 | Yes | A | A | A | A | A | A | A | A | A | A | 10 |
| [19](questions/asd/q19.md) | A | Hard | 0.41 | Yes | X | X | X | X | X | X | X | X | X | X | 0 |
| [20](questions/asd/q20.md) | E | Medium | 0.45 | Yes | X | E | X | X | X | X | E | E | E | X | 4 |
| [21](questions/asd/q21.md) | B | Hard | 0.20 | Yes | B | B | B | B | B | B | B | B | B | B | 10 |
| [22](questions/asd/q22.md) | A | Hard | 0.23 | Yes | A | A | X | A | X | X | A | A | A | A | 7 |
| [23](questions/asd/q23.md) | B | Medium | 0.30 | Yes | B | B | B | B | B | B | B | B | B | B | 10 |
| [24](questions/asd/q24.md) | D | Hard | 0.36 | Yes | D | D | D | D | D | D | D | D | D | D | 10 |
| [25](questions/asd/q25.md) | E | Hard | 0.34 | Yes | E | E | E | E | E | E | E | E | E | E | 10 |
| [26](questions/asd/q26.md) | E | Hard | -0.05 | Yes | E | E | E | E | E | E | E | E | E | E | 10 |
| [27](questions/asd/q27.md) | C | Hard | 0.27 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [28](questions/asd/q28.md) | B | Hard | 0.34 | Yes | B | B | B | B | B | B | B | B | B | B | 10 |
| [29](questions/asd/q29.md) | D | Hard | 0.39 | Yes | D | D | D | D | D | D | D | D | D | D | 10 |
| [30](questions/asd/q30.md) | C | Medium | 0.40 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [31](questions/asd/q31.md) | D | Hard | 0.05 | Yes | D | D | X | D | X | X | D | D | D | D | 7 |
| [32](questions/asd/q32.md) | B | Hard | 0.29 | Yes | B | B | B | B | B | B | B | B | B | B | 10 |
| [33](questions/asd/q33.md) | D | Hard | 0.02 | Yes | D | D | D | E | E | D | D | E | D | E | 6 |
| [34](questions/asd/q34.md) | A | Hard | 0.40 | Yes | A | X | A | X | X | A | A | X | X | A | 5 |
| [35](questions/asd/q35.md) | A | Hard | 0.26 | Yes | A | A | D | A | D | A | D | X | A | A | 6 |
| **Correct Answers** |  |  |  |  | 21 | 21 | 19 | 19 | 15 | 19 | 20 | 17 | 21 | 20 | **19,2** |
| **Accuracy %** |  |  |  |  | 77,8% | 77,8% | 70,4% | 70,4% | 55,6% | 70,4% | 74,1% | 63,0% | 77,8% | 74,1% | **71,1%** |

**Note: NTE = Deepseek did not execute/answer the question in the corresponding round.**


## Performance of **Gemini 2.5 Pro** over 10 rounds on the 27 image-based questions from the ENADE Analysis and Systems Development exam  

| Question | Answer Key | Difficulty Level | Point-Biserial Correlation | Scored | Response 1 | Response 2 | Response 3 | Response 4 | Response 5 | Response 6 | Response 7 | Response 8 | Response 9 | Response 10 | Score |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| [9](questions/asd/q09.md) | C | Hard | 0.40 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [10](questions/asd/q10.md) | D | Hard | -0.02 | Yes | B | D | D | C | C | E | B | E | D | D | 4 |
| [11](questions/asd/q11.md) | E | Hard | 0.29 | Yes | E | E | E | E | E | E | E | E | E | E | 10 |
| [12](questions/asd/q12.md) | C | Hard | -0.04 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [13](questions/asd/q13.md) | C | Hard | 0.31 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [14](questions/asd/q14.md) | E | Hard | 0.26 | Yes | E | E | E | E | E | E | E | E | E | E | 10 |
| [15](questions/asd/q15.md) | B | Hard | 0.21 | Yes | D | B | C | A | B | C | C | C | D | C | 2 |
| [16](questions/asd/q16.md) | E | Very Hard | -0.05 | Yes | X | E | C | E | E | E | B | E | B | B | 5 |
| [17](questions/asd/q17.md) | C | Hard | 0.26 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [18](questions/asd/q18.md) | A | Medium | 0.36 | Yes | A | A | A | A | A | A | A | A | A | A | 10 |
| [19](questions/asd/q19.md) | A | Hard | 0.41 | Yes | X | A | A | A | A | X | A | A | A | X | 7 |
| [20](questions/asd/q20.md) | E | Medium | 0.45 | Yes | E | E | E | E | E | E | E | E | E | E | 10 |
| [21](questions/asd/q21.md) | B | Hard | 0.20 | Yes | B | B | B | B | B | B | B | B | B | B | 10 |
| [22](questions/asd/q22.md) | A | Hard | 0.23 | Yes | A | A | A | A | A | A | A | A | A | A | 10 |
| [23](questions/asd/q23.md) | B | Medium | 0.30 | Yes | B | B | B | B | B | B | B | B | B | B | 10 |
| [24](questions/asd/q24.md) | D | Hard | 0.36 | Yes | D | C | D | X | D | C | E | D | E | C | 4 |
| [25](questions/asd/q25.md) | E | Hard | 0.34 | Yes | E | E | E | E | E | E | E | E | E | E | 10 |
| [26](questions/asd/q26.md) | E | Hard | -0.05 | Yes | E | E | E | E | X | E | E | E | E | E | 9 |
| [27](questions/asd/q27.md) | C | Hard | 0.27 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [28](questions/asd/q28.md) | B | Hard | 0.34 | Yes | B | B | B | B | B | B | B | B | B | B | 10 |
| [29](questions/asd/q29.md) | D | Hard | 0.39 | Yes | D | D | D | D | D | D | D | D | D | D | 10 |
| [30](questions/asd/q30.md) | C | Medium | 0.40 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [31](questions/asd/q31.md) | D | Hard | 0.05 | Yes | D | D | D | D | D | D | D | D | D | D | 10 |
| [32](questions/asd/q32.md) | B | Hard | 0.29 | Yes | B | B | B | B | B | B | B | B | B | B | 10 |
| [33](questions/asd/q33.md) | D | Hard | 0.02 | Yes | D | D | D | D | E | E | D | E | E | E | 5 |
| [34](questions/asd/q34.md) | A | Hard | 0.40 | Yes | A | A | A | A | A | A | A | A | A | A | 10 |
| [35](questions/asd/q35.md) | A | Hard | 0.26 | Yes | A | B | C | X | X | A | A | A | A | A | 6 |
| **Correct Answers** |  |  |  |  | 23 | 25 | 24 | 23 | 23 | 22 | 23 | 24 | 23 | 22 | **23,2** |
| **Accuracy %** |  |  |  |  | 85,2% | 92,6% | 88,9% | 85,2% | 85,2% | 81,5% | 85,2% | 88,9% | 85,2% | 81,5% | **85,9%** |

## Performance of **ChatGPT o3** over 10 rounds on the 27 image-based questions from the ENADE Analysis and Systems Development exam  

| Question | Answer Key | Difficulty Level | Point-Biserial Correlation | Scored | Response 1 | Response 2 | Response 3 | Response 4 | Response 5 | Response 6 | Response 7 | Response 8 | Response 9 | Response 10 | Score |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| [9](questions/asd/q09.md) | C | Hard | 0.40 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [10](questions/asd/q10.md) | D | Hard | -0.02 | Yes | D | X | D | D | A | A | D | D | D | X | 6 |
| [11](questions/asd/q11.md) | E | Hard | 0.29 | Yes | E | E | E | E | E | E | E | E | E | E | 10 |
| [12](questions/asd/q12.md) | C | Hard | -0.04 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [13](questions/asd/q13.md) | C | Hard | 0.31 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [14](questions/asd/q14.md) | E | Hard | 0.26 | Yes | E | E | E | E | E | E | E | E | E | E | 10 |
| [15](questions/asd/q15.md) | B | Hard | 0.21 | Yes | A | D | B | B | A | A | C | D | B | D | 3 |
| [16](questions/asd/q16.md) | E | Very Hard | -0.05 | Yes | E | E | E | E | E | E | E | E | E | E | 10 |
| [17](questions/asd/q17.md) | C | Hard | 0.26 | Yes | C | C | C | C | C | E | C | C | C | C | 9 |
| [18](questions/asd/q18.md) | A | Medium | 0.36 | Yes | A | A | A | A | A | A | A | A | A | A | 10 |
| [19](questions/asd/q19.md) | A | Hard | 0.41 | Yes | A | A | A | A | A | A | A | A | X | A | 9 |
| [20](questions/asd/q20.md) | E | Medium | 0.45 | Yes | E | E | E | E | E | E | E | E | D | E | 9 |
| [21](questions/asd/q21.md) | B | Hard | 0.20 | Yes | B | B | B | B | B | B | B | B | B | B | 10 |
| [22](questions/asd/q22.md) | A | Hard | 0.23 | Yes | A | A | A | A | A | A | A | A | A | A | 10 |
| [23](questions/asd/q23.md) | B | Medium | 0.30 | Yes | B | B | B | B | B | B | B | B | B | B | 10 |
| [24](questions/asd/q24.md) | D | Hard | 0.36 | Yes | D | D | D | D | D | D | D | D | D | D | 10 |
| [25](questions/asd/q25.md) | E | Hard | 0.34 | Yes | E | E | E | E | E | E | E | E | E | E | 10 |
| [26](questions/asd/q26.md) | E | Hard | -0.05 | Yes | E | E | E | E | E | E | E | E | E | E | 10 |
| [27](questions/asd/q27.md) | C | Hard | 0.27 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [28](questions/asd/q28.md) | B | Hard | 0.34 | Yes | B | B | B | B | B | B | B | B | B | B | 10 |
| [29](questions/asd/q29.md) | D | Hard | 0.39 | Yes | D | D | D | D | D | D | D | D | D | D | 10 |
| [30](questions/asd/q30.md) | C | Medium | 0.40 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [31](questions/asd/q31.md) | D | Hard | 0.05 | Yes | C | D | C | D | D | D | C | D | D | D | 7 |
| [32](questions/asd/q32.md) | B | Hard | 0.29 | Yes | B | B | B | B | B | B | B | B | B | B | 10 |
| [33](questions/asd/q33.md) | D | Hard | 0.02 | Yes | D | E | D | D | D | D | E | D | E | E | 6 |
| [34](questions/asd/q34.md) | A | Hard | 0.40 | Yes | A | A | A | A | A | A | A | A | A | X | 9 |
| [35](questions/asd/q35.md) | A | Hard | 0.26 | Yes | A | A | A | A | A | A | A | A | A | A | 10 |
| **Correct Answers** |  |  |  |  | 25 | 24 | 26 | 27 | 25 | 24 | 24 | 26 | 24 | 23 | **24,8** |
| **Accuracy %** |  |  |  |  | 92,6% | 88,9% | 96,3% | 100,0% | 92,6% | 88,9% | 88,9% | 96,3% | 88,9% | 85,2% | **91,9%** |

## Performance of **ChatGPT o4-mini** over 10 rounds on the 27 image-based questions from the ENADE Analysis and Systems Development exam  

| Question | Answer Key | Difficulty Level | Point-Biserial Correlation | Scored | Response 1 | Response 2 | Response 3 | Response 4 | Response 5 | Response 6 | Response 7 | Response 8 | Response 9 | Response 10 | Score |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| [9](questions/asd/q09.md) | C | Hard | 0.40 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [10](questions/asd/q10.md) | D | Hard | -0.02 | Yes | D | D | A | D | D | D | D | A | D | D | 8 |
| [11](questions/asd/q11.md) | E | Hard | 0.29 | Yes | E | E | E | E | E | E | E | E | E | E | 10 |
| [12](questions/asd/q12.md) | C | Hard | -0.04 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [13](questions/asd/q13.md) | C | Hard | 0.31 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [14](questions/asd/q14.md) | E | Hard | 0.26 | Yes | E | E | E | C | E | E | E | E | E | E | 9 |
| [15](questions/asd/q15.md) | B | Hard | 0.21 | Yes | B | E | A | A | B | A | X | A | B | A | 3 |
| [16](questions/asd/q16.md) | E | Very Hard | -0.05 | Yes | X | D | X | X | E | X | X | X | X | E | 2 |
| [17](questions/asd/q17.md) | C | Hard | 0.26 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [18](questions/asd/q18.md) | A | Medium | 0.36 | Yes | A | A | A | A | A | A | A | A | A | A | 10 |
| [19](questions/asd/q19.md) | A | Hard | 0.41 | Yes | X | X | A | X | A | A | A | A | X | A | 6 |
| [20](questions/asd/q20.md) | E | Medium | 0.45 | Yes | E | E | E | E | D | D | X | E | E | X | 6 |
| [21](questions/asd/q21.md) | B | Hard | 0.20 | Yes | B | B | B | B | B | B | B | B | B | B | 10 |
| [22](questions/asd/q22.md) | A | Hard | 0.23 | Yes | A | A | A | X | A | A | A | A | A | A | 9 |
| [23](questions/asd/q23.md) | B | Medium | 0.30 | Yes | B | B | B | B | B | B | B | B | B | B | 10 |
| [24](questions/asd/q24.md) | D | Hard | 0.36 | Yes | D | D | D | D | D | D | D | D | D | D | 10 |
| [25](questions/asd/q25.md) | E | Hard | 0.34 | Yes | E | E | E | E | E | E | E | E | E | E | 10 |
| [26](questions/asd/q26.md) | E | Hard | -0.05 | Yes | E | E | E | X | E | E | E | E | E | E | 9 |
| [27](questions/asd/q27.md) | C | Hard | 0.27 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [28](questions/asd/q28.md) | B | Hard | 0.34 | Yes | B | B | B | B | B | B | B | B | B | B | 10 |
| [29](questions/asd/q29.md) | D | Hard | 0.39 | Yes | D | D | D | D | D | D | D | D | D | D | 10 |
| [30](questions/asd/q30.md) | C | Medium | 0.40 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [31](questions/asd/q31.md) | D | Hard | 0.05 | Yes | D | D | D | D | D | D | D | D | C | X | 8 |
| [32](questions/asd/q32.md) | B | Hard | 0.29 | Yes | X | X | X | B | B | X | X | X | X | X | 2 |
| [33](questions/asd/q33.md) | D | Hard | 0.02 | Yes | D | D | D | D | D | D | D | D | D | D | 10 |
| [34](questions/asd/q34.md) | A | Hard | 0.40 | Yes | A | A | X | X | A | A | X | A | A | X | 6 |
| [35](questions/asd/q35.md) | A | Hard | 0.26 | Yes | A | A | A | A | A | A | X | A | A | A | 9 |
| **Correct Answers** |  |  |  |  | 24 | 23 | 22 | 20 | 26 | 23 | 21 | 23 | 23 | 22 | **22,7** |
| **Accuracy %** |  |  |  |  | 88,9% | 85,2% | 81,5% | 74,1% | 96,3% | 85,2% | 77,8% | 85,2% | 85,2% | 81,5% | **84,1%** |

## Information Systems exam
The tables below provide an overview of the answers produced by the LLMs for the multiple-choice questions from the ENADE Information Systems exam. The questions were supplied to the LLMs as images.

## Performance of **Deepseek - V3 R1** over 10 rounds on the 26 image-based questions from the ENADE Information Systems exam

| Question | Answer Key | Difficulty Level | Point-Biserial Correlation | Scored | Response 1 | Response 2 | Response 3 | Response 4 | Response 5 | Response 6 | Response 7 | Response 8 | Response 9 | Response 10 | Score |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [9](questions/is/q09.md) | C | Very Hard | 0.03 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [10](questions/is/q10.md) | E | Medium | 0.31 | Yes | E | E | E | E | E | D | E | E | E | D | 8 |
| [11](questions/is/q11.md) | C | Medium | 0.24 | Yes | C | C | C | C | D | C | C | D | C | C | 8 |
| [12](questions/is/q12.md) | B | Hard | 0.21 | No | B | B | B | B | B | B | B | B | B | B | 10 |
| [13](questions/is/q13.md) | D | Medium | 0.28 | No | E | D | E | D | D | E | X | D | E | X | 4 |
| [14](questions/is/q14.md) | C | Medium | 0.38 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [15](questions/is/q15.md) | D | Easy | 0.37 | Yes | D | D | D | D | D | D | D | D | D | D | 10 |
| [16](questions/is/q16.md) | A | Hard | 0.22 | Yes | A | A | A | A | A | A | A | A | A | A | 10 |
| [17](questions/is/q17.md) | C | Hard | 0.04 | No | C | B | D | C | C | B | C | C | C | D | 6 |
| [18](questions/is/q18.md) | B | Hard | 0.02 | Yes | B | B | B | B | B | B | B | B | C | B | 9 |
| [19](questions/is/q19.md) | A | Medium | 0.32 | Yes | B | B | B | B | B | B | B | B | B | D | 0 |
| [20](questions/is/q20.md) | B | Hard | 0.36 | Yes | A | A | X | B | B | B | X | B | X | X | 4 |
| [21](questions/is/q21.md) | C | Hard | 0.01 | No | D | D | X | D | D | X | X | D | X | D | 0 |
| [22](questions/is/q22.md) | E | Hard | 0.31 | Yes | D | E | X | D | X | E | X | E | X | X | 3 |
| [23](questions/is/q23.md) | B | Easy | 0.40 | Yes | B | B | B | B | B | B | B | B | B | B | 10 |
| [24](questions/is/q24.md) | B | Hard | 0.27 | Yes | NTE | NTE | NTE | NTE | NTE | NTE | NTE | NTE | NTE | NTE | 0 |
| [25](questions/is/q25.md) | E | Medium | 0.40 | No | C | C | C | C | C | C | C | C | C | C | 0 |
| [26](questions/is/q26.md) | E | Medium | 0.42 | Yes | E | E | E | E | E | E | E | E | E | E | 10 |
| [27](questions/is/q27.md) | D | Hard | 0.03 | Yes | B | B | B | B | B | B | B | B | B | B | 0 |
| [28](questions/is/q28.md) | A | Medium | 0.33 | Yes | X | E | X | E | X | E | X | E | X | E | 0 |
| [29](questions/is/q29.md) | D | Medium | 0.35 | Yes | NTE | NTE | NTE | NTE | NTE | NTE | NTE | NTE | NTE | NTE | 0 |
| [30](questions/is/q30.md) | E | Hard | 0.23 | Yes | E | E | E | E | E | E | E | E | E | E | 10 |
| [31](questions/is/q31.md) | A | Hard | 0.20 | Yes | A | A | A | A | A | A | A | A | A | A | 10 |
| [32](questions/is/q32.md) | C | Hard | 0.30 | No | E | C | C | C | D | E | B | E | B | B | 3 |
| [34](questions/is/q34.md) | D | Hard | 0.35 | Yes | D | D | D | D | D | D | D | D | D | D | 10 |
| [35](questions/is/q35.md) | D | Hard | 0.30 | Yes | D | D | D | D | X | D | D | D | D | D | 9 |
| **Correct Answers** |  |  |  |  | 15 | 17 | 15 | 18 | 15 | 15 | 15 | 17 | 14 | 13 | **15,4** |
| **Accuracy %** |  |  |  |  | 57,7% | 65,4% | 57,7% | 69,2% | 57,7% | 57,7% | 57,7% | 65,4% | 53,8% | 50,0% | **59,2%** |

**Note: NTE = Deepseek did not execute/answer the question in the corresponding round.**



## Performance of **Gemini 2.5 Pro** over 10 rounds on the 26 image-based questions from the ENADE Information Systems exam

| Question | Answer Key | Difficulty Level | Point-Biserial Correlation | Scored | Response 1 | Response 2 | Response 3 | Response 4 | Response 5 | Response 6 | Response 7 | Response 8 | Response 9 | Response 10 | Score |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [9](questions/is/q09.md) | C | Very Hard | 0.03 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [10](questions/is/q10.md) | E | Medium | 0.31 | Yes | E | E | E | E | E | E | E | E | E | E | 10 |
| [11](questions/is/q11.md) | C | Medium | 0.24 | Yes | C | C | D | C | C | C | D | C | C | C | 8 |
| [12](questions/is/q12.md) | B | Hard | 0.21 | No | C | C | C | C | C | C | C | C | C | C | 0 |
| [13](questions/is/q13.md) | D | Medium | 0.28 | No | E | E | E | E | E | E | E | E | E | E | 0 |
| [14](questions/is/q14.md) | C | Medium | 0.38 | Yes | C | C | C | C | C | C | C | C | D | C | 9 |
| [15](questions/is/q15.md) | D | Easy | 0.37 | Yes | D | D | D | D | D | D | D | D | D | D | 10 |
| [16](questions/is/q16.md) | A | Hard | 0.22 | Yes | A | A | A | A | A | A | A | A | A | A | 10 |
| [17](questions/is/q17.md) | C | Hard | 0.04 | No | C | C | C | C | C | C | C | C | C | C | 10 |
| [18](questions/is/q18.md) | B | Hard | 0.02 | Yes | B | B | B | B | B | B | B | B | B | B | 10 |
| [19](questions/is/q19.md) | A | Medium | 0.32 | Yes | B | B | A | B | B | A | B | B | B | B | 2 |
| [20](questions/is/q20.md) | B | Hard | 0.36 | Yes | B | A | B | E | B | B | A | B | B | A | 6 |
| [21](questions/is/q21.md) | C | Hard | 0.01 | No | E | C | C | C | C | E | C | C | C | C | 8 |
| [22](questions/is/q22.md) | E | Hard | 0.31 | Yes | D | D | A | D | D | D | D | A | D | D | 0 |
| [23](questions/is/q23.md) | B | Easy | 0.40 | Yes | B | E | B | B | B | B | B | B | B | B | 9 |
| [24](questions/is/q24.md) | B | Hard | 0.27 | Yes | B | B | B | B | B | B | B | B | B | B | 10 |
| [25](questions/is/q25.md) | E | Medium | 0.40 | No | E | C | E | E | E | E | E | E | E | E | 9 |
| [26](questions/is/q26.md) | E | Medium | 0.42 | Yes | E | E | E | E | E | E | E | E | A | E | 9 |
| [27](questions/is/q27.md) | D | Hard | 0.03 | Yes | B | B | B | B | B | B | B | B | B | B | 0 |
| [28](questions/is/q28.md) | A | Medium | 0.33 | Yes | E | E | E | E | E | A | E | E | E | E | 1 |
| [29](questions/is/q29.md) | D | Medium | 0.35 | Yes | D | D | C | C | D | C | C | E | E | E | 3 |
| [30](questions/is/q30.md) | E | Hard | 0.23 | Yes | E | E | E | E | E | E | E | E | E | E | 10 |
| [31](questions/is/q31.md) | A | Hard | 0.20 | Yes | A | A | A | A | A | A | A | A | A | A | 10 |
| [32](questions/is/q32.md) | C | Hard | 0.30 | No | C | C | C | C | C | C | C | C | C | C | 10 |
| [34](questions/is/q34.md) | D | Hard | 0.35 | Yes | D | D | D | D | D | D | D | D | D | D | 10 |
| [35](questions/is/q35.md) | D | Hard | 0.30 | Yes | D | D | D | D | D | D | D | D | D | D | 10 |
| **Correct Answers** |  |  |  |  | 19 | 17 | 19 | 18 | 20 | 20 | 17 | 19 | 17 | 18 | **18,4** |
| **Accuracy %** |  |  |  |  | 73,1% | 65,4% | 73,1% | 69,2% | 76,9% | 76,9% | 65,4% | 73,1% | 65,4% | 69,2% | **70,8%** |


## Performance of **ChatGPT o3** over 10 rounds on the 26 image-based questions from the ENADE Information Systems exam

| Question | Answer Key | Difficulty Level | Point-Biserial Correlation | Scored | Response 1 | Response 2 | Response 3 | Response 4 | Response 5 | Response 6 | Response 7 | Response 8 | Response 9 | Response 10 | Score |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [9](questions/is/q09.md) | C | Very Hard | 0.03 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [10](questions/is/q10.md) | E | Medium | 0.31 | Yes | E | E | E | E | E | E | E | E | E | E | 10 |
| [11](questions/is/q11.md) | C | Medium | 0.24 | Yes | C | C | C | C | C | C | C | C | D | C | 9 |
| [12](questions/is/q12.md) | B | Hard | 0.21 | No | B | D | B | B | C | B | B | B | B | D | 7 |
| [13](questions/is/q13.md) | D | Medium | 0.28 | No | D | D | D | D | D | D | D | D | X | D | 9 |
| [14](questions/is/q14.md) | C | Medium | 0.38 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [15](questions/is/q15.md) | D | Easy | 0.37 | Yes | D | D | D | D | D | D | D | D | D | D | 10 |
| [16](questions/is/q16.md) | A | Hard | 0.22 | Yes | A | A | A | A | A | A | A | A | A | A | 10 |
| [17](questions/is/q17.md) | C | Hard | 0.04 | No | C | C | C | C | C | C | C | C | C | C | 10 |
| [18](questions/is/q18.md) | B | Hard | 0.02 | Yes | B | B | B | B | B | B | B | B | B | B | 10 |
| [19](questions/is/q19.md) | A | Medium | 0.32 | Yes | B | A | B | B | B | A | B | B | A | B | 3 |
| [20](questions/is/q20.md) | B | Hard | 0.36 | Yes | X | A | A | E | A | X | A | A | X | A | 0 |
| [21](questions/is/q21.md) | C | Hard | 0.01 | No | D | D | D | D | D | D | D | D | D | E | 0 |
| [22](questions/is/q22.md) | E | Hard | 0.31 | Yes | E | E | E | D | E | E | E | E | E | E | 9 |
| [23](questions/is/q23.md) | B | Easy | 0.40 | Yes | B | B | B | B | B | B | B | B | B | B | 10 |
| [24](questions/is/q24.md) | B | Hard | 0.27 | Yes | B | B | X | B | B | B | B | B | B | B | 9 |
| [25](questions/is/q25.md) | E | Medium | 0.40 | No | E | E | E | E | E | E | C | E | C | E | 8 |
| [26](questions/is/q26.md) | E | Medium | 0.42 | Yes | E | E | E | E | E | E | E | E | E | E | 10 |
| [27](questions/is/q27.md) | D | Hard | 0.03 | Yes | B | B | B | B | B | B | B | B | B | B | 0 |
| [28](questions/is/q28.md) | A | Medium | 0.33 | Yes | C | E | C | A | C | C | C | C | E | E | 1 |
| [29](questions/is/q29.md) | D | Medium | 0.35 | Yes | D | D | D | D | D | D | D | D | X | D | 9 |
| [30](questions/is/q30.md) | E | Hard | 0.23 | Yes | E | E | E | E | E | E | E | E | E | E | 10 |
| [31](questions/is/q31.md) | A | Hard | 0.20 | Yes | A | A | A | A | A | A | A | A | A | A | 10 |
| [32](questions/is/q32.md) | C | Hard | 0.30 | No | C | E | C | E | E | C | E | E | E | C | 4 |
| [34](questions/is/q34.md) | D | Hard | 0.35 | Yes | D | D | D | D | D | D | D | D | D | D | 10 |
| [35](questions/is/q35.md) | D | Hard | 0.30 | Yes | D | D | D | D | D | D | C | D | X | D | 8 |
| **Correct Answers** |  |  |  |  | 21 | 20 | 20 | 20 | 19 | 22 | 18 | 20 | 16 | 20 | **19,6** |
| **Accuracy %** |  |  |  |  | 80,8% | 76,9% | 76,9% | 76,9% | 73,1% | 84,6% | 69,2% | 76,9% | 61,5% | 76,9% | **75,4%** |


## Performance of **ChatGPT o4-mini** over 10 rounds on the 26 image-based questions from the ENADE Information Systems exam

| Question | Answer Key | Difficulty Level | Point-Biserial Correlation | Scored | Response 1 | Response 2 | Response 3 | Response 4 | Response 5 | Response 6 | Response 7 | Response 8 | Response 9 | Response 10 | Score |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| [9](questions/is/q09.md) | C | Very Hard | 0.03 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [10](questions/is/q10.md) | E | Medium | 0.31 | Yes | E | X | E | E | A | E | A | A | E | E | 6 |
| [11](questions/is/q11.md) | C | Medium | 0.24 | Yes | D | D | D | D | D | D | D | D | D | D | 0 |
| [12](questions/is/q12.md) | B | Hard | 0.21 | No | C | E | C | C | E | C | C | C | C | E | 0 |
| [13](questions/is/q13.md) | D | Medium | 0.28 | No | X | D | X | X | D | X | X | X | X | X | 2 |
| [14](questions/is/q14.md) | C | Medium | 0.38 | Yes | C | C | C | C | C | C | C | C | C | C | 10 |
| [15](questions/is/q15.md) | D | Easy | 0.37 | Yes | D | D | D | D | D | D | D | D | D | D | 10 |
| [16](questions/is/q16.md) | A | Hard | 0.22 | Yes | A | A | A | A | A | A | A | A | A | A | 10 |
| [17](questions/is/q17.md) | C | Hard | 0.04 | No | C | C | C | C | C | C | C | C | C | C | 10 |
| [18](questions/is/q18.md) | B | Hard | 0.02 | Yes | B | B | B | B | B | B | B | B | B | B | 10 |
| [19](questions/is/q19.md) | A | Medium | 0.32 | Yes | A | B | B | B | B | B | B | B | B | B | 1 |
| [20](questions/is/q20.md) | B | Hard | 0.36 | Yes | X | X | X | X | X | X | X | X | X | A | 0 |
| [21](questions/is/q21.md) | C | Hard | 0.01 | No | D | D | D | C | D | C | X | X | C | D | 3 |
| [22](questions/is/q22.md) | E | Hard | 0.31 | Yes | E | E | E | E | E | X | E | C | E | E | 8 |
| [23](questions/is/q23.md) | B | Easy | 0.40 | Yes | B | B | B | B | B | B | B | B | B | B | 10 |
| [24](questions/is/q24.md) | B | Hard | 0.27 | Yes | B | B | B | B | B | B | B | B | B | B | 10 |
| [25](questions/is/q25.md) | E | Medium | 0.40 | No | C | E | C | C | C | C | C | C | C | E | 2 |
| [26](questions/is/q26.md) | E | Medium | 0.42 | Yes | E | E | E | E | E | E | E | E | E | E | 10 |
| [27](questions/is/q27.md) | D | Hard | 0.03 | Yes | B | B | B | B | B | B | B | B | B | B | 0 |
| [28](questions/is/q28.md) | A | Medium | 0.33 | Yes | X | X | X | X | E | X | X | X | X | X | 0 |
| [29](questions/is/q29.md) | D | Medium | 0.35 | Yes | B | B | B | C | X | D | X | X | X | X | 1 |
| [30](questions/is/q30.md) | E | Hard | 0.23 | Yes | E | E | E | E | E | E | E | E | E | E | 10 |
| [31](questions/is/q31.md) | A | Hard | 0.20 | Yes | A | A | A | A | A | A | A | A | A | A | 10 |
| [32](questions/is/q32.md) | C | Hard | 0.30 | No | C | C | E | C | E | E | C | E | E | E | 4 |
| [34](questions/is/q34.md) | D | Hard | 0.35 | Yes | D | D | D | X | D | X | D | D | D | D | 8 |
| [35](questions/is/q35.md) | D | Hard | 0.30 | Yes | C | X | X | D | X | D | X | X | X | D | 3 |
| **Correct Answers** |  |  |  |  | 16 | 16 | 14 | 16 | 14 | 15 | 14 | 12 | 15 | 16 | **14,8** |
| **Accuracy %** |  |  |  |  | 61,5% | 61,5% | 53,8% | 61,5% | 53,8% | 57,7% | 53,8% | 46,2% | 57,7% | 61,5% | **56,9%** |

