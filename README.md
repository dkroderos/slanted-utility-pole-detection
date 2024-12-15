# Slanted Utility Pole Detection Using YOLOv8

This project detects slanted utility poles in images using the YOLOv8 object detection model and a custom dataset for accurate and fast detection.

<div align="center">
<img src="https://github.com/dkroderos/slanted-utility-pole-detection/blob/main/sample-output.jpg" width = 70% height = 70%>
</div>

### Requirements

Here are the required packages to test the model.

```sh
pip install ultralytics==8.2.103 ipython
```

### Testing

Clone the repository and open the notebook.

```sh
git clone https://github.com/dkroderos/slanted-utility-pole-detection.git
cd slanted-utility-pole-detection
```

Open the notebook.

```sh
jupyter notebook
```

For contributors, make sure to clean the output of the notebook.

```sh
git config filter.strip-notebook-output.clean 'jupyter nbconvert --ClearOutputPreprocessor.enabled=True --to=notebook --stdin --stdout --log-level=ERROR'
```

### Dataset

The dataset is available at our [Roboflow Project](https://universe.roboflow.com/david-king-roderos-pde9a/slanted-utility-pole-detection/dataset/6).

### License

This project is under [MIT License](https://github.com/dkroderos/slanted-utility-pole-detection/blob/main/LICENSE).
