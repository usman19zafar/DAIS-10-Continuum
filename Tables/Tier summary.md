```mermaid
erDiagram
    TIER {
        string Tier
        string MeaningRole
        string Governance
        float Weight
        string FailureType
    }

    ESSENTIAL {
        string Tier
        string MeaningRole
        string Governance
        float Weight
        string FailureType
    }

    SEMI_ESSENTIAL {
        string Tier
        string MeaningRole
        string Governance
        float Weight
        string FailureType
    }

    CONTEXTUAL {
        string Tier
        string MeaningRole
        string Governance
        float Weight
        string FailureType
    }

    SEMI_CONTEXTUAL {
        string Tier
        string MeaningRole
        string Governance
        float Weight
        string FailureType
    }

    ENRICHMENT {
        string Tier
        string MeaningRole
        string Governance
        float Weight
        string FailureType
    }

    TIER ||--|| ESSENTIAL : contains
    TIER ||--|| SEMI_ESSENTIAL : contains
    TIER ||--|| CONTEXTUAL : contains
    TIER ||--|| SEMI_CONTEXTUAL : contains
    TIER ||--|| ENRICHMENT : contains
```
