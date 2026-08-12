# 🧪 Testes de Prompts no NotebookLM

## Sobre este documento

Este arquivo registra os principais testes realizados no **NotebookLM** durante a construção do Caderno Temático sobre **Pensamento Computacional**.

O objetivo foi observar como alterações na formulação dos prompts modificam a profundidade, a organização e o tipo de resposta produzida pela IA.

---

# Teste 1 — Exploração inicial

## Prompt

> Explique o que é Pensamento Computacional.

## Resultado obtido

O NotebookLM definiu Pensamento Computacional como a capacidade de compreender, definir, modelar, comparar, resolver, automatizar e analisar problemas e suas soluções de maneira sistemática e estruturada.

A resposta também destacou que o Pensamento Computacional não se limita à programação e pode ser aplicado à resolução de problemas em diferentes áreas.

Além da definição, a ferramenta apresentou conceitos relacionados a:

* abstração;
* automação;
* análise;
* algoritmos;
* decomposição;
* generalização.

## Análise

Mesmo com um prompt bastante simples, a resposta foi abrangente. Entretanto, a estrutura e os conteúdos abordados ficaram principalmente sob decisão da IA.

Isso motivou a criação de um prompt mais direcionado.

---

# Teste 2 — Refinamento da instrução

## Prompt

> Com base exclusivamente nas fontes fornecidas, explique o conceito de Pensamento Computacional e identifique seus principais fundamentos. Apresente exemplos simples para facilitar a compreensão.

## Resultado obtido

A resposta passou a apresentar uma organização mais explícita dos conceitos.

O NotebookLM estruturou o Pensamento Computacional em três eixos:

### Abstração

Simplificação e representação dos elementos relevantes de um problema.

### Automação

Mecanização de uma solução para permitir sua execução sistemática.

### Análise

Avaliação crítica da solução considerando aspectos como viabilidade, correção e eficiência.

Também foram apresentados exemplos envolvendo:

* preparação de um bolo;
* ordenação de figurinhas;
* organização de provas;
* rotas em mapas.

## Análise

O refinamento proporcionou maior controle sobre o resultado.

A inclusão das expressões **"com base exclusivamente nas fontes"**, **"identifique os fundamentos"** e **"apresente exemplos"** definiu melhor o escopo e a estrutura esperada.

---

# Teste 3 — Comparação entre fontes

## Prompt

> Compare as definições de Pensamento Computacional apresentadas pelas diferentes fontes deste caderno. Identifique pontos em comum e diferenças entre elas.

## Resultado obtido

O NotebookLM identificou pontos de convergência entre as fontes, principalmente:

* Pensamento Computacional como processo de resolução de problemas;
* importância dos algoritmos;
* presença de abstração, automação e análise;
* relevância do Pensamento Computacional para a formação contemporânea.

Também identificou diferentes enfoques nas fontes:

* perspectiva lógico-matemática;
* perspectiva normativa;
* organização curricular;
* aplicação educacional.

## Análise

A alteração do verbo **"explique"** para **"compare"** modificou significativamente a tarefa.

A IA deixou de apenas recuperar e organizar informações e passou a estabelecer relações entre diferentes documentos.

---

# Teste 4 — Aplicação na Educação Básica

## Prompt

> Com base nas fontes, explique como o Pensamento Computacional pode ser desenvolvido na Educação Básica. Apresente exemplos de atividades que não dependam necessariamente do uso de computadores.

## Resultado obtido

O NotebookLM apresentou uma progressão pedagógica envolvendo:

* Educação Infantil;
* Ensino Fundamental — Anos Iniciais;
* Ensino Fundamental — Anos Finais;
* Ensino Médio.

Entre as atividades desplugadas sugeridas a partir das fontes apareceram:

* trajetórias físicas utilizando o corpo;
* organização e classificação de objetos;
* algoritmos do cotidiano;
* storytelling e sequenciamento;
* jogos de mesa;
* organização de registros;
* construção de mapas;
* atividades envolvendo decomposição;
* reconhecimento de padrões.

## Análise

Esse teste mostrou que adicionar um **contexto de aplicação** ao prompt permite transformar conceitos teóricos em possibilidades práticas.

---

# Teste 5 — Pensamento Computacional × Programação

## Prompt

> Pensamento Computacional e programação são a mesma coisa? Responda utilizando apenas as fontes disponibilizadas e apresente evidências que justifiquem a resposta.

## Resultado obtido

A resposta indicou que **Pensamento Computacional e programação não são a mesma coisa**.

O Pensamento Computacional foi apresentado como um processo mais amplo de formulação, modelagem e resolução de problemas.

A programação aparece como uma possibilidade de formalização e execução de soluções por computadores.

A resposta também destacou que habilidades relacionadas ao Pensamento Computacional podem ser desenvolvidas por meio de atividades desplugadas.

## Análise

A expressão **"apresente evidências"** foi importante porque exigiu que a resposta não apresentasse apenas uma conclusão, mas também uma justificativa fundamentada nas fontes.

---

# Teste 6 — IA como ferramenta de aprendizagem ativa

## Prompt

> Imagine que estou estudando Pensamento Computacional para uma avaliação. Elabore 10 perguntas progressivas, começando por conceitos básicos e avançando para questões de aplicação e análise. Não apresente as respostas imediatamente.

## Resultado obtido

O NotebookLM organizou as questões em níveis progressivos:

### Nível 1

Conceitos e definições.

### Nível 2

Pilares e estruturas conceituais.

### Nível 3

Aplicação prática e resolução de problemas.

### Nível 4

Complexidade e limites da Computação.

## Análise

Este teste modificou o papel da Inteligência Artificial no processo.

Em vez de solicitar uma resposta pronta, o prompt utilizou a IA para criar uma situação de **recuperação ativa do conhecimento e autoavaliação**.

---

# 🩹 Principais "cicatrizes"

Os testes permitiram identificar algumas estratégias importantes de Engenharia de Prompts.

### 1. Prompt genérico não significa necessariamente resposta ruim

O primeiro prompt produziu uma resposta satisfatória, mas ofereceu maior liberdade para a IA decidir a estrutura.

### 2. Delimitar as fontes aumenta o controle

Utilizar instruções como:

> Com base exclusivamente nas fontes fornecidas...

ajudou a delimitar o espaço de informação utilizado.

### 3. O verbo utilizado altera a tarefa

Foram observados diferentes níveis de exploração ao utilizar comandos como:

**Explicar → Comparar → Aplicar → Analisar → Justificar**

### 4. Especificar o formato melhora a organização

Solicitar exemplos, níveis de dificuldade ou evidências tornou as respostas mais adequadas ao objetivo de estudo.

### 5. IA não precisa fornecer sempre a resposta

O último experimento mostrou que a IA também pode:

* formular perguntas;
* apoiar revisões;
* criar exercícios;
* estimular recuperação ativa;
* auxiliar na autoavaliação.

---

# 🎯 Síntese do experimento

A experiência mostrou que Engenharia de Prompts não consiste apenas em criar perguntas longas.

Um bom prompt combina elementos como:

**Contexto + Objetivo + Fonte + Ação + Formato esperado**

O refinamento das instruções permitiu transformar o NotebookLM de uma ferramenta de consulta em um ambiente de apoio à investigação e à aprendizagem ativa.
