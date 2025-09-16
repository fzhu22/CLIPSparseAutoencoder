# CLIPSparseAutoencoder

## Abstract

Vision models learn complex semantic relationships within their training data, but it is not well-understood what concepts those models contain, nor how architectural differences influence the concepts a model can learn. In this work, we train Sparse Autoencoders (SAEs) on a ResNet and a Vision Transformer which have been pretrained similarly and experiment with training methods, in service of a comparative analysis of human-interpretable concepts contained in similar visual networks with different architectures (CLIP-ResNet50 and CLIP-ViT-L/14). We experiment extensively and use quantitative and qualitative metrics to compare the two autoencoders; ultimately, despite poor performance in our ResNet SAE when we train it similarly to the ViT, we nonetheless find some nontrivial instances of feature alignment, indicating positive potential for future research in the area.
