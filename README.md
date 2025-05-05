# Automatic Picking of Multi-Mode Dispersion Curves Based on Instance Segmentation

[mmdetection](https://github.com/open-mmlab/mmdetection)

# Training
```
# Train a new model
python train.py dcnsolo.py --work-dir workstation_solov2
```

# Testing
```
# Test a model
python image_demo.py test workstation_solov2/dcnsolo.py --weights workstation_solov2/epoch_35.pth --out-dir out_show
```

# Get dispersion curves
```
python predict_curves.py
```
