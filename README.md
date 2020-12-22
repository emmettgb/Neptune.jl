
This package is a fork of [Pluto.jl](https://github.com/fonsp/Pluto.jl) created by [Fons van der Plas](https://github.com/fonsp)
<br>
<br>

### Neptune

Neptune is a(n) (unauthorised) fork of the Notebook platform Pluto (Pluto was written by others who choose not to be named), for those (like Data Scientists) who have requirements which conflict with the reactive aspect of Pluto.   It is hope that Neptune is only an interim solution, and that the capabilities it enables will eventually exist within the Pluto, but that it is not certain.  Those with smaller applications or which do not load external scripts, and who are unfamiliar with Pluto should first try it.

_Writing a notebook is not just about writing the final document — Neptune empowers the experiments and discoveries that are essential to getting there._

**Explore models and share results** in a notebook that is

-   **_lightweight_** - Neptune is based on the package Pluto. Both are written in pure Julia and is easy to install.
-   **_simple_** - no hidden workspace state; friendly UI.
-   **_non-reactive_** - only executes the cells you choose (like Jupyter)

### Input

A Neptune notebook is made up of small blocks of Julia code (_cells_) and together they form a notebook.

Notebook cells can contain _arbitrary_ Julia code, and you can use external libraries. There are no code rewrites or wrappers, Neptune just looks at your code once before evaluation.

### Output

Like in Pluto, your notebooks are **saved as pure Julia files** ([sample](https://github.com/fonsp/Pluto.jl/blob/master/sample/Basic.jl)), which you can then import as if you had been programming in a regular editor all along. You can also export your notebook with cell outputs as attractive HTML and PDF documents. By reordering cells and hiding code, you have full control over how you tell your story (except for the reactivity, which is only available in Pluto).   Notebooks are intended to be fully compatible with Pluto.

<br >

### Interactivity

Your programming environment becomes interactive by splitting your code into multiple cells! Changing one cell only affects that cell, giving you a fast and fun way to experiment with your model in a piecewise manner.

<br >

# Let's do it!

### Ingredients

For one tasty notebook 🥞 you will need:

-   **Julia** v1.0 or above, _v1.5 is fastest_
-   **Linux**, **macOS** or **Windows**, _Linux and macOS will work best_
-   Mozilla **Firefox** or Google **Chrome**, be sure to get the latest version

### Installation


Run Julia and add the package:

```julia
julia> ]
(v1.5) pkg> add Neptune
```

_Using the package manager for the first time can take up to 15 minutes - hang in there!_

To run the notebook server:

```julia
julia> import Neptune
julia> Neptune.run()
```

Neptune will open in your browser, and you can get started!


### To developers

Follow [these instructions](https://github.com/compleathorseplayer/Neptune.jl/blob/master/CONTRIBUTING.md) to start working on the package.


## License

Neptune.jl is open source! Specifically, it is [MIT Licensed](https://github.com/compleathorseplayer/Neptune.jl/blob/master/LICENSE). 

Neptune.jl is built by gluing together open source software:

-   `Julia` - [license](https://github.com/JuliaLang/julia/blob/master/LICENSE.md)
-   `Pluto` - [license](https://github.com/codemirror/CodeMirror/blob/master/LICENSE
-   `CodeMirror` - [license](https://github.com/codemirror/CodeMirror/blob/master/LICENSE)
-   `HTTP.jl` - [license](https://github.com/JuliaWeb/HTTP.jl/blob/master/LICENSE.md)
-   `MsgPack.jl` - [license](https://github.com/JuliaIO/MsgPack.jl)
-   `msgpack-lite` - [license](https://github.com/kawanet/msgpack-lite/blob/master/LICENSE)
-   `observablehq/stdlib` - [license](https://github.com/observablehq/stdlib/blob/master/LICENSE)
-   `preact` - [license](https://github.com/preactjs/preact/blob/master/LICENSE)
-   `developit/htm` - [license](https://github.com/developit/htm/blob/master/LICENSE)
-   `MathJax` - [license](https://github.com/mathjax/MathJax-src/blob/master/LICENSE)

Your notebook files are _yours_, you do not need to credit us. Have fun!

## From the authors

We are happy to say that Neptune.jl runs smoothly for most users, and is **ready to be used in your next project**!

The Neptune project is an ambition to make Pluto more accessible to areas liks Data Science and Machine Learning. We agree with the developers of Pluto in the belief that scientific computing can be a lot simpler and more accessible. If you feel the same, give Neptune a try! We would love to hear what you think. 😊

Finally, we would like to thank Fons van der Plas for his work and talent in creating the beautiful project that is Pluto.jl, and to apologise for any conflicts with his vision.   There is no attempt to claim credit here - any successes you may have with Neptune are due to the great work of he and his co-developers on Pluto.

_Created by [**David Edelman**](https://github.com/compleathorseplayer) . Inspired by Pluto.jl_
