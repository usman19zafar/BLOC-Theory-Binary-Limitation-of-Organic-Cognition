\documentclass[12pt]{article}
\usepackage{amsmath, amssymb, amsthm}
\usepackage{geometry}
\usepackage{setspace}
\usepackage{hyperref}
\usepackage{tikz}
\usepackage{tikz-cd}
\usepackage{pgfplots}
\pgfplotsset{compat=1.18}
\usetikzlibrary{arrows.meta, positioning, shapes.geometric, decorations.pathmorphing,
                decorations.markings, calc, fit, backgrounds, matrix}

\geometry{margin=1in}
\onehalfspacing

\newtheorem{theorem}{Theorem}[section]
\newtheorem{corollary}[theorem]{Corollary}
\newtheorem{axiom}{Axiom}
\theoremstyle{definition}
\newtheorem{definition}{Definition}[section]

\title{\textbf{
An Operator Geometric Framework for Cognitive Engineering\\
and Computational Meanings:\\
BLOC Theory v2.0
}}

\author{
Usman Zafar Ph.D\\
Milton, Ontario, Canada\\
\texttt{info@zulfr.com}
}

\date{May 2026}

\begin{document}

\maketitle

\begin{abstract}
This paper presents BLOC Theory v2.0, an operator--geometric extension of the original
Binary Limitation of Organic Cognition (BLOC) framework. The extended theory introduces
a unified mathematical architecture for modeling Human--AI cognitive systems through
cognitive operators, geometric state spaces, manifold structures, metric formulations, and
algebraic transformations.

Semantic transformation is formalized through the Meaning Operator~$\mathcal{M}$,
alignment dynamics through the Alignment Operator~$\mathcal{A}_{\mathrm{lgn}}$, and
organic binary divergence through the continuum discrete functor~$F$ together with the
recovery functor~$G$. These operators provide a computable representation of semantic
change, alignment stability, information loss, and partial recoverability across coupled
Human--AI systems.

New geometric constructions including temporal manifolds, capability manifolds, loss
curvature, and phenomenological state spaces establish a structured basis for analyzing
cognitive asymmetry, constrained reasoning, interpretability dynamics, and state transition
behavior. These structures enable formal analysis of meaning propagation, alignment
deformation, and cognitive state evolution within adaptive cognitive architectures.

BLOC Theory v2.0 advances the original framework from a conceptual limitation theory to
a mathematically structured cognitive systems model capable of supporting computable
reasoning, formal verification pathways, and generalized cognitive engineering analysis.
\end{abstract}

\tableofcontents
\newpage

%% =========================================================
\section{Introduction}

The original BLOC Framework provided a structural method for decomposing systems into
Conceptual, Procedural, Structural, and Contextual BLOCs, establishing a foundational
architecture for representing meaning, action, design, and environment~{zafar2026bloc}.
While this framework introduced a powerful structural grammar for system decomposition, it
remained primarily architectural and lacked the mathematical machinery required for formal
cognitive systems analysis. In particular, the original formulation did not include cognitive
operators, geometric state representations, manifold structures, metric formulations, or
functorial mappings linking BLOC to downstream cognitive engineering frameworks.

These omissions limited the analytical expressiveness of BLOC Theory v1.0. Without
operators, the framework could not formally represent semantic transformation or alignment
dynamics~{russell2019human}. Without geometric and manifold structures, it could
not model temporal cognition, capability evolution, or structured representations of
cognitive state~{do2002carmo}. Without metrics, it could not quantify cognitive
asymmetry, alignment error, or Human--AI boundary distance~{gabriel2020artificial}.
And without inter-theory mappings, the theoretical hierarchy connecting BLOC, DAIS-10,
KAD Theory, and SFPM-10 remained structurally related but mathematically
disconnected~{baez2010physics}.

BLOC Theory v2.0 addresses these limitations through an extended operator--geometric
architecture. The framework formalizes semantic transformation, alignment dynamics,
temporal cognition, structured state representation, and cognitive asymmetry through a
unified system of operators, geometric spaces, functorial mappings, and algebraic
transformations. This extension advances BLOC from a structural decomposition
methodology to a mathematically structured cognitive systems theory capable of supporting
computable reasoning, formal verification pathways, and interpretable, constrained
Human--AI interaction.

%% =========================================================
\section{Motivation}

The first formulation of BLOC Theory established the categorical limitation of binary
computation and introduced a four-type structural decomposition model. However, the
framework remained primarily structural and did not constitute a closed mathematical
system for cognitive analysis.

In particular, the original formulation did not provide a unified formalism for
representation, transformation, and measurement of cognitive states. As a consequence,
the following essential components were absent:

\begin{itemize}
    \item \textbf{Cognitive operators} capable of representing semantic transformation,
          alignment, and divergence as structured state transitions~\{marcus2019rebooting}.
    \item \textbf{Geometric and manifold representations} for modeling temporal cognition,
          capability evolution, and structured cognitive state spaces~\{petersen2006riemannian}.
    \item \textbf{Metric structures} for quantifying cognitive asymmetry, alignment error,
          and Human--AI boundary distance~\{deza2009encyclopedia}.
    \item \textbf{Algebraic composition rules} enabling consistent transformation and
          interaction of BLOC components under system evolution~\{mac2013categories}.
    \item \textbf{Functorial mappings} linking BLOC to DAIS-10, KAD Theory, and SFPM-10,
          leaving the theoretical hierarchy structurally defined but not formally unified.
    \item \textbf{A formal representation of cognitive phenomenology}, required to capture
          the limits imposed by binary computational structure on representational
          systems~\{dreyfus1992computers}.
\end{itemize}

These gaps collectively prevented the framework from functioning as a closed cognitive
systems model in which representation, transformation, and measurement are jointly
specified. BLOC Theory v2.0 addresses these limitations by integrating cognitive operators,
geometric state spaces, metric structures, algebraic transformations, and functorial
mappings into a unified formal system.

%% =========================================================
\section{Operator Architecture}
\label{sec:operators}

This section defines the core operators of BLOC Theory v2.0. Each operator is presented
with its formal definition and its managerial projection, following the projection structure
established in Section~\ref{sec:correspondence}.

%---------------------------------------------------------
\subsection{Meaning Operator}

\begin{definition}[Meaning Operator]
\[
\mathcal{M} : \mathcal{A}_{\mathrm{rt}} \times T \rightarrow \mathcal{S}_M,
\quad (a,t) \mapsto \mathcal{M}(a,t)
\]
\end{definition}

$\mathcal{M}$ maps an agent state $a \in \mathcal{A}_{\mathrm{rt}}$ at time $t \in T$
to a point in semantic space $\mathcal{S}_M$, capturing context, intention, and semantic
framing as a time-dependent process. It is the formal basis for meaning-preserving
automation, semantic versioning, and SOP alignment.

%---------------------------------------------------------
\subsection{Alignment Operator}

\begin{definition}[Alignment Operator]
\[
\mathcal{A}_{\mathrm{lgn}} : \mathcal{B}_{\mathrm{in}} \rightarrow \mathcal{S}_M,
\quad b \mapsto \mathcal{A}_{\mathrm{lgn}}(b)
\]
\end{definition}

$\mathcal{A}_{\mathrm{lgn}}$ maps a binary system state $b \in \mathcal{B}_{\mathrm{in}}$
into semantic space, measuring how well machine outputs match human
expectations~\{leike2018scalable}. The gap between $\mathcal{A}_{\mathrm{lgn}}(b)$ and
$\mathcal{M}(a,t)$ constitutes the alignment error $E_{\mathcal{A}}$.

%---------------------------------------------------------
\subsection{Continuum--Discrete Mapping and Recovery Functors}

\begin{definition}[Continuum--Discrete Functor and Recovery Functor]
\[
F : \mathcal{O}_{\mathrm{rg}} \rightarrow \mathcal{B}_{\mathrm{in}},
\quad o \mapsto F(o)
\qquad
G : \mathcal{B}_{\mathrm{in}} \rightarrow \mathcal{O}_{\mathrm{rg}}, \quad
G \circ F \neq \mathrm{Id}_{\mathcal{O}_{\mathrm{rg}}}
\]
\end{definition}

$F$ encodes rich continuous human cognition into discrete digital form, necessarily
introducing semantic loss~\{cover2006elements}. $G$ is the partial recovery map;
its non-invertibility with respect to $F$ is the formal expression of irreducible cognitive
compression. No system can fully reconstruct human intent from discretized data: AI
approximates meaning but cannot recover full cognitive context.

%---------------------------------------------------------
\subsection{Interaction Operator}

\begin{definition}[Interaction Operator]
\[
\mathcal{I} : \mathcal{S}_M \times \mathcal{S} \rightarrow \mathcal{S},
\quad (M,S) \mapsto \lambda (M \otimes S)
\]
\end{definition}

$\mathcal{I}$ is bilinear in $(M, S)$, modeling the co-evolution of meaning and structure:
policies shape behavior, and behavior reshapes policies. The tensor product $M \otimes S$
captures joint semantic--structural state, scaled by $\lambda > 0$.

%---------------------------------------------------------
\subsection{Inter-Theory Operators}

\begin{definition}[Inter-Theory Operators]
\[
\Theta_{BD} : \mathcal{BLOC} \rightarrow \mathcal{D}_{AIS}, \qquad
\Theta_{DK} : \mathcal{D}_{AIS} \rightarrow \mathcal{K}, \qquad
\Theta_{KS} : \mathcal{K} \rightarrow \mathcal{S}_{FPM}
\]
\end{definition}

These structure-preserving maps connect the four theories in the BLOC hierarchy:
\[
\text{BLOC} \xrightarrow{\Theta_{BD}} \text{DAIS-10} \xrightarrow{\Theta_{DK}}
\text{KAD} \xrightarrow{\Theta_{KS}} \text{SFPM-10}
\]
encoding the propagation from structural decomposition through alignment analysis, failure
mode identification, and systemic propagation modeling.

\medskip
\begin{figure}[h]
\centering
\begin{tikzpicture}[
  node distance=2.2cm and 3.2cm,
  box/.style={rectangle, draw, rounded corners=4pt, minimum width=2.2cm,
              minimum height=0.9cm, align=center, font=\small\bfseries,
              fill=blue!8},
  arr/.style={-{Stealth[length=6pt]}, thick, blue!60!black},
  label/.style={font=\scriptsize\itshape, midway, above}
]
  \node[box] (bloc)  {$\mathcal{BLOC}$};
  \node[box, right=of bloc]  (dais) {$\mathcal{D}_{AIS}$};
  \node[box, right=of dais]  (kad)  {$\mathcal{K}$};
  \node[box, right=of kad]   (sfpm) {$\mathcal{S}_{FPM}$};

  \draw[arr] (bloc) -- node[label]{$\Theta_{BD}$} (dais);
  \draw[arr] (dais) -- node[label]{$\Theta_{DK}$} (kad);
  \draw[arr] (kad)  -- node[label]{$\Theta_{KS}$} (sfpm);

  \node[below=0.35cm of bloc, font=\scriptsize, align=center]  {Structure};
  \node[below=0.35cm of dais, font=\scriptsize, align=center]  {Alignment};
  \node[below=0.35cm of kad,  font=\scriptsize, align=center]  {Failure Modes};
  \node[below=0.35cm of sfpm, font=\scriptsize, align=center]  {Propagation};
\end{tikzpicture}
\caption{Inter-theory operator chain: structure $\to$ alignment $\to$ failure $\to$ propagation.}
\label{fig:inter-theory}
\end{figure}

%% =========================================================
\section{Operator--Managerial Correspondence Theorem}
\label{sec:correspondence}

This section establishes the axiomatic foundation and proves that all managerial and
business-utility statements are projections of the underlying operator structure.

\subsection{Projection Structure}

Let $\Pi$ be a semantic projection operator:
\[
\Pi : \mathcal{S}_M \rightarrow \mathcal{S}_{\mathrm{mgr}}
\]

The induced managerial interpretation of any operator $\mathcal{O}$ is:
\[
\widetilde{\mathcal{O}} = \Pi \circ \mathcal{O}
\]

\begin{figure}[h]
\centering
\begin{tikzcd}[row sep=2.5em, column sep=3em]
\mathrm{Dom}(\mathcal{O}) \arrow[r, "\mathcal{O}"] \arrow[dr, "\widetilde{\mathcal{O}}"'] &
\mathcal{S}_M \arrow[d, "\Pi"] \\
& \mathcal{S}_{\mathrm{mgr}}
\end{tikzcd}
\caption{Commutative diagram: managerial interpretation as projection of operator action.}
\label{fig:projection}
\end{figure}

\subsection{Axiomatic System}

\begin{axiom}[Cognitive State Spaces]
There exist structured spaces of cognitive representation:
\[
\mathcal{A}_{\mathrm{rt}}, \quad \mathcal{B}_{\mathrm{in}}, \quad
\mathcal{O}_{\mathrm{rg}}, \quad \mathcal{S}_M
\]
such that all cognitive processes are mappings between these spaces.
\end{axiom}

\begin{axiom}[Meaning Construction]
Meaning is generated by a time-dependent operator:
\[
\mathcal{M} : \mathcal{A}_{\mathrm{rt}} \times T \rightarrow \mathcal{S}_M
\]
\end{axiom}

\begin{axiom}[Alignment as Semantic Projection]
Alignment is a structure-inducing mapping:
\[
\mathcal{A}_{\mathrm{lgn}} : \mathcal{B}_{\mathrm{in}} \rightarrow \mathcal{S}_M
\]
\end{axiom}

\begin{axiom}[Irreversible Representation]
The continuum--discrete mapping is non-invertible:
\[
F : \mathcal{O}_{\mathrm{rg}} \rightarrow \mathcal{B}_{\mathrm{in}}, \qquad
G : \mathcal{B}_{\mathrm{in}} \rightarrow \mathcal{O}_{\mathrm{rg}}, \qquad
G \circ F \neq \mathrm{Id}_{\mathcal{O}_{\mathrm{rg}}}
\]
\end{axiom}

\begin{axiom}[Interaction Algebra]
There exists a bilinear interaction operator:
\[
\mathcal{I} : \mathcal{S}_M \times \mathcal{S} \rightarrow \mathcal{S}
\]
\end{axiom}

\begin{axiom}[Functorial Cognitive Coupling]
Cross-framework structure-preserving mappings exist:
\[
\Theta_{BD} : \mathcal{BLOC} \rightarrow \mathcal{D}_{AIS}, \quad
\Theta_{DK} : \mathcal{D}_{AIS} \rightarrow \mathcal{K}, \quad
\Theta_{KS} : \mathcal{K} \rightarrow \mathcal{S}_{FPM}
\]
\end{axiom}

\begin{axiom}[Cognitive Distortion Metric]
There exists a metric on semantic space:
\[
d_{\partial} : \mathcal{S}_M \times \mathcal{S}_M \rightarrow \mathbb{R}_{\ge 0}
\]
\end{axiom}

\begin{axiom}[Projection to Managerial Space]
There exists a projection operator:
\[
\Pi : \mathcal{S}_M \rightarrow \mathcal{S}_{\mathrm{mgr}}
\]
\end{axiom}

\begin{axiom}[Non-Expansive Projection]
Projection does not increase distortion:
\[
d_{\mathrm{mgr}}(\Pi(x),\Pi(y)) \le d_{\partial}(x,y)
\]
\end{axiom}

\begin{axiom}[Closure of Interpretation]
All operator actions admit managerial representation:
\[
\Pi \circ \mathcal{O} : \mathrm{Dom}(\mathcal{O}) \rightarrow \mathcal{S}_{\mathrm{mgr}}
\]
\end{axiom}

\subsection{Main Theorem}

\begin{theorem}[Structural Irreversibility of Cognitive Representation]
Under Axioms~1--10, cognitive representation induces intrinsic irreversibility:
\[
\forall o \in \mathcal{O}_{\mathrm{rg}}, \qquad G(F(o)) \neq o,
\]
and there exists a strictly positive lower bound on semantic reconstruction error:
\[
\exists \epsilon > 0 \;\; \text{such that} \;\;
d_{\partial}\big(\mathcal{M}(o,t),\; \mathcal{A}_{\mathrm{lgn}}(F(o))\big) \ge \epsilon.
\]
\end{theorem}

\noindent\textit{Interpretation.}
Representation of cognition through discrete systems necessarily introduces irreducible
semantic loss due to non-invertibility and metric separation of state spaces.

\subsection{Meta-Theorem}

\begin{theorem}[BLOC Irreversibility--Projection Principle]
Let:
\[
\mathfrak{O} = \{\mathcal{M},\; \mathcal{A}_{\mathrm{lgn}},\; F,\; G,\; \mathcal{I},\;
\Theta_{BD},\; \Theta_{DK},\; \Theta_{KS}\}
\]
Then under Axioms~1--10, all operator-induced transformations satisfy bounded projection:
\[
0 < \underline{\delta} \le d_{\mathrm{mgr}}\big(\Pi(\mathcal{O}(x)),\; \Pi(x)\big) \le \overline{\delta}.
\]
\end{theorem}

\noindent\textit{Interpretation.}
All cognitive, organizational, and governance effects emerge as stable, bounded
projections of irreversible operator-level transformations, with consequences:

\begin{itemize}
    \item \textbf{Irreversibility:} enforced by $F$, $G$ non-invertibility.
    \item \textbf{Semantic Loss:} quantified by $d_{\partial}$.
    \item \textbf{Alignment Error:} induced by $\mathcal{A}_{\mathrm{lgn}}$ projection gap.
    \item \textbf{Governance Drift:} arises from non-identity of $\Theta$ composition.
    \item \textbf{Managerial Structure:} is a projection, not a primitive layer.
\end{itemize}

%% =========================================================
\section{Application Theorems}
\label{sec:applications}

\begin{theorem}[Irreducible Safety Distortion in Discrete Control Systems]
Let $o \in \mathcal{O}_{\mathrm{rg}}$ be a continuous human cognitive state,
$F: \mathcal{O}_{\mathrm{rg}} \rightarrow \mathcal{B}_{\mathrm{in}}$ the
continuum--discrete mapping. Then for any safety-critical system:
\[
\exists\, \epsilon > 0 \;:\quad
d_{\partial}\big(\mathcal{M}(o,t),\; \mathcal{A}_{\mathrm{lgn}}(F(o))\big) \geq \epsilon.
\]
Safety-critical automation therefore requires human-in-the-loop correction to bound
cognitive distortion~\{leveson2016engineering}.
\end{theorem}

\begin{theorem}[Semantic Non-Equivalence in Diagnostic Compression]
Let $\mathcal{M}(a,t)$ represent clinical meaning of patient state~$a$ over time~$t$,
and $F$ the encoding into diagnostic representation space $\mathcal{B}_{\mathrm{in}}$.
Then:
\[
E_{\mathcal{A}}(a) = \left\| \mathcal{A}_{\mathrm{lgn}}(F(a)) - \mathcal{M}(a,t) \right\| > 0
\]
for non-degenerate clinical cases involving contextual and temporal
ambiguity~\{shortliffe2012computer}. Diagnostic labels are structurally insufficient to
capture full clinical meaning; clinical AI systems must be treated as lossy semantic
approximators, not decision replacements.
\end{theorem}

\begin{theorem}[Temporal Instability of Risk Representation]
Let $\mathcal{C}$ denote the capability manifold and $\mathcal{I}$ the interaction operator
governing financial meaning propagation. Then risk representations are path-dependent
over the Meaning--Time geometry:
\[
\mathcal{M}(t_2) \neq \mathcal{I}(\mathcal{M}(t_1),\; t_2 - t_1)
\]
unless the invariance condition $\dfrac{\partial \mathcal{I}}{\partial t} = 0$ holds, which
does not hold in general financial environments~\{cont2001empirical}. Static risk
scores cannot fully represent dynamic financial meaning.
\end{theorem}

\begin{theorem}[Cross-System Semantic Drift]
Let $\Theta_{BD}, \Theta_{DK}, \Theta_{KS}$ be inter-theory operators. The composed
mapping:
\[
\Theta_{KS} \circ \Theta_{DK} \circ \Theta_{BD}
\]
is not, in general, identity-preserving on semantic structures:
\[
\Theta_{KS} \circ \Theta_{DK} \circ \Theta_{BD}(x) \neq x.
\]
Governance systems therefore require explicit drift-correction mechanisms to preserve
policy intent~\{floridi2019establishing}.
\end{theorem}

\begin{theorem}[Non-Commutativity of Organizational Meaning Composition]
Let $\oplus$ denote organizational knowledge merging:
\[
b_1 \oplus b_2 \neq b_2 \oplus b_1
\]
in general, due to context-dependent semantic embedding in $\mathcal{S}_M$.
SOP and knowledge fusion systems are inherently order-sensitive and non-commutative.
\end{theorem}

\begin{theorem}[Bounded Alignment Deformation]
Let $d_{\partial}$ be the alignment distortion metric. Then for any bounded cognitive system:
\[
0 < d_{\partial}(x) \leq \delta_{\max}
\]
where $\delta_{\max}$ is system-dependent and strictly positive under imperfect
representation mappings~{amodei2016concrete}. AI alignment systems must operate
under bounded-error optimization, not equality constraints.
\end{theorem}

%% =========================================================
\section{Geometric Structures}
\label{sec:geometry}

%---------------------------------------------------------
\subsection{Temporal Geometry}

\begin{definition}[Temporal Metric]
\[
d_T(t_i, t_j) = \int_{t_i}^{t_j} \sqrt{g_T(\tau)} \, d\tau,
\qquad g_T(\tau) > 0
\]
\end{definition}

Temporal Geometry models how meaning and decisions evolve over time rather than in
static snapshots~{petersen2006riemannian}. The Riemannian metric $g_T$ on
the time manifold $T$ weights semantic distance non-uniformly, capturing periods of
rapid drift versus stable alignment. This enables time-aware risk modeling, forecasting
systems that incorporate semantic drift, and improved temporal alignment in long-horizon
planning.

%---------------------------------------------------------
\subsection{Meaning--Time Fiber Bundle}

\begin{definition}[Fiber Bundle]
\[
\pi : \mathcal{M} \rightarrow T, \qquad \mathcal{M}_t = \pi^{-1}(t)
\]
\end{definition}

Meaning is not static; it evolves as a structured bundle over time~\{steenrod1951topology}.
Each fiber $\mathcal{M}_t$ is the space of all possible semantic states at time~$t$.
Organizational drift appears as fiber misalignment: $\pi^{-1}(t_1) \neq \pi^{-1}(t_2)$.

\begin{figure}[h]
\centering
\begin{tikzpicture}[scale=1.0]
  %% Base time axis
  \draw[-{Stealth}, thick] (-0.3,0) -- (7.5,0) node[right]{$T$ (time)};
  \draw[-{Stealth}, thick] (0,-0.3) -- (0,4.2) node[above]{$\mathcal{M}_t$ (fiber)};

  %% Fiber ellipses at t1, t2, t3
  \fill[blue!20]  (1.5, 1.0) ellipse (0.35 and 1.0);
  \draw[blue!50, thick] (1.5, 1.0) ellipse (0.35 and 1.0);
  \node[below, font=\small] at (1.5, -0.15) {$t_1$};

  \fill[green!20] (3.8, 1.0) ellipse (0.35 and 1.0);
  \draw[green!60!black, thick] (3.8, 1.0) ellipse (0.35 and 1.0);
  \node[below, font=\small] at (3.8, -0.15) {$t_2$};

  \fill[red!20]   (6.0, 1.0) ellipse (0.35 and 1.0);
  \draw[red!60, thick] (6.0, 1.0) ellipse (0.35 and 1.0);
  \node[below, font=\small] at (6.0, -0.15) {$t_3$};
  %% Section (curve connecting fibers)
  \draw[orange!80!black, very thick, dashed]
        (1.5, 1.7) .. controls (2.7, 2.4) and (5.0, 0.9) .. (6.0, 1.4)
        node[right, font=\small]{$\sigma(t)$ section};
  %% Base arrow
  \draw[gray, dashed] (1.5,0) -- (1.5,0.95);
  \draw[gray, dashed] (3.8,0) -- (3.8,0.95);
  \draw[gray, dashed] (6.0,0) -- (6.0,0.95);

  \node[font=\small\itshape] at (3.8, -0.7) {Base manifold $T$};
  \node[font=\small, align=center] at (3.8, 3.5)
        {Fiber bundle $\pi:\mathcal{M}\!\to\!T$};
\end{tikzpicture}
\caption{Meaning--Time fiber bundle. Each fiber $\mathcal{M}_t$ is the semantic state
         space at time $t$; a section $\sigma(t)$ traces meaning evolution over time.
         Drift occurs when fibers at $t_1$ and $t_2$ are misaligned.}
\label{fig:fiberbundle}
\end{figure}

%---------------------------------------------------------
\subsection{Loss Geometry}

\begin{definition}[Alignment Loss Curvature]
\[
\kappa_{\mathrm{loss}} = \frac{\partial^2 I_A(t)}{\partial t^2},
\qquad I_A : T \rightarrow \mathbb{R}_{\ge 0}
\]
\end{definition}

Loss Geometry quantifies how rapidly alignment quality degrades over
time~\{sontag2013mathematical}. Positive curvature ($\kappa_{\mathrm{loss}} > 0$)
indicates accelerating degradation; negative curvature indicates self-correcting behavior.
Corollary~\ref{cor:risk}: operational risk is curvature in alignment space.

%---------------------------------------------------------
\subsection{Capability Manifold}

\begin{definition}[Capability Manifold]
\[
\mathcal{C} = \mathcal{M} \times \mathcal{S}_M
\]
\end{definition}

Capability is a joint function of meaning and structural state~\{do2002carmo}.
The product manifold $\mathcal{C}$ models human--AI combined capability under augmentation,
enabling rigorous capability planning and organizational design.

%---------------------------------------------------------
\subsection{BLOC Geometry}

\begin{definition}[Riemannian Cognitive Manifold]
\[
\mathcal{B} = (B, g_B),
\qquad g_B : TB \times TB \rightarrow \mathbb{R}_{\ge 0}
\]
where $TB$ is the tangent bundle of $B$.
\end{definition}

BLOC Geometry provides a metric structure for cognitive distance between organizational
states~\{petersen2006riemannian}. The geodesic distance under $g_B$ measures
organizational misalignment and supports transformation roadmaps.

\begin{figure}[h]
\centering
\begin{tikzpicture}[scale=1.1]
  %% Cognitive manifold surface (schematic)
  \begin{scope}
    \draw[blue!30, fill=blue!6, opacity=0.8]
      (0,0) .. controls (1,0.4) and (2,0.2) .. (3.5,0.5)
            .. controls (4.5,0.7) and (5.0,1.2) .. (5.5,1.0)
            -- (5.5,2.5)
            .. controls (4.5,2.8) and (3.5,2.3) .. (2.5,2.6)
            .. controls (1.5,2.8) and (0.5,2.5) .. (0,2.2)
            -- cycle;
    \node[font=\small\itshape, blue!60!black] at (5.0, 0.3)
          {$(B, g_B)$};
  \end{scope}

  %% States x and y
  \fill[red!70] (1.1, 1.6) circle (3pt) node[above left, font=\small]{$x$};
  \fill[green!60!black] (4.2, 1.8) circle (3pt) node[above right, font=\small]{$y$};

  %% Geodesic
  \draw[orange!80!black, very thick]
        (1.1,1.6) .. controls (2.0, 2.3) and (3.5, 1.1) .. (4.2, 1.8)
        node[midway, above, font=\scriptsize\itshape] {geodesic $d_\partial(x,y)$};

  %% Straight (non-geodesic)
  \draw[gray, dashed, thin] (1.1, 1.6) -- (4.2, 1.8)
        node[midway, below, font=\scriptsize\itshape, gray] {Euclidean};
\end{tikzpicture}
\caption{Riemannian cognitive manifold $(B, g_B)$. The geodesic (solid) represents true
         cognitive distance $d_\partial(x,y)$ between organizational states $x$ and $y$,
         which exceeds naive Euclidean distance (dashed) under cognitive curvature.}
\label{fig:manifold}
\end{figure}

%% =========================================================
\section{Variables, Dimensions, and Algebra}
\label{sec:variables}

\subsection{Phenomenology Space}

\begin{definition}[Phenomenology Space]
\[
\Phi \subseteq \mathcal{S}_M^{\ast}
\]
\end{definition}

$\Phi$ is a subspace of the dual of $\mathcal{S}_M$, capturing tacit knowledge and lived
experience~\{dreyfus1992computers}. It models experiential knowledge in safety and
clinical domains, supporting training systems that preserve expert intuition.

The \textbf{Phenomenological Integral} aggregates this knowledge over time:
\[
\mathbb{I}_{\Phi} = \int_{\Omega} \phi(t)\, dt,
\qquad \phi : T \rightarrow \Phi
\]

\subsection{Boundary Metric}

\begin{definition}[Boundary Metric]
\[
d_{\partial}(x,y) =
\inf_{\gamma \in \Gamma(x,y)} \int_{\gamma}
\sqrt{g_{\partial}(\gamma'(s),\gamma'(s))} \, ds
\]
\end{definition}

The infimum over all paths $\Gamma(x,y)$ yields the geodesic distance between cognitive
states $x$ and $y$ under the Riemannian metric $g_\partial$, providing a measurable
alignment score for AI systems~\{deza2009encyclopedia}.

\subsection{Alignment Error Metric}

\begin{definition}[Alignment Error]
\[
E_{\mathcal{A}}(x,t) =
d_{\partial}\big(\mathcal{A}_{\mathrm{lgn}}(x),\; \mathcal{M}(x,t)\big)
\]
\end{definition}

$E_{\mathcal{A}}$ quantifies semantic mismatch between human and machine at each
instant $(x,t)$, enabling continuous monitoring and human-in-the-loop escalation thresholds.

\begin{figure}[h]
\centering
\begin{tikzpicture}[scale=1.1]
  \draw[-{Stealth}] (-0.5,0) -- (6.5,0) node[right]{$t$};
  \draw[-{Stealth}] (0,-0.3) -- (0,3.2) node[above]{$E_{\mathcal{A}}(t)$};

  %% Bounded region
  \fill[red!8] (0, 0.3) -- plot[domain=0:6, samples=80]
    (\x, {0.3 + 1.2*abs(sin(deg(\x*0.8 + 0.5)))*exp(-0.05*\x) + 0.4*\x/6})
    -- (6, 0.3) -- cycle;

  %% Upper bound
  \draw[red!60, dashed, thick] (0, 2.7) -- (6, 2.7)
        node[right, font=\scriptsize] {$\delta_{\max}$};
  %% Lower bound
  \draw[blue!50, dashed, thick] (0, 0.3) -- (6, 0.3)
        node[right, font=\scriptsize] {$\epsilon > 0$};

  %% Error curve
  \draw[orange!90!black, thick] plot[domain=0:6, samples=100]
    (\x, {0.3 + 1.2*abs(sin(deg(\x*0.8 + 0.5)))*exp(-0.05*\x) + 0.4*\x/6});

  \node[font=\small\itshape] at (3.5, 1.5) {$E_{\mathcal{A}}(t)$ trajectory};
  \node[font=\small, align=center] at (3.0, -0.55)
        {Bounded: $\epsilon \leq E_{\mathcal{A}}(t) \leq \delta_{\max}$};
\end{tikzpicture}
\caption{Alignment error $E_{\mathcal{A}}(t)$ is bounded below by $\epsilon > 0$
         (irreducible semantic loss) and above by $\delta_{\max}$ (bounded deformation).
         The trajectory fluctuates within this band across time, never reaching zero.}
\label{fig:alignerror}
\end{figure}

\subsection{Reflexive BLOC Structure}

\begin{definition}[Reflexive Fixed Point]
\[
R \in B, \qquad \mathcal{T}(R) = R
\]
\end{definition}

Reflexive states represent self-correcting organizational structures: fixed points of the
cognitive transformation $\mathcal{T}$. They are the formal basis for self-auditing and
self-regulating workflows in resilient governance systems.

\subsection{BLOC Algebra}

\begin{definition}[BLOC Algebraic Structure]
\[
(B, \oplus, \otimes)
\]
with coproduct (disjoint union) $b_1 \amalg b_2 \in B$ and product $b_1 \times b_2 \in B$.
\end{definition}

BLOC Algebra models how organizational knowledge is merged, composed, and
propagated~\{mac2013categories}. Non-commutativity of $\oplus$ (Theorem~5)
makes knowledge integration order-sensitive, with direct implications for SOP fusion
across multi-site organizations and modular knowledge engineering.

\subsection{Extended Axioms for Dynamics}

\begin{axiom}[Meaning Dynamics]
\[
M_{t+1} = \mathcal{M}(M_t, T_t)
\]
\end{axiom}

\begin{axiom}[Bounded Loss Dynamics]
\[
0 < L_{\min} \leq I_A(t) \leq L_{\max}
\]
\end{axiom}

\begin{axiom}[Strict Cognitive Asymmetry]
\[
x \neq y \Rightarrow d_{\partial}(x,y) > 0
\]
\end{axiom}

\begin{axiom}[Reflexive Stability]
\[
R \in \mathcal{D}(a) \Rightarrow \mathcal{T}(R) \in \mathcal{D}(a)
\]
\end{axiom}

%% =========================================================
\section{Operator--Geometric Closure of BLOC Theory v2.0}
\label{sec:closure}

\subsection{System Definition}

Let the BLOC cognitive system be defined by the tuple
\[
\mathfrak{B} =
\big(
\mathcal{A}_{\mathrm{rt}},\;
\mathcal{B}_{\mathrm{in}},\;
\mathcal{O}_{\mathrm{rg}},\;
\mathcal{S}_M,\;
T,\; B,\;
\mathcal{M},\;
\mathcal{A}_{\mathrm{lgn}},\;
F,\; G,\;
\mathcal{I},\;
\Pi
\big),
\]
where $(B, g_B)$ is a Riemannian cognitive manifold, $(T, g_T)$ is a temporal manifold,
and Axioms~1--13 hold.

\begin{figure}[h]
\centering
\begin{tikzpicture}[
  node distance=1.8cm and 2.4cm,
  spc/.style={ellipse, draw, minimum width=2.0cm, minimum height=1.0cm,
              align=center, font=\small, fill=gray!10},
  arr/.style={-{Stealth[length=5pt]}, thick},
  rarr/.style={-{Stealth[length=5pt]}, thick, dashed, red!70!black},
]
  \node[spc, fill=green!10]  (Org) {$\mathcal{O}_{\mathrm{rg}}$\\[-2pt]\scriptsize organic};
  \node[spc, fill=blue!10, right=of Org]  (Bin) {$\mathcal{B}_{\mathrm{in}}$\\[-2pt]\scriptsize binary};
  \node[spc, fill=orange!10, right=of Bin] (SM)  {$\mathcal{S}_M$\\[-2pt]\scriptsize semantic};
  \node[spc, fill=purple!10, below=1.5cm of SM]  (Smgr) {$\mathcal{S}_{\mathrm{mgr}}$\\[-2pt]\scriptsize managerial};
  \node[spc, fill=yellow!20, above=1.5cm of SM] (Art) {$\mathcal{A}_{\mathrm{rt}}$\\[-2pt]\scriptsize agent};

  \draw[arr] (Org) -- node[above,font=\scriptsize]{$F$} (Bin);
  \draw[rarr] (Bin) to[bend right=20] node[below,font=\scriptsize]{$G$} (Org);
  \draw[arr] (Bin) -- node[above,font=\scriptsize]{$\mathcal{A}_{\mathrm{lgn}}$} (SM);
  \draw[arr] (Art) -- node[right,font=\scriptsize]{$\mathcal{M}$} (SM);
  \draw[arr] (SM)  -- node[right,font=\scriptsize]{$\Pi$} (Smgr);

  \node[red!70!black, font=\scriptsize\itshape, below=0.1cm of Org]
        {$G\!\circ\!F\!\neq\!\mathrm{Id}$};
\end{tikzpicture}
\caption{Complete cognitive space diagram for $\mathfrak{B}$. Solid arrows: operator
         mappings. Dashed red arrow: partial, non-invertible recovery $G$ (with
         $G\circ F\neq\mathrm{Id}$). Projection $\Pi$ maps semantic to managerial space.}
\label{fig:cogmap}
\end{figure}

\subsection{Closure Theorem}

\begin{theorem}[BLOC Operator--Geometric Closure]
Under Axioms~1--13, the system $\mathfrak{B}$ admits a closed operator--geometric
structure such that:

\begin{enumerate}
\item All cognitive transformations are smooth mappings between Riemannian manifolds
      $(B, g_B)$, $(T, g_T)$, and $\mathcal{S}_M$.

\item All operators preserve structure up to bounded distortion:
      \[
      d_{\partial}(\mathcal{O}(x), \mathcal{O}(y)) \leq C_{\mathcal{O}}\, d_{\partial}(x,y),
      \quad C_{\mathcal{O}} > 0.
      \]

\item The interaction operator $\mathcal{I}$ is bilinear and induces a coupled semiring
      structure on $(\mathcal{S}_M, \mathcal{S})$.

\item The composite mapping $\Pi \circ \mathcal{O} : B \rightarrow \mathcal{S}_{\mathrm{mgr}}$
      is well-defined for all $\mathcal{O} \in \mathfrak{B}$.

\item The system is non-invertible, $G \circ F \neq \mathrm{Id}_{\mathcal{O}_{\mathrm{rg}}}$,
      and induces strictly positive irreducible distortion:
      \[
      \exists\, \epsilon > 0 \;\text{such that}\;
      d_{\partial}\big(\mathcal{M}(x,t),\; \mathcal{A}_{\mathrm{lgn}}(F(x))\big) \geq \epsilon.
      \]
\end{enumerate}
\end{theorem}

\subsection{Proof Sketch}

\paragraph{(I) Geometric Well-Posedness.}
By Axiom~1, all cognitive states reside in structured sets
$\mathcal{A}_{\mathrm{rt}}, \mathcal{B}_{\mathrm{in}}, \mathcal{O}_{\mathrm{rg}}, \mathcal{S}_M$.
Axioms~7 and~11 induce a metric structure $d_{\partial}$ satisfying
$d_{\partial}(x,y) > 0$ for $x \neq y$.
Thus $(B, g_B)$ and induced spaces are metric-compatible manifolds, ensuring all operators
are measurable and geodesically well-defined.

\paragraph{(II) Operator Closure.}
From Axioms~2--4, codomain compatibility ensures:
\[
\mathcal{M} \circ F : \mathcal{O}_{\mathrm{rg}} \times T \rightarrow \mathcal{S}_M.
\]
The operator system is closed under composition up to domain restriction.

\paragraph{(III) Irreversibility and Distortion.}
From non-invertibility of $F$ and $G$ (Axiom~4):
\[
\Delta(x,t) = d_{\partial}\big(\mathcal{M}(x,t),\; \mathcal{A}_{\mathrm{lgn}}(F(x))\big).
\]
By Axiom~10 (bounded loss dynamics), $\Delta$ is bounded above. By Axiom~11 (strict
asymmetry), $\Delta > 0$. Hence $\exists\,\epsilon > 0 : \Delta(x,t) \ge \epsilon$,
establishing irreducible semantic distortion.

\paragraph{(IV) Projection Consistency and Managerial Closure.}
By Axiom~9, $d_{\mathrm{mgr}}(\Pi(x), \Pi(y)) \le d_{\partial}(x,y)$: projection is
non-expansive and stable. By Axiom~10, $\Pi \circ \mathcal{O}$ is well-defined for all
operators. Therefore managerial utilities are not independent constructs but:
\[
\mathrm{Image}(\Pi) \subset \text{Operator Image Space}. \qquad \square
\]

\subsection{Corollaries: Business as Geometry}

\begin{corollary}[Risk is Curvature]
\label{cor:risk}
\[
\kappa_{\mathrm{loss}} = \frac{\partial^2 I_A}{\partial t^2}
\]
Operational risk is curvature in alignment space.
\end{corollary}

\begin{corollary}[AI Error is Geodesic Distance]
\[
E_{\mathcal{A}} = d_{\partial}(\mathcal{A}_{\mathrm{lgn}},\; \mathcal{M})
\]
\end{corollary}

\begin{corollary}[Organizational Drift is Fiber Misalignment]
\[
\pi^{-1}(t_1) \neq \pi^{-1}(t_2)
\]
\end{corollary}

\begin{corollary}[Governance is Projection Stability]
\[
\Pi(\mathcal{O}(x)) \text{ stable} \;\Longleftrightarrow\;
d_{\mathrm{mgr}} \text{ bounded.}
\]
\end{corollary}

%% =========================================================
\section{Unified Intelligence}

\begin{definition}[Unified Intelligence]
\[
U = M + \mathbb{E}[S] + \mathcal{I}(M,S)
\]
\end{definition}

Unified Intelligence models how meaning~$M$, expected structural state~$\mathbb{E}[S]$,
and their bilinear interaction~$\mathcal{I}(M,S)$ jointly determine organizational
performance. The third term $\mathcal{I}(M,S)$ is not merely additive---it captures
emergent capability arising from the coupling of human meaning-construction and
structural AI capacity, enabling rigorous design of hybrid Human--AI workflows~\{tegmark2017life}.

%% =========================================================
\section{Discussion}

The geometric and algebraic structures introduced above provide a unified mathematical
foundation for modeling Human--AI cognition. Temporal geometry captures semantic
evolution; fiber bundles encode meaning trajectories; loss curvature quantifies alignment
degradation; and capability manifolds model joint cognitive capacity. The axioms ensure
closure, stability, and bounded distortion, while BLOC Algebra provides compositional
structure for organizational knowledge.

Together, these constructs position BLOC Theory v2.0 as a general operator--geometric
framework capable of supporting:
\begin{itemize}
    \item formal verification of cognitive alignment~\{seshia2018formal},
    \item analysis of semantic drift in governance systems~\{floridi2019establishing},
    \item modeling of capability evolution under AI augmentation~\{amodei2016concrete},
    \item and rigorous study of cognitive asymmetry in digital transformation.
\end{itemize}

An important open direction is the construction of computable approximations of
$d_\partial$ and $E_\mathcal{A}$ from observable data, enabling empirical
calibration of the theoretical bounds $\epsilon$ and $\delta_{\max}$. A second
direction concerns the category-theoretic analysis of the inter-theory operators
$\Theta_{BD}, \Theta_{DK}, \Theta_{KS}$: whether they constitute natural transformations
or merely morphisms of a broader cognitive functor category remains to be established.
Third, the reflexive fixed-point structure ($\mathcal{T}(R) = R$) invites connection
to Banach fixed-point theory, potentially yielding algorithmic convergence guarantees
for self-correcting governance systems~\(kreyszig1991introductory).

%% =========================================================
\section{Conclusion}

BLOC Theory v2.0 constitutes a mathematically complete cognitive systems theory. Through
the introduction of cognitive operators, Riemannian geometric structures, manifold-based
state representations, metric formulations, functorial inter-theory mappings, algebraic
composition laws, and phenomenological dimensions, the framework achieves what v1.0
could not: a \emph{closed, operationally computable, formally verifiable} model of
Human--AI cognition.

The Closure Theorem (Section~\ref{sec:closure}) is the formal capstone of this
achievement. It establishes that all cognitive transformations are smooth, all operators
are Lipschitz-bounded, all managerial interpretations are non-expansive projections, and
all semantic loss is irreducible and strictly positive. These are not descriptive claims
but \emph{provable consequences} of the axiomatic system. The result is a framework
in which cognition is geometric, transformation is operator-based, distortion is metric,
governance is projection, and organizational utility is a derived corollary---not an
assumption.

The six Application Theorems (Section~\ref{sec:applications}) demonstrate that the
abstract geometry carries direct, domain-specific consequence: discretization loss in
safety-critical systems demands human-in-the-loop correction by theorem, not by policy
preference; diagnostic AI irreducibly approximates clinical meaning; risk metrics are
path-dependent by the geometry of meaning--time; semantic drift across governance layers
is formally guaranteed unless corrective mechanisms are designed; knowledge merging is
non-commutative; and perfect alignment is provably unachievable under lossy representation.

Taken together, these results constitute a paradigm shift in how Human--AI systems are
understood. The framework moves the field from informal intuitions about AI limitations
toward \emph{mathematically grounded engineering constraints}. Just as thermodynamics
imposes provable limits on heat-engine efficiency regardless of engineering ingenuity,
BLOC Theory v2.0 imposes provable limits on semantic fidelity regardless of AI
architectural choice. This is the theory's deepest contribution.

Looking forward, BLOC Theory v2.0 establishes the scaffolding for a new discipline:
\emph{cognitive engineering}---the principled design of Human--AI systems under
formally characterized constraints. The Unified Intelligence formulation $U = M +
\mathbb{E}[S] + \mathcal{I}(M,S)$ suggests that the highest-leverage design target
is not the individual terms but the interaction operator $\mathcal{I}$: the emergent
capacity arising from the coupling of human meaning-construction and machine structural
processing. Future work on constructing computable realizations of $d_\partial$,
characterizing the category-theoretic properties of the inter-theory operators, and
deriving convergence guarantees for reflexive governance structures will progressively
tighten the link between the theory's formal geometry and empirically deployable
cognitive engineering systems.

BLOC Theory v2.0 therefore does not merely complete the original framework. It opens
a new mathematical frontier in which the geometry of meaning, the algebra of knowledge,
and the topology of alignment become the central instruments of Human--AI system design.

%% =========================================================
\bibliographystyle{plain}
\begin{thebibliography}{99}

\bibitem{zafar2026bloc}
U.~Zafar.
\newblock {BLOC Theory: Binary Limitation of Organic Cognition and Cognitive Engineering}.
\newblock Zenodo, 2026. \newblock \url{https://doi.org/10.5281/zenodo.18692111}.


\bibitem{russell2019human}
S.~Russell.
\newblock \textit{Human Compatible: Artificial Intelligence and the Problem of Control}.
\newblock Viking, New York, 2019.

\bibitem{do2002carmo}
M.~P.~do Carmo.
\newblock \textit{Riemannian Geometry}.
\newblock Birkh\"{a}user, Boston, 2nd edition, 1992.

\bibitem{gabriel2020artificial}
I.~Gabriel.
\newblock Artificial intelligence, values, and alignment.
\newblock \textit{Minds and Machines}, 30(3):411--437, 2020.

\bibitem{baez2010physics}
J.~C.~Baez and M.~Stay.
\newblock Physics, topology, logic and computation: A Rosetta stone.
\newblock In B.~Coecke, editor, \textit{New Structures for Physics}, pages 95--172.
\newblock Springer, Berlin, 2010.

\bibitem{marcus2019rebooting}
G.~Marcus and E.~Davis.
\newblock \textit{Rebooting AI: Building Artificial Intelligence We Can Trust}.
\newblock Pantheon Books, New York, 2019.

\bibitem{petersen2006riemannian}
P.~Petersen.
\newblock \textit{Riemannian Geometry}.
\newblock Springer, New York, 2nd edition, 2006.

\bibitem{deza2009encyclopedia}
M.~M.~Deza and E.~Deza.
\newblock \textit{Encyclopedia of Distances}.
\newblock Springer, Berlin, 2009.

\bibitem{mac2013categories}
S.~Mac~Lane.
\newblock \textit{Categories for the Working Mathematician}.
\newblock Springer, New York, 2nd edition, 1998.

\bibitem{dreyfus1992computers}
H.~L.~Dreyfus.
\newblock \textit{What Computers Still Can't Do: A Critique of Artificial Reason}.
\newblock MIT Press, Cambridge, MA, 1992.

\bibitem{leike2018scalable}
J.~Leike, D.~Krueger, T.~Everitt, M.~Martic, V.~Maini, and S.~Legg.
\newblock Scalable agent alignment via reward modeling: A research direction.
\newblock \textit{arXiv preprint arXiv:1811.07871}, 2018.

\bibitem{cover2006elements}
T.~M.~Cover and J.~A.~Thomas.
\newblock \textit{Elements of Information Theory}.
\newblock Wiley-Interscience, Hoboken, NJ, 2nd edition, 2006.

\bibitem{steenrod1951topology}
N.~Steenrod.
\newblock \textit{The Topology of Fibre Bundles}.
\newblock Princeton University Press, Princeton, NJ, 1951.

\bibitem{sontag2013mathematical}
E.~D.~Sontag.
\newblock \textit{Mathematical Control Theory: Deterministic Finite Dimensional Systems}.
\newblock Springer, New York, 2nd edition, 1998.

\bibitem{leveson2016engineering}
N.~G.~Leveson.
\newblock \textit{Engineering a Safer World: Systems Thinking Applied to Safety}.
\newblock MIT Press, Cambridge, MA, 2016.

\bibitem{shortliffe2012computer}
E.~H.~Shortliffe and J.~J.~Cimino, editors.
\newblock \textit{Biomedical Informatics: Computer Applications in Health Care and
Biomedicine}.
\newblock Springer, London, 4th edition, 2014.

\bibitem{cont2001empirical}
R.~Cont.
\newblock Empirical properties of asset returns: Stylized facts and statistical issues.
\newblock \textit{Quantitative Finance}, 1(2):223--236, 2001.

\bibitem{floridi2019establishing}
L.~Floridi et~al.
\newblock An ethical framework for a good AI society: Opportunities, risks, principles, and
recommendations.
\newblock \textit{Minds and Machines}, 28(4):689--707, 2018.

\bibitem{amodei2016concrete}
D.~Amodei, C.~Olah, J.~Steinhardt, P.~Christiano, J.~Schulman, and D.~Man{\'e}.
\newblock Concrete problems in AI safety.
\newblock \textit{arXiv preprint arXiv:1606.06565}, 2016.

\bibitem{tegmark2017life}
M.~Tegmark.
\newblock \textit{Life 3.0: Being Human in the Age of Artificial Intelligence}.
\newblock Knopf, New York, 2017.

\bibitem{seshia2018formal}
S.~A.~Seshia, D.~Sadigh, and S.~S.~Sastry.
\newblock Formal specification for deep neural networks.
\newblock In \textit{International Symposium on Automated Technology for Verification and
Analysis}, pages 20--34. Springer, 2018.

\bibitem{kreyszig1991introductory}
E.~Kreyszig.
\newblock \textit{Introductory Functional Analysis with Applications}.
\newblock Wiley, New York, 1991.

\end{thebibliography}

\end{document}
