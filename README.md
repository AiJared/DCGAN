# Deep Convolutional Generative Adversarial Network

**DCGAN** was a significant breakthrough in **GAN architecture**, introduced by *Radford et al. in 2015*. It established several best practices for designing stable GAN architectures.
## Key Architectural Innovations

1. **Convolutional Layers**:

    - Replaces **fully connected layers** with **convolutional layers**.
    - Allows for more efficient processing of **image** data.
    - Helps capture **spatial hierarchies** in images.

2. **Architectural Guidelines**:

    - Use **strided convolutions** for **downsampling** in the **discriminator**.
    - Use **transposed convolutions** for **upsampling** in the **generator**.
    - Apply **batch normalization** in both generator and discriminator.
    - Use **LeakyReLU** activation functions instead of **standard ReLU**.
    - Remove **fully connected** **hidden** layers.



## Architecture Comparison

 - **Traditional GAN**: Uses **dense layers**, *less stable training*.
 - **DCGAN**: Uses **convolutional layers**, more stable and better *image quality*.

## Training Characteristics

 - More *stable training* process.
 - Better **convergence**.
 - Ability to generate more **coherent** images.
 - Works well with *image datasets* like faces, objects, etc.
