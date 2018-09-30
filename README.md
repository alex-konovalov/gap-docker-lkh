# gap-docker-lkh

## Docker container for GAP with added LKH installation

This Docker container is built from the Docker container with the latest 
public release of GAP (<https://hub.docker.com/r/gapsystem/gap-docker/>).

It adds to it one more component, namely LKH, which is a C implementation
of the Lin-Kernighan heuristic for solving the traveling salesman problem
(<http://akira.ruc.dk/~keld/research/LKH/>) by Keld Helsgaun.

This container is used to provide a working environment to reproduce
calculations described in the arXiv preprint "Cayley graphs of order
kp are hamiltonian for k < 48" by Dave Witte Morris and Kirsten Wilk
(<https://arxiv.org/abs/1805.00149>).

For the supplementary code for the mentioned preprint and instructions on
how to use the code in an interactive Jupyter notebook on Binder, see
<https://github.com/alex-konovalov/hamiltonian-cayley-graphs>.
