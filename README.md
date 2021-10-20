# CatDCGAN 🐱‍💻

Cat DCGAN is a Deep Convolutional Generative Adversarial Network (DCGAN) that generates pictures of cats.


## Getting Started 📝
- Clone this repo
- <b>Download the pre-trained model</b>: https://drive.google.com/drive/folders/1zdZZ91fjOUiOsIdAQKZkUTATXzqy7hiz?usp=sharing
- Place the downloaded model in the `models/` directory
- Launch Jupyter Notebook `jupyter notebook --no-browser`
- Open the Cat DCGAN notebook
- <b>If you want to train from scratch</b>: change `from_checkpoint = False`
- <b>If you want to train from last model saved (you save 20 hours of training 🎉)</b>: keep `from_checkpoint = True`
- Follow the notes in the notebook and the tutorial


## The tutorial 📃
If you want to implement it by yourself and understand how it works, please read Thomas Simonini's [article on FreeCodeCamp](https://medium.freecodecamp.org/how-ai-can-learn-to-generate-pictures-of-cats-ba692cb6eae4).


## Links 🔗
🌐 : https://simoninithomas.github.io/CatDCGAN/


## Important note 🤔
<b> You can't run this on your computer </b> (except if you have GPUs or wait 10 years 😅). Thomas Simonini recommends to train this DCGAN for 20 hours with Microsoft Azure and their Deep Learning Virtual Machine (they offer 170$)
https://azuremarketplace.microsoft.com/en-us/marketplace/apps/microsoft-ads.dsvm-deep-learning

If you have some troubles to use follow the explainations of this excellent article here (without last the part fast.ai): https://medium.com/@manikantayadunanda/setting-up-deeplearning-machine-and-fast-ai-on-azure-a22eb6bd6429


## Contributing 🙌
If you want to contribute to the project, your help is very welcome. This is an open source project.

![](https://media.giphy.com/media/14cAg6Rn5jndIc/giphy.gif)


We currently working on improving our Generative adversarial network architecture. If you're motivated come join us and submit your pull requests.

## Acknowledgements 👏
This project was made possible thanks to:
- Udacity Face Generator Project 
- The start.sh and preprocess part (modified) made by Alexia Jolicoeur-Martineau https://ajolicoeur.wordpress.com/cats/
- Siraj's Raval PokeGan https://github.com/llSourcell/Pokemon_GAN
- The choice of learning rate by Alexia Jolicoeur-Martineau https://ajolicoeur.wordpress.com/cats/

## Examples

Visualisation of generated images changing as the model trains:

![Training DCGAN](assets/training2.gif)

A grid of generated images:

![CatDCGAN output](assets/output.png)
