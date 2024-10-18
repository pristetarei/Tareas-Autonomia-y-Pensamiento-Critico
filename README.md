# Actividad 5: Mapa Conceptual

```mermaid
graph LR
    subgraph Herramientas de Organización
        style A width:185px, height:55px
        style B width:400px, height:160px
        style C width:400px, height:160px
        style D width:400px, height:160px
        style E width:400px, height:160px
        style F width:400px, height:160px
        style G width:400px, height:160px
        style H width:400px, height:160px
        style I width:400px, height:160px
        style J width:400px, height:160px
        style K width:400px, height:160px
        A(Pensamiento Analítico) --> B{Herramientas}
        B --> C(Mapa Mental)
        C --> D(Jerárquico)
        C --> E(Visual)
        B --> F(Cuadro Sinóptico)
        F --> G(Estructurado)
        F --> H(Conciso)
        B --> I(Nube de Palabras)
        I --> J(Frecuencia)
        I --> K(Impacto visual)
    end
    subgraph Herramientas de Visualización
        style L width:400px, height:160px
        B --> L(Línea de Tiempo)
        L --> M(Secuencial)
        L --> N(Cronológico)
    end
    subgraph Herramientas de Definición
        style O width:400px, height:160px
        B --> O(Tabla Informativa)
        O --> P(Organizada)
        O --> Q(Comparativa)
        style R width:400px, height:160px
        B --> R(Glosario)
        R --> S(Conceptos clave)
        R --> T(Definiciones precisas)
    end
    subgraph Herramientas de Relación
        style U width:400px, height:160px
        B --> U(Mapa de Significados)
        U --> V(Conexiones)
        U --> W(Semánticas)
    end

    style D width:400px, height:160px
    style E width:400px, height:160px
    style G width:400px, height:160px
    style H width:400px, height:160px
    style J width:400px, height:160px
    style K width:400px, height:160px
    style M width:400px, height:160px
    style N width:400px, height:160px
    style P width:400px, height:160px
    style Q width:400px, height:160px
    style S width:400px, height:160px
    style T width:400px, height:160px
    style V width:400px, height:160px
    style W width:400px, height:160px

    D((Jerárquico)):::note --> C((Organiza ideas en niveles))
    E((Visual)):::note --> C((Representa conceptos gráficamente))
    G((Estructurado)):::note --> F((Presenta información de forma ordenada))
    H((Conciso)):::note --> F((Resume ideas principales))
    J((Frecuencia)):::note --> I((Muestra la frecuencia de palabras))
    K((Impacto visual)):::note --> I((Resalta términos importantes))
    M((Secuencial)):::note --> L((Ordena eventos en una línea))
    N((Cronológico)):::note --> L((Muestra la evolución en el tiempo))
    P((Organizada)):::note --> O((Presenta datos en filas y columnas))
    Q((Comparativa)):::note --> O((Compara diferentes conceptos))
    S((Conceptos clave)):::note --> R((Define términos importantes))
    T((Definiciones precisas)):::note --> R((Explica el significado de términos))
    V((Conexiones)):::note --> U((Muestra relaciones entre conceptos))
    W((Semánticas)):::note --> U((Representa significados y asociaciones))
