---
title: Cellular Automata
date: "2020-01-24"
description: "Implementing Rule 30 in Web Assembly"
---

# Implementating [Rule 30](https://en.wikipedia.org/wiki/Rule_30) in Web Assembly

## Background

[Mike](https://www.myoldgoat.com/), a colleague of mine, recently mentioned Web Assembly to me. It's something that first showed up on the scene in 2017, and is the fourth and newest language to run in your internet browser, along with HTML, CSS, and JS. 

Web Assembly (Wasm) is a [compiled language](https://en.wikipedia.org/wiki/Compiled_language). Unlike an [interpreted language](https://en.wikipedia.org/wiki/Interpreted_language) like Python or Javascript, Wasm can take advantage of size and time efficient execution. People on the internet are telling me I can do cool things because of that, so I want to figure out a small tutorial for myself. 

### Web Assembly

https://webassembly.org/

https://en.wikipedia.org/wiki/WebAssembly


### Cellular Automata

They're these freaky complex systems built out of tiny, simple cellular agents. A cellular automaton can be thought of like a zero-player game, where the starting position of the game is the only part that matters, and each turn the cells in the game change based on a set of rules.

https://www.youtube.com/watch?v=DKGodqDs9sA

https://en.wikipedia.org/wiki/Cellular_automaton

Famous cellular automata:

[The Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life) - Implemented here: https://bitstorm.org/gameoflife/
    
[Rule 30](https://en.wikipedia.org/wiki/Rule_30)

Bonus Reading:

[Wolfram's A New Kind of Science](https://www.wolframscience.com/nks/chap-3--the-world-of-simple-programs/)

### The Exercise 

I found a [tutorial](https://rustwasm.github.io/book/introduction.html) that implements [Conway's Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life) in [Rust](https://www.rust-lang.org/) and compiles that into Wasm.

Rather than following the recipe directly, I figured I'd spice it up. Instead, I will be implementing [Rule 30](https://en.wikipedia.org/wiki/Rule_30), a different cellular automaton.






