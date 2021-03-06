# Video2Shop: Exact Matching Clothes in Videos to Online Shopping Images
![Python badge](https://img.shields.io/static/v1?label=python&message=3.6%7C3.7%7C3.8&color=blue)
![PyTorch badge](https://img.shields.io/static/v1?label=pytorch&message=1.6&color=%3CCOLOR%3E)

An un-official PyTorch implementation of Video2Shop: [Exact Matching Clothes in Videos to Online  Shopping Images](https://openaccess.thecvf.com/content_cvpr_2017/html/Cheng_Video2Shop_Exact_Matching_CVPR_2017_paper.html)



## Install

Conda environment is suggested.

### Requirements
* Python 3.6 or +
* PyTorch 1.6 with Cuda
* torchvision
* tensorboardX
* easydict
* tqdm

## Training

To train with one GPU

```
python train.py -tph <training_phase: 0 first part - 1 fusion nodes - 2 both> -e <num_epochs> -lr <learning-rate> --dataset <dataset> --gpus 0
```


## Evaluation

```
python evaluation.py -ckpt <ckpt>
```


## Citation

If you use this code in your research, please use the following BibTeX entry.

```
@inproceedings{cheng2017video2shop,
  title={Video2shop: Exact matching clothes in videos to online shopping images},
  author={Cheng, Zhi-Qi and Wu, Xiao and Liu, Yang and Hua, Xian-Sheng},
  booktitle={Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition},
  pages={4048--4056},
  year={2017}
}
```
