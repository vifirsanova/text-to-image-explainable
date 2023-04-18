**Description**

The images in the folder are generated with [VQGAN+CLIP](https://arxiv.org/abs/2204.08583) through [Colab Turial by Katherine Crowson](https://colab.research.google.com/github/justinjohn0306/VQGAN-CLIP/blob/main/VQGAN%2BCLIP(Updated).ipynb).

**Features**

*Image size*: 400 x 400 px

*Prompts* are given in the names of images *.png and are the following:

- word in Chinese 
- word in Japanese 
- word in Hebrew 
- word in Yiddish 
- word in Persian 
- word in Arabic 
- text in English 
- caption in Russian 
- text in Greek 
- word in Hindi 
- word in Thai 
- word in Korean

*Hyperparameters*: 

- manual random seed values were chosen randomly
- number of inference steps vary from 50 to 400, were chosen according to [guidelines](https://www.cs.columbia.edu/~chilton/web/my_publications/LiuPromptsAIGenArt_CHI2022.pdf) as well as by trial and error

The values were randomely mixed and used for image generation. The information about parameters is given in the names of images *.png as follows:

`{prompt}_steps_{number of inference steps}_gen_{seed}.png`
