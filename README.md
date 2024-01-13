# FFT-high_low_pass_fftFlters


## Project Overview

This project focuses on the application of Fast Fourier Transform (FFT) in image processing. It demonstrates the ability to transform images into the frequency domain, apply various filters, and then reconstruct the images. This approach is crucial in understanding the frequency components of images and the effects of different filters.

### Key Features

#### Task 1: Fast Fourier Transformational Images

- **FFT Function (`fft(image)`)**: Applies a Fast Fourier Transform to the given image, transforming it into the frequency domain.
- **Inverse FFT Function (`inv_fft(image)`)**: Converts a Fourier-transformed image back to its original spatial domain.
- **FFT Shift (`fft_shift(image)`)**: Shifts the zero-frequency component to the center of the spectrum, making it easier to analyze the frequency components.
- **Inverse FFT Shift (`inv_fft_shift(image)`)**: Performs the inverse operation of `fft_shift`, decentralizing the origin back to its original position.

#### Task 2: Low Pass and High Pass Filters

- **Gaussian Low Pass Filter (`gaussian_low_pass(A, image)`)**: Implements a Gaussian low pass filter for a given image, which allows low-frequency components to pass while attenuating high-frequency components.
- **Gaussian High Pass Filter (`gaussian_high_pass(A, image)`)**: Creates a Gaussian high pass filter for a given image, which allows high-frequency components to pass while attenuating low-frequency components.

#### Task 3: Filters in the FFT Domain

- **FFT Domain Filtering**: This task involves applying FFT to a masked image, experimenting with suppressing dominant frequency components (the bright spots), and then performing an inverse Fourier transform to reconstruct the image.
- **Analysis and Comments**: After applying the filters, the project includes a detailed analysis of the results, providing insights into how different frequency components affect the overall image.

