# Case Ismart — Análise da Prova Única

## Objetivo
Analisar os resultados da Prova Única para identificar padrões de desempenho dos alunos e gerar insights que possam orientar ações pedagógicas.

## Base de dados
A base contém as notas dos alunos em quatro áreas da prova:
- Ciências Humanas (CH)
- Ciências da Natureza (CN)
- Matemática (MA)
- Linguagens (LI)

Cada área possui três métricas:
- NOTA_DESEMPENHO
- Media_ENEM
- ENEM_Projetado

## Análises realizadas

### Bloco 1
Construção de uma base consolidada em que cada aluno aparece apenas uma vez, utilizando a métrica ENEM_Projetado para cada área.

### Bloco 2
- Análise de correlação entre as métricas da prova
- Comparação da média de ENEM Projetado entre as praças
- Análise exploratória para identificar áreas críticas de desempenho

## Principais insights

- Forte correlação entre as métricas de avaliação (0.86–0.97)
- Diferenças de desempenho entre praças
- São José dos Campos e Rio de Janeiro apresentam menor desempenho em Matemática
- Cotia apresenta as maiores médias da rede

## Tecnologias utilizadas
- Python
- Pandas
- Seaborn
- Matplotlib
