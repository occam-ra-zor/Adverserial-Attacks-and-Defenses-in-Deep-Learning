# Adversarial Attacks and Defenses  in Deep Learning

Following is the list of papers that I have read for understanding about Adverserial Attacks and Defenses. Along with the PyTorch Code I implemented (not yet added. will be added).Main reason for this repo is that there very less open implementations of papers in Pytorch.

Adversarial Examples are like optical illusions for Deep Perception Models. But they exist for other kinds of data (audio,RL) and models(SVM,decision trees) too. But this repo will primarily concentrate on adversarial examples for Image Data in context of Deep Learning. Adversarial Examples can be used to comprise any Machine Learning System. Watch these video [Turtle as Rifle](https://www.youtube.com/watch?v=piYnd_wYlT8) where they 3D printed special type of Turtle to make it classify as Rifle.Problem is not with Models , But how we define our objective.Standard Machine Learning is good if it is good *average case* But Adversarial Machine Learning asks to good on *worst case*. Apart from security reasons, Adversarially Robust Deep Learning Modles were shown to be more semantically meaningful.So any machine learning system should work under notion of Adversarial Machine Learning and it will most likely replace Notion of Standard Machine Learning.


Standard Machine Learning          : 

![\displaystyle \LARGE \mathtt{R}_{Standard}(f_{\mathbf{\theta}})=  \argmin_{\mathbf{\theta}}\,\,\,\mathbb{E}_{(x,y)\sim\mathcal{D}} \Big\[ \ell(f_{\mathbf{\theta}}(x+\delta),y)\Big\]](https://render.githubusercontent.com/render/math?math=%5Cdisplaystyle%20%5CLARGE%20%5Cmathtt%7BR%7D_%7BStandard%7D(f_%7B%5Cmathbf%7B%5Ctheta%7D%7D)%3D%20%20%5Cargmin_%7B%5Cmathbf%7B%5Ctheta%7D%7D%5C%2C%5C%2C%5C%2C%5Cmathbb%7BE%7D_%7B(x%2Cy)%5Csim%5Cmathcal%7BD%7D%7D%20%5CBig%5B%20%5Cell(f_%7B%5Cmathbf%7B%5Ctheta%7D%7D(x%2B%5Cdelta)%2Cy)%5CBig%5D)



Adversarial Machine Learning       : 

![\displaystyle \LARGE \mathtt{R}_{Adversarial}(f_{\mathbf{\theta}})=  \argmin_{\mathbf{\theta}}\,\,\,\mathbb{E}_{(x,y)\sim\mathcal{D}} \Big\[   \max_{\delta \in \Delta} \,\, \ell(f_{\mathbf{\theta}}(x+\delta),y)\Big\]](https://render.githubusercontent.com/render/math?math=%5Cdisplaystyle%20%5CHuge%5Cmathtt%7BR%7D_%7BAdversarial%7D(f_%7B%5Cmathbf%7B%5Ctheta%7D%7D)%3D%20%20%5Cargmin_%7B%5Cmathbf%7B%5Ctheta%7D%7D%5C%2C%5C%2C%5C%2C%5Cmathbb%7BE%7D_%7B(x%2Cy)%5Csim%5Cmathcal%7BD%7D%7D%20%5CBig%5B%20%20%20%5Cmax_%7B%5Cdelta%20%5Cin%20%5CDelta%7D%20%5C%2C%5C%2C%20%5Cell(f_%7B%5Cmathbf%7B%5Ctheta%7D%7D(x%2B%5Cdelta)%2Cy)%5CBig%5D)




 
## Papers :


* [Intruiging Properties of Neural Networks](https://arxiv.org/pdf/1312.6199.pdf)
* [Explaining and Harnessing Adversarial Examples](https://arxiv.org/abs/1412.6572)
* [DeepFool: a simple and accurate method to fool deep neural networks](https://arxiv.org/abs/1511.04599.pdf)
* [Adversarial Examples In Physical World](https://arxiv.org/pdf/1607.02533.pdf)
* [Distillation as a Defense to Adversarial Perturbations against Deep Neural Networks](https://arxiv.org/pdf/1511.04508.pdf)
* [Towards Evaluting the Adversarial Robustness of Neural Networks](https://arxiv.org/pdf/1608.04644.pdf)
* [Towards Deep Learning Models Resistant to Adversarial Attacks](https://arxiv.org/pdf/1706.06083.pdf)
* [Adverserial Machine Learning At Scale](https://arxiv.org/pdf/1611.01236.pdf)
* [SoK: Towards the Science of Security and Privacy in Machine Learning](https://arxiv.org/pdf/1611.03814.pdf)
* [Ensemble Adverserial Training : Attack and Defense](https://arxiv.org/pdf/1705.07204.pdf)
* [Distributional Smoothing with Virtual Adversarial Training](https://arxiv.org/abs/1507.00677)
* [Universal Adversarial Perturbations](https://arxiv.org/abs/1610.08401.pdf)
* [On Detecting Adversarial Perturbations](https://arxiv.org/pdf/1702.04267.pdf)
* [Detecting Adversarial Examples from artifacts](https://arxiv.org/pdf/1703.00410.pdf)
* [Obfuscated Gradients Give a False Sense of Security : Circumventing Defenses to Adversarial Examples](https://arxiv.org/pdf/1802.00420.pdf)
 
 
## Surveys : 


## Similar Repos :
