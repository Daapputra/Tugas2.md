# Tugas2.md

```mermaid
graph TD;
    A[Mulai] --> B[Input A, B, C];
    B --> C[Hitung D = B^2 - 4 * A * C];
    C --> D{D < 0?};
    D -- Yes --> E[Akar Imajiner];
    D -- No --> F{D = 0?};
    F -- Yes --> G[X1 = X2 = -B / 2 * A];
    F -- No --> H[X1 = (-B + sqrt(D)) / (2 * A)];
    H --> I[X2 = (-B - sqrt(D)) / (2 * A)];
    E --> J[End];
    G --> J[End];
    I --> J[End];

