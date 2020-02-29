<center><h2>Topological Condensed matter: Lecture 28th February </h2></center>

#### Quick Summary
We are interested in the edge modes of the Graphene Nano Ribbon. A nano ribbon is a 2D structure in which the molecules extend infinitely in one of the directions and finite in the other. One more visualizations of the above is forming a chain of atoms(Periodic boundary conditions) in one of the directions and finite chain(Open boundary conditions) in the other direction.

#### Two kinds of Nano Ribbon

One of the ways to obtain the nano ribbon structure is to terminate of cut the Graphene in one direction of an extended Graphene layer. We can end up in two kinds of the structures:

- Zig Zag structure
- Arm Chair structure

![Zigzag_armchair](edge_structure.png)

The above image depicts the situation stated above. The fig (a) shows the directional dependence cutting choice of the Graphene structure. Depending on our two choices indicated by the Red and Green coloured path, we end up in Zig-zag structure (c) or Arm-Chair structure (d).

> **Aim:** We would like to obtain the energy spectrum and the edge states in the above two scenarios.

#### 1. Zig-Zag Structure
*The figure will be updated soon!*

The above figure indicates periodic boundary conditions in the $x$ direction and open boundary conditions in the $y$ direction. We consider finite chain of N unit cells in the $x$ direction.
Let us jot down the tight binding Hamiltonian:
$$ \mathcal{H} = -t\sum_{n_1=0}^{N-1}\sum_{n_2=0}^{N-1}|A_{n_1n_2}\rangle\langle B_{n_1,n_2}| + |A_{n_1n_2}\rangle\langle B_{n_1,n_{2}+1}| + |A_{n_1n_2}\rangle\langle B_{n_1-1,n_{2}+1}| + \text{h.c.}$$
The Hamiltonian is periodic with respect to $n_1$ variable, i.e., $|A/B_{N,n_2}\rangle = |A/B_{0,n_2}\rangle$.  Let us proceed to obtain the energy spectrum of the Hamiltonian. Since the Hamiltonian is periodic in the $x$ direction, we can use the Bloch's Theorem to fulfil our goals. We have, $$|k\rangle = \frac{1}{\sqrt{N}}\sum_m\left[\alpha_n|A_{m,n}\rangle + \beta_n|A_{m,n}\rangle\right]e^{ikm} $$
