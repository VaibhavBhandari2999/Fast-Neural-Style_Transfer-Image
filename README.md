# Fast-Neural-Style_Transfer-Image

Run the download.sh file to download all the model to a /models/ folder.

Neural style transfer is an optimization technique used to take three images, a content image, a style reference image (such as an artwork by a famous painter), and the input image you want to style — and blend them together such that the input image is transformed to look like the content image, but “painted” in the style of the style image.
<br>
Neural style transfer uses a pretrained convolution neural network. Then to define a loss function which blends two images seamlessly to create visually appealing art, NST defines the following inputs: A content image (c) — the image we want to transfer a style to A style image (s) — the image we want to transfer the style from An input (generated) image (g) — the image that contains the final result (the only trainable variable) The architecture of the model as well as how the loss is computed is shown below.
<br>
<b>Instead of using a VGG19 model to train for the style from scratch, a few pretrained models are provided by http://cs.stanford.edu/people/jcjohns/fast-neural-style/models/", which we use in this project.</b>
  <br>
 Technology Used:
 <br>
 ![image](https://user-images.githubusercontent.com/30387574/83508707-f0a57f80-a4e7-11ea-9792-ce1eabee5d84.png)
<br>
<br>
<h3>Output got-></h3>
<br>
![Original](https://user-images.githubusercontent.com/30387574/83508797-129f0200-a4e8-11ea-8439-3f9ae1447569.jpg)
<h1>+</h1>
![la_muse](https://user-images.githubusercontent.com/30387574/83508933-437f3700-a4e8-11ea-9111-47e6ef79aa99.jpg)
<h1>=</h1>
![Neural Transfer Style](https://user-images.githubusercontent.com/30387574/83508986-57c33400-a4e8-11ea-931f-a7e0079b5fd8.jpg)

