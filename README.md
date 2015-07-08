# Learning Spatio-Temporal Fetures using 3D-Convolutional Networks

Sign languages are primarily used for communication with deaf people and people
who can hear but can not physically speak. We intend to propose a system for
sign language recognition. In the simplest form, recognition can be interpreted as
conversion of sign language to the text in other regular languages, although some
systems go one step further by giving spoken language as the output.
We propose to address the spatio-temporal nature of the problem by employing
Convolutional Neural Networks that learn features across time. Following recent
works, in order to extend traditional CNNs to include temporal information, we
use 3D convolutions where common weights are learned over several frames and
whole image. Our chief contribution lies in adapting these existing methods for
learning sign language features that are both spatial and temporal in nature.

The project implements a 3D CNN network in theano, more specifically the slow fusion 
architecture suggest by Karpathy et al. in the Youtube Video Classification
Paper. The model is run on the American Sign Language Lexicon Video Dataset
http://www.bu.edu/av/asllrp/dai-asllvd.html
