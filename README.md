# War Image Search

A natural text to image search using CLIP

[Demo on Kaggle](https://www.kaggle.com/code/pradeepjina/ukraine-war-images-search)

## Overview

This is an example that implements search for War Images (currently for Ukraine War only)

Features

* You'll be able to use **natural text** queries for image search
* The search will work even **when the image has no such info in the captions** or metadata
* The search will work even when you make a ~typpo~ typo

**Example natural text queries and results**


[![WcUknj.md.png](https://iili.io/WcUknj.md.png)](https://freeimage.host/i/WcUknj)


Possibilities are endless. As long as the data has the images matching your natural text, you get sruprisingly accurate results.

Checkout [the code](./ukraine-war-images-search.ipynb)

## Get started

Just run the code in [Kaggle notebook](https://www.kaggle.com/code/pradeepjina/ukraine-war-images-search/edit/run/94888326) or copy [the notebook](./ukraine-war-images-search.ipynb) to your favorite ML notebook editor e.g. Colab, Jupyter, etc.

## Roadmap

- [x] Backend to search images using natural text
- [ ] REST APIs for search to be used in frontend
- [ ] Frontend Web UI to search easily
- [ ] Backend APIs to upload image to the dataset
- [ ] Frontend Web UI to upload your images to the dataset(with source citation)
- [ ] Frontend Web UI to change the image dataset
- [ ] Production deployment guide
- [ ] Show image match score
- [ ] Command palette for quick actions

## Contributions

You can contribute to this project in two ways

1. Contributing to the [code](./ukraine-war-images-search.ipynb) to refine this example and add features
2. Contributing to [the dataset](https://www.kaggle.com/datasets/mathurinache/ukraine-war-images) for war images. No labeling required.

## License
MIT
