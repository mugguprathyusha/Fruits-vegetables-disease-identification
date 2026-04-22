# Fruits-and-Vegetables-Disease-Detection
Abstract:
When fruit and vegetable diseases are not treated quickly, they dramatically diminish yield.
Fruit and vegetable diseases are often brought on by pests, insects, and pathogens. Farmers
are losing money as a result of several illnesses. These issues that farmers are facing have a
remedy in the suggested system. The suggested system offers a solution to the problems
that farmers are experiencing. Pre-processing is used during the first stage. The noisy and
fuzzy portions of the segmented image are removed in the second phase using a variety of
features, and finally, images are classified into one of the classes using a multi-class
algorithm. We examined fruit and vegetable illnesses as a test case. Our findings show that
the suggested strategy can significantly aid in the accurate detection and automatic
recognition of vegetable and fruit diseases.


Introduction:
In the modern world, the agriculture field provides more than just food. However, as a result
of climatic and other changes over time, crop yields and agricultural output are now more
vulnerable to a number of significant problems that are of grave concern. Agriculture will
play a significant role in the global economy since demand is expected to outpace supply at
an increasingly high rate in the coming years. Currently, production is falling short of rising
demand. In general, the size of the cultivation area and the number of crops grown in
horticulture are different from those in agriculture. These issues that farmers are facing
have a remedy in the suggested system. The suggested system offers a solution to the
problems that farmers are experiencing. We list any diseases that may be present in fruits
and vegetables along with their symptoms and pesticides so that farmers can take
immediate action to prevent them. Fruit and vegetable diseases have a significant negative
impact on the productivity and financial losses of the global agricultural industry. An
adaptable method for identifying fruit and vegetable diseases is proposed in this study and
experimentally validated. Convolutional Neural Network algorithm (CNN) is used.

Why CNN ?:
A Convolutional Neural Network Architecture is suggested for the image-based disease
detection of leaves and fruits. When compared to current models, our suggested model
provides a 98% accuracy.

Algorithm:
Convolutional Neural Networks with a focus on image and video recognition applications.
CNN is primarily utilized for image analysis tasks like segmentation, object detection, and
image recognition.
Convolutional Neural Networks have three different kinds of layers:
Convolutional layer: Each input neuron is connected to the following hidden layer in a
typical neural network through the convolutional layer. Only a small portion of the input
layer neurons in CNN are connected to the hidden layer of neurons.
Pooling Layer: The feature map&#39;s dimensionality is decreased using the pooling layer. Inside
the CNN&#39;s hidden layer, there will be numerous activation and pooling layers.
Fully connected layer: The final few layers of the network are known as Fully Connected
Layers. The output from the final pooling or convolutional layer is fed into the fully
connected layer, where it is flattened before being applied.

Mathematical Model:
Let S be the Whole system S= {I,P,O}
I-Input
P-procedure
O-output
Input (I),
I= {Image }
Where,
Dataset-&gt; Image
Procedure (P),
P= {I, Using I System perform operations and performs the prediction}
Output(O)-
O= {System detects the diseases in fruits and vegetables}

Methodology:
1. Gather and upload a collection of images of fruits and vegetables.
2. Pre-processing: Scale the image, remove blur and distortion, and convert RGB and
greyscale to binary.
3. Extract the image&#39;s features, including its edges, size, width, and pixel values.
4. Create two distinct groups from the dataset: training (80%) and testing (20%).
5. Classification: Sort the dataset into categories using the CNN algorithm.
6. Create a CNN Training simulation. The CNN model has been used to analyze images.
7. As a result, find the disease in fruits and vegetables.

Architecture Diagram:

Common Architecture of CNN

By giving the Convolution Neural Network (CNN) algorithm the proper attributes and clean
data, these steps can help it make the most of its capabilities and generate data that is as
accurate as possible.

Activity Diagram :

Tools/Technologies used in the system :
Python :
Python is a general-purpose, high-level programming language. Its design philosophy
prioritizes code readability through extensive indentation in accordance with the off-side
rule. Python is garbage-collected and dynamically typed. It supports various programming
paradigms, including structured (especially procedural), object-oriented, and functional
programming. Because of its enormous standard libraries, it is frequently referred to as a
&quot; batteries included&quot; language.
Python Libraries used :
Tkinter - Tkinter is Python&#39;s standard GUI library. When hooked with Tkinter, Python
provides an immediate and simple approach to constructing a graphical user interface (GUI)
applications. Tkinter serves as an object-oriented interface that utilizes the Tk GUI toolkit.
Cv2 - OpenCV is a Python package designed for image processing and computer vision
applications. It offers multiple features, especially object detection, facial recognition, and
tracking.
Numpy - NumPy is a Python library that incorporates support for huge, multi-dimensional
arrays and matrices, as well as a vast number of high-level mathematical functions to work
on these arrays. Numeric, NumPy&#39;s precursor, was designed by Jim Hugunin with help from
numerous other people.
Sqlite3 - SQLite is an open-source database engine built in C. It is not a separate
program, but rather a library that software developers include in their applications. As
such, it is a member of the embedded database family.
Keras - Keras is a Python interface for artificial neural networks that is open-source
software. Keras serves as a front end for the TensorFlow library.

Matplotlib - Matplotlib is a Python visualization toolkit, as well as its numerical mathematics
extension NumPy. It provides an object-oriented API for introducing plots into programs
that use general-purpose GUI toolkits such as Tkinter, wxPython, Qt, or GTK.
Spyder :
Spyder is an open-source cross-platform integrated development environment (IDE) for
scientific programming in the Python language. Spyder integrates with a number of
prominent packages in the scientific Python stack,
including NumPy, SciPy, matplotlib, pandas, IPython, SymPy, and Cython, as well as other
open-source software. It is released under the MIT license.
DB Browser for SQLite:
DB Browser for SQLite (DB4S) is a high-quality, visual, open-source tool to create, design,
and edit database files compatible with SQLite.DB4S is for users and developers who want
to create, search, and edit databases. DB4S uses a familiar spreadsheet-like interface, and
complicated SQL commands do not have to be learned.
Working :
Cvtcolor is an inbuilt function of the cv2 library which we used to convert RGB images into grey
images. These Grey images generated were then resized as per requirement. We took the
help of the Threshold function to convert greyscale images into binary values. Many layers of
Keras libraries were used such as the Sequential layer to pass or process data in a proper
sequence. Then we used the Max Pooling layer which will get all active pixels and features and
will create a 2D matrix. Then we used Flatten layer to convert 2D matrix into 1D matrix and
the elements created by them are called Dense or nodes. Dropout were used to drop
irrelevant or unfamiliar or mismatched features. The features which were dropout by the model
were passed again and again to ensure that they matched with the categorized function or not.
We have used activation functions like Relu and SoftMax. While training data we had
rescaled the image, given a particular range, zoomed that image as per requirements, and
flipped it horizontally to obtain features more accurately. Once the model is trained, we
used testing data set to check if the given output is valid or not. When the model was
trained, we also calculated its accuracy with the help of Matplotlib library which is shared in
the Result section.

Example :
Apple disease:
Apples come in many different varieties, including Aceymac, Adanac, Akane, and Akero. The
diseases that affect apples vary depending on the variety and climatic conditions in which
they are growing, and they are categorized as black rot, rust, crown rot, scab, fire blight, and
numerous other diseases. The disease that has the worst impact on apple growth out of the
ones mentioned is apple scab. Apple scab is one of the most pervasive diseases of apples in
the world and is brought on by a fungus called Venturia Inequalis. It is a fungal disease that
affects both leaves and fruits. On the surface of tree bark, leaves, buds, and fruits, the
disease manifests as pale black or gray-brown lesions. Occasionally, lesions will develop on
the tree&#39;s woody tissues. The disease&#39;s lifecycle begins with the arrival of spring and
develops over the course of about 15 days. The secondary infection may also develop as a

result of the rising leaf moisture content and high temperature. The relationship between
temperature and wetness can be used to predict the progression of a disease. Around the
fruit&#39;s calyx, the lesions mostly take the shape of a cluster. Lesions are smaller and can have
a diameter of up to 1 cm.
So, We have got a dataset from the Kaggle website which is a supervised data means which is
inbuilt and categorized according to diseases. We select an image from the training dataset and
process using CNN and then predict the diseases with their corresponding treatment
pesticides or fertilizers.
Result :

We have successfully trained the model with 10K+ images of fruits and vegetables to detect
diseases in them and obtained 98% accuracy.
