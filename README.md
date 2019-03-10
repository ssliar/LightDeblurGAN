# LightDeblurGAN
# lightly-DeblurGAN
 DeblurGAN is a image deblur model based on conditional generative adverisarial network.But lt's speend very slow,we improve the model in several aspect and make it suit video.

**Requirements:**
- python 3.6
- ubuntu 16.06
- pytorch>=0.4.0
- cuda 9.0

**Test on Image:**
```bash
    python test_image.py --input {input_image} --output {output_image}
``` 
**Test on video:**
```bash
    python test_video.py --input {video.mp4} 
```
**Results:**
![input](imgs/1_input.png)![output](imgs/1_output.png)![detect](imgs/1_detect.png)
![input](imgs/2_input.png)![output](imgs/2_output.png)![detect](imgs/2_detect.png)
![input](imgs/3_input.png)![output](imgs/3_output.png)![detect](imgs/3_detect.png)
![input](imgs/4_input.png)![output](imgs/4_output.png)![detect](imgs/4_detect.png)
![input](imgs/5_input.png)![output](imgs/5_output.png)![detect](imgs/5_detect.png)
![input](imgs/6_input.png)![output](imgs/6_output.png)![detect](imgs/6_detect.png)

**References:**
- [DeblurGAN: Blind Motion Deblurring Using Conditional Adversarial Networks](https://arxiv.org/abs/1712.04440).
  Orest Kupyn, Volodymyr Budzan, Mykola Mykhailych, Dmytro Mishkin, Jiri Matas.
- [Generative Adversarial Networks](https://arxiv.org/abs/1406.2661).
  Ian J. Goodfellow, Jean Pouget-Abadie, Mehdi Mirza, Bing Xu, David Warde-Farley, 
  Sherjil Ozair, Aaron Courville, Yoshua Bengio.
- [YOLOv3:An Incremental Improvement](https://pjreddie.com/media/files/papers/YOLOv3.pdf).
  Joseph Redmon, Ali Farhadi.
**References:**
- [DeblurGAN: Blind Motion Deblurring Using Conditional Adversarial Networks](https://arxiv.org/abs/1712.04440).
  Orest Kupyn, Volodymyr Budzan, Mykola Mykhailych, Dmytro Mishkin, Jiri Matas.
- [Generative Adversarial Networks](https://arxiv.org/abs/1406.2661).
  Ian J. Goodfellow, Jean Pouget-Abadie, Mehdi Mirza, Bing Xu, David Warde-Farley, 
  Sherjil Ozair, Aaron Courville, Yoshua Bengio.
- [YOLOv3:An Incremental Improvement](https://pjreddie.com/media/files/papers/YOLOv3.pdf).
  Joseph Redmon, Ali Farhadi.
