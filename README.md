<h3> Image-to-Image-Translation-Using-Conditional-GANs <a href= "https://colab.research.google.com/github/shahkarKhan24/Image-to-Image-Translation-Using-Conditional-GANs/blob/main/Image_to_Image_Translation.ipynb?authuser=1">   <img src="https://colab.research.google.com/assets/colab-badge.svg" width="150" alt="Open In Colab"/>
</h3>

<p>Here we are trying to use conditional adversarial networks to solve the general purpose solution of the image-to-image translation. This network can be used for the segmentation, coloring, or styling of an image given the dataset. Here we are trying to convert satellite images into Google map type images.</p>
<h3> Dataset </h3>
<p>The data set was downloaded from Kaggle which was specifically made for this kind of task. it contains combine images of input and target which we split during preprocessing. You can find more details <a href="https://www.kaggle.com/datasets/vikramtiwari/pix2pix-dataset"> HERE </p>

<h3>Results</h3>
<p>The model was trained on above-mentioned maps dataset for more than 400 epochs, the result is not that good as compared to the original paper but it can be better by tuning some hyperparameters and training for a little more. Below you can see the cherry pics that were generated by my trained model</p>

<div>
  <p>Generated Fake Image</p>
<img src="https://raw.githubusercontent.com/shahkarKhan24/Image-to-Image-Translation-Using-Conditional-GANs/main/Images/Generated_Fake.png" width="700" alt="Generated images"/>
</div>

<div>
  <p>Target Image</p>
<img src="https://raw.githubusercontent.com/shahkarKhan24/Image-to-Image-Translation-Using-Conditional-GANs/main/Images/Target.png" width="700" alt="Generated images"/>
</div>

<div>
  <p>Input Image</p>
<img src="https://github.com/shahkarKhan24/Image-to-Image-Translation-Using-Conditional-GANs/blob/main/Images/Input.png?raw=true" width="700" alt="Generated images"/>
</div>
