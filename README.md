# Book-Recommendation-System
Book-Recommendation-System是一个基于隐语言模型的图书推荐系统。  

# 数据集  
* MovieLens数据集：[ml-latest-small](https://github.com/efishliu/Book-Recommendation-System/tree/master/Recommendation%20on%20Tensorflow/movies/ml-latest-small)  
* Book-Crossing数据集：[book-rating](https://github.com/efishliu/Book-Recommendation-System/tree/master/Recommendation%20on%20Tensorflow/books/other)  
# 主要内容
* 隐因子对模型的影响：[Different_f_for_LFM.ipynb](https://github.com/efishliu/Book-Recommendation-System/blob/master/Recommendation%20on%20Tensorflow/movies/Different%20f%20on%20LFM.ipynb)
* 使用梯度下降法，对隐含语言模型的改进算法Bias-SVD,SVD++，AsymmetricSVD在tensorflow进行比较；  
  各算法的比较代码：[Comparing_different_recommended_models_by_GD.ipynb](https://github.com/efishliu/Book-Recommendation-System/blob/master/Recommendation%20on%20Tensorflow/movies/Comparing%20different%20recommended%20models%20by%20GD.ipynb)
* 对隐语义模型的训练速度提出改进学习率的梯度下降法和Adam：[Diffrent_method_on_LFM](https://github.com/efishliu/Book-Recommendation-System/blob/master/Recommendation%20on%20Tensorflow/movies/Latent%20factor%20model%20.ipynb)    
* 根据隐语义模型的特性对图书标签进行聚类，最后使用隐语义模型构建了一个图书推荐系统。
  * BSVD在图书推荐上的实现：[BSVD_book_recommendation](https://github.com/efishliu/Book-Recommendation-System/blob/master/Recommendation%20on%20Tensorflow/books/web%20recommendation.ipynb)
  * 图书推荐系统web设计：[Book Recommadation Web](https://github.com/efishliu/Book-Recommendation-System/tree/master/Book%20Recommadation%20Web)  
  
