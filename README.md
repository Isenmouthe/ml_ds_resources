# ml_ds_resources
my collected resources for data science and machine learning

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


## Maths
[A book to cover most of math needed for machine learning](https://www.cis.upenn.edu/~jean/math-deep.pdf)

## Data Websites
[UC Irvine Machine Learning Repository](https://archive-beta.ics.uci.edu/)

## Tutorials
[Data Science in VS Code tutorial](https://code.visualstudio.com/docs/datascience/data-science-tutorial)


## Technical things

[Anaconda Installation guide on Windows for Data Science](https://medium.com/@kiran.poudel/anaconda-installation-guide-on-windows-for-data-science-770eb18599c2)

[](https://jakevdp.github.io/blog/2017/12/05/installing-python-packages-from-jupyter/)

[](https://towardsdatascience.com/a-data-scientists-guide-to-python-virtual-environments-858841922f14)

[](https://towardsdatascience.com/setting-up-an-environment-for-machine-learning-with-conda-pip-tools-9e163cb13b92)

[](https://www.folkstalk.com/2022/10/how-to-update-python-using-anaconda-conda-with-code-examples.html)

[](https://towardsdatascience.com/pipenv-vs-conda-for-data-scientists-b9a372faf9d9)

-----
-----

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
