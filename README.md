# Tugas2.md

flowchart TD
    A[Mulai] --> B[Masukkan A, B, C]
    B --> C[Hitung D]
    C --> D{D < 0?}
    D -- Ya --> E[Akar Imajiner]
    D -- Tidak --> F{D = 0?}
    F -- Ya --> G[X1 = X2]
    F -- Tidak --> H[Hitung X1 dan X2]
    H --> I[Hitung X1]
    H --> J[Hitung X2]
    I --> K[X1 = (-B + sqrt(D)) / (2 * A)]
    J --> L[X2 = (-B - sqrt(D)) / (2 * A)]
    G --> M[Selesai]
    K --> M
    L --> M
    E --> M


