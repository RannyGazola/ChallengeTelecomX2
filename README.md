# Desafio TelecomX: Análise de Evasão de Clientes
O objetivo deste desafio é analisar os fatores que influenciam a evasão de clientes em uma empresa de telecomunicações e propor estratégias de retenção baseadas em modelos preditivos.
O dataset fornecido contém informações de clientes, incluindo dados demográficos, uso de serviços e histórico de pagamentos.

# Passos
- Preparação dos Dados
- Limpeza e tratamento de dados faltantes.
- Conversão de variáveis categóricas em numéricas quando necessário.
- Balanceamento da base utilizando técnicas de undersampling (NearMiss) para tratar desbalanceamento entre clientes ativos e evasores.
- Seleção de Variáveis
- Identificação das variáveis mais relevantes com base em análise de correlação e importância fornecida pelos modelos.
- Consideração de métricas de desempenho e impacto de cada variável na evasão.

# Modelos Preditivos
- Decision Tree Classifier: Modelo inicial para identificar padrões de evasão.
- K-Nearest Neighbors (KNN): Alternativa para comparação de desempenho.

Avaliação dos modelos com classification_report e matrizes de confusão.

# Fatores que Mais Influenciam a Evasão
Com base na análise de correlação e importância das variáveis nos modelos:
- Tempo de contrato: Clientes com contratos mais curtos apresentam maior risco de evasão.
- Valor da fatura mensal: Faturas mais altas estão associadas a maior probabilidade de cancelamento.
- Uso de serviços adicionais: Baixo uso de serviços extras correlaciona-se com maior evasão.
- Satisfação do cliente: Clientes insatisfeitos tendem a cancelar mais rapidamente.

# Estratégias de Retenção Propostas
Com base nos fatores identificados, as seguintes estratégias podem ser implementadas:
- Programas de Fidelidade: Oferecer benefícios e descontos para clientes com contratos curtos ou histórico de cancelamento.
- Avaliar planos e faturas para reduzir churn relacionado ao custo.
- Promoções Personalizadas: Incentivar o uso de serviços adicionais com ofertas direcionadas.
- Monitoramento de Satisfação: Implementar pesquisas regulares e análise de feedback para identificar clientes em risco.
- Suporte Proativo: Identificar clientes que têm alta frequência de contato com suporte e oferecer soluções rápidas.

# Resultados
O modelo Decision Tree Classifier apresentou melhor desempenho na previsão de evasão, com maior precisão e recall para a classe de clientes evasores.
As variáveis mais importantes para retenção foram destacadas como prioridade para ações estratégicas.

# Conclusão
A análise revelou os fatores críticos que levam à evasão de clientes, permitindo à empresa atuar de forma preventiva e estratégica. A combinação de modelos preditivos e ações direcionadas pode reduzir significativamente a taxa de churn.
