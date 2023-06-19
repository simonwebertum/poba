# Power Bundle Adjustment for Large-Scale 3D Reconstruction, CVPR 2023

Welcome to the official page of the paper [Power Bundle Adjustment for Large-Scale 3D Reconstruction (CVPR 2023)](https://arxiv.org/pdf/2204.12834.pdf). You can find a video presentation [here](https://www.youtube.com/watch?v=2DXJvJM2ExQ).

## Open-Source Implementation

The official implementation of PoBA **is available [here](https://github.com/NikolausDemmel/rootba/blob/master/docs/PoBATutorial.md)**.

## Abstract

We introduce Power Bundle Adjustment as an expansion type algorithm for solving large-scale bundle adjustment problems. It is based on the power series expansion of the inverse Schur complement and constitutes a new family of solvers that we call inverse expansion methods. We theoretically justify the use of power series and we prove the convergence of our approach. Using the real-world BAL dataset we show that the proposed solver challenges the state-of-the-art iterative methods and significantly acceleates the solution of the normal equation, even for reaching a very high accuracy. This easy-to-implement solver can also complement a recently presented distributed bundle adjustment framework. We demonstrate that employing the proposed Power Bundle Adjustment as a sub-problem solver significantly improves speed and accuracy of the distributed optimization.
