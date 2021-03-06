# Realistic Translation Network

This is a [Torch](http://torch.ch/) implementation
of realistic translation network. The network is
composed of two modules, where the first module serves
as scene parser and the second module serves as parsing-
to-real image translation network. Each of the 
two modules is an image-to-image translation network.

# Image segmentation:

Different colors for different objects:
Sky = [128,128,128]

Building = [128,0,0]

Pole = [192,192,128]

Road_marking = [255,69,0]

Road = [128,64,128]

Pavement = [60,40,222]

Tree = [128,128,0]

SignSymbol = [192,128,128]

Fence = [64,64,128]

Car = [64,0,128]

Pedestrian = [64,64,0]

Bicyclist = [0,128,192]

Unlabelled = [0,0,0]

# image to image translation network

The image to image translation network comes
from [pix2pix](https://github.com/phillipi/pix2pix).

