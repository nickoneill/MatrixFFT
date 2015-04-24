### MatrixFFT

From the [original README](https://github.com/nickoneill/MatrixFFT/raw/master/README-original):

> This directory contains the MatrixFFT implementation as well as a number of programs used to verify the correct operation of MatrixFFT and to measure the performance of MatrixFFT, basic Accelerate.framework FFT, and the FFTW library. MatrixFFT is a set of algorithms based on matrix decomposition used to improve the performance of large-signal FFTs.

This code, as well as help from the late [Richard Crandall](http://en.wikipedia.org/wiki/Richard_Crandall) and the [scitech list](https://lists.apple.com/mailman/listinfo/scitech) helped me immensely when working on FFTs for [LAFeatureDetection](https://github.com/nickoneill/LAFeatureDetection). The code and associated paper has since disappeared from the Apple site.

The files were publicly available previously, albeit tucked away on a mailing list in an unsearchable in a tar file. Hopefully hosting them here will bring some clarity to new users working with the Accelerate framework and FFTW.

As for the referenced paper ("Large-scale FFTs and convolutions
on Apple hardware") to go with the code, it's available as [FFTapps.pdf](https://github.com/nickoneill/MatrixFFT/raw/master/FFTapps.pdf).

I've posted exactly the files as I retrieved them (last updated October 2011) and it looks like there are a few deprecations that require fixing for building with the latest SDK. I don't have plans to do this myself but I would accept pull requests.

**Disclaimer:** I am not the original creator of this code and I am in no way claiming ownership or copyright on it. It is simply no longer hosted on the Apple Advanced Computation Group site.
