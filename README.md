# Quantum State Discrimination  
Repository: quantum-state-discrimination

## Overview  
This repository collects code notebooks and tools to study and implement quantum state discrimination protocols—specifically minimum-error discrimination (Helstrom bound) and generalized discrimination methods using POVM/Naimark dilation.

## Motivation  
Quantum state discrimination is a core problem in quantum information theory: given a quantum system prepared in one of several non-orthogonal states, how accurately can we distinguish which state was prepared? This has deep applications in quantum communication and quantum cryptography.
In particular, my interest lies in extending the standard models (like the Helstrom bound for two non-orthogonal pure states) to custom discrimination strategies such as:

- Generalized state discrimination: balancing the probabilities of incorrect and inconclusive outcomes to yield higher efficiency (~86% accuracy in my experiments).  
- Hybrid discrimination methods expanding on the standard unambiguous discrimination or minimum‐error discrimination frameworks.

## Related Work  
For further exploration of generalized state discrimination applied to quantum key distribution (QKD), see my other repository:  
[the-phiQKD-protocol-codes]((https://github.com/AnimeshBanik144/the-phiQKD-protocol-codes))


## What’s Inside  
- `Helstrom_approach.ipynb` — A notebook implementing the minimum-error discrimination strategy between two pure states.  
- `naimark_dilation_implementation_of_POVM.ipynb` — A notebook showing how to realize arbitrary POVM elements via Naimark dilation in a larger Hilbert space.  
- `README.md` — This file: overview, instructions and background context.  

### Running the Notebooks  
1. Clone the repository:  
   ```bash
   git clone https://github.com/AnimeshBanik144/quantum-state-discrimination.git
   cd quantum-state-discrimination
