# Visual-Reasoning-eXplanation
An implementation of “A Peek Into the Reasoning of Neural Networks: Interpreting with Structural Visual Concepts” [Visual-Reasoning-eXplanation](CVPR 2021)(https://github.com/gyhandy/Visual-Reasoning-eXplanation)

Please download data from [here](https://drive.google.com/drive/folders/1jSpqvyWQCkGPP_vIsnrVGgYX2lhtPgfF?usp=sharing), and unzip "source.zip" to `./source`, "result.zip" to `./result`. Source data are the images for discovering concepts, and result data are the files that contain concept information. I only implement some basic functions to inference designated images. You can select the image you want to do reasoning from ./result/img2vec/\*detect_img. For example, there is a file named `./result/img2vec/fire_engine_detect_img/n03345487_10367_img.png`, so the "img_class" is "fire_engine" and "img_idx" is 10367.

You can simply run ```python Xception_WhyNot.py --img_class fire_engine --img_idx 10367``` to do reasoning.



## Citation
If you use this code for your research, please cite the original paper.
```
@inproceedings{ge2021peek,
  title={A Peek Into the Reasoning of Neural Networks: Interpreting with Structural Visual Concepts},
  author={Ge, Yunhao and Xiao, Yao and Xu, Zhi and Zheng, Meng and Karanam, Srikrishna and Chen, Terrence and Itti, Laurent and Wu, Ziyan},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={2195--2204},
  year={2021}
}
```
