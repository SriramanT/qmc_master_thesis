# qmc_master_thesis

This folder contains all the files needed to compile the code that builds the .pdf file with the thesis itself.

## To do list

- Section on Wick's theorem
- Variants of the Hubbard model
- Conclude state of the art
- Write ouline and original contributions
- Fix what's already written on the auxField QMC section
- Write keywords and summary
- Benchmark 1D QMC Hubbard
- Extend MFT
- Use MFT for the nanoribbon
- Quantify the matrix blow-up
- Flat-histogram, ..., DOS of || B B ... B ||
- Sign problem, sigma / < X > >> 1$

## **Planning the thesis**

## 1. Introduction

In this chapter the goal is to motivate the work and expose clearly some fundamental concepts. I want to be vague, but not unclear. The underlying structure should guide the reader through the questions we are trying to answer with this work and through the basic concepts required to understand the questions.

### **Emergence in condensed matter physics**

Define the scope of this work and how it fits in the rest of condensed matter physics, mentioning the concepts of emergence, and strongly correlated system.

### **What are TMD nanoribbons and why are they interesting**

Explain what is the motivation to study these materials and how electron correlations within them give rise to properties that do not appear in graphene.

### **Dealing with correlations is hard**

Briefly give a run through of different methods to deal with electron correlations, explain their failures and their successes and how they can be improved upon.

### **The many-body problem consists of solving the Schrödinger equation in a 3N-dimensional space**

Emphasize the hardness of the many-body problem and note that it is impossible to simulate it.

### **The problem of computing expectations of observables may be reduced to calculating integrals in this high dimension space**

Mention the thermodynamic limit, importance sampling, and finite size corrections.

### **Monte Carlo sampling is an appropriate method to compute these integrals**

Point out that Monte Carlo methods become more efficiente as the dimensionality grows and that they are a natural choice to tackle this problem.

### **Classical vs Quantum Monte Carlo**

Contrast the intuitive views of Monte Carlo for classical and quantum systems: CMC simulates thermal fluctuations and QMC simulates quantum fluctuations.

### **State of the art**

Brief history of what was developed before, its successes and its failures.

### **A Survey of Quantum Monte Carlo Methods**

Summarize the existing QMC methods, and explain why we focus on detQMC

### **Original contributions**

Describe what were the main achievements of this work and how it contributed to an increased physical understanding of this type of system.

### **Outline**

Explain the structure of the thesis.


## 2. Minimal models of electron correlation in energy bands



## 4. Auxiliary Field Quantum Monte Carlo

## 5. Discussion of the algorithm

## 6. Applications

## 7. Conclusion
