# SLTFNet: A Spatial and Language-Temporal Tensor Fusion Network for Video Moment Retrieval

To well align the given textual query and the video moment candidates, we devise a spatial and language-temporal tensor fusion model to adaptively identify the relevant objects and interactions based on the query information.

## Environment Settings
We use the framework tensorflow. 
- tensorflow version:  '1.7.0'
- python version: '3.6'

## Example to run the codes.

Run SLTF:

```
SLTF.ipynb
```

After training process, the value of "R@n, IoU=m" in the test dataset will be printed in command window after each optimization iteration.

Output:

```
IoU=0.1, R@10: 0.59266802444; IoU=0.1, R@5: 0.459703229561; IoU=0.1, R@1: 0.223741635147
IoU=0.3, R@10: 0.41780622636; IoU=0.3, R@5: 0.31859179517; IoU=0.3, R@1: 0.170788478324
IoU=0.5, R@10: 0.262729124236; IoU=0.5, R@5: 0.207739307536; IoU=0.5, R@1: 0.11492580739
IoU=0.7, R@10: 0.149549025313; IoU=0.7, R@5: 0.122490544079; IoU=0.7, R@1: 0.0677916787896
IoU=0.9, R@10: 0.0389874890893; IoU=0.9, R@5: 0.0328775094559; IoU=0.9, R@1: 0.0139656677335
```


## Parameter Tuning

we put all the papameters in the SLTF.ipynb

## Dataset

We provide three processed dataset: TACoS, Charades-STA, DiDeMo.

You can download them from the [Baidu SkyDrive](https://pan.baidu.com/s/1AFrUYKJ_iiZXwhK2I10lVA) and password is:

```
zlpq
```
