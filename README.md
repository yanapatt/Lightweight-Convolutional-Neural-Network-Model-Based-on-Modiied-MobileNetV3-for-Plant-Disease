# **Lightweight Convolutional Neural Network Model Based on Modified MobileNetV3 for Plant Disease Classification**
## **Environment setup** 
All jupyter notebook file in this project using Tensorflow version 2.19.0, Keras version 3.10.0 and Python version 3.12.11 on Google Colab runtime using Nvidia Tesla T4 GPU (15.0 GB of GPU memory) and 12.67 GB of RAM in the Colab instance.
## **Datasets**
* PlantVillage dataset: <a href="https://www.kaggle.com/datasets/emmarex/plantdisease">Click here</a>
* Apple dataset: <a href="https://www.kaggle.com/competitions/plant-pathology-2020-fgvc7/data">Click here</a> 
* Maize and Rice dataset: <a href="https://data.mendeley.com/datasets/6nv7gt2636/1">Click here</a>
## **Table of notebook**
| No    | Folder Name                                    | Link      |
|-------|----------------------------------------------|-----------|
| 1     | MobileNetV3 Small                    | <a href="https://github.com/yanapatt/Lightweight-Convolutional-Neural-Network-Model-Based-on-Modiied-MobileNetV3-for-Plant-Disease/tree/main/Colab/MBNv3S">Click here</a>  |
| 2     | MobileNetV3 Small Minimalistic                                | <a href="https://github.com/yanapatt/Lightweight-Convolutional-Neural-Network-Model-Based-on-Modiied-MobileNetV3-for-Plant-Disease/tree/main/Colab/MBNv3S_Mini">Click here</a>  |
| 3     | MobileNetV3 Small Modify A                                | <a href="https://github.com/yanapatt/Lightweight-Convolutional-Neural-Network-Model-Based-on-Modiied-MobileNetV3-for-Plant-Disease/tree/main/Colab/MBNv3S_Modify_A">Click here</a>  |
| 4     | MobileNetV3 Small Modify B                                | <a href="https://github.com/yanapatt/Lightweight-Convolutional-Neural-Network-Model-Based-on-Modiied-MobileNetV3-for-Plant-Disease/tree/main/Colab/MBNv3S_Modify_B">Click here</a>  |
| 5     | MobileNetV3 Small Minimalistic Modify A                                | <a href="https://github.com/yanapatt/Lightweight-Convolutional-Neural-Network-Model-Based-on-Modiied-MobileNetV3-for-Plant-Disease/tree/main/Colab/MBNv3S_Mini_Modify_A">Click here</a>  |
| 6     | MobileNetV3 Small Minimalistic Modify B                                | <a href="https://github.com/yanapatt/Lightweight-Convolutional-Neural-Network-Model-Based-on-Modiied-MobileNetV3-for-Plant-Disease/tree/main/Colab/MBNv3S_Mini_Modify_B">Click here</a>  |
| 7     | Preprocess images, helper function and model config file                               | <a href="https://github.com/yanapatt/Lightweight-Convolutional-Neural-Network-Model-Based-on-Modiied-MobileNetV3-for-Plant-Disease/tree/main/Colab">Click here</a>  |
| 8     | Dataset index setting                                | <a href="https://github.com/yanapatt/Lightweight-Convolutional-Neural-Network-Model-Based-on-Modiied-MobileNetV3-for-Plant-Disease/tree/main/DatasetSetting">Click here</a>  |
| 9     | Model weight files                               | <a href="https://github.com/yanapatt/Lightweight-Convolutional-Neural-Network-Model-Based-on-Modiied-MobileNetV3-for-Plant-Disease/tree/main/modelTest2">Click here</a>  |
## **Result**
| Model                                      | #Params   | Dataset       | Test Accuracy % | Test Loss |
|--------------------------------------------|-----------|---------------|-----------------|-----------|
| MobileNetV3 Small                          | 939,120   | Plant Village | 93.29           | 0.2030    |
|                                            |           | Apple         | 84.66           | 0.4447    |
|                                            |           | Maize         | 86.42           | 0.4122    |
|                                            |           | Rice          | 90.00           | 0.2628    |
| MobileNetV3 Small Minimalistic             | 441,000   | Plant Village | 90.92           | 0.2919    |
|                                            |           | Apple         | 83.01           | 0.5000    |
|                                            |           | Maize         | 83.95           | 0.5337    |
|                                            |           | Rice          | 93.33           | 0.2983    |
| MobileNetV3 Small Modify A                 | 916,080   | Plant Village | 98.16           | 0.0535    |
|                                            |           | Apple         | 89.59           | 0.3350    |
|                                            |           | Maize         | 85.19           | 0.8654    |
|                                            |           | Rice          | 93.33           | 0.1965    |
| MobileNetV3 Small Modify B                 |          | Plant Village | 97.07           | 0.1016    |
|                                            |           | Apple         | 87.67           | 0.4093    |
|                                            |           | Maize         | 81.48           | 0.7929    |
|                                            |           | Rice          | 91.67           | 0.3033    |
| **MobileNetV3 Small Minimalistic Modify A (Proposed Model)** | 399,528   | Plant Village | 93.68           | 0.2104    |
|                                            |           | Apple         | 84.38           | 0.4614    |
|                                            |           | Maize         | 90.12           | 0.6533    |
|                                            |           | Rice          | 96.67           | 0.1386    |
| MobileNetV3 Small Minimalistic Modify B    |          | Plant Village | 92.10           | 0.2624    |
|                                            |           | Apple         | 85.75           | 0.4536    |
|                                            |           | Maize         | 85.19           | 0.7333    |
|                                            |           | Rice          | 93.33           | 0.1804    |

