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

The different pre trained models provided by Stanford are:<br>
- Candy.t7
- la_muse.t7
- mosiac.t7
- feathers.t7
- the_scream.t7
- udnie.t7
- the_wave_eccv16.t7
- starry_night_eccv16.t7
- la_muse_eccv16.t7
- composition_vii_eccv16.t7

