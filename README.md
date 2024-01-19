# Mars-Crater-Detection
A ML model to detect and classify craters on martian surface

Data Handling: The train dataset was modified to increase its size and improve the accuracy of the model.
  Following transformations were performed on the dataset:
  1. Convert images to grayscale.
  2. Randomly change the brightness, contrast, saturation and hue of an image.
  3. Crop the given image at a random location.
  4. Horizontally flip the given image randomly with a given probability(p=0.5).
  5. Randomly rotate the image by an angle.
