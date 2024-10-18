# Tareas-Autonomia-y-Pensamiento-Critico
flowchart LR
    subgraph Pensamiento Analítico
        A((Pensamiento Analítico))
    end

    subgraph Herramientas de Análisis
        B{Mapas Mentales}
        C{Cuadros Sinópticos}
        D{Diagramas de Flujo}
        E{Matrices de Decisión}
        F{Análisis Estadístico}
        G{Análisis de Datos Cualitativos}
    end

    A --> B
    A --> C
    A --> D
    A --> E
    A --> F
    A --> G

    subgraph Tipos de Análisis
        H{Análisis Cuantitativo}
        I{Análisis Cualitativo}
    end

    E --> H
    F --> H
    G --> I
