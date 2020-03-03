---
title: Academic Writing Lesson I
date: 2020-02-23 23:42:00 +0800
categories: [AcademicWriting]
tags: [academic writing]
seo:
  date_modified: 2020-02-23 23:42:00 +0800
---


# Words and Phrases

1. **assign** $x_i$ **to** each node $i$ = **associate** $x_i$ **with** each node $i$
2. Obiviously = Apparently <u>(using less)</u>
3. previous : prior
4. In addition = Furthermore = additionally=also=
5. efficacy, effectiveness, efficiency
6. presents, demonstrates, manifests, illustrate, describes, shows
7. Note that ….; Observe that …





1. each node **executes** its () update
2. xxx **iteratively** updates
3. **in a computationally efficient way**
4. the nodes are able to **jointly implement xxx in a distributed fashion**
5. **obtain the following algorithmic form**
6. be referred to as
7. be camparable to xxx(algorithm)
8. apply … to ...
9. such xxxx is abel to ...
10. achieves an O(x) rate of convergence to the optimal solution.
11. be further assumed to be + diff assumption; further impose the following assumption
12. The entire network dynamics can thus be described by  + updates equations.
13. …, thus we introduce the following notations.



### Related Work:

1. There have been a substantial number of …. reported in the literature, such as ….

### Distributed Optimization

- Advantage: 
  1. have better applicablility to large-scale optimisation problems
  2. more robus and scalable.
- Application:
  1. wireless sensor networks 
  2. cognitive radio networks
  3. machine learning 

### Outline

*The outline of the paper is as follows: Section II formulates the distributed optimization problem, and Section III describes the proposed IFDG algorithm. Section IV presents the convergence analysis, and Section V shows the simulation results. Section VI concludes the paper.*

### Problem Formualtion

Consider an undirected and connected graph $\mathcal{G}=(\mathcal{V},\mathcal{E})$, where $\mathcal{V}=\{1,2,…,N\}$ , $N\ge2$ is the set of nodes and $\mathcal{E}\subseteq \{\{i,j\},i,j\in\mathcal{V}, i\ne j\}$ is the set of links.	

### Assumption:

1. **condition** = assumption
2. **impose the conditions on problem**
3. Assumption …  **implies** that ...
  4. **without less of generality,** in the rest of paper we assume … 


### Numerical Examples

1. validate the efficiency of xxx 

2. simulation results demonstrate that ...

   ​

# Diction

#### Lemma & Theorem: 

1. **Suppose….Then,...**
2. **i.e. (+,)**  = that is
3. If + assumptions. 
4. *Only use one of "if" and “if and only if” in one sentence.*

#### Other algorithm: 

1. **the + abbreviation**: the DIGing algorithms

#### Proof:

1. **an equation —> one sentence.**

#### Others：

1. **then**: adv. instead of conj.
2. Both **nodes and agents** are okay, but choose one diction and keep the using unified.




# Terminology

1. constrained optimization + (problems) 

2. $\mathcal{N}_i$ : node $i$'s (one-hop) neighbours.  

3. nonidentical local constraints

   ​

# Notice

1. $Nd!=d$
2. Heed the symbol of $\mathcal{V},\mathcal{E}$




# Latex

1. Section label: Use **\label{sec: probform}** instead of \label{section2}.

2. Lemma/Theorem label: Use **\label{lem:xxx}, \label{the:xxx}**. *xxx is the description of the corresponding theorem or lemma.*

3. Equation:

   1. Add **a space** (usually use big space: \quad, sometimes: \;) before **\forall**
   2. **…**：
      1. **\ldots**; (x_1, \ldots, x_N)
      2. **\cots**: x_1=\cdots=x_N
   3. *only referenced equation needs number*; use **\nonumber** to remove the equation number
   4. $a^{1/2}$ -> $a^{\frac{1}{2}}$
   5. The difference between \begin{align}, \begin{align*}, \begin{aligned}.

4. In-text Equation:

   1. No need to add ',' before **\forall**. A regular space is enough.

5. Notation:

   1. *One notation represents one thing.*

   2. Mark the size of all zero vector, all one vector, zero matrix and identity matrix: $\mathbf{0}_d, \mathbf{1}_d,I_{d},O_{d}$.

      ​


