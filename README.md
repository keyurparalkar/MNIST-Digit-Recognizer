## MNIST-Digit-Recognizer

### Dataset information
MNIST ("Modified National Institute of Standards and Technology") is the de facto “hello world” dataset of computer vision. Since its release in 1999, this classic dataset of handwritten images has served as the basis for benchmarking classification algorithms. As new machine learning techniques emerge, MNIST remains a reliable resource for researchers and learners alike.

### Aim
Goal is to correctly identify digits from a dataset of tens of thousands of handwritten images.

### Model
Creating LeNet5 nn class module

    conv2d => relu => maxpooling => conv2d => relu => maxpooling => fully connected layer(fc)1 => fc2 => softmax output

### Libraries required
    pytorch
    numpy
    pandas
    matplotlib
    
### For installing pytorch
    conda install pytorch torchvision -c pytorch

### For running this project
1. Activate the fastai environment: `source activate pytorch`
2. Run the notebook: `jupyter notebook`