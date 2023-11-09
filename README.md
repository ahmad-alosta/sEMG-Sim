# sEMG-Sim version: 1.0
  Surface Electromyography Simulator

# Authors: Ahmad AlOsta & Josef Erik Djärf 
This code is the result of our Master's thesis project. What follows below is some general information about the project and a discription of the project.
Our objective was to implement an sEMG simulation model in Python. The model is based on mathematical models obtained
from scientific literature. The model contains several adjustable parameters including motor unit properties (size, firing rate, etc),
volume conductor, and setup for the recording electrodes.

# Title:
Multiple parameter modelling of synthetic electromyography (EMG) data.
In association with the Neuroengineering group, Departement of Biomedical Engineering, Faculty of Engineering, Lund Universty, Sweden.

# Authors:  Ahmad Alosta & Josef Djärf
# Supervisors: Robin Rohlén, & Jonathan Lundsberg (Assistant)
# Examiner: Christian Antfolk
Start-End Dates: Started 2023-08-29, preliminary ending date 2024-01-14. (Academic Term)

# Background:
Voluntary movements start in the brain as instructions and pass the spinal cord to the specific nerves that control
the skeletal muscle of interest through the so-called motor units. A motor unit is the combination of an individual
motor neuron and all of the muscle fibers that it innervates. Increased motor unit recruitment will increase muscle
output. By using high-density surface electrode electromyography, we can record the electrical signals of the
muscles from the skin surface. These signals can be decoded into neural information (spike trains) from the nerves.
This decoding is based on blind source separation algorithms previously validated against intramuscular
electromyography. Yet, current decoding algortihms may have a low motor unit yield. To improve these algorithms
or develop new ones, an EMG simulation model is needed with ground truth for evaluation purposes. Although,
there exists EMG simulation models in the literature, no open source implementation exists, which would be of
great benefit for the research community. The EMG signal is generated by motor units which are groups of
cylindrical muscle fibers that contract in unison. The motor unit action potential is spread out both in time and
along the length of the fibers and passes through the body which acts as a volume conductor. The implementation
of a comprehensive and adaptable mathematical model from this thesis work. The model can be used to assess
decomposition algorithms for large amounts of data with ground truth.
