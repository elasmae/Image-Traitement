## Project Overview

This work proposes two approaches for performing color transfer between two images based on optimal transport algorithms:

1. **Approximate Optimal Transport**: Using the *Sliced Optimal Transport* method to approximate the transfer between point clouds (pixels in RGB space).  
2. **Color Histogram Transport**: Applying optimal transport on the color histograms of the images, rather than on their individual pixels.

In both cases, a final spatial regularization is implemented to smooth the colors and reduce visual artifacts generated by the raw transfer.