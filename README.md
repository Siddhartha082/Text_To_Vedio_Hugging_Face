# Text_To_Vedio_Huging_Face
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

# OUTPUT
![image](https://github.com/Siddhartha082/Text_To_Vedio_Huging_Face/assets/110781138/0725d9e4-f50a-4dce-b55f-d41a112cdb96)
