模型支持 数据集结构如下 ：
```plaintext
ImageNet/
├── train/
│   ├── n01440764/
│   │   ├── n01440764_10026.JPEG
│   │   ├── n01440764_10027.JPEG
│   │   └── ...
│   ├── n01443537/
│   │   ├── n01443537_10007.JPEG
│   │   ├── n01443537_10014.JPEG
│   │   └── ...
│   └── ...
└── val/
    ├── n01440764/
    │   ├── ILSVRC2012_val_00000293.JPEG
    │   └── ...
    ├── n01443537/
    │   ├── ILSVRC2012_val_00000543.JPEG
    │   └── ...
    └── ...
```

---
预训练权重 ：
  - vit_base_patch16_224_in21k ：[点击下载](https://github.com/rwightman/pytorch-image-models/releases/download/v0.1-vitjx/jx_vit_base_patch16_224_in21k-e5005f0a.pth)
  - vit_base_patch32_224_in21k ： [点击下载](https://github.com/rwightman/pytorch-image-models/releases/download/v0.1-vitjx/jx_vit_base_patch32_224_in21k-8db57226.pth)
  - vit_large_patch16_224_in21k ： [点击下载](https://github.com/rwightman/pytorch-image-models/releases/download/v0.1-vitjx/jx_vit_large_patch16_224_in21k-606da67d.pth)
  - vit_large_patch32_224_in21k ： [点击下载](https://github.com/rwightman/pytorch-image-models/releases/download/v0.1-vitjx/jx_vit_large_patch32_224_in21k-9046d2e7.pth)