# Machine Learning (Miniproject2)

  I chose the topic of machine learning for my miniproject2 since it is popular and widely used in such as the field of computer vision. Before then, I learn nothing about Machine Learning so it’s a good opportunity for me to explore some new knowledge.<br/>
  The first thing I know to learn is the definition of Machine Learning. It is the scientific study of algorithms and statistical models that computer systems use to perform a specific task without using explicit instructions, relying on patterns and inference instead. It is seen as a subset of Artificial intelligence. The algorithms of Machine Learning build a mathematical model based on the sample data, known as “training data”, in order to make predictions or decisions without being explicitly programmed to perform the task. <br/>
  The next step I am going to do is to choose a open-source software. There are multiple softwares for me to learn. Here I choose Tensorflow to start, it is developed by Google and also widely used in deep learning now.<br/>
  For this project, my goal is to learn some basic operations in TensorFlow and try to use it to detect images & images classification.<br/>
Tensorflow provides me with good examples to start learning.<br/>
This code is going to practice the basic image classification. It uses the __Fashion MNIST__ dataset with low resolutions to classify. 60,000 images are used to train the network and 10,000 images to evaluate how accurately the network learned to classify images. <br/>
There are 9 classes here for me to classify: 'T-shirt/top', 'Trouser', 'Pullover', 'Dress', 'Coat', 'Sandal', 'Shirt', 'Sneaker', 'Bag', 'Ankle boot'<br/>
For results: correct predictions are marked "blue", incorrect predictions are marked "red"<br/>
The screenshots for result and accuray are shown below.<br/>
![result](https://github.com/Yufeng-L/MiniProject2/blob/master/trainresults.png)

![accuracy](https://github.com/Yufeng-L/MiniProject2/blob/master/testaccuracy.png)

### Reference:
https://en.wikipedia.org/wiki/Machine_learning <br/>
https://www.tensorflow.org/tutorials/keras/classification <br

## Summary of others Reports：

### Qi Luxuan's Report:
The topic is unsupervised machine learning.Comparing with the category I used in project1, unsupervised learning do not requrie any tags & labels. It classifies data sets by learning those unlabeled data and revealing the laws and characteristics that exist in the data. However, sometimes it can not yield satisfactory results which are often inferior to supervised learning. So unsupervised learning is primarily used to process unlabeled data sets. It also contains a variety processing methods such as K-means algorithm, hierarchical clustering algorithm, etc.

### Yuan Wei's Report:
He generally introduces object segmentation which is a subset of computer vision. It uses machine learning algorithm to deal with problems. It basically uses numbers to represent different objects of an image. In this topic, he mainly focused on how to segement an image. Machine learning method for object segmentation contains upsampling method, fully convolutional networks with other improved method, and dilated/atrous convolution. It needs some background of R, python and statistics methods.

### Xia Yaqun's Report:
Similar to Qi Luxuan's report, yaqun's report is also about unsupervised machine learning. For pros, less complexity in comparison with supervised learning.In unsupervised learning, no one is required to understand and then to label the data inputs. This makes unsupervised learning less complex and explains why many people prefer unsupervised techniques. It can take place in real time and help learners understand different models of raw data. For cons, it has less accuracy comparing to supervised learning as mentioned above and the results of analysis can not be ascertained because there is no prior knowledge in this category.

### Jiang Lingtao's Report:
His report is about image recognition. In order to analyze images, the encoding is transformed into constructs to depict the physical features of the objects. After then computers will analyze these constructions automatically by classification and feature extraction. Image classification consists of several steps including simplify image by extracting key feature of object and generating feature vectors and output class label. Predictive module is needed and traning data will be fed into module to recognize image. He also introduces YOLO, a image dector algorithm which has high speed for image processing.

