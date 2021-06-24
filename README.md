# Visual-Reasoning-eXplanation
An implementation of “A Peek Into the Reasoning of Neural Networks: Interpreting with Structural Visual Concepts” (CVPR 2021)

Please download data from *link*, and unzip "source.zip" to ./source, "result.zip" to ./result. Source data are the images for discovering concepts, and result data are the files that contain concept information. I only implement some basic functions to inference designated images. You can select the image you want to do reasoning from ./result/img2vec/\*detect_img. For example, the is a file named "./result/img2vec/fire_engine_detect_img/n03345487_10367_img.png", so the "img_class" is "fire_engine" and "img_idx" is 10367.

You can simply run '''python Xception_WhyNot.py --img_class fire_engine --img_idx 10367''' to do reasoning.
