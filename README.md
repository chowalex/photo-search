# Image Semantic Search with CLIP and Pinecone

## Overview
This project demonstrates how to perform semantic searches of images using text descriptions. It leverages the CLIP (Contrastive Language–Image Pre-training) model from OpenAI and Pinecone for efficient similarity search. By embedding both images and text into a shared vector space, CLIP allows for powerful cross-modal search capabilities.

The Jupyter notebook is a quick demo of the procedure. I hope to incorporate this as part of a Django backend which can be integrated into a python version of the [Media Organizer](https://github.com/chowalex/media-organizer).

## CLIP
CLIP (Contrastive Language–Image Pre-training) is a neural network model developed by OpenAI that learns to associate images and text by training on a large dataset of image-text pairs. The key idea behind CLIP is to train a model that can understand and generate both visual and textual information, making it highly versatile for various applications such as image classification, captioning, and, as demonstrated here, semantic search.

## Procedure
* Generate embeddings for images and text using CLIP.
* Normalize embeddings for consistent similarity comparisons.
* Store and search embeddings using Pinecone's vector database.