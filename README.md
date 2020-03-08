# Art-Style-Transfer
Style transfer method used is outlined in the paper, Image Style Transfer Using Convolutional Neural Networks, by Gatys in PyTorch.
      
      A pre-trained VGG19 Net is used to extract content or style features from a passed in image. 
      The idea of content and style losses is used and then iterated to update the target image until the required result is obtained.
      The content_weight used is 1 and style_weight is 1e6. 
      Number of steps used is 3500.
