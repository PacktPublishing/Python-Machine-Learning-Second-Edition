# Python Machine Learning - Second Edition
This is the code repository for [Python Machine Learning - Second Edition](https://www.packtpub.com/big-data-and-business-intelligence/python-machine-learning-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781787125933), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
This highly acclaimed book has been extended and modernized to now include the popular TensorFlow deep learning library. The scikit-learn code has also been fully updated to include recent improvements and additions to this versatile machine learning library. The result is a new edition of this classic book at the cutting edge of machine learning.
## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.



The code will look like the following:
```
>>> from sklearn.neighbors import KNeighborsClassifier
>>> knn = KNeighborsClassifier(n_neighbors=5, p=2,
... metric='minkowski')
>>> knn.fit(X_train_std, y_train)
>>> plot_decision_regions(X_combined_std, y_combined,
... classifier=knn, test_idx=range(105,150))
>>> plt.xlabel('petal length [standardized]')
>>> plt.ylabel('petal width [standardized]')
>>> plt.show()
```

The execution of the code examples provided in this book requires an installation of Python 3.6.0 or newer on macOS, Linux, or Microsoft Windows. We will make frequent use of Python's essential libraries for scientific computing throughout this book, including SciPy, NumPy, scikit-learn, Matplotlib, and pandas.The first chapter will provide you with instructions and useful tips to set up your Python environment and these core libraries. We will add additional libraries to our repertoire; moreover, installation instructions are provided in the respective chapters: the NLTK library for natural language processing (Chapter 8, Applying Machine Learning to Sentiment Analysis), the Flask web framework (Chapter 9, Embedding a Machine Learning Algorithm into a Web Application), the Seaborn library for statistical data visualization (Chapter 10, Predicting Continuous Target Variables with Regression Analysis), and TensorFlow for efficient neural network training on graphical processing units (Chapters 13 to 16).
You can also find the code files at the following link:
https://github.com/rasbt/python-machine-learning-book-2nd-edition
## Related Products
* [Python Machine Learning](https://www.packtpub.com/big-data-and-business-intelligence/python-machine-learning?utm_source=github&utm_medium=repository&utm_campaign=9781783555130)

* [Python: End-to-end Data Analysis](https://www.packtpub.com/big-data-and-business-intelligence/python-end-end-data-analysis?utm_source=github&utm_medium=repository&utm_campaign=9781788394697)

* [Python: Real World Machine Learning](https://www.packtpub.com/big-data-and-business-intelligence/python-real-world-machine-learning?utm_source=github&utm_medium=repository&utm_campaign=9781787123212)

### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions.
