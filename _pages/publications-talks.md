---
layout: archive
title: "Publications & talks"
permalink: /publications-talks/
author_profile: true
---

<!-- QCE 2024 -->
<h2 class="archive__item-title" itemprop="headline" style="color: #52adc8;">
  Benchmarking Quantum Annealers with Near-Optimal Minor-Embedded Instances
</h2>

<p class="page__date">
  <strong><i class="fa fa-fw fa-calendar" aria-hidden="true"></i> Published:</strong> 
  <time datetime="2024-09-15T00:00:0+02:00">Sept 15, 2024</time> 
  <br/>
  <strong><i class="fa fa-fw fa-users" aria-hidden="true"></i> Authors:</strong> 
  Valentin Gilbert, Julien Rodriguez, Stéphane Louise
  <br/>
  <strong><i class="fa fa-fw fa-globe" aria-hidden="true"></i> Conference:</strong> 
  <a href="https://qce.quantum.ieee.org/2024/" target="_blank">QCE</a> IEEE International Conference on Quantum Computing and Engineering
</p>

**Abstract**: Benchmarking Quantum Process Units (QPU) at an application level usually requires considering the whole programming stack of the quantum computer. One critical task is the minor-embedding (resp. transpilation) step, which involves space-time overheads for annealing-based (resp. gate-based) quantum computers. This paper establishes a new protocol to generate graph instances with their associated near-optimal minor-embedding mappings to D-Wave Quantum Annealers (QA). This set of favorable mappings is used to generate a wide diversity of optimization problem instances. We use this method to benchmark QA on large instances of unconstrained and constrained optimization problems and compare the performance of the QPU with efficient classical solvers. The benchmark aims to evaluate and quantify the key characteristics of instances that could benefit from the use of a quantum computer. In this context, existing QA seem best suited for unconstrained problems on instances with densities less than 10%. For constrained problems, the penalty terms used to encode the hard constraints restrict the performance of QA and suggest that these QPU will be less efficient on these problems of comparable size.
<div style="display: flex; flex-direction: row; justify-content: space-evenly;">
  <span>Peer-reviewed paper: <a href="/files/2024-publication-QCE.pdf" target="_blank"><i class="fas fa-solid fa-download"></i></a></span>
  <span>Slides: <a href="/files/2024-slide-QCE.pdf" target="_blank"><i class="fas fa-solid fa-download"></i></a></span>
</div>


<!-- ICCS 2024 -->
<h2 class="archive__item-title" itemprop="headline" style="color: #52adc8;">
  Quantum Annealers Chain Strengths: A Simple Heuristic to Set Them All
</h2>

<p class="page__date">
  <strong><i class="fa fa-fw fa-calendar" aria-hidden="true"></i> Published:</strong> 
  <time datetime="2024-06-30T00:00:0+02:00">June 30, 2024</time> 
  <br/>
  <strong><i class="fa fa-fw fa-users" aria-hidden="true"></i> Authors:</strong> 
  Valentin Gilbert, Stéphane Louise
  <br/>
  <strong><i class="fa fa-fw fa-globe" aria-hidden="true"></i> Conference:</strong> 
  <a href="https://www.iccs-meeting.org/iccs2024/" target="_blank">ICCS</a> International Conference on Computational Science
</p>

**Abstract**: Quantum annealers (QA), such as D-Wave systems, become increasingly efficient and competitive at approximating combinatorial
optimization problems. However, solving problems that do not directly map the chip topology remains challenging for this type of quantum computer. The creation of logical qubits as sets of interconnected physical qubits overcomes limitations imposed by the sparsity of the chip at the expense of increasing the problem size and adding new parameters to optimize. This paper explores the advantages and drawbacks provided by the structure of the logical qubits and the impact of the rescaling of coupler strengths on the minimum spectral gap of Ising models. We show that logical qubits encoded over densely connected physical qubits require a lower chain strength to maintain the ferromagnetic coupling. We also analyze the optimal chain strength variations considering different minor embeddings of the same instance. This experimental study suggests that the chain strength can be optimized for each instance. We design a heuristic that optimizes the chain strength using a very low number of shots during the preprocessing step. This heuristic outperforms the default method used to initialize the chain strength on D-Wave systems, increasing the quality of the best solution by up to 17.2% for tested instances on the max-cut problem.
<div style="display: flex; flex-direction: row; justify-content: space-evenly;">
  <span>Peer-reviewed paper: <a href="/files/2024-publication-Quantum-Annealers-Chain-Strengths.pdf" target="_blank"><i class="fas fa-solid fa-download"></i></a></span>
  <span>Slides: <a href="/files/2024-slide-Quantum-Annealers-Chain-Strengths.pdf" target="_blank"><i class="fas fa-solid fa-download"></i></a></span>
</div>


<!-- ICCS 2023 TAQOS -->
<h2 class="archive__item-title" itemprop="headline" style="color: #52adc8;">
  TAQOS: A Benchmark Protocol for Quantum Optimization Systems
</h2>

<p class="page__date">
  <strong><i class="fa fa-fw fa-calendar" aria-hidden="true"></i> Published:</strong> 
  <time datetime="2023-06-26T00:00:0+02:00">June 26, 2023</time> 
  <br/>
  <strong><i class="fa fa-fw fa-users" aria-hidden="true"></i> Authors:</strong> 
  Valentin Gilbert, Stéphane Louise, Renaud Sirdey
  <br/>
  <strong><i class="fa fa-fw fa-globe" aria-hidden="true"></i> Conference:</strong> 
  <a href="https://www.iccs-meeting.org/iccs2023/" target="_blank">ICCS</a> International Conference on Computational Science
</p>

**Abstract**: The growing availability of quantum computers raises questions about their ability to solve concrete problems. Existing benchmark protocols still lack problem diversity and attempt to summarize quantum advantage in a single metric that measures the quality of found solutions. Unfortunately, the solution quality metric is insuﬃcient for measuring quantum algorithm performance and should be presented along with time and instances coverage metrics. This paper aims to establish the TAQOS protocol to perform a Tight Analysis of Quantum Optimization Systems. The combination of metrics considered by this protocol helps to identify problems and instances liable to produce quantum advantage on Noisy-Intermediate Scale Quantum (NISQ) devices for useful applications. The methodology used for the benchmark process is detailed and an illustrative short case study on the Max-Cut problem is provided.
<div style="display: flex; flex-direction: row; justify-content: space-evenly;">
  <span>Peer-reviewed short paper: <a href="/files/2023-publication-TAQOS.pdf" target="_blank"><i class="fas fa-solid fa-download"></i></a></span>
  <span>Poster: <a href="/files/2023-poster-TAQOS.pdf" target="_blank"><i class="fas fa-solid fa-download"></i></a></span>
</div>


<!-- ICCS 2023 HOBO -->
<h2 class="archive__item-title" itemprop="headline" style="color: #52adc8;">
  Solving Higher Order Binary Optimization Problems on NISQ Devices: Experiments and Limitations
</h2>

<p class="page__date">
  <strong><i class="fa fa-fw fa-calendar" aria-hidden="true"></i> Published:</strong> 
  <time datetime="2023-06-26T00:00:0+02:00">June 26, 2023</time> 
  <br/>
  <strong><i class="fa fa-fw fa-users" aria-hidden="true"></i> Authors:</strong> 
  Valentin Gilbert, Julien Rodriguez, Stéphane Louise, Renaud Sirdey
  <br/>
  <strong><i class="fa fa-fw fa-globe" aria-hidden="true"></i> Conference:</strong> 
  <a href="https://www.iccs-meeting.org/iccs2023/" target="_blank">ICCS</a> International Conference on Computational Science
</p>

**Abstract**: With the recent availability of Noisy Intermediate-Scale Quantum devices, the potential of quantum computers to impact the field of combinatorial optimization lies in quantum variational and annealing-based methods. This paper further compares Quantum Annealing (QA) and the Quantum Approximate Optimization Algorithm (QAOA) in solving Higher Order Binary Optimization (HOBO) problems. This case study considers the hypergraph partitioning problem, which is used to generate custom HOBO problems. Our experiments show that D-Wave systems quickly reach limits solving dense HOBO problems. Although the QAOA demonstrates better performance on exact simulations, noisy simulations reveal that the gate error rate should remain under 10−5 to match D-Wave systems’ performance, considering equal compilation overheads for both device.
<div style="display: flex; flex-direction: row; justify-content: space-evenly;">
  <span>Peer-reviewed short paper: <a href="/files/2023-publication-HOBO.pdf" target="_blank"><i class="fas fa-solid fa-download"></i></a></span>
  <span>Poster: <a href="/files/2023-poster-HOBO.pdf" target="_blank"><i class="fas fa-solid fa-download"></i></a></span>
</div>


<!-- Metaheuristique Troyes -->
<h2 class="archive__item-title" itemprop="headline" style="color: #52adc8;">
  Discussions about High-quality Embeddings on Quantum
</h2>

<p class="page__date">
  <strong><i class="fa fa-fw fa-calendar" aria-hidden="true"></i> Published:</strong> 
  <time datetime="2023-04-17T00:00:0+02:00">April 17, 2023</time> 
  <br/>
  <strong><i class="fa fa-fw fa-users" aria-hidden="true"></i> Authors:</strong> 
  Valentin Gilbert, Julien Rodriguez
  <br/>
  <strong><i class="fa fa-fw fa-globe" aria-hidden="true"></i> Summer School:</strong> 
  <a href="https://perso.isima.fr/~lacomme/GT2L/EUME_JE/EUME_Joint_Event.php" target="_blank">EU/ME Meeting</a>
</p>

**Abstract**: Quantum Annealers (QA) such as D-Wave systems constitute a noisy implementation of the Adiabatic Quantum Computing process (AQC) and are used to find the ground state of an Ising problem. Qubit interconnections of a quantum chip are usually limited, and finding a good mapping of the Ising problem onto the quantum chip can be challenging. In fact, even defining what is a high-quality embedding is not trivial. After presenting a short review of existing embedding methods, we propose different experiments that could identify important criteria to consider while mapping problems on Quantum Annealers.
<div style="display: flex; flex-direction: row; justify-content: space-evenly;">
  <span>Peer-reviewed short paper: <a href="https://perso.isima.fr/~lacomme/GT2L/EUME_JE/papers/25_Papier_Julien_Rodriguez_2023_Troyes_placement.pdf" target="_blank"><i class="fas fa-solid fa-download"></i></a></span>
  <span>Slides: <a href="/files/2023-slide-EUME.pdf" target="_blank"><i class="fas fa-solid fa-download"></i></a></span>
</div>


<!-- Esquisse 2022 -->
<h2 class="archive__item-title" itemprop="headline" style="color: #52adc8;">
  Exploration of the QAOA Energy Landscape
</h2>

<p class="page__date">
  <strong><i class="fa fa-fw fa-calendar" aria-hidden="true"></i> Published:</strong> 
  <time datetime="2022-07-04T00:00:0+02:00">July 04, 2022</time> 
  <br/>
  <strong><i class="fa fa-fw fa-users" aria-hidden="true"></i> Authors:</strong> 
  Valentin Gilbert, Stéphane Louise, Renaud Sirdey
  <br/>
  <strong><i class="fa fa-fw fa-globe" aria-hidden="true"></i> Summer School:</strong> 
  <a href="https://esquisses2022.sciencesconf.org/" target="_blank">Esquisse</a> summer school
</p>

**Abstract**: The QAOA (Quantum Approximate Optimization Algorithm) is a quantum algorithm based on parameters optimized by a classical solver. It is mainly used to solve combinatorial optimization problems on graphs. Previous work has shown the relation between the energy landscape of the QAOA and the characteristics of the graph instance (especially concerning graph structure). Yet, we think that a better understanding of this landscape would help select cases that are easy to solve for the QAOA and identify hard ones. Finding maximum independent sets in graphs is a widely studied optimization problem in the quantum community. We inspect this problem with slight variations on input instances (in structure and weights) to grasp the impact of these modifications on the energy landscape of the QAOA.

<div style="display: flex; flex-direction: row; justify-content: space-evenly;">
  <span>Poster: <a href="/files/2022-poster-esquisse.pdf" target="_blank"><i class="fas fa-solid fa-download"></i></a></span>
</div>


<!-- ICCS 2022 -->
<h2 class="archive__item-title" itemprop="headline" style="color: #52adc8;">
  Quantum Approaches for WCET-related Optimization Problems
</h2>

<p class="page__date">
  <strong><i class="fa fa-fw fa-calendar" aria-hidden="true"></i> Published:</strong> 
  <time datetime="2022-06-15T00:00:0+02:00">June 15, 2022</time> 
  <br/>
  <strong><i class="fa fa-fw fa-users" aria-hidden="true"></i> Authors:</strong> 
  Gabriella Bettonte, Valentin Gilbert, Daniel Vert, Stéphane Louise, Renaud Sirdey
  <br/>
  <strong><i class="fa fa-fw fa-globe" aria-hidden="true"></i> Conference:</strong> 
  <a href="https://www.iccs-meeting.org/iccs2022/" target="_blank">ICCS</a> International Conference on Computational Science
</p>

**Abstract**: This paper explores the potential of quantum computing on a WCET(Worst-Case Execution Time (of a program).)-related combinatorial optimization problem applied to a set of several polynomial special cases. We consider the maximization problem of determining the most expensive path in a control ﬂow graph. In these graphs, vertices represent blocks of code whose execution times are ﬁxed and known in advance. We port the considered optimization problem to the quantum framework by expressing it as a QUBO. We then experimentally compare the performances in solving the problem of classic Simulated Annealing (SA), Quantum Annealing (QA), and Quantum Approximate Optimization Algorithm (QAOA). Our experiments suggest that QA represents a fast equivalent of simulated annealing. Indeed, we measured the approximation ratio on the results of QA and SA, showing that their performances are comparable, at least on our set of simpliﬁed problems.

<div style="display: flex; flex-direction: row; justify-content: space-evenly;">
  <span>Peer-reviewed paper: <a href="/files/2022-publication-wcet.pdf" target="_blank"><i class="fas fa-solid fa-download"></i></a></span>
</div>


<!-- Roadef 2022 -->
<h2 class="archive__item-title" itemprop="headline" style="color: #52adc8;">
  Benchmarking QAOA through Maximum Cardinality Matching
</h2>

<p class="page__date">
  <strong><i class="fa fa-fw fa-calendar" aria-hidden="true"></i> Published:</strong> 
  <time datetime="2022-02-23T00:00:0+02:00">February 23, 2022</time> 
  <br/>
  <strong><i class="fa fa-fw fa-users" aria-hidden="true"></i> Authors:</strong> 
  Valentin Gilbert, Renaud Sirdey, Stéphane Louise
  <br/>
  <strong><i class="fa fa-fw fa-globe" aria-hidden="true"></i> Conference:</strong> 
  <a href="https://roadef2022.sciencesconf.org/" target="_blank">ROADEF</a> 23ème Congrès annuel de la société Française de Recherche Opérationnelle et d'Aide à la Décision
</p>

**Abstract**: The Quantum Approximate Optimization Algorithm constitues one of the most promising variational algorithm using noisy devices due to its low depth. This paper investigates different mixers to approximate solutions to the Maximum Cardinality Matching problem. 

<div style="display: flex; flex-direction: row; justify-content: space-evenly;">
  <span>Peer-reviewed short paper: <a href="/files/2022-publication-Benchmarking_QAOA_Max_Card_Matching.pdf" target="_blank"><i class="fas fa-solid fa-download"></i></a></span>
  <span>Slides: <a href="/files/2022-slide-Benchmarking_QAOA_Max_Card_Matching.pdf" target="_blank"><i class="fas fa-solid fa-download"></i></a></span>
  <span>Live presentation: <a href="https://www.youtube.com/watch?app=desktop&v=SVBMxMBwnJI" target="_blank"><i class="fab fa-solid fa-youtube"></i></a></span>
</div>

