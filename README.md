# Segundo Cérebro: Data Analytics

> Notebook especialista em Análise de Dados, criado no Gemini Notebook (antigo NotebookLM) a partir de fontes que eu selecionei.

**Link do notebook compartilhado:** [COLE AQUI O LINK DO NOTEBOOK]

---

## 1. Tema e objetivo

**Tema:** Análise de Dados (Data Analytics), com foco no caminho para atuar como Analista de Dados.

**Objetivo:** Ter um notebook que me ajude a entender as competências, ferramentas, conceitos e a ordem de estudos para me tornar Analista de Dados, respondendo apenas com base em vídeos e textos que eu selecionei e mostrando de onde tirou cada resposta.

---

## 2. Fontes que entraram

O notebook tem 11 fontes, em dois formatos: vídeos do YouTube e páginas da web.

| # | Fonte | Formato | Por que entrou |
|---|-------|---------|----------------|
| 1 | 2026 FREE Data Analyst Bootcamp [24 Hours+] | Vídeo (YouTube) | Curso completo de Analista de Dados (SQL, BI, Excel, Python, carreira), do Alex The Analyst |
| 2 | SQL Tutorial for Data Analysis: Beginner SQL Guide | Vídeo (YouTube) | Reforço didático de SQL para análise |
| 3 | Mean, Mode and Median - Measures of Central Tendency | Vídeo (YouTube) | Base de estatística descritiva |
| 4 | Standard Deviation | Vídeo (YouTube) | Base de estatística (medidas de variabilidade) |
| 5 | Treinamento para analistas de dados | Página web (Microsoft Learn) | Documentação oficial do fabricante do Power BI |
| 6 | Dados de modelo com o Power BI | Página web (Microsoft Learn) | Documentação oficial sobre modelagem de dados |
| 7 | Prepare data for analysis with Power BI | Página web (Microsoft Learn) | Documentação oficial sobre preparação e limpeza de dados |
| 8 e 9 | Learn data and analytics for free with Tableau (2 páginas) | Página web (Tableau) | Material oficial do fabricante do Tableau |
| 10 | DAX | Página web (SQLBI) | Referência técnica sobre a linguagem DAX |
| 11 | Vídeos | Página web (SQLBI) | Aulas em vídeo complementares sobre DAX e modelagem |

**Critérios que usei para aceitar uma fonte:**
1. Quem publica e se tem autoridade no assunto.
2. Se é recente o bastante para o tema.
3. Se cita referências ou dados verificáveis.
4. Se posso compartilhar o material sem problema (sem dados pessoais ou conteúdo restrito).

**Limitações que reconheço:**
- Várias fontes vêm de fornecedores de ferramentas (Microsoft, Tableau, SQLBI), que tendem a destacar o próprio produto.
- Há poucas fontes dedicadas a Python, R e Excel; o conteúdo sobre esses temas vem principalmente do bootcamp.

---

## 3. Diretriz de comportamento do notebook

Em todas as perguntas usei uma diretriz de papel e de restrição às fontes:

```
Atue como um mentor sênior de Análise de Dados. Com base exclusivamente nas
fontes deste notebook, responda indicando quais fontes sustentam cada
afirmação importante. Não invente informações que não estejam nas fontes.
```

---

## 4. Perguntas, respostas e fontes

### Pergunta 1: Visão geral da área

**Prompt:** Pedi uma visão geral da área de Análise de Dados organizada em 7 partes: competências técnicas, ferramentas, conceitos fundamentais, fluxo de um projeto, habilidades de negócio e comunicação, erros comuns de iniciantes e ordem recomendada de estudos, com as fontes de cada afirmação importante.

**Resposta (resumo):** O notebook montou um guia com SQL, ferramentas de BI (Tableau e Power BI), Excel, Python e R, nuvem (AWS, Azure), conceitos como métricas vs. KPIs, tipos de dados e Arquitetura Medallion, o fluxo de ingestão até a publicação do dashboard e a ordem de estudos: SQL, BI, Excel, linguagem de programação e nuvem.

**Fontes das respostas:** bootcamp de Data Analyst (ordem de estudos, portfólio, entrevistas), Microsoft Learn (preparação e modelagem de dados), Tableau (visualização), SQLBI (DAX) e os vídeos de estatística (tendência central).

![Resposta 1](prints/chat-01-visao-geral.png)

---

### Pergunta 2: Auditoria crítica das fontes

**Prompt:** Pedi que o notebook auditasse a própria resposta anterior, separando as afirmações em (1) diretamente sustentadas, (2) parcialmente sustentadas e (3) não encontradas nas fontes, com atenção a AWS, Azure, Google Cloud, Databricks, Snowflake, Medallion, mercado de trabalho, entrevistas, portfólio e ordem de estudos.

**Resposta (resumo):** O notebook classificou a maior parte como diretamente sustentada e apontou dois pontos **não encontrados nas fontes**: a afirmação de que o Snowflake é baseado em Spark e detalhes de serviços do Google Cloud. Também indicou que "dplyr" e "ggplot2" aparecem nas fontes só como transcrições fonéticas de vídeo.

**Fontes das respostas:** bootcamp de Data Analyst e aulas de Databricks/engenharia de dados presentes nas fontes.

![Resposta 2](prints/chat-02-auditoria.png)

---

### Pergunta 3: Roteiro prático de SQL

**Prompt:** Pedi um roteiro de SQL em níveis (iniciante, intermediário e avançado) com, para cada conceito, o que é, para que serve, quando usar, um exemplo e a fonte.

**Resposta (resumo):** Iniciante: SELECT, WHERE, funções agregadas, GROUP BY, ORDER BY e HAVING. Intermediário: JOINs, CASE WHEN, subqueries e funções de janela. Avançado: CTEs. Os exemplos usam as tabelas `employee_demographics` e `employee_salary` do bootcamp.

**Fontes das respostas:** lições de MySQL do bootcamp de Data Analyst.

---

### Pergunta 4: Auditoria dos níveis do roteiro

**Prompt:** Pedi que o notebook verificasse se as fontes afirmam explicitamente o nível de cada conceito, em formato de tabela.

**Resposta (resumo):** O instrutor declara explicitamente os níveis intermediário (JOINs, UNIONs, case statements, subqueries e window functions) e avançado (CTEs). Para o nível iniciante, a classificação decorre da ordem das aulas.

**Minha observação:** o nível iniciante é inferido pela ordem das aulas, e os níveis são os de um único curso, não um padrão geral do mercado.

---

### Pergunta 5: Verificação das afirmações principais

**Prompt:** Pedi a verificação da ordem de estudos, Arquitetura Medallion, métricas vs. KPIs, portfólio, entrevistas, lacunas (Snowflake e Google Cloud) e exemplos de código.

**Resposta (resumo):**
- A **ordem de estudos** (SQL, BI, Excel, Python/R, nuvem) vem de uma única fonte: o bootcamp.
- A **Arquitetura Medallion** (Bronze, Silver, Gold) aparece nas aulas de Databricks.
- A frase "todos os KPIs são métricas, mas nem todas as métricas são KPIs" consta nas transcrições.
- O **Snowflake** é citado apenas como concorrente do Databricks; as fontes não dizem que ele é baseado em Spark.
- A query com `HAVING AVG(salary) > 75000` aparece na aula de HAVING vs WHERE, mas foi **simplificada** pelo notebook (a aula também usa `WHERE occupation LIKE '%manager%'`).
- A query com `DENSE_RANK() OVER(PARTITION BY ...)` vem da aula de Window Functions.

**Conferência manual:** abri a citação da ordem de estudos e confirmei o trecho na fonte.

![Citação da ordem de estudos](prints/citacao-01-ordem-de-estudos.png)

---

## 5. Pontos de atenção que registrei

- O nível iniciante do roteiro de SQL é inferido pela ordem das aulas.
- Os níveis vêm de um único curso.
- O roteiro não incluiu UNIONs, LIMIT e aliasing, que aparecem nas fontes.
- Um exemplo de código foi simplificado em relação à aula.
- A auditoria foi feita pelo próprio notebook; por isso conferi manualmente ao menos a citação mais importante.

---

## 6. Materiais gerados no Estúdio

| Material | Arquivo |
|----------|---------|
| Mapa mental | [materiais/mapa-mental.png.png](materiais/mapa-mental.png.png) |
| Playbook do Analista de Dados (PDF) | [materiais/playbook-analista-dados.pdf.pdf](materiais/playbook-analista-dados.pdf.pdf) |

---

## 7. Estrutura do repositório

```
.
├── README.md
├── materiais/
│   ├── mapa-mental.png.png
│   └── playbook-analista-dados.pdf.pdf
└── prints/
    ├── chat-01-visao-geral.png
    ├── chat-02-auditoria.png
    └── citacao-01-ordem-de-estudos.png
```

---

## 8. Aprendizados

- Um notebook com poucas fontes bem escolhidas responde melhor e permite conferir cada resposta pela citação.
- Pedir que a IA audite a própria resposta ajudou a encontrar o que não estava nas fontes (Snowflake e Spark).
- Mesmo com a auditoria, vale abrir as citações: a decisão sobre o que confiar continua sendo minha.
