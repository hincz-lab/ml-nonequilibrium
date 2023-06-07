# ml-nonequilibrium
Code and data related to the article "Machine learning in and out of equilibrium"
by Shishir Adhikari, Alkan Kabakçıoğlu, Alexander Strang, Deniz Yuret, and Michael Hinczewski

6/6/23: *This repository is a work in progress: additional code and data will be made available in the near future.*

The implementation and analysis of stochastic gradient descent training for the numerical examples is written in Julia, using the [Knet deep learning framework](https://github.com/denizyuret/Knet.jl).

Data files associated with the project are stored in an [OSF repository](https://doi.org/10.17605/OSF.IO/VN6A8).

## Code:

[**Nonlinear regression WR**](https://github.com/hincz-lab/ml-nonequilibrium/tree/main/Nonlinear%20regression%20WR): Nonlinear regression example, minibatching with replacement (WR)

[**Nonlinear regression WOR**](https://github.com/hincz-lab/ml-nonequilibrium/tree/main/Nonlinear%20regression%20WOR): Nonlinear regression example, minibatching without replacement (WOR)

## Data:

[**Gaussian_wr_ss-30000000-1.0e-7.jld2**](https://osf.io/vk7yu): Sample stationary state trajectory for the nonlinear regression WR example ($3 \times 10^7$ time steps, $\eta = 10^{-7}$, Julia data format)

[**Gaussian_wor_ss-15000000-1.0e-7.jld2**](https://osf.io/p7zbw): Sample stationary state trajectory for the nonlinear regression WOR example ($1.5 \times 10^7$ epochs, batch size = 10,  $\eta = 10^{-7}$, Julia data format)
