Data Science Portafolio
======================
<a href="https://github.com/jespinozallanos/portafolio2">
    <img src="https://github.com/jespinozallanos/portafolio2/blob/main/proy1.png" alt="logo" title="logo" align="right" height="160" />
</a>



<p align="center">
  • <a href="#overview">Overview</a> •
  <a href="#Cómo usar">Cómo usar</a> •
  <a href="#Descripción">Descripción</a> •
  <a href="#Créditos">Créditos</a> •
  <a href="#Licencias">Licencias</a>
</p>



Overview
======================

### Implementation of DCGAN as data augmentation of images of surface defects in steel to improve the performance of classifiers.

In the industry, the production of steel 
and specifically the detection and classification of 
defects in these becomes of vital importance since
their mere appearance can lead to significant 
economic losses. Nowadays, existing classification 
models have improved remarkably, however, they 
require a large amount of data or images to be 
trained, which remains a deficiency in the industry. 
In this study, an innovative solution is proposed to 
improve the performance of classifiers by 
implementing a convolutional deep adversarial 
generative network (DCGAN) as a data 
augmentation technique, which has the potential to 
overcome the limitations associated with the 
availability of data, by providing an expanded and 
diverse set of images to train the classifiers. The 
results show that the generation of artificial images 
of steel defects is feasible, with an 
indistinguishable visual difference from a real 
image.

<p align="center"><img width=40% src="https://github.com/jespinozallanos/portafolio2/blob/main/res5.png"></p>

| [Jupyter Notebook](https://github.com/jespinozallanos/portafolio2/blob/main/DCGAN_SCRATCHES.ipynb)  |



*  DCGAN as data augmentation of images of surface defects in steel
* The best result I got was with 6,000 epochs.


Cómo usar
======================

* Requeriments
  * Google Colab
  * Python V3.8.6
  * Keras
  * Dataset Northeastern University Surface Defect Database.
  * RUN

* Go to the notebook folder and throught Colab access to the notebook (.ipynb).
  
Descripción
======================
1. Initial data treatment and exploration.
2. First DCGAN Model.
3. DCGAN final model.
4. Evaluation Metrics


Créditos
======================
JULIO ESPINOZA LLANOS

Licencias
======================
MIT
