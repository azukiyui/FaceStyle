# FaceStyle: Example-based Stylization of Face Portraits

> Code to generate G_seg, G_pos and G_app images from "Example-Based Synthesis of Stylized Facial Animations" by JAKUB FIŠER et al.

The [ebsynth](https://github.com/jamriska/ebsynth) repository provides code to perform [facestyle](https://github.com/jamriska/ebsynth#facestyle-example-based-stylization-of-face-portraits) which transfers the style of a portrait painting onto another person's photograph.

Besides the source and target images, the algorithm requires a soft segmentation guide `G_seg`, a positional guide `G_pos` and an appearance guide `G_app`. The code to generate these images from both the source and target images was not provided.

In this repository you can find the code and models to generate the aforementioned images.

## Theory

<img src="https://i.imgur.com/0UcjEmz.png"/>
*Fig. 1: Source [1]*

<img src="https://i.imgur.com/hhvbIJl.png"/>
*Fig. 2: Source [1]*

## Tasks:

### G_seg:

[1] Hair segmentation:

[2] Face segmentation:

[3] Face landmarks estimation:


## Citation

```
@misc{Jamriska2018,
  author = {Jamriska, Ondrej},
  title = {Ebsynth: Fast Example-based Image Synthesis and Style Transfer},
  year = {2018},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/jamriska/ebsynth}},
}
```
