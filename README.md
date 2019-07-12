Code for A Closed-form Solution to Universal Style Transfer (https://arxiv.org/abs/1906.00668)
=============

This work mathematically derives a closed-form solution to universal style transfer. It is based on the theory of optimal transport and is closed related to AdaIN and WCT. AdaIN ignores the correlation between channels and WCT does not minimize the content loss. We consider both of them. Details of the derivation can be found in the paper.


![Teaser](./teaser3.png)

## Acknowledgments

Link to AdaIN : https://github.com/xunhuang1995/AdaIN-style

Link to WCT : https://github.com/Yijunmaverick/UniversalStyleTransfer

## Usage

1. Install Torch from http://torch.ch/

2. Download encoders, decoders from [here](https://drive.google.com/open?id=1uv1m15RqTwgWQog7BMAW38bDVE7BkzO4)

3. For single image usage, see demo.sh

4. For folder images usage, see demo_folder.sh


## Citation

If you find this code useful in your research, please consider to cite the following paper:

```
@article{lu2019optimal,
  title={a closed form solution to universal style transfer},
  author={Ming Lu, Hao Zhao, Anbang Yao, Yurong Chen, Feng Xu, Li Zhang},
  journal={arXiv preprint arXiv:1906.00668},
  year={2019}
}
```



