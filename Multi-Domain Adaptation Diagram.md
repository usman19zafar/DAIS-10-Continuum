```mermaid
flowchart LR
    A[DAIS-10 Core Standard] --> B[Retail Domain Rules]
    A --> C[Finance Domain Rules]
    A --> D[Healthcare Domain Rules]
    A --> E[HR Domain Rules]

    B --> F[Domain-Specific Tier Adjustments]
    C --> F
    D --> F
    E --> F
```
