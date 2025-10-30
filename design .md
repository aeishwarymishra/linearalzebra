```mermaid

graph TD
  A[Linear Algebra]:::main --> B[Vectors]
  A --> C[Matrices]
  A --> D[Transformations]
  A --> E[Eigenvalues & Eigenvectors]
  A --> F[Projections & Orthogonality]
  A --> G[Decompositions (SVD, LU, QR)]

  %% Vectors
  B --> B1[Represent data points]
  B --> B2[Define directions & magnitudes]
  B --> B3[Feature vectors in ML]

  %% Matrices
  C --> C1[Combine multiple vectors]
  C --> C2[Perform transformations]
  C --> C3[Encode relationships between features]

  %% Transformations
  D --> D1[Scaling & rotation in graphics]
  D --> D2[Weight matrices in neural nets]
  D --> D3[Mapping input to output spaces]

  %% Eigenvalues and Eigenvectors
  E --> E1[Reveal natural axes of a system]
  E --> E2[PCA for dimensionality reduction]
  E --> E3[PageRank computation]

  %% Projections and Orthogonality
  F --> F1[Least squares regression]
  F --> F2[Noise filtering]
  F --> F3[Signal separation]

  %% Decompositions
  G --> G1[SVD - core of PCA & compression]
  G --> G2[LU, QR for solving equations]
  G --> G3[Matrix factorization in ML]

  %% Applications
  subgraph Applications
    H[Machine Learning]
    I[Computer Graphics]
    J[Signal Processing]
    K[Optimization]
    L[Quantum Computing]
  end

  B3 --> H
  D2 --> H
  E2 --> H
  G3 --> H
  D1 --> I
  F2 --> J
  F3 --> J
  G1 --> J
  F1 --> K
  E1 --> L

  classDef main fill:#f6d365,stroke:#f6a635,stroke-width:2px;
```

