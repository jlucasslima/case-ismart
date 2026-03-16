# Case Ismart — Análise da Prova Única 2023
# Autor - João Lucas de Lima Souza

## Objetivo
Analisar os resultados do simulado **Prova Única** para identificar padrões de desempenho dos alunos nas diferentes praças da rede Ismart e gerar insights que possam orientar ações pedagógicas.

## Estrutura da Análise

O projeto foi dividido em duas etapas:

### Bloco 1 — Preparação dos Dados
A base original possuía múltiplas linhas por aluno (uma para cada área da prova).  
Foi construída uma base consolidada onde cada aluno aparece em **uma única linha**, utilizando a métrica **ENEM_Projetado** para cada área.

### Bloco 2 — Análise Exploratória
Foram realizadas as seguintes análises:

- Matriz de correlação entre `NOTA_DESEMPENHO`, `Media_ENEM` e `ENEM_Projetado`
- Comparação da média do ENEM Projetado entre as praças
- Heatmap de desempenho por **praça × área do conhecimento**

## Principais Insights

1. **Correlação entre métricas**  
   Existe forte correlação positiva entre as três métricas de avaliação (0.86–0.97).

2. **Desempenho em Matemática**  
   As praças de **São José dos Campos (SJC)** e **Rio de Janeiro (RJ)** apresentam as menores médias em Matemática.

   *Ação sugerida:* reforço acadêmico focado em disciplinas de exatas nessas unidades.

3. **Destaque de desempenho**  
   **Cotia (CO)** apresenta as maiores médias da rede em diversas áreas.

   *Ação sugerida:* investigar práticas pedagógicas aplicadas na unidade para possível replicação.

## Tecnologias
- Python
- Pandas
- Seaborn
- Matplotlib
