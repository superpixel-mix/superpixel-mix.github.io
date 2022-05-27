## <center> Robust Semantic Segmentation with Superpixel-Mix</center>
<div align=center><font size='6' color=green> Robust Semantic Segmentation with Superpixel-Mix </font></div>

<center>
<font color=blue>Gianni Franchi<sup>1</sup>, Nacim Belkhir<sup>2</sup>, Mai Lan Ha<sup>3</sup>, Yufei Hu<sup>1</sup>, Andrei Bursuc<sup>4</sup>, Volker Blanz<sup>3</sup>, Angela Yao<sup>5</sup></font>
</center>
<center>
<sup>1</sup> U2IS ENSTA Paris Institut Polytechnique de Paris
</center>
<center>
<sup>2</sup> Safrantech, Safran Group
</center>
<center>
<sup>3</sup> Department of Computer Science University of Siegen
</center>
<center>
<sup>4</sup> valeo.ai
</center>
<center>
<sup>5</sup> School of Computing National University of Singapore
</center>
<div align=center><font size='6' color=red> BMVC2021 </font></div>

&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; [<font size=6>Paper</font>](https://www.bmvc2021-virtualconference.com/assets/papers/0509.pdf) &nbsp; &nbsp; &nbsp; &nbsp; [<font size=6>Code</font>]( https://github.com/giannifranchi/deeplabv3-superpixelmix)&nbsp; &nbsp; &nbsp; &nbsp;[<font size=6>Dataset</font>](https://drive.google.com/file/d/1pKdlglcvsGseLzS1MX8SdjzQO2o1KZm6/view?usp=sharing)



### Abstract
Along with predictive performance and runtime speed, robustness is a key require- ment for real-world semantic segmentation. Robustness encompasses accuracy, pre- dictive uncertainty, stability under data perturbation and distribution shift, and reduced bias. To improve robustness, we introduce Superpixel-mix, a new superpixel-based data augmentation method with teacher-student consistency training. Unlike other mixing- based augmentation techniques, mixing superpixels between images is aware of object boundaries, while yielding consistent gains in segmentation accuracy. Our proposed technique achieves state-of-the-art results in semi-supervised semantic segmentation on the Cityscapes dataset. Moreover, Superpixel-mix improves the robustness of semantic segmentation by reducing network uncertainty and bias, as confirmed by competitive results under strong distributions shift (adverse weather, image corruptions) and when facing out-of-distribution data.

### Superpixel-mix
![](./images/backbone.png)

### OOD detection
![](./images/ood.png)
![](./images/ood_performance.png)

### Semi-supervised learning
![](./images/semi.png)

### Uncertainty experiments
![](./images/uncertainty_1.png)
![](./images/uncertainty_2.png)
