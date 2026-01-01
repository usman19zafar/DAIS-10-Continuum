```mermaid
erDiagram
    TIER {
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

    ESSENTIAL {
        Tier "Essential"
        MeaningRole "Meaning-defining"
        Governance "Strict"
        Weight "1.00"
        FailureType "Critical"
    }

    SEMI_ESSENTIAL {
        Tier "E-C"
        MeaningRole "Transitional"
        Governance "Conditional"
        Weight "0.85"
        FailureType "Conditional Critical"
    }

    CONTEXTUAL {
        Tier "Contextual"
        MeaningRole "Meaning-enhancing"
        Governance "Soft"
        Weight "0.60"
        FailureType "Interpretability Loss"
    }

    SEMI_CONTEXTUAL {
        Tier "C-N"
        MeaningRole "Transitional"
        Governance "Flexible"
        Weight "0.35"
        FailureType "Minor Loss"
    }

    ENRICHMENT {
        Tier "Enrichment"
        MeaningRole "Analytical"
        Governance "Monitoring"
        Weight "0.10"
        FailureType "Analytical Loss"
    }
```
