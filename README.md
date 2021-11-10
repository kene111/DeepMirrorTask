# DeepMirrorTask

### Model Structure:

Notebook Folder: This contains the notebook used in training and running inference on the model.
Images: This contains the total training loss for training sessions when feature noise was added, and when feature noise was not added.


### Procedure Taken:

1) Pytorch implementation of MaskRCNN used is the detectron2 framework. Cloned Repository can be found [here](https://drive.google.com/drive/folders/13Rx9_MBTskwU5TsZXGHITu06SNQnqyo6?usp=sharing).

2) A subset of the coco dataset was used with a single class. Link to the dataset used can be found [here](https://drive.google.com/drive/folders/18Tf_K4bwFgPieSTxdP_Jqavv5ZhRWuTX?usp=sharing)

3) Addition of the Feature noise was done [here](https://drive.google.com/file/d/1YNlQWaL1a0UHPEHCXPASzTyORGy6a4HM/view?usp=sharing) in the local detectron2 architecture folder.
Notebook training with and without the addition of feature noise can be found here respectively: [Link 1](https://github.com/kene111/DeepMirrorTask/blob/main/NoteBooks/Deep_Mirror_ML_Task_Feature_Noise.ipynb)
[Link 2](https://github.com/kene111/DeepMirrorTask/blob/main/NoteBooks/Deep_Mirror_ML_Task_No_Feature_Noise.ipynb)

4) Comparing of Total training Loss is displayed below:



![Total Loss - With Feature Noise](images/Training_Loss_Feature_Noise.png)
![Total Loss - - Without Feature Noise](images/Training_Loss_No_Feature_Noise.png)
