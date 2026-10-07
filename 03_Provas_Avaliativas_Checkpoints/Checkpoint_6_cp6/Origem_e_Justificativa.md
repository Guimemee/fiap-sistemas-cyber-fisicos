# Origem e Justificativa do Problema

**Disciplina:** Sistemas Cyber-Físicos & Tecnologias Assistivas
**Ano Letivo:** 2026 | **Turma:** 5ECS
**Avaliação:** Checkpoint 6

### Enunciado do Problema
Analisar a resiliência e mitigar vulnerabilidades cibernéticas em redes de controle de Sistemas Cyber-Físicos conforme as diretrizes da norma internacional IEC 62443. Simular ataques de injeção de pacotes falsos (False Data Injection Attack - FDIA) e negação de serviço (DoS) na rede de controle, projetando um detector de anomalias baseado em resíduos estatísticos (Chi-Quadrado de Cusum).

### Formulação Formal
$$z_k = y_k - C \hat{x}_{k|k-1}, \quad g_k = z_k^T \Sigma_z^{-1} z_k \sim \chi^2(m), \quad g_k > \gamma \implies \text{Alarme de Ataque}$$
