# AA228V/CS238V: Validation of Safety-Critical Systems
[![website](https://img.shields.io/badge/website-Stanford-b31b1b.svg)](https://aa228v.stanford.edu/)
[![textbook](https://img.shields.io/badge/textbook-MIT%20Press-0072B2.svg)](https://algorithmsbook.com/validation/)

<p align="center"> <img src="./media/coverart.svg"> </p>

**Winter 2025 teaching team**:
- Sydney Katz: [@smkatz12](https://github.com/smkatz12)
- Mykel Kochenderfer: [@mykelk](https://github.com/mykelk)
- Robert Moss: [@mossr](https://github.com/mossr)
- Harrison Delecki: [@hdelecki](https://github.com/hdelecki)
- Francois Chaubard: [@fchaubard](https://github.com/fchaubard)
- Sidharth Tadeparti: [@sidt36](https://github.com/sidt36)

# Projects
- **[Project 0](./projects/project0)** — _A light-weight introduction to falsification._
- **[Project 1](./projects/project1)** — _Efficiently finding the most-likely failure._
- **[Project 2](./projects/project2)** — _TODO._
- **[Project 3](./projects/project3)** — _TODO._

# Installation
For additional installation help, [please post on Ed](https://edstem.org/us/courses/69226/discussion).

## Install `git`
- https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

## Install Julia
**Requires Julia 1.11+**: https://julialang.org/downloads/

- Windows users:
    ```
    winget install julia -s msstore
    ```
- Linux/macOS users:
    ```
    curl -fsSL https://install.julialang.org | sh
    ```

This will give you the `julia` command in your terminal.

## Install Packages
1. Clone this git repo:
    1. Open a terminal and navigate to where you want the code to live.
    1. Run:
        ```
        git clone https://github.com/sisl/AA228V.jl
        ```
1. Navigate to the code: `cd AA228V.jl`
1. Open Julia: `julia`
1. In the Julia REPL, go into pkg mode: `]`
1. Add **Pluto** and **PlutoUI** in pkg mode:
    ```
    add Pluto PlutoUI
    ```
1. Add the **AA228V** package in pkg mode:
    ```
    dev .
    ```

## Update AA228V (if necessary)
- Open a terminal and navigate to your "AA228V.jl" directory.
- Run: `git pull`
