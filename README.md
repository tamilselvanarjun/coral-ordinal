# CORAL ordinal classification in tf.keras


Tensorflow Keras implementation of ordinal classification using CORAL by Cao et al. (2019), with thanks to [Sebastian Raschka](https://github.com/rasbt) for the help in porting from PyTorch. This package includes an ordinal output layer and an associated loss function.

This is a work in progress, so please post any issues to the [issue queue](https://github.com/ck37/coral-ordinal/issues).

[Source repository](https://github.com/Raschka-research-group/coral-cnn/) for the original PyTorch implementation. Docs and tests will eventually be added.

## Installation

Install the stable version via pip:

```bash
pip install coral_ordinal
```

Install the most recent code on GitHub via pip:

```bash
pip install git+https://github.com/ck37/coral-ordinal/
```

## Dependencies

This package relies on Python 3.6+, Tensorflow 2, numpy, pandas, and scipy.

## Example

See [this colab notebook](https://colab.research.google.com/drive/1AQl4XeqRRhd7l30bmgLVObKt5RFPHttn) for an example of using an ordinal output layer with MNIST.

## References

Cao, W., Mirjalili, V., & Raschka, S. (2019). [Consistent rank logits for ordinal regression with convolutional neural networks]( https://arxiv.org/abs/1901.07884). arXiv preprint arXiv:1901.07884, 6. 