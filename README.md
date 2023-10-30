# HintTrainingPytorch

This is a project exploring the hint training techniques brought forth in FITNETS: HINTS FOR THIN DEEP NETS from Romero et. al. The goal of this project is to use the two-stage knowledge distillation process in this paper to create smaller models that can perform as well as a large teacher teacher model. In Romero et. al they did not consider the hint and guided layer locations except for the middle of the networks, so we set up an experiment to test performance if the hint and guided layers are also in the beginning and end of the networks. we run another experiment experimenting to see whether student depth improves performance. We also run an experiment seeing whether having multiple hint and guided layers in training improve the performance of the student model. Overall, this project is an exploration and adaptation of the hint training techniquies brought forth in FITNETS: HINTS FOR THIN DEEP NETS and trying some concepts not brought forth in the paper. Also, the original paper used the THEANO library which is quite old and outdated, so we implemented our experiments using PyTorch which is an extremely commonly used library for machine learning nowdays.
