graph TD
    A[Начало] --> B[Ввести коэффициенты a, b, c]
    B --> C[Вычислить дискриминант D = b² - 4ac]
    C --> D{D < 0?}
    D -->|Да| E[Разложение невозможно<br>нет действительных корней]
    D -->|Нет| F[Вычислить корни:<br>x₁ = -b + √D / 2a<br>x₂ = -b - √D / 2a]
    F --> G[Записать разложение:<br>ax² + bx + c = a(x - x₁)(x - x₂)]
    G --> H[Конец]
    E --> H

    style A fill:#e1f5fe
    style H fill:#e1f5fe
    style D fill:#fff3e0
    style E fill:#ffebee
    style F fill:#e8f5e9
    style G fill:#e8f5e9
