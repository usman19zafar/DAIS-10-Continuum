```mermaid
flowchart LR
    A0[0 Enrichment] --> A20[20]
    A20 --> A40[40]
    A40 --> A60[60]
    A60 --> A80[80]
    A80 --> A100[100 Essential]

    subgraph Zones
        A0:::N
        A20:::CN
        A40:::C
        A60:::EC
        A80:::E
        A100:::E
    end

    classDef E fill:#ff4d4d,stroke:#b30000,color:#fff
    classDef EC fill:#ff9999,stroke:#b30000,color:#000
    classDef C fill:#ffd966,stroke:#b38f00,color:#000
    classDef CN fill:#c6e0b4,stroke:#6aa84f,color:#000
    classDef N fill:#9fc5e8,stroke:#3d85c6,color:#000
```
