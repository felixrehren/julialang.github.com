---
layout: default
title:  Julia for new Contributors
---

Julia: a fresh approach to technical computing.
Now at version 0.6-dev. Next stop: v1.0!

This page is a 60 second guide to get you started for taking part and pitching in.

# Features of Julia

* **Optional typing** lets you annotate code with logic, and allows blazing-fast compiler optimization!
* **Multiple dispatch** lets you write flexible, intuitive function definitions according to argument types [new logic for this in 0.6!)
* You can run scripts, work/play interactively, or write beautiful notebooks
* It's **fast**. As fast as we can push it. We compete with C, Fortran and Matlab
* **Everything is first class** and you can easily inspect and generate your own code with the power of macros
* **Dogfooding**: almost all the Julia-internals are written in Julia!
* A super strong **package ecosystem**
* Ability to call C and Python inline
* [NEW IN v0.5] **Vectorisation** made easy with `f.()` as syntax for vectorised `f()`. Easy parallelization available too ...
* And, finally, a brilliant **community** that welcomes contributors! Ask anything on [Discourse](https://discourse.julialang.org/), for us on [Github](https://github.com/JuliaLang/julia)

<div class="figure">
<div class="cs-benchmark-table">
{% include benchmarks.html %}
</div>
<p class="caption"><b>Figure:</b>
benchmark times relative to C (smaller is better, C performance = 1.0).
</p>
</div>

If you've seen Julia before, check out what we achieved in [2016's version 0.5](http://julialang.org./blog/2016/10/julia-0.5-highlights). There's more to come for Julia. Much more!

## Have a go on [Juliabox.com](https://www.juliabox.com/)
<a href="/images/ijulia.png"><img class="u-center" src="/images/ijulia.png" width="90%" /></a>

# What's next for Julia

Lots of things are planned for Julia 1.0. It's our first stable release, and it's coming out this year. Here are three big things planned for 1.0.
* What
* Is
* Planned?

# How you can help!

* Work on packages. There are lots of great projects that would like a hand:
    * [DiffEq.jl](https://github.com/JuliaDiffEq/DifferentialEquations.jl), a unifying differential equations framework
    * [Optim.jl](https://github.com/JuliaOpt/Optim.jl), a unifying package for optimization
    * [Nemo.jl](http://nemocas.org/), a unifying pure maths and algebra package
    * ...
* Take on a  project! We will run 6 positions as part of the [Google Summer of Code](http://julialang.org/soc/ideas-page). But we would love anyone to get their hands dirty for immortal glory. Here's three samples from the list.
    * [A Swirl-style tutorial for Julia](http://julialang.org/soc/ideas-page#swirl-style-tutorial)
    * [Improvements to the Plots.jl ecosystem](http://julialang.org/soc/ideas-page#improvements-to-the-plotsjl-ecosystem)
    * [Theme: Machine Learning Frameworks](http://julialang.org/soc/ideas-page#theme-machine-learning-frameworks)
* We could do with help swatting outstanding issues. Here are a few interesting categories:
    * The [intro-issue](https://github.com/JuliaLang/julia/labels/intro%20issue) category. Just get started!
    * Good at writing and explaining? Improving [docs](https://github.com/JuliaLang/julia/labels/doc) would help every user after you
    * [Parallel](https://github.com/JuliaLang/julia/labels/parallel) computing
    * **LLVM**-experts: we have open [codegen](https://github.com/JuliaLang/julia/labels/codegen) questions
    * [Linear algebra](https://github.com/JuliaLang/julia/labels/linear%20algebra) is a big one
    * We would welcome more hands on deck anywhere. Star or fork Julia on [Github](https://github.com/JuliaLang/julia)!

Here's our [CONTRIBUTING.md](https://github.com/JuliaLang/julia/blob/master/CONTRIBUTING.md)
