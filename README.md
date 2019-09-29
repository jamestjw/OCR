## Optical Character Recognition

Currently, I have tried two approaches (that are similar in a number of ways), they both involve a CNN feature extractor - > Bi-LSTM -> GRU decoder with attention. 
1. Use a resnet18 backbone
2. Use a simpler CNN backbone inspired by https://arxiv.org/pdf/1903.07377.pdf
