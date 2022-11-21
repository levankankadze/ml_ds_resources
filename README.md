# ml_ds_resources
my collected resources for data science and machine learning

## Courses
[CS231n: Convolutional Neural Networks for Visual Recognition.](https://cs231n.github.io/)

[ML recipes](https://bipinkrishnan.github.io/ml-recipe-book/about.html)

[Huggingface Course](https://huggingface.co/course/chapter1/1)

## Various Tool
[Deepnote](https://deepnote.com/)

[Codepen](https://codepen.io/)

[Normalization and Standardization in 2 Minutes](https://towardsdatascience.com/normalization-and-standardization-in-2-minutes-e0609a01e76)
[Dimitris Effrosynidis-Normalization and Standardization](https://deffro.github.io/tutorials/normalization-standardization/)
## Python
[EPAM Python](https://learn.epam.com/detailsPage?id=dce9b895-d4fc-4fe7-9d4c-999fa095d533)

[The Hitchhiker’s Guide to Python!](https://docs.python-guide.org/)

## Markdown
[Markdown and Visual Studio Code](https://code.visualstudio.com/docs/languages/markdown)

## Data Science Interview 
[Data Science Interviews](https://github.com/alexeygrigorev/data-science-interviews)

## Blogs
[Rishabh Shukla](http://rishy.github.io/)

## Glossaries
[Machine Learning Glossary](https://ml-cheatsheet.readthedocs.io/en/latest/index.html)

[Data Science](https://datasciencebook.ca/)

[Awesome Machine Learning On Source Code](https://github.com/src-d/awesome-machine-learning-on-source-code)

## Label Encoding
[Label Encoder vs. One Hot Encoder in Machine Learning](https://contactsunny.medium.com/label-encoder-vs-one-hot-encoder-in-machine-learning-3fc273365621)

## Boosting
[Quick Introduction to Boosting Algorithms in Machine Learning](https://www.analyticsvidhya.com/blog/2015/11/quick-introduction-boosting-algorithms-machine-learning/)

[Complete Machine Learning Guide to Parameter Tuning in Gradient Boosting (GBM) in Python](https://www.analyticsvidhya.com/blog/2016/02/complete-guide-parameter-tuning-gradient-boosting-gbm-python/)

## XGBoost
[original Parallel Gradient Boosting Decision Trees](http://zhanpengfang.github.io/418home.html)

[XGBoost Documentation](https://xgboost.readthedocs.io/en/stable/index.html)

[Complete Guide to Parameter Tuning in XGBoost with codes in Python](https://www.analyticsvidhya.com/blog/2016/03/complete-guide-parameter-tuning-xgboost-with-codes-python/)

[WHEN and WHY are batches used in machine learning ?](https://medium.com/analytics-vidhya/when-and-why-are-batches-used-in-machine-learning-acda4eb00763)

## Maths
[A book to cover most of math needed for machine learning](https://www.cis.upenn.edu/~jean/math-deep.pdf)

## Data Websites
[UC Irvine Machine Learning Repository](https://archive-beta.ics.uci.edu/)

## Tutorials
[Data Science in VS Code tutorial](https://code.visualstudio.com/docs/datascience/data-science-tutorial)

[Introduction to Machine Learning](https://github.com/davifrossard/iml)

## Technical things
[https://cs231n.github.io/setup-instructions/]

[Anaconda Installation guide on Windows for Data Science](https://medium.com/@kiran.poudel/anaconda-installation-guide-on-windows-for-data-science-770eb18599c2)

[](https://jakevdp.github.io/blog/2017/12/05/installing-python-packages-from-jupyter/)

[](https://towardsdatascience.com/a-data-scientists-guide-to-python-virtual-environments-858841922f14)

[](https://towardsdatascience.com/setting-up-an-environment-for-machine-learning-with-conda-pip-tools-9e163cb13b92)

[](https://www.folkstalk.com/2022/10/how-to-update-python-using-anaconda-conda-with-code-examples.html)

[](https://towardsdatascience.com/pipenv-vs-conda-for-data-scientists-b9a372faf9d9)

[](https://www.machinelearningplus.com/deployment/conda-create-environment-and-everything-you-need-to-know-to-manage-conda-virtual-environment/)

[](https://stackoverflow.com/questions/64500342/creating-requirements-txt-in-pip-compatible-format-in-a-conda-virtual-environmen)

[](https://pythonforundergradengineers.com/new-virtual-environment-with-conda.html)
-----
-----

## Software
### [Tensorflow](https://www.tensorflow.org/)
>TensorFlow is a free and open-source software library for machine learning and artificial intelligence. It can be used across a range of tasks but has a particular focus on training and inference of deep neural networks. TensorFlow was developed by the Google Brain team for internal Google use in research and production.

### [Pytorch](https://pytorch.org/)
>PyTorch is a machine learning framework based on the Torch library, used for applications such as computer vision and natural language processing, originally developed by Meta AI and now part of the Linux Foundation umbrella. It is free and open-source software released under the modified BSD license.

### [Keras](https://keras.io/)
>Keras is an open-source software library that provides a Python interface for artificial neural networks. Keras acts as an interface for the TensorFlow library. Up until version 2.3, Keras supported multiple backends, including TensorFlow, Microsoft Cognitive Toolkit, Theano, and PlaidML.

### [Optuna](https://optuna.org/)
>An open source hyperparameter optimization framework to automate hyperparameter search

### [Ray](https://docs.ray.io/en/latest/tune/)
> Ray Tune apart from the other hyperparameter optimization libraries. State of the art algorithms Maximize model performance and minimize training costs by using the latest algorithms such as PBT, HyperBAND, ASHA, and more.

## Some questions
> Pandas has both isna() and isnull(). I usually use isnull() to detect missing values and have never met the case so that I had to use other than that. So, when to use isna()?
### Answer
isnull is an alias for isna. Literally in the code source of pandas:
```python
isnull = isna
```
Indeed:
```
>>> pd.isnull
<function isna at 0x7fb4c5cefc80>
```
So I would recommend using isna.
[source](https://stackoverflow.com/questions/52086574/pandas-isna-and-isnull-what-is-the-difference)

----

>Use Pipenv or other tools is recommended for improving your development flow.
```python
pip freeze > requirements.txt  # Python3
```
[source](https://stackoverflow.com/questions/31684375/automatically-create-requirements-txt)

### 
> Accuracy and precision

Precision and accuracy are two ways that scientists think about error. Accuracy refers to how close a measurement is to the true or accepted value. Precision refers to how close measurements of the same item are to each other. Precision is independent of accuracy.

[Alt text](image/precsionvsaccuracy_crashcourse-579x600.png)