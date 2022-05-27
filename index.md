## Robust Semantic Segmentation with Superpixel-Mix

<center>
<font color=blue>Gianni Franchi<sup>1</sup>, Nacim Belkhir<sup>2</sup>, Mai Lan Ha<sup>3</sup>, Yufei Hu<sup>1</sup>, Andrei Bursuc<sup>4</sup></font>, Volker Blanz<sup>3</sup></font>, Angela Yao<sup>5</sup></font>
</center>
<center>
<sup>1</sup>U2IS ENSTA Paris Institut Polytechnique de Paris
</center>
<center>
<sup>2</sup>Safrantech, Safran Group
</center>
<center>
<sup>3</sup> Department of Computer Science University of Siegen
</center>
<center>
<sup>4</sup>valeo.ai
</center>
<center>
<sup>5</sup>School of Computing National University of Singapore
</center>

&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; [<font size=6>Paper</font>](https://www.bmvc2021-virtualconference.com/assets/papers/0509.pdf) &nbsp; &nbsp; &nbsp; &nbsp; [<font size=6>Code</font>]( https://github.com/giannifranchi/deeplabv3-superpixelmix)



### Abstract
Along with predictive performance and runtime speed, robustness is a key require- ment for real-world semantic segmentation. Robustness encompasses accuracy, pre- dictive uncertainty, stability under data perturbation and distribution shift, and reduced bias. To improve robustness, we introduce Superpixel-mix, a new superpixel-based data augmentation method with teacher-student consistency training. Unlike other mixing- based augmentation techniques, mixing superpixels between images is aware of object boundaries, while yielding consistent gains in segmentation accuracy. Our proposed technique achieves state-of-the-art results in semi-supervised semantic segmentation on the Cityscapes dataset. Moreover, Superpixel-mix improves the robustness of semantic segmentation by reducing network uncertainty and bias, as confirmed by competitive results under strong distributions shift (adverse weather, image corruptions) and when facing out-of-distribution data.

### SUPERPIXEL-MIX
![](./images/NAO_deeplabv3plus.png)
![](./images/segmentation.png)

