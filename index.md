# Kai-Oliver Prott
This page gives an overview about me and my projects.

<style>
  @media screen and (min-width: 900px) {
    .grid-flex {
      -webkit-column-count: 2; 
      -moz-column-count: 2; 
      column-count: 2;
    }
    .grid-item-big {
      display: inline-block;
      width: 125%;
    }
    .grid-item-pic {
      display: inline-block; 
      float: right;
    }
    #kaiprott-pic {
      width: 250px;
    }
  }

  @media not screen and (min-width: 900px) {
    #kaiprott {
      width: auto; 
    }
  }
</style>
<div class="grid-flex">
  <div class="grid-item-big">
    <h2 id="about-me">About me</h2>
    <p>
I am working at the Kiel University as a PhD Student since November 2020 in the Department of Computer Science. 
My Research Group is "Programming Languages and Compiler Construction", where I am working under <a href="https://www.informatik.uni-kiel.de/~mh/">Prof. Dr. Michael Hanus</a>. 
You can find contact details at <a href="https://www.ps.informatik.uni-kiel.de/en/team/m-sc-kai-prott">my department page</a>.
    </p>
  </div>
  <div class="grid-item-pic">
   <img id="kaiprott-pic" src="https://raw.githubusercontent.com/Ziharrk/Ziharrk.github.io/main/Img.png">
  </div>
</div>

### Interests and Projects
I am interested in Functional programming (preferrably with Haskell) and compiler tooling.
In the past I have also worked a bit with Coq and on high-performance numerical computations with CPU and GPU.  

My current project is a plugin for GHC that adds an implicit monadic effect to a language. The tool aims to simplify development of research languages/DSLs and to provide a tight integration with Haskell. The project is currently unpublished (see below), but the github repository for the tool is available [here](https://github.com/cau-placc/ghc-language-plugin). 
Within this project I learned a lot about the internals of the Glasgow Haskell Compiler. 
I also contributed a small patch to GHC for an [itch](https://gitlab.haskell.org/ghc/ghc/-/issues/20671) that bothered me. 

### Publications 
- [Haskell⁻¹: automatic function inversion in Haskell](https://dl.acm.org/doi/10.1145/3471874.3472982) (2021, F. Teegen, K. Prott, N. Bunkenburg)
- Master's Thesis: [Extending the Glasgow Haskell Compiler for functional-logic Programs with Curry-Plugin](https://www.informatik.uni-kiel.de/~mh/lehre/abschlussarbeiten/msc/Prott.pdf) (2020, K. Prott)

Yet to be published: 
- A project on using a plugin to add an implicit monadic effect to Haskell code ([https://github.com/cau-placc/ghc-language-plugin](https://github.com/cau-placc/ghc-language-plugin)).
- A project on modeling Curry as a monad with memoization to increase runtime performance ([https://github.com/cau-placc/curry-monad](https://github.com/cau-placc/curry-monad)).

### Education 
- November 2020 - current: PhD Student at Kiel University in Computer Science
- October 2018 - October 2020: Studied at Kiel University -- Master of Science (Computer Science) -- Graduated with Grade 1.0.
- October 2015 - October 2018: Studied  at Kiel University -- Master of Science (Computer Science) -- Graduated with Grade 1.3.
 
## Teaching
- [WS22/23: Declarative programming (in german)](https://www.informatik.uni-kiel.de/~mh/lehre/deklprog22/)
- [WS22/23: Declarative programming languages (in german)](https://www.informatik.uni-kiel.de/~mh/lehre/dps22/)
- [WS21/22: Advanced Programming (in german)](https://www.informatik.uni-kiel.de/~mh/lehre/fortprog21/)
- SS21: Functional Programming
- [WS20/21: Advanced Programming (in german)](https://www.informatik.uni-kiel.de/~mh/lehre/fortprog20/)
- WS20/21: Concurrent and distributed programming
- WS19/20: Functional Programming
- [WS18/19: Advanced Programming (in german)](https://www.informatik.uni-kiel.de/~mh/lehre/fortprog18/)
