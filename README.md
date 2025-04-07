<div align="center">
  <h1>FGCV Aircraft prediction</h1>
</div>
<br>

## Timeline ⏲️

> `0.1` `04/07/2025` - Created repository.

<br>

## File diagram

```
|  resources           # Folder with different files used for showing the model in action.
│  model_weights.pt    # The best model weights.
│  main.ipynb          # The notebook that the model was trained with
│  classes.csv         # The available classes.
```
<br>
  
## Description

This project aims to be able to classify planes from the [FGCV dataset](https://www.robots.ox.ac.uk/~vgg/data/fgvc-aircraft/). The model we use here is the `yolo11n` from the [ultralitycs library](https://docs.ultralytics.com/models/yolo11/). The dataset from [pytorch datasets](https://pytorch.org/vision/main/datasets.html#:~:text=FGVC%20Aircraft%20Dataset.). 

Everything else is quite easy. Half of the [notebook](main.ipynb) is focused on preprocessing the data. After that we load our `yolo` model using the [weights](model_weights.pt) in the repo.

You can see the model in action here: https://colab.research.google.com/drive/18nlsrKk2FIlxxOU16HT0RSUw-LVUwgGy?usp=sharing




