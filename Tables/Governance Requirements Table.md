```mermaid
classDiagram
    class Essential {
        Documentation: Mandatory
        Enforcement: Strict
        AuditLevel: High
    }

    class SemiEssential {
        Documentation: Conditional
        Enforcement: Conditional
        AuditLevel: High
    }

    class Contextual {
        Documentation: Required
        Enforcement: Soft
        AuditLevel: Medium
    }

    class SemiContextual {
        Documentation: Optional
        Enforcement: Flexible
        AuditLevel: Low-Medium
    }

    class Enrichment {
        Documentation: Minimal
        Enforcement: Monitoring
        AuditLevel: Low
    }
```
