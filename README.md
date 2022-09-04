# Code

The main code of the CycleGan is in the CycleGans.ipynb 

# Network

the mode has four net work which are Generator_a2b,Generator_b2a,Discriminator_a,Discriminator_b. And the state dictionary of each network are in the Gen_a2b,Gen_b2a,Dis_a,Dis_b files.

# Dataset

The first file package(data/images/CycleGan/horses2zebras) is the final result which transfer horses to zebras and zebras to horses

The second file package(torch_data/CycleGAN/horse2zebra) contains the pictures which are used while training the model
