
# This is a record of current experiment result on some realistic noisy label datasets

## 1. Clothing1M dataset
from: [CVPR-15: Learning from Massive Noisy Labeled Data for Image Classification](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Xiao_Learning_From_Massive_2015_CVPR_paper.pdf)
 + 14 classes: T-shirt, Shirt, Knitwear, Chiffon, Sweater, Hoodie, Windbreaker, Jacket, Down Coat, Suit, Shawl, Dress, Vest, and Underwear
 + noisy labeled training dataset ($D_\eta$): $10^6$
 + clean train data($D_c$): 47,570
 + clean validation set: 14,313
 + clean test set: 10,526
 
 ![Noise confusion matrix](https://github.com/guixianjin/Some-research-on-noisy-labels/blob/master/PicturesForClothing1M/Clothing1Mnoise_transition_matrix.png) 
 
 
#### 1. [CVPR-15: Learning from Massive Noisy Labeled Data for Image Classification]()
![some result](https://github.com/guixianjin/Some-research-on-noisy-labels/blob/master/PicturesForClothing1M/Clothing1MResult.png)


#### 2. [CVPR-17: Making Deep Neural Networks Robust to Label Noise: A Loss Correction Approach](https://arxiv.org/pdf/1609.03683.pdf)
![some resutl](https://github.com/guixianjin/Some-research-on-noisy-labels/blob/master/PicturesForClothing1M/cvpr17_result.PNG)

#### 3. [CVPR-18: Joint Optimization Framework for Learning With Noisy Labels](https://arxiv.org/pdf/1803.11364v1.pdf)
![some result](https://github.com/guixianjin/Some-research-on-noisy-labels/blob/master/PicturesForClothing1M/cvpr18_result.PNG)

#### 4. [CVPR-18: CleanNet: Transfer Learning for Scalable Image Classifier Training With Label Noise](https://arxiv.org/pdf/1711.07131.pdf)
![some result](https://github.com/guixianjin/Some-research-on-noisy-labels/blob/master/PicturesForClothing1M/clean_net.PNG)

#### 5. [AAAI-19: Safeguarded Dynamic Label Regression for Noisy Supervision(journal verison)](https://arxiv.org/abs/1903.02152?context=cs.CV)
![some result](https://github.com/guixianjin/Some-research-on-noisy-labels/blob/master/PicturesForClothing1M/LCNN.PNG)

#### 6. [CVPR-19：Probabilistic End-to-End Noise Correction for Learning with Noisy Labels](https://arxiv.org/pdf/1903.07788.pdf)
![some result](https://github.com/guixianjin/Some-research-on-noisy-labels/blob/master/PicturesForClothing1M/pencil2.PNG)

#### 7. [CVPR-19: Learning to Learn from Noisy Labeled Data](http://openaccess.thecvf.com/content_CVPR_2019/papers/Li_Learning_to_Learn_From_Noisy_Labeled_Data_CVPR_2019_paper.pdf)
![some result](https://github.com/guixianjin/Some-research-on-noisy-labels/blob/master/PicturesForClothing1M/Learning2Learn.PNG)

#### 8. [CVPR-19: MetaCleaner: Learning to Hallucinate Clean Representations for Noisy-Labeled Visual Recognition](http://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_MetaCleaner_Learning_to_Hallucinate_Clean_Representations_for_Noisy-Labeled_Visual_Recognition_CVPR_2019_paper.pdf)
![some result](https://github.com/guixianjin/Some-research-on-noisy-labels/blob/master/PicturesForClothing1M/MetaCleaner.PNG)

#### 7. [ICML-19: Unsupervised Label Noise Modeling and Loss Correction](https://arxiv.org/pdf/1904.11238v2.pdf)
about 71%
#### 8. [NIPS-19: L_DMI: A Novel Information-theoretic Loss Function for Training Deep Nets Robust to Label Noise](https://arxiv.org/pdf/1909.03388.pdf)
![some result](https://github.com/guixianjin/Some-research-on-noisy-labels/blob/master/PicturesForClothing1M/DMI.PNG)

#### 9. [Improving MAE’s Fitting Ability while Preserving Its Noise-robustness](https://arxiv.org/pdf/1903.12141.pdf)

![some result](https://github.com/guixianjin/Some-research-on-noisy-labels/blob/master/PicturesForClothing1M/IMAE.PNG)








## 2. [WebVison dataset](http://www.vision.ee.ethz.ch/webvision/index.html)
from: [Arxiv17: Webvision database: Visual learning and understanding from web data](https://arxiv.org/pdf/1708.02862.pdf)
+ 1,000 classes: concepts in ImageNet ILSVRC12
+ noise rate: 20-40%

#### 1. [CVPR-18: CleanNet: Transfer Learning for Scalable Image Classifier Training With Label Noise]()
#### 2. [ICML-18: MentorNet: Learning Data-Driven Curriculum for Very Deep Neural Networks on Corrupted Labels](http://proceedings.mlr.press/v80/jiang18c/jiang18c.pdf)
#### 3. [AAAI-19: Safeguarded Dynamic Label Regression for Noisy Supervision]()

#### 4. [ICML-19:	Understanding and Utilizing Deep Neural Networks Trained with Noisy Labels]()
only use the first 50 classes
 
## 3. Food101-N
from: [CVPR-18: CleanNet: Transfer Learning for Scalable Image Classifier Training With Label Noise]()
+ 101 food classes 
+ 310k image, 55k verification, 
+ noise rate: 20%

#### 1. [CVPR-18: CleanNet: Transfer Learning for Scalable Image Classifier Training With Label Noise]()
#### 2. [ICCV-19: Deep self-Learning from Noisy Labels]()

### [ANIMAL10N](https://dm.kaist.ac.kr/datasets/animal10n)
from: [ICML-19: SELFIE: Refurbishing Unclean Samples for Robust Deep Learning]()
#### 1. [ICML-19: SELFIE: Refurbishing Unclean Samples for Robust Deep Learning]()
#### 2. [ICLR-2020: Prestopping: How Does Early Stopping Help Generalization Against Label Noise?]()

