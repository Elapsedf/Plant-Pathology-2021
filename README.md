# Install

## Envs

```bash
conda create -n plant_kaggle python=3.8
conda activate plant_kaggle
pip install -r requirements.txt
```

If you have GPU, Please install **pytorch** corresponding to the CUDA version because it could faster your training.



## DataSet

链接：https://pan.baidu.com/s/1N10URTnXCaWbBWlRLISAWg  

提取码：zvjs

This dataset is provided by the Prof.Liang

# Run

Install the **extensions for jupyter Notebook** And change the **work dir path**

**Change the jupyter kernel to the plant_kaggle and run all.**





# Result

`Histogram.png` and `PieChart.png` show the distribution of the dataset

The figure in the `./Result/`  dir are the results I trained.

**And Swin-B base model show the best performance, The ACC is 0.8716666666666667**
