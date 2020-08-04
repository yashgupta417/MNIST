# MNIST
Applied Deep Learning on MNIST dataset.

<h3>Multilayer Perceptron</h3>

->Dense layer emsp     [512, activation='sigmoid']<br>
->BatchNormalisation<br>
->Dropout         [dropout_rate=0.5]<br>
->Dense layer     [128, activation='sigmoid']<br>
->BatchNormalisation<br>
->Dropout         [dropout_rate=0.5]<br>
->Softmax layer   [10]<br><br>

Accuracy: 98.07%<br>

<h3>CNN Model</h3>

->Convolution layer  [6, kernel_size=5, padding='same', activation='relu']<br>
->MaxPool            [pool_size=(2,2), strides=(2,2)]<br> 
->Convolution layer  [16, kernel_size=5, activation='relu']<br>
->MaxPool            [pool_size=(2,2), strides=(2,2)]<br> 
->Convolution layer  [120, kernel_size=5, activation='relu']<br>
->Relu Dense layer   [84]<br>
->Softmax layer      [10]<br><br>

Accuracy: 98.91%


