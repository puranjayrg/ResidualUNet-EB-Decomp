# E-B Decomposition Using Residual U-nets

+ The code for model definition, training, testing, and plotting of results can be found in `code/unet_main`  or by clicking [here.](code/unet_main/unet_main_multigpu.py)
+ The code for image (patch) dataset generation can be found in `code/dataset_generation`  or by clicking [here.](code/dataset_generation/patchgen_lowmem_h5.py)
+ The code for tuning of the model for multiple hyperparameters of the U-net including learning rate and the choice of backbone can be found in `code/unet_tuning` or by clicking [here.](code/unet_tuning/unet_tune_deep_gpu.py)