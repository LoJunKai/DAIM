# Computer Vision

- `create_coco_tf_record.ipynb` notebook is used to generate TFRecord files from COCO format for training using TF OD API. This notebook calls the code stored in `junkai_tf_utils`.
- `FashionODFinal-checkpoint Master.ipynb` notebook is the original adapted DSTA provided template, based on the YOLO model. (35% accuracy)
- `Jun_Kai_Roboflow_Tutorial_Eval.ipynb` notebook is largely the original Roboflow tutorial for the training sections. Edited parts are under `Run inference test` section, for inference and evaluation. This notebook used to evaluate the frcnn models from the other notebooks.
- `Jun_Kai_Roboflow_Tutorial.ipynb` notebook is based on the frcnn architecture, with original parameters, training on the original DSTA dataset.
- `Jun_Kai_improved_frcnn_Tutorial.ipynb` notebook is based on the frcnn architecture, with fine-tuned parameters, training on the DeepFashion2 dataset.
