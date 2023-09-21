# Tiny Machine Learning for Human Activity Recognition
Tiny Machine Learning for Human Activity Recognition
Tiny Machine Learning (TinyML) has emerged as
a promising approach for deploying machine learning models on
resource-constrained devices, enabling real-time inference and
edge computing capabilities. Human Activity Recognition (HAR)
is a significant application domain where TinyML models can
provide valuable insights for healthcare monitoring, sports analysis,
and human-computer interaction. In this report, we present
a comparative analysis of Dense Neural Networks (DNN) and 2D
Convolutional Neural Networks (2D CNN) for TinyML in HAR,
considering feature selection based on variance as a preprocessing
step. Our study utilizes a dataset comprising samples of a
561-feature vector with time and frequency domain variables,
collected from wearable sensors. To reduce dimensionality and
optimize model performance, we apply feature selection based on
variance to select the most informative features. We investigate
the impact of different feature subset sizes on the performance
of DNN and 2D CNN models. For each model type, we trained
and evaluated the models on the reduced feature set using as
performance metrics the micro F1 score. To further optimize
the models for deployment on microcontrollers, we applied a
post-training quantization technique aimed at reducing the size
of the models. This quantization process converts the model’s
floating-point parameters to fixed-point representations, effectively
reducing memory requirements without significant loss of
accuracy. We evaluated various parameters, including Multiply-
Accumulate operations (MACC), latency, and flash usage, to
assess the effectiveness of the quantization process in optimizing
the model for resource-constrained environments.
The experimental results demonstrate that both DNN and 2D
CNN models, with the applied feature selection and post-training
quantization, achieve competitive accuracy in HAR tasks. We
observed that the models strike a balance between complexity
and accuracy, considering the limitations of resource-constrained
environments
