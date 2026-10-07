# Origem e Justificativa do Problema

**Disciplina:** Sistemas Cyber-Físicos & Tecnologias Assistivas
**Ano Letivo:** 2026 | **Turma:** 5ECS
**Avaliação:** Checkpoint 2

### Enunciado do Problema
Consolidar os relatórios experimentais das aulas laboratoriais da disciplina, demonstrando o processamento de sinais de sensores inerciais (IMU MPU6050/ICM-42688) utilizando Filtro Complementar e Filtro de Kalman discreto para estimativa precisa dos ângulos de Roll e Pitch, eliminando o efeito do drift do giroscópio e o ruído de vibração do acelerômetro.

### Formulação Formal
$$\theta_k = \alpha \cdot (\theta_{k-1} + \omega_k \cdot \Delta t) + (1 - \alpha) \cdot \theta_{\text{acc}}, \quad K_k = \frac{P_{k|k-1} H^T}{H P_{k|k-1} H^T + R}$$
