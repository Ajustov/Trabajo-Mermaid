# Diagrama de ejemplo con Mermaid

```mermaid
graph TD
    A[Inicio] --> B{¿Condición?}
    B -- Sí --> C[Haz algo]
    B -- No --> D[Haz otra cosa]
    C --> E[Fin]
    D --> E[Fin]