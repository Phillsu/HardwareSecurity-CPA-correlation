## 專案介紹
本專案的 Jupyter Notebook 示例：[M1326021_HWS_HW2.ipynb](M1326021_HWS_HW2.ipynb) 

為加速 correlation 計算，本程式碼透過 [Cupy](https://cupy.dev/) 將Numpy的矩陣計算透過Cuda 加速，  
將 CPA 計算總時間降低 87.5%。

## cupy acclerate
cupy 套件安裝指令如下，需先確認自身電腦之cuda版本，安裝對應套件  
```python
!pip install cupy-cuda12x
```
