# Image Captioning with TensorFlow

## Requirements

python3

```
virtualenv -p python3 .env
source .env/bin/activate
pip install -r requirements.txt
```
## Task

- Automated image captioning using CNN and RNN

## Guidelines to train and evaluate model and predict captions for input image.
- loading the training and validation data
- creating the model, loss_fn and metrics
- training the model for a given number of epochs by calling `train_and_evaluate(...)`

`data_loader.py` to
- load jpg images and transforms to torch Tensors
- `data_iterator`: creates a batch of data and labels and pads sentences

- `model/net.py` : Neetwork, loss function and metrics
- `model/data_loader.py` : data loader
- `train.py` : Train module 

## References:

- [Show and Tell: A Neural Image Caption Generator](https://arxiv.org/abs/1411.4555)
- [Show, Attend and Tell: Neural Image Caption Generation with Visual Attention](https://arxiv.org/abs/1502.03044)
- [Where to put the Image in an Image Caption Generator](https://arxiv.org/abs/1703.09137)
- [What is the Role of Recurrent Neural Networks (RNNs) in an Image Caption Generator?](https://arxiv.org/abs/1708.02043)
- [Automated Image Captioning with ConvNets and Recurrent Nets](https://cs.stanford.edu/people/karpathy/sfmltalk.pdf)
- [Photo Caption Generator](https://machinelearningmastery.com/develop-a-deep-learning-caption-generation-model-in-python/)

## Resources

- [PyTorch documentation](https://pytorch.org/docs/stable/)
