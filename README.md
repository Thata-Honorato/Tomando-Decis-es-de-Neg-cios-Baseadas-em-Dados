# Sprint 9 – Priorização de Hipóteses e Análise de Teste A/B

## Descrição do Projeto

Neste projeto, a análise é voltada para uma grande loja online. Trabalhando com o departamento de marketing, priorizar hipóteses que podem aumentar a receita, realizar um teste A/B e analisar os resultados para tomar decisões baseadas em dados.

---

## Descrição dos Dados

### Parte 1 – Priorização de Hipóteses

Arquivo: `/datasets/hypotheses_us.csv`

| Coluna      | Descrição |
|------------|-----------|
| Hypotheses | Breve descrição da hipótese |
| Reach      | Alcance estimado da hipótese (1 a 10) |
| Impact     | Impacto esperado nos usuários (1 a 10) |
| Confidence | Nível de confiança na hipótese (1 a 10) |
| Effort     | Recursos necessários para testar a hipótese (1 a 10) |

> Nota: Quanto maior o valor de `Effort`, mais recursos são necessários para testar a hipótese.

### Parte 2 – Análise de Teste A/B

Arquivos: `/datasets/orders_us.csv` e `/datasets/visits_us.csv`

**orders_us.csv**

| Coluna       | Descrição |
|--------------|-----------|
| transactionId | Identificador único do pedido |
| visitorId    | Identificador do usuário |
| date         | Data do pedido |
| revenue      | Receita do pedido |
| group        | Grupo do teste A/B (A ou B) |

**visits_us.csv**

| Coluna | Descrição |
|--------|-----------|
| date   | Data da visita |
| group  | Grupo do teste A/B (A ou B) |
| visits | Número de visitas para o grupo no dia especificado |


---

## Parte 1 – Priorização de Hipóteses

1. Aplicar o **framework ICE** para priorizar hipóteses e classificar em ordem decrescente de prioridade.
2. Aplicar o **framework RICE** para priorizar hipóteses e classificar em ordem decrescente de prioridade.
3. Comparar como a priorização muda de ICE para RICE e explicar as diferenças.

---

## Parte 2 – Análise de Teste A/B

1. Gerar gráficos da receita acumulada por grupo e tirar conclusões.
2. Plotar o tamanho médio acumulado do pedido por grupo e interpretar os resultados.
3. Calcular a diferença relativa no tamanho médio acumulado do pedido para o grupo B em relação ao grupo A e interpretar.
4. Calcular a **taxa de conversão diária** de cada grupo e plotar comparações.
5. Calcular a diferença relativa na conversão cumulativa entre os grupos.
6. Determinar os percentis 95 e 99 para número de pedidos por usuário e identificar anomalias.
7. Plotar dispersão dos preços dos pedidos e identificar outliers.
8. Calcular percentis 95 e 99 dos preços dos pedidos para detectar anomalias.
9. Verificar significância estatística da diferença de conversão entre grupos usando dados brutos e filtrados.
10. Verificar significância estatística da diferença no tamanho médio do pedido entre grupos usando dados brutos e filtrados.
11. Tomar decisão final baseada nos resultados do teste:
    - Parar o teste e considerar um grupo líder.
    - Parar o teste e concluir que não há diferença.
    - Continuar o teste.

---

## Avaliação do Projeto

O projeto será avaliado com base nos seguintes critérios:

- Preparação adequada dos dados para análise
- Priorização clara e fundamentada de hipóteses
- Interpretação correta dos gráficos e métricas
- Cálculo adequado da significância estatística
- Conclusões bem fundamentadas baseadas no teste A/B
- Organização do código e clareza na apresentação
- Comentários explicativos em cada etapa

Todos os notebooks originais estão hospedados na plataforma TripleTen e não podem ser alterados.  
- Este repositório documenta o projeto e o aprendizado adquirido.
