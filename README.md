# ADEQ. Code under collation, available soon.

## Requirements

- Python >= 3.7.10
- Pytorch >= 1.7.0
- Torchvision >= 0.4.0

## Reproduce the Results 

1. The pre-trained model will be downloaded automatically. If the download process fails, please use the URL in the console to download manually.
2. run:
    
    `cd ADEQ`

    `bash run_cifar100.sh`
    for CIFAR-100
    
    `bash run_imagenet.sh`
    for ImageNet
    
    Following results can be obtained:

| Model     | Bit-width| Dataset  | Top-1 Acc.|
| --------- | -------- | -------- | --------- | 
for ImageNet
| resnet18  | W3A3     | ImageNet | 41.15%    | 
| resnet18  | W4A4     | ImageNet | 66.32%    | 
| resnet18  | W5A5     | ImageNet | 69.90%    | 
| --------- | -------- | -------- | --------- | 
for CIFAR-100
| resnet20  | W3A3     | ImageNet | 54.33%    | 
| resnet20  | W4A4     | ImageNet | 66.35%    | 
| resnet20  | W5A5     | ImageNet | 69.34%    | 
| --------- | -------- | -------- | ----------|
