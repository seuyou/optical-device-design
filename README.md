Plasmonic nanostructure design and characterization via Deep Learning 

This repository is a fully implementation of [paper](https://www.nature.com/articles/s41377-018-0060-7), using
the most famous deep neural network framework [tensorflow](https://www.tensorflow.org/), while the 
initial implemention uses torch7 which is a lua numerical computation library, you can find it [here]( https://github.com/ItzikMalkiel/DeepNanoDesign
)

The following is the training process:

![](https://github.com/seuyou/optical-device-design/blob/master/image/loss.png)

From the test loss, even though eventually we can reach overfitting and the loss can reach the optimum, there are still
some exceptions in the training process which are unexpected or can even be catastrophic. Then we optimize this bidirectional
neural network such that test data shows it's really effective. After our paper comes out, we will show the result.
