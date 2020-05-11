To test the model, please 

1. download all the files here.
2. cd #your_folder
3. put your imgs in 'test' folder
4. create a output directory
5. enter: python test.py --image_dir '' --output_image_dir #your_output_dir --pre_trained_model generator.pkl
replace #your_output_dir with the folder name in step 4.

Note: The result may not be desirable for some images. You better try with a close-up face images, as clear as possible.
Also, please feel free to try original author's model. 
CartoonGAN: https://github.com/Yijunmaverick/CartoonGAN-Test-Pytorch-Torch
AnimeGAN: https://github.com/TachibanaYoshino/AnimeGAN


[1] Chen, Yang, Yu-Kun Lai, and Yong-Jin Liu. "CartoonGAN: Generative Adversarial Networks for Photo Cartoonization." Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2018.
