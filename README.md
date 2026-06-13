# 🧠 Miniguia de Estudos: NotebookLM aplicado ao Informe Epidemiológico sobre Demência (Projeto VETERA - UnB)

Este repositório foi desenvolvido como atividade avaliativa para o curso da **DIO (Digital Innovation One)**. O objetivo é demonstrar o uso do **NotebookLM** (Google) como uma ferramenta de aprendizagem ativa e curadoria de conhecimento para a estruturação de um **Informe Epidemiológico sobre Demência focado em idosos**.

---

## 📌 1. Contexto e Objetivos

### Contexto
O **Projeto VETERA da Universidade de Brasília (UnB)** realiza ações voltadas para o público idoso. A pedido dos próprios participantes, o tema **Demência e Doença de Alzheimer** foi escolhido para a elaboração de um informe epidemiológico. Para consolidar os dados epidemiológicos locais do Distrito Federal, diretrizes mundiais e critérios de diagnóstico, foi criado um Caderno Temático no NotebookLM.

### Objetivos de Estudo
* **Análise Epidemiológica Local e Global:** Cruzar os dados mundiais de prevalência com a realidade de mortalidade no Distrito Federal.
* **Curadoria de Saúde Pública:** Sintetizar conceitos complexos (fatores de risco, diagnóstico e custos) em uma linguagem acessível para o público do projeto.
* **Superação de Limitações Tecnológicas:** Utilizar a IA de forma analítica para suprir lacunas de arquivos visuais que não puderam ser processados diretamente pela plataforma.

---

## 📚 2. Curadoria de Fontes

O caderno foi alimentado com documentos técnicos estruturados e artigos da pasta de insumos do projeto, servindo como base textual para contornar a limitação de upload de relatórios puramente visuais do Infosaúde-DF:

1. **`Demencia.docx`**: Contém dados de mortalidade do Distrito Federal (2022-2024), além de detalhar as codificações da CID-10 (Capítulo V - F00 a F03) e o uso do CIAP na Atenção Primária.
2. **`Psicologia.docx`**: Artigo científico focado nas vantagens e limitações dos instrumentos de rastreio cognitivo utilizados no Brasil (MEEM, TDR, etc.) e critérios diagnósticos do DSM-5.
3. **`Demência.xlsx` (Dados do SIM - MS/SVSA/CGIAE)**: Matriz com dados consolidados de mortalidade por residência e capítulos da CID-10.

---

## 🔬 3. Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Nesta seção, documenta-se o processo real de interação com o NotebookLM, evidenciando as estratégias para extrair o melhor resultado e como as limitações técnicas foram superadas.

### 🔴 O Desafio Tecnológico (Troubleshooting)
* **Problema:** Havia imagens de relatórios gráficos do **Infosaúde-DF** essenciais para a contextualização regional, mas o NotebookLM apresentou limitações para processar arquivos puramente visuais/imagens diretamente como fonte de texto.
* **Solução Adotada:** Os dados epidemiológicos mais importantes contidos nas imagens do Infosaúde-DF foram extraídos manualmente e consolidados na fonte textual `Demencia.docx`, permitindo que a IA fizesse o cruzamento com precisão.

### 🤖 Prompt Executado e Validação do Resultado
* **Prompt Utilizado:** *"Explique os pontos principais das fontes e quais as informações mais importantes sobre demência (incluindo Alzheimer)"*
* **Comportamento da IA:** A IA processou com sucesso o compilado de arquivos e estruturou as respostas divididas em 6 pilares fundamentais: Definição Clínica, Panorama Epidemiológico (Global e DF), Fatores de Risco, Diagnóstico/Rastreio, Tratamento/Cuidados e Impacto Econômico. 
* **Análise Crítica do Resultado:** A IA conseguiu extrair com precisão o dado regionalizado que inserimos no texto (o registro de 1.065 óbitos por transtornos mentais e 2.044 por doenças do sistema nervoso no Distrito Federal entre 2022 e 2024), validando a estratégia de contorno do problema das imagens.

---

## 📖 4. Miniguia de Estudo (Entrega Final)

### 📑 Resumo Estruturado do Assunto

#### 1. O que é a Demência e a Doença de Alzheimer?
A demência (Transtorno Neurocognitivo Maior) é uma síndrome crônica e progressiva que causa a deterioração da função cognitiva (memória, linguagem, julgamento) além do esperado no envelhecimento normal. A **Doença de Alzheimer (DA)** é a sua forma mais comum, correspondendo a **60% ou 70% dos casos**.

#### 2. Panorama Epidemiológico (Mundo vs. Distrito Federal)
* **Global:** 55,2 milhões de pessoas viviam com demência em 2019 (previsão de 139 milhões em 2050). É a 7ª maior causa de morte no mundo e afeta desproporcionalmente as **mulheres (65% das mortes)**.
* **Brasil e DF:** O Brasil ocupa a 9ª posição mundial em número de casos. No Distrito Federal (2022-2024), os dados apontam um impacto severo com **1.065 óbitos** por transtornos mentais/comportamentais e **2.044 óbitos** por doenças do sistema nervoso (incluindo Alzheimer).

#### 3. Fatores de Risco e Prevenção
Cerca de **40% dos casos podem ser prevenidos ou retardados**. Os fatores modificáveis incluem: inatividade física, tabagismo, hipertensão na meia-idade, diabetes, isolamento social, baixa escolaridade (reserva cognitiva) e fatores inflamatórios crônicos.

#### 4. Instrumentos de Rastreio no Brasil
O diagnóstico precoce ainda é um desafio. Os principais instrumentos de rastreio em território nacional são:
* **MEEM (Mini Exame do Estado Mental):** Mais utilizado, avalia orientação e memória, mas sofre forte influência da escolaridade do paciente.
* **TDR (Teste do Desenho do Relógio):** Focado em funções visuoespaciais e executivas.

#### 5. Cuidados e Impacto Econômico
As demências neurodegenerativas não têm cura. O tratamento baseia-se em intervenções não farmacológicas (estimulação cognitiva, exercícios) e medicamentos para alívio de sintomas (Donepezila, Rivastigmina). O custo global da doença passa de **1,3 trilhão de dólares**, sendo que metade disso vem do trabalho informal e não remunerado de familiares.

---

### 🔤 Glossário de Conceitos Aprendidos

* **Transtorno Neurocognitivo Maior:** Termo clínico do DSM-5 equivalente à demência, caracterizado pelo declínio cognitivo que impede a independência do indivíduo.
* **Reserva Cognitiva:** Capacidade do cérebro de tolerar melhor os efeitos da patologia associada à demência, altamente ligada a anos de estudo e estímulo intelectual.
* **Fatores Modificáveis:** Hábitos ou condições de saúde que podem ser alterados ao longo da vida para reduzir o risco de desenvolver uma doença.
* **Cuidado Informal:** Assistência prestada a pacientes de forma não profissional e não remunerada, geralmente por membros da família.

---

### 🔄 Prompts Reutilizáveis para Revisões Futuras

```text
1. "Com base nos dados estruturados do Distrito Federal (2022-2024), crie um roteiro de palestra de 15 minutos voltado para os idosos do projeto VETERA explicando a importância do controle da hipertensão e do diabetes na prevenção do Alzheimer."

2. "Gere uma tabela comparativa detalhando as vantagens e as limitações do Mini Exame do Estado Mental (MEEM) e do Teste do Desenho do Relógio (TDR) com base no arquivo Psicologia.docx."

3. "Escreva um texto informativo e acolhedor direcionado aos cuidadores familiares de idosos com demência, abordando estratégias não farmacológicas para o dia a dia e a importância do suporte à sobrecarga do cuidador."
