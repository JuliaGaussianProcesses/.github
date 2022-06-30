# Welcome to JuliaGPs

JuliaGPs is an organisation interested in making Gaussian process models work well in the [Julia programming language](https://julialang.org/).
A lot of us use [Gaussian processes](https://en.wikipedia.org/wiki/Gaussian_process) in our research, or do methodological research on Gaussian processes.

If you're new to the organisation, you should develop an understanding of the core packages:
1. [KernelFunctions.jl](https://github.com/JuliaGaussianProcesses/KernelFunctions.jl)
2. [AbstractGPs.jl](https://github.com/JuliaGaussianProcesses/AbstractGPs.jl)
3. [ApproximateGPs.jl](https://github.com/JuliaGaussianProcesses/ApproximateGPs.jl)

`ApproximateGPs` depends on `AbstractGPs` and `KernelFunctions`, and `AbstractGPs` dependends on `KernelFunctions`, so it's best to develop and understanding of these packages in the above order.
These core packages are maintained jointly by [all org members](https://github.com/orgs/JuliaGaussianProcesses/people), and we try to ensure that they work well and are of a high standard.
Consequently, you should expect to recieve good support when working with them, for example you should expect prompt responses when you open issues / pull requests.

You'll notice a variety of other packages in this organisation.
These are all packages which depend on the above core packages in some way or another.
Often they're developed by an org member to support their personal research agenda.
They generally only have 1 or 2 maintainers, so you should expect a lower level of support.
