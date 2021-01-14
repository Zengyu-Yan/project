# project - Interpretation of Latent Space in Deep-Learning Based Image Compression
In this project we study the state-of-art learning-based image compression technique, and analyzed their performance by conducting experiment and generating rate-distortion plots using four objectice assessment metrics: PSNR, SSIM, MS-SSIM and VIF. We also extract the latent space from one selected codec to see how changes in the latent space bring any different result. The main tasks are listed below:
1. Study the state of the art in deep-learning based image compression.
2. Get familiarized with the tools used for deep learning (PyTorch, Tensorflow, Google Colab)
3. Select most promising end-to-end implementations of deep-learning based image compression algorithms.
4. Analyze the performance of the selected end-to-end deep-learning based image compression algorithms (rate-distortion plots).
5. Study the state of the art of the latent space interpretation in deep learning.
6. *(Optional) Extract a latent space vector for one of the deep-learning based image codecs and explore the possibilities of meaningful modifications of such a vector that can cause an observable change in the reconstructed image.
7. Document all the development process and source code.


We test four models, each with different bitrate levels. The results are saved in four folders:'b2018','bmshj2018','hific' and 'mbt2018'. The code for performance analysis is in 'image quality assessment.ipynb'. The presentation slides and project report are also uploaded.
