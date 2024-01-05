"Alphabet and Common Word Recognition of American Sign Language"

The project focuses on American Sign Language recognition (ASL) to bridge the gap between ASL users and non ASL users. The project made use of a CNN in combination with residual network, Depth wise separable convolutions, spatial attention, and transformer like attention block. The model provides an 80% accuracy on ASL colour and MNIST fingerspelling datasets combined but can be improved on the ASL depth data and WLASL video data. The project also incorporates an accessibility feature where the translated text can then also be read aloud. Dynamic augmentations were made on the image data that generated virtual training samples by taking convex combinations of pairs of inputs and their corresponding labels.

ASL fingerspelling and MNIST data were trained on colab whereas WLASL was trained on Jupyter notebook due to computational constraints.
