# The Unigrid network orange paper

*Unigrid: The Next Internet Revolution - A decentralized, encrypted network
for storage, bandwidth and, in time, compute - © 2021-2026 Stiftelsen The
Unigrid Foundation*

The orange paper is the non-technical companion to the Unigrid white paper.
It describes the problems of today's centralized Internet, how the Unigrid
network addresses them with gridnodes, side chains and sharded, encrypted
storage, the market the network enters, its tokenomics and economic model,
and the roadmap of what has been delivered and what comes next.

The paper follows the network as it is built. Features that are not yet part
of the node software are described as planned, and the paper is updated
together with the implementation.

## Reading the paper

Each version of the paper is published as a PDF under
[Releases](https://github.com/unigrid-project/documentation-orange-paper/releases).

## Building the paper

The paper is written in LaTeX and needs TeX Live and Inkscape. The version
and date on the title page come from git, written by the hooks in
`.githooks`:

```sh
git config core.hooksPath .githooks
sh .githooks/post-checkout
pdflatex -shell-escape unigrid-orangepaper.tex
```

Run `pdflatex` three times to resolve the references.

## Further reading

For a technical description of how the network functions, see the
[Unigrid white paper](https://github.com/unigrid-project/documentation-white-paper).
