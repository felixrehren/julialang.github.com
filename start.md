---
layout: default
title:  Julia for new Contributors
---

Julia: a fresh approach to technical computing.
Now at version 0.6-dev. Next stop: 0.6, then v1.0!

This page is a 3-times-60-seconds guide to get you started for taking part and pitching in.

# Julia's Features

* **Optional typing** lets you annotate code with logic, and allows blazing-fast compiler optimization!
* **Multiple dispatch** lets you write flexible, intuitive function definitions according to argument types (new logic in 0.6!)
* It's **fast**. As fast as we can push it. We compete with C, Fortran and Matlab
* You can run scripts, work/play interactively, or write beautiful notebooks (try it! [juliabox.com](https://www.juliabox.com/))
* **Everything is first class** and you can easily inspect and generate your own code with the power of macros
* **Dogfood**: almost all the Julia-internals are written in Julia!
* A great **package ecosystem**
* Ability to call C and Python inline
* [NEW IN v0.5] **Vectorisation** made easy with `f.()` as syntax for vectorised `f()`. Easy parallelizations available too ...
* And, finally, a brilliant **community** that welcomes contributors! Ask anything on [Discourse](https://discourse.julialang.org/), fork us on [Github](https://github.com/JuliaLang/julia)

If you've seen Julia before, check out what we achieved in [2016's version 0.5](http://julialang.org./blog/2016/10/julia-0.5-highlights). There's more to come for Julia. Much more!

<div class="figure">
<div class="cs-benchmark-table">
{% include benchmarks.html %}
</div>
<p class="caption"><b>Figure:</b>
benchmark times relative to C (smaller is better, C performance = 1.0), see [benchmarking](http://julialang.org/benchmarks/)
</p>
</div>

<a href="/images/ijulia.png"><img class="u-center" src="/images/ijulia.png" width="90%" /></a>

# What's next

Lots of things are planned for Julia 1.0. It's our first stable release, and it's coming out this year. Here are three big plans:
* What
* Is
* Planned?

# How you can help

Any help is welcome. Here's our [CONTRIBUTING.md](https://github.com/JuliaLang/julia/blob/master/CONTRIBUTING.md), and here are a few ideas to get started.

* Work on packages. There are lots of great projects that would like a hand:
    * [DifferentialEquations.jl](https://github.com/JuliaDiffEq/DifferentialEquations.jl), a unifying differential equations framework ([blog](http://www.stochasticlifestyle.com/6-months-differentialequations-jl-going/))
    * [Nemo.jl](http://nemocas.org/), a computer algebra system
    * [Juno](https://github.com/JunoLab/atom-julia-client/issues), the Atom-based IDE
    * [Turing.jl](https://github.com/yebai/Turing.jl), for probabilistic programming
    * ... lots more! Want your package listed here? Submit a PR!
* Take on a  project! We will run 6 positions as part of the [Google Summer of Code](http://julialang.org/soc/ideas-page). But we would love anyone to get their hands dirty for immortal glory. Here's three samples from the list.
    * [A Swirl-style tutorial for Julia](http://julialang.org/soc/ideas-page#swirl-style-tutorial)
    * [Improvements to the Plots.jl ecosystem](http://julialang.org/soc/ideas-page#improvements-to-the-plotsjl-ecosystem)
    * [Theme: Machine Learning Frameworks](http://julialang.org/soc/ideas-page#theme-machine-learning-frameworks)
* We could do with help swatting outstanding issues. Here are a few interesting categories:
    * The [intro-issue](https://github.com/JuliaLang/julia/labels/intro%20issue) category. Just get started!
    * Good at writing and explaining? Improving [docs](https://github.com/JuliaLang/julia/labels/doc) would help every user after you
    * [Parallel](https://github.com/JuliaLang/julia/labels/parallel) computing
    * LLVM-experts: we have open [codegen](https://github.com/JuliaLang/julia/labels/codegen) questions
    * [Linear algebra](https://github.com/JuliaLang/julia/labels/linear%20algebra)

More hands on deck are welcome anywhere. Star or fork Julia on [Github](https://github.com/JuliaLang/julia)!
