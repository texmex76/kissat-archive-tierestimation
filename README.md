[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Kissat-Archive-Tierestimation
=====================

This is a modified version of the kissat SAT solver. We introduce an *archive* where we store deleted clauses. After propagation, if we have found no conflict, we go over the archive and see if we had gotten a conflict using deleted clauses. That way, we can evaluate clause deletion strategies.

Run `./configure && make test` to configure, build and test in `build`.

Binaries are provided with each major [release](https://github.com/arminbiere/kissat/releases/).

You can get more information about Kissat in the last solver description for the SAT Competition 2024:

<p>
<a href="https://cca.informatik.uni-freiburg.de/biere/index.html#publications">Armin Biere</a>,
<a href="/biere/index.html">Tobias Faller</a>,
Katalin Fazekas,
<a href="https://cca.informatik.uni-freiburg.de/fleury/index.html">Mathias Fleury</a>,
Nils Froleyks
and
<a href="https://cca.informatik.uni-freiburg.de/pollittf.html">Florian Pollitt</a>
<br>
<a href="https://cca.informatik.uni-freiburg.de/papers/BiereFallerFazekasFleuryFroleyksPollitt-SAT-Competition-2024-solvers.pdf">CaDiCaL, Gimsatul, IsaSAT and Kissat Entering the SAT Competition 2024</a>
<br>
<i>Proc.&nbsp;SAT Competition 2024: Solver, Benchmark and Proof Checker Descriptions</i>
<br>
Marijn Heule, Markus Iser, Matti J&auml;rvisalo, Martin Suda (editors)
<br>
Department of Computer Science Report Series B
<br>
vol.&nbsp;B-2024-1,
pages 8-10,
University of Helsinki 2024
<br>
[ <a href="https://cca.informatik.uni-freiburg.de/papers/BiereFallerFazekasFleuryFroleyksPollitt-SAT-Competition-2024-solvers.pdf">paper</a>
| <a href="https://cca.informatik.uni-freiburg.de/papers/BiereFallerFazekasFleuryFroleyksPollitt-SAT-Competition-2024-solvers.bib">bibtex</a>
| <a href="https://github.com/arminbiere/cadical">cadical</a>
| <a href="https://github.com/arminbiere/kissat">kissat</a>
| <a href="https://github.com/arminbiere/gimsatul">gimsatul</a>
| <a href="https://cca.informatik.uni-freiburg.de/sat24medals">medals</a>
]
</p>

See [NEWS.md](NEWS.md) for feature updates.
