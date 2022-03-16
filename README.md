# Generate Fake Cells

For deep learning (pre-training) we want to have some pristine data with a known ground truth. The model should be adjusted later to real data but might need less of it and/or train faster.

Our model of cells have
- cell walls
- a tiny nucleus

We want to develop a segmentation of a cell and sample from it the image. In that way the ground truth image is the segmentation and the
generated image is just a representation based on imaging physics.

