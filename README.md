```mermaid
graph TD
    A[ADQUISICIÓN DEL SUELO CONTAMINADO] --> B[CARACTERIZACIÓN INICIAL DEL SUELO<br>• Color<br>• Olor<br>• Textura<br>• TPH inicial]
    B --> C[(BASE DE DATOS)]
    C --> D[PREPARACIÓN DE UNIDADES EXPERIMENTALES]
    D --> E[APLICACIÓN DE TRATAMIENTOS]
    E --> T0[T0<br>0 g]
    E --> T1[T1<br>50 g]
    E --> T2[T2<br>100 g]
    T0 --> F[INCUBACIÓN Y MONITOREO<br>Día 0 — Día 15 — Día 30]
    T1 --> F
    T2 --> F
    F --> G[ANÁLISIS DE TPH<br>Laboratorio acreditado]
    G --> H[ANÁLISIS ESTADÍSTICO<br>ANOVA + TUKEY]
    H --> I[DETERMINACIÓN DE LA DOSIS ÓPTIMA DE ESTIÉRCOL]
    I --> J([CONCLUSIONES])

    style A fill:#EAF2F8,stroke:#2C3E50,stroke-width:2px
    style B fill:#EAF2F8,stroke:#2C3E50,stroke-width:2px
    style C fill:#FADBD8,stroke:#2C3E50,stroke-width:2px
    style D fill:#EAF2F8,stroke:#2C3E50,stroke-width:2px
    style E fill:#FCF3CF,stroke:#2C3E50,stroke-width:2px
    style T0 fill:#EAFAF1,stroke:#2C3E50,stroke-width:2px
    style T1 fill:#EAFAF1,stroke:#2C3E50,stroke-width:2px
    style T2 fill:#EAFAF1,stroke:#2C3E50,stroke-width:2px
    style F fill:#EAF2F8,stroke:#2C3E50,stroke-width:2px
    style G fill:#EAF2F8,stroke:#2C3E50,stroke-width:2px
    style H fill:#EAF2F8,stroke:#2C3E50,stroke-width:2px
    style I fill:#FCF3CF,stroke:#2C3E50,stroke-width:2px
    style J fill:#D5F5E3,stroke:#2C3E50,stroke-width:2px
)# enmiendad
