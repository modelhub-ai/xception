# xception
This repository hosts the contributor source files for the xception model. ModelHub integrates these files into an engine and controlled runtime environment. A unified API allows for out-of-the-box reproducible implementations of published models. For more information, please visit [www.modelhub.ai](http://modelhub.ai/) or contact us [info@modelhub.ai](mailto:info@modelhub.ai).
## meta
| | |
|-|-|
| id | dbf35840-9c8d-408f-8a36-b9fe2f8e5546 | 
| application_area | ImageNet | 
| task | Classification | 
| task_extended | ImageNet classification | 
| data_type | Image/Photo | 
| data_source | http://www.image-net.org/challenges/LSVRC/2012/ | 
## publication
| | |
|-|-|
| title | Xception: Deep Learning with Depthwise Separable Convolutions | 
| source | Arxiv | 
| url | https://arxiv.org/abs/1610.02357 | 
| year | 2016 | 
| authors | Francois Chollet | 
| abstract | We present an interpretation of Inception modules in convolutional neural networks as being an intermediate step in-between regular convolution and the depthwise separable convolution operation (a depthwise convolution followed by a pointwise convolution). In this light, a depthwise separable convolution can be understood as an Inception module with a maximally large number of towers. This observation leads us to propose a novel deep convolutional neural network architecture inspired by Inception, where Inception modules have been replaced with depthwise separable convolutions. We show that this architecture, dubbed Xception, slightly outperforms Inception V3 on the ImageNet dataset (which Inception V3 was designed for), and significantly outperforms Inception V3 on a larger image classification dataset comprising 350 million images and 17,000 classes. Since the Xception architecture has the same number of parameters as Inception V3, the performance gains are not due to increased capacity but rather to a more efficient use of model parameters. | 
| google_scholar | https://scholar.google.com/scholar?oi=bibs&hl=en&cites=3110565860331647079 | 
| bibtex | @article{DBLP:journals/corr/Chollet16a, author = {Francois Chollet}, title = {Xception: Deep Learning with Depthwise Separable Convolutions}, journal = {CoRR}, volume = {abs/1610.02357}, year = {2016}, url = {http://arxiv.org/abs/1610.02357}, archivePrefix = {arXiv}, eprint = {1610.02357}, timestamp = {Mon, 13 Aug 2018 16:46:20 +0200}, biburl = {https://dblp.org/rec/bib/journals/corr/Chollet16a}, bibsource = {dblp computer science bibliography, https://dblp.org}} | 
## model
| | |
|-|-|
| description | Xception is inspired by Inception and introduces modified depthwise separable convolutions. | 
| provenance | https://github.com/fchollet/deep-learning-models/blob/master/xception.py | 
| architecture | Convolutional Neural Network (CNN) | 
| learning_type | Supervised learning | 
| format | .h5 | 
| I/O | model I/O can be viewed [here](contrib_src/model/config.json) | 
| license | model license can be viewed [here](contrib_src/license/model) | 
## run
To run this model and view others in the collection, view the instructions on [ModelHub](http://app.modelhub.ai/).
## contribute
To contribute models, visit the [ModelHub docs](https://modelhub.readthedocs.io/en/latest/).

