# Image-to-Prompts
The goal of the models is to reverse the typical direction of a generative text-to-image model: instead of generating an image from a text prompt creating a model which can predict the text prompt given a generated image.

Model-1 makes use of a simple encoder-decoder architecture.Feature embeddings fromthe image are obtained by using resnet-50 while a gru based model ,combined withself attention,has beenused for the decoder part of the model.

Model 2 makes use of a combination of VIT and Gpt2 inorder to generate the final prompts.

Further I believe results can be improved by experimenting withother pretrained models like OFA and clip-blip architectures. Morever  data augmentation and feature extraction can help in improving the results.
