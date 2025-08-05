## Vehicle Color Detection

### Environment Setup

Follow instructions for MMRotate setup:
```bash
conda create -n vehicle-detect python=3.8
conda activate vehicle-detect
conda install pytorch torchvision cpuonly -c pytorch-lts
pip install openmim
mim install mmcv-full
mim install mmdet
git clone https://github.com/open-mmlab/mmrotate.git
cd mmrotate
pip install -r requirements/build.txt
pip install -v -e .
```

The vehicle detection code is in `vehicle-detection.ipynb`