# Different Techniques To Reduce Inference Time of Deep Learning Models

## Techniques Implemented

## Transfer Learning

- **Purpose**: Reusing pre-trained models on large datasets (e.g., ImageNet) to accelerate training and improve performance on smaller, target datasets.
- **Models**: VGG, Inception, ResNet, MobileNet, DenseNet
- **Benefits**: 
  - Faster training
  - Better performance with limited data
  - Reduced computational overhead

## Quantization

- **Purpose**: Reducing model size and improving inference speed by converting high-precision floating-point weights to lower-precision formats (e.g., 16-bit, 8-bit).
- **Techniques**: 
  - Post-training quantization (PTQ)
  - Quantization-aware training (QAT)
- **Challenges**: Potential loss of accuracy due to reduced dynamic range.

## Pruning

- **Purpose**: Removing unnecessary parameters from the model to improve efficiency and reduce computational complexity.
- **Methods**: Removing entire feature maps from convolutional layers.
- **Benefits**: 
  - Faster inference
  - Smaller model size
  - Reduced memory footprint

## Implementation Details

- **Framework**: [PyTorch]
- **Hardware**: [Intel Xenon -8480 , Nvidia A6000]
- **Optimization Tools**: [Pytorch,ONNX]
