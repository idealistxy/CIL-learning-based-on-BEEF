# CIL-learning-based-on-BEEF
machine-learning, CIL, greenhand-learning, Course Requirements

## Prerequisites

The following packages are required to run the scripts:

- [torch](https://github.com/pytorch/pytorch)
- [torchvision](https://github.com/pytorch/vision)
- [tqdm](https://github.com/tqdm/tqdm)
- [numpy](https://github.com/numpy/numpy)

## Training scripts

- Train CIFAR-100

  ```
  python main.py --config=./configs/beef/cifar-50-10.json
  ```
- Train ImageNet-100

  ```
  python main.py --config=./configs/beef/imagenet-50-10.json
  ```
- Trian Tiny-ImageNet-200
  ```
  python main.py --config=./configs/beef/tiny-imagenet-50-10.json
  ```

  ## notices
  If you want to run the tiny-imagenet, please unzip our zip document, we did some basic operation which cause dataset different from what you can get from the webside.
  
  If you want to modify the Hyperparameters, you can check the  setting file in ICLR23-BEEF-master\configs\beef\*.json
