## PCA
PCA is a systemized way to transform input features into principle components, then those principle components are used as **new features.**
It is basiclly a mathematical technique used for dimensionality reduction.

### Working:
PCA finds a new coordinate system that is obtained from the old one by translation and rotation only. and it moves the center of the coordinate sysetm with the centre of the data.
##### PCA is resolved as:
<img src="https://alexhwilliams.info/itsneuronalblog/img/pca/pca_two_views.png" width="1000" height="500" >
<img src="https://liorpachter.files.wordpress.com/2014/05/pca_figure1.jpg" width="500" height="500">

The amount of information we loose is equal to the distance between a given point(as it existed in the sort od 2D space) and its new spot in the line. 

#### Documentation:

<a href="https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html"> https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html </a>
<hr> </hr>

## Facial Recognition using PCA:
One of the simplest and most effective PCA approaches used
in face recognition systems is the so-called eigenface
approach. This approach transforms faces into a small set of
essential characteristics, eigenfaces, which are the main
components of the initial set of learning images (training set).
Recognition is done by projecting a new image in the
eigenface subspace, after which the person is classified by
comparing its position in eigenface space with the position of
known individuals. 

##### Dataset: <a href="https://scikit-learn.org/stable/auto_examples/applications/plot_face_recognition.html"> https://scikit-learn.org/stable/auto_examples/applications/plot_face_recognition.html </a>

### Evaluation:
**Classification Report:**
 
 
                    precision    recall  f1-score   support

    Ariel Sharon      0.60      0.69      0.64        13
    Colin Powell      0.78      0.88      0.83        60
    Donald Rumsfeld   0.73      0.70      0.72        27
    George W Bush     0.91      0.88      0.90       146
    Gerhard Schroeder 0.81      0.88      0.85        25
    Hugo Chavez       0.73      0.53      0.62        15
    Tony Blair        0.91      0.86      0.89        36

    accuracy                              0.84       322
    macro avg         0.78      0.78      0.78       322
    weighted avg      0.84      0.84      0.84       322
    
## Prediction:

**(a) The most significant faces:** 

<img src="https://github.com/geekquad/Facial-Recognition-with-PCA/blob/master/signi.png">

**(b) Eigenfaces:**

<img src="https://github.com/geekquad/Facial-Recognition-with-PCA/blob/master/eigenfaces.png">


    
