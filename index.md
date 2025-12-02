# 📄 Introdução: Construção do Modelo de Credit Scoring

O presente relatório técnico detalha a **construção e validação** de um modelo de **_Credit Scoring_** desenvolvido para apoiar a tomada de decisão em concessão de crédito.

## 🎯 Objetivo Central

O objetivo primário é estimar a probabilidade de inadimplência (default) de clientes em potencial, fornecendo um score robusto e interpretável que permita a automação e otimização das políticas de risco do banco.

## 📊 Estrutura do Desafio e Dados

A base de dados utilizada compõe-se de 10.738 registros e 81 variáveis mascaradas. O desenvolvimento do modelo é guiado pela necessidade de transparência e interpretabilidade, que são cruciais para a governança e auditoria regulatória em instituições financeiras.

## 🛡️ Escopo e Metodologia de Risco

O projeto abrange o fluxo completo de Data Science, focado em entregar um modelo de Credit Scoring estável e aplicável ao negócio.

A metodologia é estruturada em **quatro pilares**:

>1. **Pré-processamento:** Tratamento de dados, remoção de redundâncias (Multicolinearidade) e análise de estabilidade das variáveis (PSI).
>
>2. **Modelagem e Seleção:** Comparação de algoritmos (priorizando estabilidade e interpretabilidade) para identificar o melhor preditor.
>
>3. **Validação OOT:** Teste rigoroso de desempenho em um conjunto Out-of-Time (OOT) (safras Outubro, Novembro e Dezembro), crucial para simular o risco futuro e comprovar a estabilidade temporal.
>
>4. **Recomendação:** Análise final de métricas (AUC, Gini, KS) e calibração para definir o Scorecard e o ponto de corte ideal para a tomada de decisão de crédito.