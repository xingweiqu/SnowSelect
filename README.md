# SnowSelected Paper List (WIP)

Here is an academic paper list which contains the papers that [SnowCloud.ai](https://www.snowcloud.ai) AI Research Lab considered to be *very important, must read*.

The reason of any paper to be selected in this list may be any of the following:

1. The paper had brought a paradigm shift in its own domain.

2. The paper contained vital parts which lead the appearance of papers in 1.

3. The paper may cause a paradigm shift within 5 years.

After each subdomain, we proposed several ideas that may inspire your work that might be qualified to appear in this list. 

**SnowSelected  is all you need.**

## Natual Language Processing

- [Long and Short-Term Memory](https://www.mitpressjournals.org/doi/10.1162/neco.1997.9.8.1735) : An original idea for long sentences processing, inspired by human neural information processing mechanism.
- [Recurrent neural network based language model](https://www.isca-speech.org/archive/archive_papers/interspeech_2010/i10_1045.pdf) : An original idea of introducing RNN-like structure into the language model(LM).
- [GRU](https://arxiv.org/pdf/1412.3555.pdf) : A simple yet effective model for RNN-like structure. A large number of effective, high-precision models based on this architecture.
- [Connectionist temporal classification](ftp://ftp.idsia.ch/pub/juergen/icml2006.pdf) : Inspired by dynamic processing and dynamic time warping(DTW) when dealing with time-warped sequences like audio data.
- [Learning Longer Memory in RNN](https://arxiv.org/pdf/1413.7753.pdf) : Formulated Recursive Neural Network which can be applied on sequences recursively by only using a single compact model.
- [Learning phrase representations using RNN encoder-decoder for statistical machine translation](https://arxiv.org/pdf/1406.1078.pdf) : "Cho Model" for NMT.
- [Seq2Seq](https://arxiv.org/pdf/1409.3215.pdf): "Sutskever Model" for NMT, an advanced version.
- [A Convolutional Neural Network for Modelling Sentences](https://arxiv.org/pdf/1404.2188.pdf) : Conv model for NLP.. More efficient on AI chips.
- [CNN on Sentence Classification](https://arxiv.org/pdf/1408.5882.pdf) : Conv model for NLP.
- [Very Deep Convolutional Networks
   for Text Classification](https://arxiv.org/pdf/1606.01781.pdf) : Conv model foor NLP.
- [Neural Machine Translation by Jointly Learning to Align and Translate](https://arxiv.org/pdf/1409.0473.pdf) :  Attention mechanism first introduced in NLP field.
- [Soft And Hard Attention](https://arxiv.org/pdf/1502.03044.pdf) : Introduced the choice of soft and hard attention along features.
- [Global And Local Attention](https://arxiv.org/pdf/1508.04025.pdf) : Introduced attention along data.
- [Character-Aware Neural Language Models](https://arxiv.org/pdf/1508.06615.pdf): Character level Conv model for NLP.
- [Attention is All You Need.](https://arxiv.org/pdf/1706.03762.pdf) : First transduction model relying entirely on self-attention to compute representations of its input and output without using RNNs or convolution, but global FC. Introduced positional encoding, 15% mask sampling and multihead (plus, minus, eltwise product) additive attention.
- [BERT](https://arxiv.org/abs/1810.04805): Bidirectional. Optimized for downstream tasks.
- [Attentive Neural Processes](https://arxiv.org/pdf/1901.05761.pdf)
- [Transformer-XL](https://arxiv.org/abs/1901.02860): Introduced relative positional encoding. State reuse resolved the problem may caused by excessive long sentence.
- [Focused Attention Networks](https://arxiv.org/pdf/1905.11498.pdf)
- [XLNet](https://arxiv.org/pdf/1906.08237.pdf) : Combined AR and AE models. Introduced DAG while learning AR parameters in sentence segments.
- [Generating Long Sequences with Sparse Transformers](https://arxiv.org/pdf/1904.10509.pdf) : Simplified structure of XLNet AR part. And BERT for CV.(ADDRESS OUR #3 in [what is NEXT])

So what is NEXT? 

- Better sampling to keep locally complete information of data.
- Better relative positional encoding beyond "learned from position".
- Simplified structure of XLNet AR part.


## Computer Vision

### Invertible 1x1

### Architecture

- [AlexNet](https://dl.acm.org/citation.cfm?id=3065386) : The Beginning of Deep Learning for CV. Achieve new high rcoord  in imagenet classification
- [VGG](https://arxiv.org/pdf/1409.1556.pdf) : Deeper (19 layers at most) Conv3x3 models.

* Google Series
  * [GoogLeNet](https://www.cs.unc.edu/~wliu/papers/GoogLeNet.pdf) : Combinations of different kernel sizes.
  * [Inception v3](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Szegedy_Rethinking_the_Inception_CVPR_2016_paper.pdf)
  * [Inception v4](https://www.aaai.org/ocs/index.php/AAAI/AAAI17/paper/download/14806/14311)

- [First Attention Solution](https://arxiv.org/abs/1109.3737) : 
- [Convolutional Implementation of Sliding Windows](https://arxiv.org/pdf/1312.6229.pdf) : The core idea is CNN must recognize things invariant to position shifts.
- [1 x 1 Convolution](https://arxiv.org/pdf/1312.4400.pdf) : Introduced inplace inter-channel information exchange.
- [Triplet Loss](https://arxiv.org/pdf/1503.03832.pdf) : Combined differential learning and hard example mining.
- [Highway Networks](https://papers.nips.cc/paper/5850-training-very-deep-networks.pdf) : Must read before ResNet. Introduced branching schemes to accelerate deep learning training process.
- [Dilate Convolution](https://arxiv.org/pdf/1511.07122.pdf): Introduced more effective method for enlarging receptive field.
- [ResNet](https://arxiv.org/pdf/1512.03385.pdf) : Branching scheme with standardized implementation (18/34/50/101), combinations of Conv3x3 and Conv1x1
- [DenseNet](https://arxiv.org/pdf/1605.07110.pdf) : Introduced distillation idea in Conv Neural Networks.
- [ResNeXt](https://arxiv.org/pdf/1611.05431.pdf) : A tradeoff between a sparse MobileNet and a dense ResNet.
- [MobileNets](https://arxiv.org/pdf/1704.04861.pdf) : Efficient on some mobile devices. Introduced Depthwise Separable Conv which is very sparse. Save space for model parameters to the extreme. No saving for infer-time feature map.
- [SqueezeNet](https://arxiv.org/pdf/1602.07360.pdf) : Introduced attention mechanism vertical to image.
- [Wide ResNet](https://arxiv.org/pdf/1605.07146.pdf) : Ablation study for changing channel sizes.
- [R-FCN](https://arxiv.org/pdf/1605.06409.pdf) : Introduced 3x3 pixel shuffler.
- [Deformable Convolutional Networks](https://arxiv.org/pdf/1703.06211.pdf)
- [Deep Neural Networks for Object Detection](https://pdfs.semanticscholar.org/713f/73ce5c3013d9fb796c21b981dc6629af0bd5.pdf)
- [Glow](https://arxiv.org/pdf/1807.03039.pdf) : Introduced Invertible 1x1 Convolutions to save parameters in Encoder/Decoder , relying on PixelShuffler. 

### Detection

* R-CNN Original
  * [R-CNN](https://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Girshick_Rich_Feature_Hierarchies_2014_CVPR_paper.pdf)
  * [Fast R-CNN](https://arxiv.org/pdf/1504.08083.pdf)

* Kaiming He Series
  * [SPP Net](https://arxiv.org/pdf/1406.4729.pdf) : Introduced Pyramid like conventional SIFT.
  * Improved R-CNN
    * [Faster R-CNN](https://arxiv.org/pdf/1506.01497.pdf)
    * [Mask R-CNN](https://arxiv.org/pdf/1703.06870.pdf) :  Introduced segmentation after ROI-Align. **Not efficient on AI chip.**
    * [TensorMask](https://arxiv.org/pdf/1903.12174.pdf)
* Jia Deng Series
  * [Stacked Hourglass Networks](https://arxiv.org/pdf/1603.06937.pdf) : Recombination of ResNet. Achieved SOTA using hourglass104.
  * [CornerNet](http://openaccess.thecvf.com/content_ECCV_2018/papers/Hei_Law_CornerNet_Detecting_Objects_ECCV_2018_paper.pdf)

* YOLO Series
  * [YOLO](https://arxiv.org/abs/1506.02640) : Deal Classification problem using coarse segmentation.
  * [YOLO9000](https://arxiv.org/pdf/1612.08242.pdf) : Yolov2. Better, Stronger, Faster. Introduced Darknet architecture using less Conv1x1. Introduced label tricks. 
  * [YOLOv3](https://pjreddie.com/media/files/papers/YOLOv3.pdf) : Introduced unsupervised clustering in RPN/NMS stage.
* [Segmentation is All You Need](https://arxiv.org/pdf/1904.13300.pdf) : Introduced Segmentation methodology for detection task.

### Segmentation

* [Fully Convolutional Networks](https://people.eecs.berkeley.edu/~jonlong/long_shelhamer_fcn.pdf) : Pixelwise classification as Segmentation.
* [UNet](https://arxiv.org/pdf/1505.04597.pdf) : Introduced spatial features extraction and restorations. Backbone of many works like image compression/imputations/segmentation. Ideas might be inspired by MPEG4 rev.11 i.e. H264.
* [Pixel Shuffler](https://arxiv.org/pdf/1609.05158.pdf)
* [DeepLab](http://arxiv.org/pdf/1606.00915.pdf) ,[DeepLab v2](https://arxiv.org/pdf/1606.00915.pdf) and [DeepLab v3](https://arxiv.org/pdf/1706.05587.pdf)
* [FPN](https://arxiv.org/pdf/1612.03144.pdf)
* [STS](https://arxiv.org/pdf/1611.07932.pdf) and [STS++](https://arxiv.org/pdf/1905.11358.pdf)

### Optical Flow

- [FlowNet](https://arxiv.org/pdf/1504.06852.pdf) and [FlowNet2.0](https://arxiv.org/pdf/1612.01925.pdf) Introduced temporal features extraction. Backbone of many works based on video understanding. Ideas might be inspired by MPEG4 rev.11 i.e. H264.
- [SelFlow](https://arxiv.org/pdf/1904.09117.pdf)

### Unsupervised Methods

- [Unsupervised learning of object landmarks by factorized spatial embeddings](https://arxiv.org/pdf/1705.02193.pdf)
- [Deep Image Prior](https://arxiv.org/pdf/1711.10925.pdf)

### Loss Function

- [ArcFace](https://arxiv.org/pdf/1801.07698.pdf) : A final human face recognition paper combines sphereface idea and different order loss margins (Order 0,1,2 are hyper parameters)

### Pose Estimation

- [Convolution Pose Machines](https://arxiv.org/pdf/1602.00134.pdf) : 
- [OpenPose + PAF](https://arxiv.org/pdf/1611.08050.pdf) : The core idea is to predict directed vectors in between keypoints to form a feature map (PAF) thus one can join KP to different instances in a bottom-up way.

So what is NEXT?

- A much more robust way to deal with larger/smaller object.
- Beyond the invariance to shift/mirroring, a much more decent way to implement invariance to rotation.
- A "1-for-all" attention mechanism.


## Optimization

- [On Optimization Methods for Deep Learning](http://ai.stanford.edu/~ang/papers/icml11-OptimizationForDeepLearning.pdf)
- [Adam Optimization](https://arxiv.org/pdf/1412.6980.pdf)

## GAN

- [VAE](https://arxiv.org/abs/1312.6114)
- [GAN](https://arxiv.org/pdf/1406.2661.pdf)
- [conditional GAN](https://arxiv.org/pdf/1411.1784.pdf)
- [Generalized Denoising Auto-Encoders as Generative Models](http://papers.nips.cc/paper/5023-generalized-denoising-auto-encoders-as-generative-models.pdf)
- [LAPGAN](https://arxiv.org/pdf/1506.05751.pdf)
- [GAN for Combinatorial Optimization](https://arxiv.org/pdf/1509.09235.pdf)
- [A note on the evaluation of generative models](https://arxiv.org/pdf/1511.01844.pdf)
- [DCGAN](https://arxiv.org/pdf/1511.06434.pdf)
- [SRGAN](https://arxiv.org/pdf/1609.04802.pdf)
- [Pix2Pix](https://arxiv.org/pdf/1611.07004.pdf)
- [WGAN](https://arxiv.org/pdf/1701.07875.pdf) and [WGAN-GP](https://arxiv.org/pdf/1704.00028.pdf)
- [CycleGAN](https://arxiv.org/pdf/1703.10593.pdf)
- [XGAN](https://arxiv.org/pdf/1711.05139.pdf)
- [StarGAN](https://arxiv.org/pdf/1711.09020.pdf)

## Transfer Learning

- [JMMD](https://www.cv-foundation.org/openaccess/content_iccv_2013/papers/Long_Transfer_Feature_Learning_2013_ICCV_paper.pdf)
- [Adaptation regularization](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.708.6330&rep=rep1&type=pdf)
- [Feature Ensemble Plus Sample Selection: Domain Adaptation for Sentiment Classification](http://www.nlpr.ia.ac.cn/2013papers/gjkw/gk107.pdf)
- [Net2Net](https://arxiv.org/pdf/1511.05641.pdf)

## Deep Representations

- [Better Mixing via Deep Representations](https://arxiv.org/pdf/1207.4404.pdf)
- [Provable Bounds for Learning Some Deep
   Representations](https://arxiv.org/pdf/1310.6343.pdf)

## Audio Processing

- [WaveNet](https://arxiv.org/pdf/1609.03499.pdf)
- [Deep Voice](https://arxiv.org/pdf/1702.07825.pdf)
- [WaveNet for Denoising](https://arxiv.org/pdf/1706.07162.pdf)

## Tricks

- [Dropout](http://papers.nips.cc/paper/4882-dropout-training-as-adaptive-regularization.pdf)
- [Batch Normalization](https://arxiv.org/pdf/1502.03167.pdf) : Deal with large scale dynamic range of features.
- [No More Pesky Learning Rates](https://arxiv.org/pdf/1206.1106.pdf)
- [Bag of Tricks for CV](https://arxiv.org/pdf/1812.01187.pdf)
- [Accurate, Large Minibatch SGD: Training ImageNet in 1 Hour](https://arxiv.org/pdf/1706.02677.pdf)
- [LARS](https://arxiv.org/pdf/1709.05011.pdf)
- [SNIPER: Efficient Multi-Scale Training](https://arxiv.org/pdf/1805.09300.pdf)
- [Learning Data Augmentation Strategies for Object Detection](https://arxiv.org/pdf/1906.11172.pdf)

## Systems

1. [Hyperband: A Novel Bandit-Based Approach to Hyperparameter Optimization](https://arxiv.org/pdf/1603.06560.pdf)
2. [Learning to Optimize](https://arxiv.org/pdf/1606.01885.pdf)
3. [Neural Architecture Search with Reinforcement Learning](https://arxiv.org/pdf/1611.01578.pdf)
4. [AMC: AutoML for Model Compression and Acceleration on Mobile Devices](http://openaccess.thecvf.com/content_ECCV_2018/papers/Yihui_He_AMC_Automated_Model_ECCV_2018_paper.pdf)
5. [TVM: An Automated End-to-End Optimizing Compiler for Deep Learning](https://arxiv.org/abs/1802.04799)
6. [Horvord](https://arxiv.org/pdf/1802.05799.pdf)
7. [A Meta Learning-Based Framework for Automated Selection and Hyperparameter Tuning for Machine Learning Algorithms](http://openproceedings.org/2019/conf/edbt/EDBT19_paper_235.pdf)
8. [DARTS: Differentiable Architecture Search](https://arxiv.org/pdf/1806.09055.pdf)
