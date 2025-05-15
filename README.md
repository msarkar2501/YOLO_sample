# YOLOv8 Object Detection on Pascal VOC

This project contains multiple training and evaluation experiments using the YOLOv8 object detection model on the Pascal VOC dataset.

## 📁 Project Structure

- `yolov8_run_X.ipynb`: Jupyter/Colab notebooks for each training and evaluation run.
- `datasets/`: Converted Pascal VOC dataset in YOLO format.
- `runs/`: YOLO training results, saved automatically to Google Drive.
- `val_X/`: Validation results for each model.
- `eval_X/`: Evaluation results on sample images.

## 🧠 Models Used
- `YOLOv8n` (nano variant from Ultralytics)

## 📊 Evaluation
Each model is evaluated using:
- Loss curves
- Confusion matrix
- mAP (mean Average Precision)
- Sample image predictions

## 🔁 Workflow
1. VOC dataset is downloaded and converted to YOLO format.
2. Multiple training runs are performed with changes in hyperparameters and configurations.
3. Each run is validated on the test set.
4. Predictions are generated on custom `sample_images`.

## 🔗 Report & References
- Assignment report contains links to the respective notebook runs.
- [Ultralytics YOLOv8 Docs](https://docs.ultralytics.com/)
- [Pascal VOC Dataset Info](http://host.robots.ox.ac.uk/pascal/VOC/)
- [YOLO Code Sample](https://github.com/ultralytics/ultralytics/blob/main/ultralytics/cfg/datasets/VOC.yaml)

## 📦 Requirements
- Google Colab
- PyTorch
- `ultralytics` library
- Internet connection (for dataset download and Drive sync)

## 🔒 License
This is an academic project for learning purposes only.

## Acknowledgments
- This project uses the [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics) framework under the [AGPL-3.0 license](https://ultralytics.com/license).
- The dataset used is the [PASCAL VOC dataset](http://host.robots.ox.ac.uk/pascal/VOC/) by the University of Oxford.
- Dataset conversion script inspired by the official [Ultralytics VOC format example](https://docs.ultralytics.com/datasets/detect/voc/).



