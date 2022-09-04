# Understanding and Evaluating Commonsense Reasoning in Transformer-based Architectures [PAPER](https://ieeexplore.ieee.org/document/9579601)
Ascertaining the reason for and identifying the differences between sensical and nonsensical statements is a task that humans are naturally adept at. NLP methods, however, might struggle with such a task. This paper aims to evaluate various transformer-based architectures on common sense validation and explanation task, methods to improve their performance, as well as interpreting how fine-tuned language models perform such tasks, using the attention distribution of sentences at inference time. The tasks entail identifying the nonsensical statement from a given pair of similar statements (validation), followed by selecting the correct reason for its nonsensical nature(explanation). An accuracy of 83.90 and 88.42 is achieved on the respective tasks, using RoBERTa (large) language model fine-tuned on the datasets using the ULMFiT training approach.

## Inter-task transfer learning framework
![image](https://user-images.githubusercontent.com/55736716/135570971-b3331bb9-31f9-4ab4-8a49-af133d16c55d.png)

## Explaining results with attention distribution
![image](https://user-images.githubusercontent.com/55736716/135569918-f2c55141-40d6-4345-8601-ae3390f88aec.png)

## Results
![image](https://user-images.githubusercontent.com/55736716/135569977-cf53f857-1e9a-423a-a98e-1c90776eeaad.png)


