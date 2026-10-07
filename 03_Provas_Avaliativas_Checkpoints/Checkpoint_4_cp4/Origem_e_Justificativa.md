# Origem e Justificativa do Problema

**Disciplina:** Sistemas Cyber-Físicos & Tecnologias Assistivas
**Ano Letivo:** 2026 | **Turma:** 5ECS
**Avaliação:** Checkpoint 4

### Enunciado do Problema
Desenvolver a co-simulação e validação de um Gêmeo Digital sincronizado em tempo real com o exoesqueleto robótico físico via protocolo MQTT e WebSocket. Avaliar o erro de rastreamento de trajetória (Tracking Error) entre o modelo computacional preditivo baseado em equações dinâmicas de Newton-Euler e os dados reais de bancada sob perturbações externas.

### Formulação Formal
$$e(t) = \theta_{\text{real}}(t) - \theta_{\text{twin}}(t), \quad \text{RMSE} = \sqrt{\frac{1}{N}\sum_{k=1}^{N} e_k^2} \le 1,5^\circ$$
