# Text_To_Vedio_Huging_Face

![image](https://github.com/Siddhartha082/Text_To_Vedio_Huging_Face/assets/110781138/a1a02595-098a-4e6b-b5ef-078171411c95)

![image](https://github.com/Siddhartha082/Text_To_Vedio_Huging_Face/assets/110781138/99ede279-bc6e-4f21-9075-b6038f98afb4)


# https://huggingface.co/damo-vilab/text-to-video-ms-1.7b
![image](https://github.com/Siddhartha082/Text_To_Vedio_Huging_Face/assets/110781138/a60b36b2-8374-489a-b1b6-33176d4f99ab)

# Model description
The text-to-video generation diffusion model consists of three sub-networks: text feature extraction model, text feature-to-video latent space diffusion model, and video latent space to video visual space model. The overall model parameters are about 1.7 billion. Currently, it only supports English input. The diffusion model adopts a UNet3D structure, and implements video generation through the iterative denoising process from the pure Gaussian noise video.

This model is meant for research purposes. Please look at the model limitations and biases and misuse, malicious use and excessive use sections.

# Model Details
Developed by: ModelScope
Model type: Diffusion-based text-to-video generation model
Language(s): English
License: CC-BY-NC-ND
Resources for more information: ModelScope GitHub Repository, Summary.
Cite as:

# Use cases
This model has a wide range of applications and can reason and generate videos based on arbitrary English text descriptions.

# Usage
Let's first install the libraries required:

$ pip install diffusers transformers accelerate torch

![image](https://github.com/Siddhartha082/Text_To_Vedio_Huging_Face/assets/110781138/b1adfd4b-d966-49df-918f-8ba169eb2206)

![image](https://github.com/Siddhartha082/Text_To_Vedio_Huging_Face/assets/110781138/d9d1f1c4-3b3b-4c39-b2d1-2fd1dcd20f7d)

![image](https://github.com/Siddhartha082/Text_To_Vedio_Huging_Face/assets/110781138/7192b5af-e8d2-4ad6-a36f-8ac3313ad1bf)

![image](https://github.com/Siddhartha082/Text_To_Vedio_Huging_Face/assets/110781138/7da1e15e-0809-4024-9ae1-d024e7582dfb)

![image](https://github.com/Siddhartha082/Text_To_Vedio_Huging_Face/assets/110781138/f32394ef-19cb-4a48-9211-2a7a4d16e530)

# OUTPUT
![image](https://github.com/Siddhartha082/Text_To_Vedio_Huging_Face/assets/110781138/0725d9e4-f50a-4dce-b55f-d41a112cdb96)
