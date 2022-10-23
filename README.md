# Orbiters.AI

A project for creating fine tuned, machine learning models of livestreamers, that can be used with stable diffusion to create AI generated Art.  


## Getting Started

1. This project uses stable diffusion to train and run the models.  You can get started by downloading, and following the instructions in the most popular SD repo here:  https://github.com/AUTOMATIC1111/stable-diffusion-webui

2. After downloading, running, and confirming that this works by generating a few test images, you will need to import the fine tunned embeddings that are in this repo. These models have file names that are in the format of "streamername-model-version.pt".  

    For every streamer that you want to include in your model, place the file associated with that streamer in the '\embeddings' directory.  

3. Create images!  In txt2image prompt tab, you can now reference and generate images from the model.  To do so, type a regular prompt, but include the name of the model, as the keyword you want to create images us.  ex: "A picture of streamername-model-version" would be a valid prompt.  

    Note, you cannot just use a streamers name, unless you rename the model filename to that name.  

## Creating new embeddings

A general guide for how to train a model, with your favorite streamer, can be found here:  https://github.com/AUTOMATIC1111/stable-diffusion-webui/wiki/Textual-Inversion

## Publish your model!

If you create a cool model, and want to share it with the community, please submit the embedding to this repo, in a pull request.  

Useful information to include, would be example generated images, your training data, and your parameters that you used to generate the model.  

More specific requirements will be added in the future.  The general goal of this project, though, is to be an open and collaborative project, where people can learn from each other, share training data sets, and training parameters.  
