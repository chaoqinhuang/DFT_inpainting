# DFT_inpainting
Image inpainting using frequency domain priors
# Abstract
The objective of image inpainting tasks is to restore missing pixels of an incomplete image in coherence with its surroundings. Prior works on image inpainting predict the missing pixels by training neural networks using only the spatial domain information. However, these methods often lead to blurry artifacts or mismatched structures inconsistent with their surroundings. In this paper, we investigate if it is possible to obtain better performance by training the networks using frequency domain, i.e., discrete Fourier transform (DFT) domain input representations along with the spatial domain information. To this end, we propose a frequency-based deconvolution module that enables the network to learn the global context while selectively reconstructing the high-frequency components as well, leading to better missing region prediction. We evaluate our proposed method on the publicly available datasets CelebA, Paris Streetview, and DTD texture dataset, thus showing that our method outperforms current state-of-the-art image inpainting techniques both quantitatively and qualitatively. 
