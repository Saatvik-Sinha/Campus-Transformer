# Campus-Transformer
PointTransformer Implementation for IIITB-Campus Point Cloud Benchmarking Dataset

To view training & validation metrics & graphs, run the following inside the repository folder:

`
conda activate open3dclone
`

`
tensorboard --logdir ./train_log --port 6006
`

Everytime you need to rerun the notebook- that is train and validate a new model:
1. Delete logs and train_log folder first.
2. Restart the kernel
