
# Client-specific anomaly detection for face presentation attack detection

- This GitHub repository contains the codes and protocols used in the following paper:
https://www.sciencedirect.com/science/article/pii/S0031320320304994

- The proposed work follows a pure anomaly detection formulation in which only real samples are used to train One-class Classifiers (OCCs).

- The experiments are performed on 3 benchmarking anti-spoofing datasets including Replay-Attack, Replay-Mobile and Rose-Youtu.

- The following links forward you to the webpage of the used datasets:

   1. Replay-Attack via https://www.idiap.ch/dataset/replayattack
   2. Replay-Mobile via https://www.idiap.ch/dataset/replay-mobile
   3. Rose-Youtu via http://rose1.ntu.edu.sg/Datasets/faceLivenessDetection.asp

## Rose-Youtu Experiments 

- To perform the experiments on the Rose-Youtu dataset, a new protocol is proposed which splits the data into three subsets namely training, testing and validation. The proposed protocol is available in this repository:
   - https://github.com/12sf12/client-specific-anomaly-detection-PR/blob/master/Rose-Youtu_Protocol.txt
