### EIP

Score:
[0.030765441474336193, 0.9932]


Short Description of following terms: 

1. Convolution : 
Convolution in DNN is the scanning of given input image by a feature extractor to get a reduced feature map of the image which forms a new layer in the network.

2. Filters/Kernels : 
Filter is a matrix of some dimension(usually 3 X 3) that extract a particular feature out of the image.
It is randomly initialised by the network and is updated by back propagation if required.
   
3. Epochs : 
Epoc is a network training parameter which is described as when network is trained by the entire training data once, we call it 1 epoch.

4. 1x1 Convolution : 
Used to reduce the number of depth channels.

5. 3x3 Convolution : 
3x3 Convolution matrix is most widely used convolution filter. Current hardware support is very good.

6. Feature Maps : 
Feature Maps are Map/collection of Features. The output of trained kernel resuls to a feature map

7. Activation Function :
Activation Function is a mathematical function applied on each convolution in the network that somehow(not clear to me) impacts the output . RELU is an example of activation function.

8. Receptive Field :
The receptive field is the part of the image that is visible to one filter at a time. 
It can be of two types: Global Receptive Fileds and Local receptive fields
