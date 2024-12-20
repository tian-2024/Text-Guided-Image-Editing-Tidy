# [Tidy Up Text-Guided Image Editing (TIE) Methods](https://github.com/tian-2024/Image-Edit-Diff)


Each notebook contains text-guided image editing methods using diffusion models.

The code has been modified from the original version with the following improvements:
1. Retains only the key logic for easier understanding.
2. Common functions have been extracted into `utils.py` to provide a unified interface.
3. Each method is organized in a separate subdirectory under `methods/`, named after the method, making the structure more intuitive and easier to navigate.


## Implemented Methods

- [x] 00-img.ipynb: Preprocess images to get 512x512 images.

### Synthetic Image Editing


- [x] 01-ptp.ipynb:  (2023 ICLR) [Prompt-to-Prompt Image Editing with Cross-Attention Control](https://prompt-to-prompt.github.io/)

### Real Image Editing

- [x] 02-nti.ipynb:  (2023 CVPR) [Null-text Inversion for Editing Real Images using Guided Diffusion Models](https://null-text-inversion.github.io/)
- [x] 03-dds.ipynb:  (2023 ICCV) [Delta Denoising Score](https://delta-denoising-score.github.io/)
- [x] 04-fpe.ipynb:  (2024 CVPR) [Towards Understanding Cross and Self-Attention in Stable Diffusion for Text-Guided Image Editing](https://github.com/alibaba/EasyNLP/tree/master/diffusion/FreePromptEditing)
- [x] 05-cds.ipynb:  (2024 CVPR) [Contrastive Denoising Score for Text-guided Latent Diffusion Image Editing](https://github.com/HyelinNAM/ContrastiveDenoisingScore)


## Planned Methods

1. [Paint by Example: Exemplar-based Image Editing with Diffusion Models](https://github.com/Fantasy-Studio/Paint-by-Example)
2. [Imagic: Text-Based Real Image Editing with Diffusion Models](https://github.com/justinpinkney/stable-diffusion/blob/main/notebooks/imagic.ipynb)