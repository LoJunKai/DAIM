# Main Folder

- `FashionODFinal.ipynb` notebook is the original DSTA model given, running on YOLO v3 architecture.

- `roboflow` is the original notebook from Roboflow, running on Faster RCNN architecture, trained with the DSTA dataset.

- `improved_frcnn` is the modified (changed .config file) notebook of Roboflow, running on Faster RCNN architecture, trained with the curated DeepFashion2 dataset.

- `.pb` files are the exported model.

- `tf_save_folder` stores the model checkpoints and weights to resume training from.

The 5 digit number at the end states the number of training steps done.
