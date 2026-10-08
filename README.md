# MexEE 402: Data Preprocessing Case Study

MexEE Elective 2: Data Science and Machine Learning
Batangas State University, Alangilan Campus
1st Semester, AY 2026-2027

## Members

| Name | Student Number | Section |
|:---:|:---:|:---:|
| Tolentino, Aeoshi Klyd | 23-04557 | MEXE 4101 |
| Vidal, Andrea Eunice | 23-03207 | MEXE 4101 |

## Notebook links

| Chapter | Member 1 | Member 2 |
|---|---|---|
| Ch1_2_3 | [link](https://colab.research.google.com/drive/1KT12QOWFuxI8skqfrSgdj8Gn79_r-jho?usp=sharing) | [link](https://colab.research.google.com/drive/16Yi6fXGthcTDuLhKCh0jOuaOxynzoRp6?usp=sharing) |
| Ch4 | [link](https://colab.research.google.com/drive/1XtBg2vlpj4XA0w_PY75yJ3Dw-yvpRu-H?usp=sharing) | [link](https://colab.research.google.com/drive/1Rv6iYqi-lfoenA_eNHuW79RpWMfSYeJ6?usp=sharing) |
| Ch5 | [link](https://colab.research.google.com/drive/1SvKIFi3HjTeENQvsFf1auI8xI3CH0z1Q?usp=sharing) | [link](https://colab.research.google.com/drive/1E_0FacCvWmaU-flApXBg3xnSJtW12ZdW?usp=sharing) |
| Ch6 | [link](https://colab.research.google.com/drive/1VDJ2KY1rpPvUp9EtljSfmfr2A8pbullG?usp=sharing) | [link](https://colab.research.google.com/drive/1_BgVbZXDo8Pir6Lj4uBhxDPHsbgFeCsY?usp=sharing) |
| Ch7 | [link](https://colab.research.google.com/drive/1fjweDKnmZLJjSwIO8z5JUlRt8eZUJqPp?usp=sharing) | [link](https://colab.research.google.com/drive/1Z1z6QFrM75Zu3JfSdFwq205JpJSFANw_?usp=sharing) |
| Ch8 | [link](https://colab.research.google.com/drive/1AZ1IUIVFI-e4047rQfeayXjJ5H4FuIsb?usp=sharing) | [link](https://colab.research.google.com/drive/12ARr-Niv22VePcyGkDhcKCfTv_sUjIoj?usp=sharing) |
| Ch9 | [link](https://colab.research.google.com/drive/1TyCOeoHOlQqllZP4KAOHIp9NiMIW0Z_L?usp=sharing) | [link](https://colab.research.google.com/drive/1wFUQ4_o7Kkvazo64OnMGb_5Hee6sarvP?usp=sharing) |

## What we learned

### 📁 Chapter 1-3: Introduction to preprocessing exploring, and cleaning data.
<div align = justify>
  
* These chapters introduced us  to the basic process of working with datasets for machine learning. At first, we thought that as long as we have a datasets we could immediately use it to train a mode. With these chapter, we learn that before data can be used, it needs to be organized and cleaned. We learned how to explore and understand data by utilizing Python. What surprise us the most is how data set greatly affect how a model learn.
</div>

### 📁 Chapter 4: Transformation, Feature Engineering, and Encoding
<div align = justify>

* After learning how to clean the data on the previous chapter. This chapter taught us how to transform cleaned data and change it into a form which a machine learning model generally work with numbers rather than text label, that's why we need to convert categorical values to numerical one. It is fascinating to see how much the way data is represented can affect how useful it is for machine learning.
</div>

### 📁 Chapter 5: Scaling and Normalization
<div align = justify>

* Building from the data transformation process in the previous chapter, we learned how to scale and normalized data so that different feature have a more consistent range. We learned that some features can have a very different values, and the model may be biased towards higher value. To avoid this, we need to change the scale of the features so it would be more comparable to other features. It is surprisingly effective because we are only changing the scale of the data without changing the actual information.
</div>

### 📁 Chapter 6: Outlier Detection
<div align = justify>

 * With the data already transformed and scaled, this chapter introduce us to outliers and how they affect the data. We learned that outliers are values that are very different from the majority of data points, but they are not always errors and should not be automatically removed. It was interesting to learn that even a few unusual values can affect the results and how a machine learning model understand the data.
</div>

### 📁 Chapter 7: Feature Selection
<div align = justify>

  * In this chapter, we understand how to select the most useful features for a machine learning model. We understand how to use correlations and the three basic feature selection methods to find the best feature. We also learned how Recursive Feature Elimination with Cross-Validation or RFECV, and how Lasso regression works. 
</div>

### 📁 Chapter 8: Constructing a Preprocessing Pipeline
<div align = justify>

  * This chapter teaches us how to build a data preprocessing pipeline that automatically prepares raw data for machine learning. We used the Train.csv dataset that is provided and learned how to separate features and targets, handle missing values with imputation, scale numerical features with StandardScaler, and organize using Pipeline and ColumnTransform. After learning all these, it really do look like a conveyor since it has stations where raw data will go through before being ready for a machine learning model.
</div>

### 📁 Chapter 9: Real-World Application: Data Preprocessing
<div align = justify>

  * Using the train.csv or titanic dataset, this chapter uses what we learned from previous chapters how to apply in a real-world application. We learned how to graph using matplotlib.pylot and seaborn. We then evaluated the results and check if there is any pattern showed in the visualizations of the data. 
</div>

## Errors we found

List any mistake you found in the original notebooks, and the correct version.
There are real ones in there. Finding them earns points.

## Note on AI tools

We utilized AI powered tool (Grammarly) to review our work for grammar and punctuation errors. We also use Chatgpt to help us summarize the resources and website we used as a reference, which help us understand the main points of the material. We also use it to provide a code for us to connect the Kaggle directly to the Google Colab, so that we wouldn't upload the file each time we run it.

## References

McKinney, W. (2021). Python for Data Analysis, 3rd ed. O'Reilly.
VanderPlas, J. Python Data Science Handbook.
GeeksforGeeks. (n.d.). Feature engineering: Scaling, normalization and standardization. 
GeeksforGeeks. (2025, July 23). Feature selection using SelectFromModel and LassoCV in Scikit Learn.
