# postcards-from-my-jungle
Your strategies for training the models
how you generated your fictional beasts' images, sounds, and language
how the quality of the images and sounds could be improved.

# Strategies used to Train the Image model and Generating Images

To train my image, I started by searching databases on Hugging Face. I first selected a most downloaded database which was a large one; mertcobanov/animals. It took a long time to train but at the end worked after multiple tries. When attempting to generate the 50 images, CUDA ran out of memory and after multiple attempts and errors, I ran out of CPU memory. Therefore, I created another account and switched to a smaller dataset; "Rapidata/Other-Animals-10" which was allow a faster trainning by using the first 103 images. However when trying to generate the 50 images I had the same memory issue  After asking genAI about why and experiment with it for lot of hours, I ended being able to generate the 50 images that are grainy with muted of colors.

# Generation sounds

To generate sounds, I chose a pretrained diffusion model, stabilityai/stable-audio-open-1.0. To use it, I had to create an Hugging Face account and generate an authentication token to log in from Google Colab. I created 4 different prompts to create unique and distinct sounds for the jungle postcard images. However, I had to adjust one of the prompt because it sounded too much like a melody instead of ressembling an animal sound.

# Generating Fictional Languages

To generate the fictional language of the animals, I used a pre-trained transformer model, CHATGPT-4 model. I asked to generated 16 text mimicked how an imagined creature might communicate based on the prompt of the generated sounds.

# How the quality of the images and sounds could be improved
To improve the quality of the images, using a larger dataset and higher quality images could improve results by providing the model with more shapes, features etc. Also, increasing the number of epochs to allow the model to learn better about the textures and shapes of the images. Ugrading to a better GPU could also help.
</b>To improve the quality of the sounds, applying audio enhancement techniques could make the sound better and using a differemt sound generation model could make a big different too.
