# 🧠 Miniguia de Estudos: NotebookLM aplicado ao Informe Epidemiológico sobre Demência (Projeto VETERA - UnB)

Este repositório foi desenvolvido como atividade avaliativa para o curso da **... (Digital Innovation One)**. O objetivo é demonstrar o uso do **NotebookLM** (Google) como uma ferramenta de aprendizagem ativa e curadoria de conhecimento para a estruturação de um **Informe Epidemiológico sobre Demência focado em idosos**.

---

## 📌 1. Contexto e Objetivos

### Contexto
O **Projeto VETERA da Universidade de Brasília (UnB)** realiza ações voltadas para o público idoso. A pedido dos próprios participantes, o tema **Demência e Doença de Alzheimer** foi escolhido para a elaboração de um informe epidemiológico. Para consolidar as diretrizes globais da OMS, revisões sistemáticas de literatura nacional e dados de mortalidade locais, foi estruturado um Caderno Temático no NotebookLM.

### Objetivos de Estudo
* **Análise Epidemiológica Integrada:** Cruzar as diretrizes do relatório global da OMS com indicadores reais de mortalidade e prevalência no Brasil e no Distrito Federal.
* **Curadoria Científica de Alta Maturidade:** Compilar revisões sistemáticas sobre intervenções de cuidados paliativos e rastreio neuropsicológico.
* **Superação de Limitações Tecnológicas:** Utilizar a engenharia de prompts para extrair dados estruturados e contornar a impossibilidade de leitura direta de relatórios visuais/gráficos.

---

## 📚 2. Curadoria de Fontes

O caderno temático no NotebookLM foi alimentado com a seguinte base documental científica e de dados abertos:

1. **`9789240033245-eng.pdf` (OMS/WHO)**: *Global status report on the public health response to dementia*. Relatório global da Organização Mundial da Saúde que estabelece os panoramas mundiais, metas e o impacto socioeconômico da demência.
2. **`162+BJHR.pdf` (Maragno et al.)**: *Intervenções de cuidados paliativos em pacientes com demência avançada: uma revisão sistemática*. Publicado na Brazilian Journal of Health Review, detalha o manejo de sintomas e suporte à família.
3. **`admin,+ART.+321+BJHR.pdf` (Gonçalves et al.)**: *A problemática da epidemia de demência vascular no Brasil: uma revisão bibliográfica*. Estudo focado nos fatores de risco e prevalência da demência vascular em território nacional.
4. **`alba,+70_79.pdf` (Argimon et al.)**: *Contribuições da avaliação neuropsicológica na investigação da doença de Alzheimer*. Focado na importância de exames precoces e diagnósticos diferenciais.
5. **`admin,+v17n3a10.pdf` (Lentsck et al.)**: *Prevalência de sintomas depressivos e sinais de demência em idosos na comunidade*. Estudo transversal que mapeia os sinais iniciais da síndrome demencial.
6. **Dados do DATASUS (SIM) & Infosaúde-DF**: Dados brutos do Sistema de Informações sobre Mortalidade (MS/SVSA/CGIAE) e relatórios do Distrito Federal que forneceram a base estatística regional.

---

## 🔬 3. Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

### 🔴 O Desafio Tecnológico (Troubleshooting)
* **Problema:** O NotebookLM é uma excelente ferramenta para processar documentos textuais e PDFs complexos (como o relatório global da OMS), mas apresentou limitações para processar diretamente os arquivos e imagens puramente visuais/gráficos extraídos do **Infosaúde-DF**.
* **Solução Adotada (Raciocínio Crítico):** Os dados essenciais dos infográficos do Infosaúde-DF e as planilhas do **DATASUS** foram consolidados textualmente e contextualizados nos prompts estruturados ou cruzados dinamicamente com as fontes literárias inseridas no caderno, permitindo que a IA os interpretasse no contexto epidemiológico correto.

### 🤖 Prompt Executado e Validação do Resultado
* **Prompt Utilizado:** *"Explique os pontos principais das fontes e quais as informações mais importantes sobre demência (incluindo Alzheimer)"*
* **Comportamento da IA:** A IA realizou uma varredura nas fontes científicas carregadas (OMS, BJHR, estudos de rastreio e prevalência) e estruturou um resumo analítico completo dividido em pilares (Definição, Panorama Global/DF, Fatores de Risco, Diagnóstico/Rastreio, Tratamento/Cuidados e Impacto Econômico).
* **Análise Crítica:** A IA validou perfeitamente as estatísticas de mortalidade inseridas do Distrito Federal (1.065 óbitos por transtornos mentais e 2.044 por doenças do sistema nervoso entre 2022 e 2024), comprovando a eficácia de extrair os dados do Infosaúde-DF/DATASUS e contextualizá-los junto à literatura científica.

---

## 📖 4. Miniguia de Estudo (Entrega Final)

### 📑 Resumo Estruturado do Assunto

#### 1. Definição Clínica e Epidemiologia (OMS & Literatura)
A demência (Transtorno Neurocognitivo Maior) é uma síndrome crônica e progressiva caracterizada pela deterioração cognitiva global. A **Doença de Alzheimer (DA)** representa a etiologia mais prevalente (**60% a 70% dos casos**), seguida de perto pela **Demência Vascular (DV)**, considerada um grave problema de saúde pública no Brasil. Segundo a OMS, em 2019 estimava-se 55,2 milhões de pessoas vivendo com a condição no mundo. O Brasil já ocupa a 9ª posição mundial.

#### 2. Recorte Regional (Infosaúde-DF & DATASUS)
No Distrito Federal, o impacto epidemiológico mapeado entre os anos de 2022 e 2024 aponta uma alta taxa de mortalidade relacionada a estas condições: foram registrados **1.065 óbitos** por transtornos mentais e comportamentais e **2.044 óbitos** por doenças do sistema nervoso (categoria que engloba a Doença de Alzheimer). Globalmente e regionalmente, a demência afeta desproporcionalmente as **mulheres (cerca de 65% das mortes relacionadas)**.

#### 3. Prevenção, Diagnóstico e Rastreio Neuropsicológico
A literatura aponta que **40% dos casos podem ser prevenidos ou retardados** através do controle de fatores modificáveis (inatividade física, tabagismo, hipertensão, diabetes, isolamento social e inflamações crônicas). O baixo nível educacional é um fator crítico, enquanto a alta escolaridade constrói a *reserva cognitiva*. 
Para o diagnóstico precoce e diferencial, a **avaliação neuropsicológica** é indispensável. Instrumentos aplicados no Brasil como o **Mini Exame do Estado Mental (MEEM)** e o **Teste do Desenho do Relógio (TDR)** auxiliam na triagem de sinais de demência e sintomas depressivos na comunidade, embora o MEEM sofra forte influência do nível de alfabetização.

#### 4. Tratamento, Cuidados Paliativos e Custo Informal
Por se tratarem de patologias neurodegenerativas sem cura, as intervenções não farmacológicas (estimulação cognitiva, exercícios físicos, musicoterapia) e o tratamento medicamentoso sintomático (inibidores da acetilcolinesterase) visam a manutenção da autonomia. Na demência avançada, os **Cuidados Paliativos (CP)** tornam-se essenciais para o manejo da dor e conforto.
O impacto financeiro global ultrapassa **1,3 trilhão de dólares**, sendo que metade desse valor é sustentado pelo **cuidado informal e não remunerado** desempenhado por familiares e cuidadores, evidenciando uma sobrecarga física e emocional gritante.

---

### 🔤 Glossário de Conceitos Aprendidos

* **Transtorno Neurocognitivo Maior:** Terminologia clínica atualizada que engloba as síndromes demenciais onde há declínio cognitivo significativo com perda da independência funcional.
* **Avaliação Neuropsicológica:** Investigação detalhada das funções cognitivas e comportamentais que permite o diagnóstico diferencial entre o envelhecimento normal e os subtipos de demência (Alzheimer vs. Vascular).
* **Cuidados Paliativos em Demência:** Abordagem multidisciplinar focada na qualidade de vida, manejo do sofrimento e controle de sintomas em fases avançadas da doença.
* **Cuidado Informal:** Assistência diária oferecida ao paciente de forma voluntária e não profissional, majoritariamente realizada por familiares sem remuneração.

---

### 🔄 Prompts Reutilizáveis para Revisões Futuras

```text
1. "Baseando-se no relatório global da OMS (9789240033245-eng.pdf) e na revisão sobre demência vascular, elabore um texto explicativo para os idosos do projeto VETERA detalhando como os hábitos de vida saudáveis protegem os vasos cerebrais e reduzem o risco de demência."

2. "Considerando as contribuições da avaliação neuropsicológica (alba, 70_79.pdf), explique as diferenças na aplicação prática entre o MEEM e o Teste do Desenho do Relógio e como interpretar os resultados em pacientes de baixa escolaridade."

3. "A partir da revisão sobre cuidados paliativos na demência avançada (162+BJHR.pdf), sintetize os principais desafios apontados no cenário brasileiro para a implementação dessas intervenções e quais estratégias podem aliviar a sobrecarga do cuidador familiar."
