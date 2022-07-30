## Liver tumor CT scan segmentation (STILL IN PROGRESS)
In this project I've built a UNET model for liver tumor segmentation via PyTorch. <br>
The dataset: [Liver Tumor Segmentation](https://www.kaggle.com/datasets/andrewmvd/liver-tumor-segmentation). <br>
For now it's just a jupyter notebook with: 
- exploration of the initial dataset
- creation of new dataset of 2D images and their target masks
- defining Datasets and Dataloaders for our model
- defining UNET model
- experiments with fresh new UNET model
- experiments with small sanity-check dataset on fresh new UNET model

After understanding that this problem will take too much time to train a model from scratch, I've decided my next steps will be:
- refactor the code
- use pretrained ResNet layers UNET's encoder
- train it on the whole dataset of scans
- maybe more experiments with loss function and over/undersampling duo to big class imbalance and importance of class 2
