---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% include base_path %}

I work on quantum gravity, using the gravitational path integral as a window into
the quantum-mechanical structure of spacetime. One thread runs through most of my
work: in gravity, entropy is computed by geometry. The Ryu-Takayanagi/HRT formula
equates an entanglement entropy with the area of a surface; generalized entropy
and gravitational Rényi entropies behave similarly. Why a geometric quantity
should know about quantum information, and what Hilbert space and algebra of
observables that entropy actually belongs to, is the question I keep returning to.

## Real-time gravitational path integrals

Replica-wormhole computations are conventionally Euclidean, which makes them
hostage to a difficult question: which contour is one really integrating over?
With collaborators I developed a real-time, Lorentz-signature formulation of
replica wormholes, including the
[variational principle that defines its saddle points](https://arxiv.org/abs/2012.00828)
and [explicit low-dimensional examples](https://arxiv.org/abs/2105.07002) in JT
gravity and holographic 2D CFTs. These saddles necessarily involve complex
metrics, reached by deforming the original real contour, yet the construction
need not rely on analytic continuation — so it applies even with non-analytic
boundary sources. More recently I have shown that the same Rényi entropies and
complex geometries can be
[read directly off the bulk quantum wavefunction](https://arxiv.org/abs/2409.17428),
which is insensitive to the subtleties of defining the Euclidean path integral
and consistent with many different choices of contour.

This machinery has consequences for unitarity. When a saddle preserves both
replica and conjugation symmetry, its replica-invariant "splitting surface" turns
out to be causally inaccessible from the boundary domain of dependence whose
entropy it computes, which forces gravitational Rényi entropies to be
[independent of the choice of Cauchy slice and of boundary sources](https://arxiv.org/abs/2106.07835)
— a hallmark of unitary evolution in any dual field theory.

## Gravitational entropy from algebras and Hilbert spaces

If the HRT formula is really an entropy, it should be the entropy of *something*.
I have argued that it is, and that one need not assume a holographic dual to see
it: from a Euclidean gravitational path integral satisfying a short list of
largely familiar axioms, one can
[construct Hilbert spaces and type I von Neumann algebras](https://arxiv.org/abs/2310.02189)
that are commutants of one another, one for each asymptotic boundary, together with entropies on them that reduce to the
quantum-corrected RT formula semiclassically. Positivity of the inner product
then quantizes the entropy of any projection in the form ln N. Because the axioms
constrain UV bulk structure only weakly, the argument plausibly applies to string
field theory, spin foams, or any other UV completion.

One axiom — a trace inequality mirroring Tr(AB) ≤ Tr(A)Tr(B) on the CFT side — is
substantive enough to deserve its own treatment. I have
[argued it holds to all orders in the semiclassical expansion](https://arxiv.org/abs/2309.02497),
modulo a conjectured property of the classical gravitational action that amounts
to a new positive action conjecture, proven for JT gravity.

More recently I have been studying
[gravitational algebras on spacetimes with two extremal surfaces](https://arxiv.org/abs/2512.04435),
where the split property yields type II algebras via the crossed product in the
left exterior, the right exterior, and the intervening "python's lunch" region.
Keeping only the area sum or the area difference — achieved by choosing the right
microcanonical ensemble — gives algebras that are type II or type III depending on
the region. In the area-difference case the crossed product produces a weight for which
*differences* of relative entropies reproduce differences of generalized entropies —
an algebraic reading of the order parameter controlling entanglement-wedge phase
transitions.

## Fixed-area states and the geometry of entanglement

Fixed-area states — holographic states in which the HRT area is constrained to a
narrow window — are a useful probe of gravity beyond leading semiclassical order.
Decomposing a general holographic state into them — and conjecturing that a
certain "diagonal approximation" holds — produces a correction of order
G<sup>-1/2</sup> near RT phase transitions, parametrically larger than bulk
entanglement corrections and
[large enough to turn the "phase transition" into a smooth crossover](https://arxiv.org/abs/2006.10089).
I have also studied the Lorentzian spacetime geometry
[intrinsic to such states](https://arxiv.org/abs/2203.04973), which is real and
free of conical singularities but develops power-law curvature divergences along
null congruences from the fixed-area surface — suggesting these states are
well-defined quantum mechanically only when the surface is smeared.

On the more geometric side, I introduced
[restricted maximin surfaces](https://arxiv.org/abs/1901.03879) to extend the
existence theorem for HRT surfaces to generic charged and spinning AdS black
holes, whose mass-inflation singularities the original maximin argument could not
handle.

## Wormholes, factorization, and what they are really telling us

Euclidean wormholes appear to spoil factorization, and much of my recent work asks
how seriously to take that. In
[*Wormholes as red herrings*](https://arxiv.org/abs/2607.01322) my collaborator and
I prove a reconstruction theorem: unitary quantum field theories are determined up
to unitary isomorphism by their closed-manifold partition functions, and every
reflection-positive partition function comes from a unitary QFT. Read
gravitationally, this makes apparent Hilbert-space non-factorization an artifact
of restricting to an incomplete spectrum of charged states — a direct analog of
Coleman's argument that the partition-function version is a red herring.

Whether particular wormholes even contribute is a separate question, and the
answer is sensitive to details. Using a real Lorentzian contour, Euclidean axion
wormholes turn out to be
[subdominant to a UV-sensitive endpoint contribution](https://arxiv.org/abs/2601.02507),
becoming dominant only when the asymptotic axion value is taken near the negative
imaginary axis, and failing to contribute at all in the upper half plane. For real
positive values the saddle sits on a Stokes line, where its relevance is a matter
of convention. Applying the same methods to the seemingly analogous
[JT wormholes with imaginary scalars](https://arxiv.org/abs/2601.09932), by
contrast, finds that those *do* dominate.

Wormholes also reshape the state space itself. In a
[topological toy model forced to evolve in time](https://arxiv.org/abs/2405.04571),
non-perturbative effects make the true number of states far smaller than
perturbation theory predicts, and generic operator insertions can make time
evolution depart dramatically from semiclassical expectations even when no quantum
extremal surface exists. In a more geometric setting, 3D wormholes with
[end-of-the-world branes, conical defects, kinks, and punctures](https://arxiv.org/abs/2504.12278)
compute statistical averages over ensembles of boundary CFTs, matching universal
OPE asymptotics from the conformal bootstrap. Earlier, I showed that the
Gao-Jafferis-Wall mechanism extends to
[multi-boundary wormholes](https://arxiv.org/abs/2012.04635) in AdS<sub>3</sub>:
in the hot limit, where the causal shadow becomes exponentially small, a
double-trace deformation can make any two asymptotic regions mutually traversable,
even at different temperatures and angular momenta.

## Quantum information in many-body systems

Some of these questions have analogs with no gravity in them at all. In recent
work I study
[approximate quantum error-correcting codes realized at the chiral edges of 2D
topologically ordered phases](https://arxiv.org/abs/2608.06258), which combine a
gapped bulk with a gapless edge CFT and avoid the fine-tuning to criticality that
CFT codes normally require. Relating coherent-information loss under erasure to a
relative entropy reduces recoverability to universal edge-theory data and yields
power-law scaling with the size of the erased region.

## Other work

I have also examined holographic complexity, showing that for multi-boundary
AdS<sub>3</sub> wormholes both the CV and CA proposals give a complexity,
measured relative to copies of the massless BTZ black hole, proportional to the
central charge times the Euler character of the bulk time-symmetric surface. The
coefficient is independent of temperature and of the moduli controlling the
geometry inside the black hole; compared against the known structure of the dual
CFT states in the hot wormhole limit, this implies that
[any CFT gate set defining either complexity cannot be local](https://arxiv.org/abs/1801.01137);
and constructed
[folded spinning strings coupled to gravity in AdS<sub>3</sub>](https://arxiv.org/abs/2203.02492),
whose leading Regge trajectory terminates at a maximal spin where the solution
approaches an extremal rotating BTZ black hole.

A complete list of papers is on the [publications page]({{ base_path }}/publications/).
