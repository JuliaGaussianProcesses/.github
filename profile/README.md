# Welcome to JuliaGPs

JuliaGPs is an organisation interested in making Gaussian process models work well in the [Julia programming language](https://julialang.org/).
The packages in this ecosystem are targeted at people who want to use [Gaussian processes](https://en.wikipedia.org/wiki/Gaussian_process) as Bayesian statistical models,
or people who want to do methodological research on Gaussian processes.

If you're new to the organisation, you should develop an understanding of the core packages:
1. [KernelFunctions.jl](https://github.com/JuliaGaussianProcesses/KernelFunctions.jl)
2. [GPLikelihoods.jl](https://github.com/JuliaGaussianProcesses/GPLikelihoods.jl)
3. [AbstractGPs.jl](https://github.com/JuliaGaussianProcesses/AbstractGPs.jl)
4. [ApproximateGPs.jl](https://github.com/JuliaGaussianProcesses/ApproximateGPs.jl)

`KernelFunctions` and `GPLikelihoods` are low-level packages implementing APIs for kernel functions and observation likelihoods, respectively, and include implementations of the most common
classes of kernels and likelihoods used in pratice.
`AbstractGPs` and `ApproximateGPs` are higher-level packages that implement inference of full and sparse GPs. `AbstractGPs` is restricted to Gaussian likelihoods, while `ApproximateGPs` also allows for non-Gaussian ones.
`AbstractGPs` dependends on `KernelFunctions`, while `ApproximateGPs` depends on `AbstractGPs` and additionally on `GPLikelihoods`. 
The lower-level packages are reexported, and thus to have the complete experience at your fingertips, you can just use `ApproximateGPs`.
In order to develop an understanding of the ecosystem, however, it is best to study the packages in the above order 1-4.

These core packages are maintained jointly by [all org members](https://github.com/orgs/JuliaGaussianProcesses/people), and we try to ensure that they work well and are of a high standard.
Consequently, you should expect to recieve good support when working with them, for example you should expect prompt responses when you open issues / pull requests.

You'll notice a variety of other packages in this organisation.
These are all packages which depend on the above core packages in some way or another.
Often they're developed by an org member to support their personal research agenda.
They generally only have 1 or 2 maintainers, so you should expect a lower level of support.

<details>
<summary>Team</summary>
<p>While numerous people have contributed to the JuliaGPs ecosystem, core contributors (in alphabetical order) include <a href="https://www.widmann.dev/">David Widmann</a>, <a href="https://mlg.eng.cam.ac.uk/hong/">Hong Ge</a>, <a href="https://github.com/rossviljoen">Ross Viljoen</a>, <a href="https://sharanry.github.io/">Sharan Yalburgi</a>, <a href="http://www.infinitecuriosity.org/">ST John</a>, <a href="https://theogf.dev/">Théo Galy-Fajou</a>, and <a href="https://github.com/willtebbutt/">Will Tebbutt</a></p>
</details>