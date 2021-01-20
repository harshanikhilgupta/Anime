# AnimeFaceNotebooks
Notebooks and some data for playing with animeface stylegan2 and deepdanbooru. Versions for colab included (colab/ directory, or links below)

## Stylegan2 Anime Face model
This notebook has a few simple functions to use stylegan2s projection code to project input images (quality of results varies, but honestly surprisingly good), and sliders for interactively modifying a few tags. The directions in dlatent space were obtained by generating a lot of faces, tagging them with deepdanbooru, and then finding a regression line in disentangled latent space fit to the tag confidence values from deepdanbooru. This version uses Lasso regression to try and exploit sparsity in the disentangled latent space. There's some development notes in the notebook, and code that you can use to calculate your own directions. latents/dlatents + tags for 100000 generated images are included.

