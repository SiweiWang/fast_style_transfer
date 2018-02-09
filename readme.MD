# Fast style transfer using deep learning and TensorFlow

The main code is from [here](https://github.com/lengstrom/fast-style-transfer) with some changes.

Local setup

1. Install python 3.7
1. Install [Miniconda](https://conda.io/miniconda.html)
1. Create a new enviornment that hold the package needed for the style transfer code. `condas create -n style-transfer python=3.7`
1. `source activate style-transfer` setup the style-transfer enviornment
1. `pip install tensorflow` installs tensorflow
1. `conda install scipy pillow` installs Tensoflow, Scipy and Pillow (image processing libray)
1. put the image under content dir
1. `python evaluate.py --checkpoint ./rain-princess.ckpt --in-path <path_to_input_file> --out-path ./output_image.jpg` for example `
python evaluate.py --checkpoint ./rain-princess.ckpt --in-path ~/playgroud/fast_style_transfer/content/Siwei.JPG --out-path ./results/output_image.jpg`
