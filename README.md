# Privacy-Preserving-Representation-for-Audio-Visual-Speech-Understanding
Multimodal datasets can contain personally identifiable information. We propose a general framework for privacy-aware representation of audio-visual (AV) data.

## Data
VidTIMIT (Video Dynamic TIMIT)
DeepfakeTIMIT
MSP-Improv (Multimodal Sensitive Periods Improvisation Corpus)

## Method
1. Feature Extraction Using AV-HuBERT
2. Privacy Transformer
3. Differential privacy filter
4. Speaker Recognition
5. Emotion Recognition

![image](https://github.com/user-attachments/assets/367e0dd4-2aad-418c-8608-66f56ab3d154)

## Results
### Speaker Recognition
| Method            | Accuracy (VidTIMIT                                  |
|-------------------|-----------------------------------------------------|
| AV-HuBERT          | 88.24 (batches of 2 )                      |
| Differential Privacy filter        | 50 (batches of 2 )                    |
| Transformer Privacy filter        | 	58  (batches of 2 )                     |

### Emotion Recognition
 | Method            | F1 Score                               | Accuracy |
|-------------------|-----------------------------------------------------|------|
| AV-HuBERT          | 41                   | 41 |
| Differential Privacy filter        | 22                   | 22 |
| Transformer Privacy filter        | 	36                    | 36 |
