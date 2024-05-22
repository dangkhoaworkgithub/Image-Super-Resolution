# Image-Super-Resolution
Despite advancements in single-image super-resolution using faster and deeper convolutional
neural networks, a significant challenge remains: how to restore fine texture details when upscaling images by large factors. Current optimization-based methods primarily rely on minimizing
mean squared reconstruction error, resulting in high peak signal-to-noise ratios but lacking highfrequency details and perceptual satisfaction at higher resolutions. In our research, we introduce
SRGAN, a generative adversarial network (GAN) for image super-resolution. This innovative
framework can generate photorealistic natural images at 4× upscaling factors, a feat not achieved
before. We achieve this by proposing a novel perceptual loss function comprising an adversarial
loss and a content loss. The adversarial loss guides the solution toward the natural image space
using a discriminator network trained to distinguish between super-resolved images and original
photorealistic ones. Additionally, our content loss is based on perceptual similarity rather than
pixel space similarity. Our deep residual network excels at recovering photorealistic textures from
heavily downsampled images in public benchmarks. Extensive mean-opinion-score (MOS) tests
demonstrate significant improvements in perceptual quality with SRGAN. The MOS scores obtained with SRGAN are much closer to those of the original high-resolution images compared to
any existing state-of-the-art method.
