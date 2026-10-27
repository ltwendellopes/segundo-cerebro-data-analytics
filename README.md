# Segundo Cérebro: Data Analytics

> Notebook especialista em Análise de Dados, construído no Gemini Notebook (antigo NotebookLM) a partir de fontes que eu mesmo selecionei e conferi.

**Link do notebook compartilhado:** [PREENCHER: cole aqui o link de compartilhamento]

---

## 1. Tema e objetivo

**Tema:** Análise de Dados (Data Analytics), com foco no caminho para atuar como Analista de Dados.

**Objetivo (em uma frase):**
[PREENCHER: escreva com as suas palavras. Sugestão de formato: "Quero que meu notebook me ajude a entender as competências, ferramentas e a ordem de estudos para me tornar Analista de Dados, com base em vídeos e textos confiáveis."]

---

## 2. Fontes que entraram

O notebook tem 11 fontes, em formatos diferentes (vídeos do YouTube e páginas da web). Abaixo, cada uma com o motivo da minha confiança.

| # | Fonte | Formato | Quem publica | Por que confio |
|---|-------|---------|--------------|----------------|
| 1 | 2026 FREE Data Analyst Bootcamp [24 Hours+] | Vídeo (YouTube) | [PREENCHER: Alex The Analyst?] | [PREENCHER] |
| 2 | SQL Tutorial for Data Analysis: Beginner SQL Guide | [PREENCHER] | [PREENCHER] | [PREENCHER] |
| 3 | Mean, Mode and Median - Measures of Central Tendency | [PREENCHER] | [PREENCHER] | [PREENCHER] |
| 4 | Standard Deviation | Vídeo (YouTube) | [PREENCHER] | [PREENCHER] |
| 5 | Treinamento para analistas de dados (Microsoft Learn) | Página web | Microsoft | [PREENCHER] |
| 6 | Dados de modelo com o Power BI (Microsoft Learn) | Página web | Microsoft | [PREENCHER] |
| 7 | Prepare data for analysis with Power BI (Microsoft Learn) | Página web | Microsoft | [PREENCHER] |
| 8 | Learn data and analytics for free with Tableau | Página web | Tableau | [PREENCHER] |
| 9 | DAX (SQLBI) | Página web | SQLBI | [PREENCHER] |
| 10 | Vídeos (SQLBI) | Página web | SQLBI | [PREENCHER] |
| 11 | [PREENCHER: confirme a fonte restante ou remova a duplicada do Tableau] | | | |

**Critérios que usei para aceitar uma fonte:**
1. Quem publica e se tem autoridade no assunto.
2. Se é recente o bastante para o tema.
3. Se cita referências ou dados verificáveis.
4. Se posso compartilhar o material sem problema (sem dados pessoais ou conteúdo restrito).

**Limitações que reconheço:**
- [PREENCHER: por exemplo, "boa parte das fontes vem de fornecedores de ferramentas (Microsoft, Tableau, SQLBI), que tendem a destacar o próprio produto".]
- [PREENCHER: por exemplo, "as fontes sobre Python, R e Excel são menos numerosas que as de SQL e BI".]

---

## 3. Diretriz de comportamento do notebook

```
[PREENCHER: cole aqui o texto exato da diretriz, por exemplo:
Comporte-se como um mentor sênior de Análise de Dados. Responda com base exclusivamente nas fontes deste notebook, indique quais fontes sustentam cada afirmação importante e não invente informações que não estejam nas fontes.]
```

---

## 4. Perguntas, respostas e fontes

Cada resposta abaixo foi gerada pelo notebook. Em cada uma, abri as citações para conferir de onde veio a informação. Os prints estão na pasta `prints/`.

### Pergunta 1: Visão geral da área

**Prompt:**
> Atue como um mentor sênior de Análise de Dados. Com base exclusivamente nas fontes deste notebook, construa uma visão geral da área de Análise de Dados para alguém que deseja atuar profissionalmente como Analista de Dados. Organize a resposta em: 1) principais competências técnicas, 2) principais ferramentas, 3) conceitos fundamentais, 4) fluxo completo de um projeto de análise de dados, 5) habilidades de negócio e comunicação, 6) erros comuns de iniciantes e 7) uma ordem recomendada de estudos. Para cada afirmação importante, indique quais fontes sustentam a resposta. Não invente informações que não estejam nas fontes.

**Resumo da resposta:** [PREENCHER: 3 a 5 linhas com o que o notebook respondeu.]

**Fontes citadas:** [PREENCHER: títulos das fontes que apareceram nas citações.]

**Print:** ![Resposta 1](prints/chat-01-visao-geral.png)

---

### Pergunta 2: Auditoria crítica das fontes

**Prompt:** Pedi que o notebook auditasse a própria resposta anterior, separando as afirmações em (1) diretamente sustentadas, (2) parcialmente sustentadas ou interpretação e (3) não encontradas nas fontes, com atenção a AWS, Azure, Google Cloud, Databricks, Snowflake, Arquitetura Medallion, mercado de trabalho, entrevistas, portfólio e ordem de estudos.

**Resumo da resposta:** O notebook classificou a maior parte como diretamente sustentada e identificou dois pontos que **não estavam nas fontes**: a afirmação de que o Snowflake é baseado em Spark e detalhes de serviços do Google Cloud. Ele também apontou que "dplyr" e "ggplot2" aparecem nas fontes apenas como transcrições fonéticas de vídeo.

**Fontes citadas:** [PREENCHER]

**Print:** ![Resposta 2](prints/chat-02-auditoria.png)

---

### Pergunta 3: Roteiro prático de SQL

**Prompt:** Pedi um roteiro de SQL em níveis (iniciante, intermediário e avançado), com, para cada conceito, o que é, para que serve, quando usar, um exemplo prático e a fonte que sustenta.

**Resumo da resposta:** O notebook organizou SELECT, WHERE, funções agregadas, GROUP BY, ORDER BY e HAVING no nível iniciante; JOINs, CASE WHEN, subqueries e funções de janela no intermediário; e CTEs no avançado, com exemplos usando as tabelas `employee_demographics` e `employee_salary`.

**Fontes citadas:** [PREENCHER]

**Print:** ![Resposta 3](prints/chat-03-roteiro-sql.png)

---

### Pergunta 4: Auditoria dos níveis do roteiro

**Prompt:** Pedi que o notebook verificasse se as fontes afirmam explicitamente o nível (iniciante, intermediário, avançado) de cada conceito, em formato de tabela.

**Resumo da resposta:** O notebook indicou que o instrutor declara explicitamente os níveis intermediário (JOINs, UNIONs, case statements, subqueries e window functions) e avançado (CTEs). Para o nível iniciante, a classificação decorre da ordem das aulas.

**Minha observação:** O nível iniciante é **inferido pela ordem das aulas**, não declarado pelo instrutor. Os níveis são os do bootcamp de **um único curso**, não um padrão geral do mercado.

**Fontes citadas:** [PREENCHER]

**Print:** ![Resposta 4](prints/chat-04-niveis.png)

---

### Pergunta 5: Verificação com citações

**Prompt:** Pedi que o notebook mostrasse a verificação das afirmações principais (ordem de estudos, Medallion, KPIs, portfólio, entrevistas, lacunas e exemplos de código).

**Resumo da resposta:** O notebook indicou que uma única fonte (o bootcamp) traz a ordem de estudos completa; que a Arquitetura Medallion aparece nas aulas de Databricks; que as definições de métricas e KPIs constam nas transcrições; e que o Snowflake é citado apenas como concorrente do Databricks.

**Fontes citadas:** [PREENCHER]

**Print:** ![Resposta 5](prints/chat-05-verificacao.png)

---

## 5. O que eu verifiquei (minha curadoria)

O notebook pode auditar a si mesmo, mas a verificação que conta é a minha. Abri as citações e conferi:

| Afirmação | Fonte | Print | Confere? | Observação |
|-----------|-------|-------|----------|------------|
| Ordem de estudos (SQL → BI → Excel → Python/R → nuvem) | Bootcamp (vídeo) | [citacao-01](prints/citacao-01-ordem-de-estudos.png) | [PREENCHER: sim / em parte / não] | Uma única fonte traz a sequência |
| Arquitetura Medallion (Bronze, Silver, Gold) | [PREENCHER] | [citacao-02](prints/citacao-02-medallion.png) | [PREENCHER] | |
| Métricas vs. KPIs | [PREENCHER] | [citacao-03](prints/citacao-03-kpis.png) | [PREENCHER] | Frase literal nas transcrições |
| 3 a 5 projetos de portfólio no GitHub Pages | Bootcamp (vídeo) | [citacao-04](prints/citacao-04-portfolio.png) | [PREENCHER] | |
| Snowflake não é descrito como baseado em Spark | [PREENCHER] | [citacao-05](prints/citacao-05-snowflake.png) | [PREENCHER] | Erro da primeira resposta, corrigido na auditoria |
| Query com `HAVING AVG(salary) > 75000` | Aula HAVING vs WHERE | [citacao-06](prints/citacao-06-having.png) | [PREENCHER] | Versão simplificada: a aula usa também `WHERE occupation LIKE '%manager%'` |
| Query com `DENSE_RANK() OVER(PARTITION BY ...)` | Aula Window Functions | [citacao-07](prints/citacao-07-dense-rank.png) | [PREENCHER] | |

**Pontos de atenção que registrei:**
- O nível iniciante do roteiro de SQL é inferido pela ordem das aulas.
- Os níveis vêm de um único curso.
- O roteiro não incluiu UNIONs, LIMIT e aliasing, que aparecem nas fontes.
- Um exemplo de código foi simplificado em relação à aula.
- [PREENCHER: outros pontos que você encontrou ao conferir.]

---

## 6. Materiais gerados no Estúdio

| Material | Arquivo |
|----------|---------|
| Mapa mental | [materiais/mapa-mental.png](materiais/mapa-mental.png) |
| Apresentação de slides | [materiais/slides.pdf](materiais/slides.pdf) |
| [PREENCHER: guia de estudos / teste / resumo em áudio, se gerar] | [PREENCHER] |

---

## 7. Estrutura do repositório

```
.
├── README.md
├── materiais/
│   ├── mapa-mental.png
│   └── slides.pdf
└── prints/
    ├── chat-01-visao-geral.png
    ├── chat-02-auditoria.png
    ├── chat-03-roteiro-sql.png
    ├── chat-04-niveis.png
    ├── chat-05-verificacao.png
    └── citacao-01-ordem-de-estudos.png ... citacao-07-dense-rank.png
```

---

## 8. Aprendizados

- [PREENCHER: o que você aprendeu sobre Análise de Dados.]
- [PREENCHER: o que aprendeu sobre escolher fontes e conferir respostas de IA.]
- [PREENCHER: o que faria diferente numa próxima vez.]

---

## Checklist antes de enviar

- [ ] Cada resposta citada no README mostra de qual fonte veio.
- [ ] O notebook abre pelo link (testado em aba anônima).
- [ ] Nenhuma fonte tem dado pessoal ou material que não posso compartilhar.
- [ ] Todo arquivo citado no README existe e tem conteúdo.
- [ ] O link enviado é o do repositório, não o do notebook.
- [ ] O repositório está na minha conta e público.
- [ ] O nome do repositório está em minúsculas e sem acento.
