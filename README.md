# Generate Fake Cells

For deep learning (pre-training) we want to have some pristine data with a known ground truth. The model should be adjusted later to real data but might need less of it and/or train faster.

![2000 example training images](images/montage_black.jpg)

Our model cells have
- cell walls
- a tiny nucleus

We start backwards, instead of segmenting an image we will create a segmentation and distort it to looks like an image. In that way the ground truth image is the segmentation and the generated image is just a representation based on imaging physics like a 3d point-spread function and photon-shot noise. Our generated images look a little like light-microscopy images.
