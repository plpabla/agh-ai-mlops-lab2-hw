# Model selection

`clip-ViT-B-32` [HuggingFace](https://huggingface.co/sentence-transformers/clip-ViT-B-32) - text-image transformer to place images and text on the same vector space which allows to text-text, text-image, image-text and image-image search

- Vector space size: 512 [ref](https://unfoldai.com/images-to-vectors-using-vector-forge-and-clip/)
- ViT - Vision Transformer
- B - size (Base) - ViT-B has 12 transformer layers (L has 24)
- 32 - patch size - 32x32 (for how big chunks a picture is cut)

# Image preprocessing

File: `filter_downloaded_images.ipynb`
