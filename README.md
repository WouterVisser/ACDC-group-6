# ACDC challenge Group 6

## Requirements
These models were created using Python 3.8.10, and the following libraries:

    numpy == 1.23.1
    monai  == 1.3.0
    SimpleITK ==2.3.1
    torch == 1.13.1+cu116
    wandb == 0.17.0

## Instructions
To run our models:
- Clone this repository
- Create a models directory,  download the models and add them to the directory:
 - [2D model](https://drive.google.com/file/d/134QXSPpFoicF2h5JlOdHXQG2MCGCjMuf/view?usp=drive_link)
 - [3D model](https://drive.google.com/file/d/132-oZBrX7rmT-WdfwNVBfRY2wPAfXSj_/view?usp=drive_link)
- Download the [orginal dataset](https://humanheart-project.creatis.insa-lyon.fr/database/#collection/637218c173e9f0047faa00fb) and extract it.

After this, your directory should be structured like this:
```text
.
├── models
│   ├── trainedUNet2D_final.pt
│   └── trainedUNet3D_final.pt
├── figures                                    # All figures are added here
├── database
│   ├── training
│   │    ├── patient*
│   └── testing
│          └── patient*
├── 2D training.ipynb
├── 3D training.ipynb
└── Metrics calculations.ipynb
```
To run the models or train new ones, simply run the notebooks
