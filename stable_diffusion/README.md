**Description**

The images in the folder are generated with [Stable Diffusion v. 2.1 base](https://huggingface.co/stabilityai/stable-diffusion-2-1-base) through [Hugging Face Diffusers](https://huggingface.co/docs/diffusers/index). The code for image generation is provided in [image_generation.ipynb](https://github.com/Anonimous-Submission/anonymous_submission/blob/main/stable_diffusion/image_generation.ipynb). 

**Features**

*Image size*: 512 x 512 px

*Prompts* are given in the names of images *.png and are the following:

- text in Chinese 
- text in Japanese 
- text in Hebrew 
- text in Yiddish 
- text in Persian 
- text in Arabic 
- text in English 
- text in Russian 
- text in Greek 
- text in Hindi 
- text in Thai 
- text in Korean

*Hyperparameters*: 

- manual random seed values: 8, 56, 128, 512 (were chosen randomely)
- number of inference steps: 15, 25, 30, 50 (were chosen according to [guidelines](https://huggingface.co/blog/stable_diffusion#:~:text=Stable%20Diffusion%20works%20quite%20well,you%20can%20use%20larger%20numbers.) as well as by trial and error

The values were randomely mixed and used for image generation. The information about parameters is given in the names of images *.png as follows:

`{prompt}_steps_{number of inference steps}_gen_{seed}.png`
