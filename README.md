# course.fast.ai
coursework from course.fast.ai

a segmentation model with fastai, using a subset of the CamVid dataset
from the paper “Semantic Object Classes in Video: A High-Definition
Ground Truth Database” by Gabriel J. Brostow et al.:


We can visualize how well it achieved its task by asking the model to
color-code each pixel of an image. As you can see, it nearly perfectly
classifies every pixel in every object. For instance, notice that all
of the cars are overlaid with the same color, and all of the trees are
overlaid with the same color (in each pair of images, the lefthand image
is the ground truth label, and the right is the prediction from the model):
