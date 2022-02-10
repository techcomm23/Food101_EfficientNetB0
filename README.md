
# Food-101 paper through EfficientNet lens

![Food-101](food-101.png)

## Intro

EfficientNet (Hongkun Yu et al) is a model scaling method that uses a highly effective compound coefficient to scale up CNNs in a more structured manner. Rather than arbitrarily scale network dimensions, this method uniformly scales each dimension with a fixed set of scaling coefficients.

![EfficientNet1](EfficientNet1.png)

Food-101 is a dataset that consists of 101 food categories with 750 training and 250 test images per category. 

In "Food-101 – Mining Discriminative Components with Random Forests" [paper](https://data.vision.ee.ethz.ch/cvl/datasets_extra/food-101/static/bossard_eccv14_food-101.pdf), the authors(Lukas Bossard et al) used RF architecture to train a model to achieve an average accuracy of 50.76%. We will use this paper as a baseline to evaluate the performance of EfficientNet-B0 Architecture

---
## Goals

### Transfer Learning
In the 101-food paper, authors achieved an average accuracy of 50.76% using RF model. We need to explore the impact of utilizing EfficientNet transfer learning and fine-tuning on the performance of a model and compare it to the performance of the model used in Food-101 paper.

---
## License

This project is licensed under the GNU GPLv3 License





