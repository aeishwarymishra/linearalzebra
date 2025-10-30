```mermaid
graph TB
  %% Core
  LA[Linear Algebra]

  subgraph Core_Concepts
    V[Vectors]
    M[Matrices]
    LM[Linear maps]
    IP[Inner products]
    EV[Eigenvalues & eigenvectors]
    SVD[SVD / PCA]
    SP[Sparse operations]
  end

  LA --> V
  LA --> M
  LA --> LM
  LA --> IP
  LA --> EV
  LA --> SVD
  LA --> SP

  %% Applications
  subgraph Applications
    ML[Machine Learning]
    CV[Computer Vision]
    CG[Computer Graphics]
    NLP[Natural Language Processing]
    SIG[Signal & Image Processing]
    SYS[Systems & Algorithms]
    OPT[Optimization]
    ROB[Robotics & Control]
    Q[Quantum Computing]
    IR[Search/IR & Recommenders]
  end

  V --> ML
  M --> ML
  SVD --> ML
  SP --> SYS
  EV --> SYS
  LM --> CG
  LM --> CV
  IP --> NLP
  SVD --> SIG
  EV --> SIG
  LM --> ROB
  OPT --> ML
  OPT --> ROB
  EV --> Q
  M --> Q
  SVD --> IR

  %% Concrete examples
  subgraph Examples
    ex1[Neural nets = matrix ops]
    ex2[PCA for dimensionality]
    ex3[3D transforms]
    ex4[PageRank eigenvector]
    ex5[JPEG compression]
    ex6[Kalman filters]
    ex7[Quantum state vectors]
  end

  ML --- ex1
  ML --

```
