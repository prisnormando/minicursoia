# Roteiro de Oficina Introdutória: IA para Pesquisa em Saúde Coletiva e Organização de Congressos

**Duração:** 6 horas
**Público-alvo:** Profissionais de vigilância em saúde, pesquisadores e organizadores de eventos científicos.
**Ferramenta Principal:** Microsoft Copilot (via web, licença educacional do Teams).
**Tema de Aplicação:** Elaboração de um congresso técnico-científico na área de vigilância em saúde.

---

## Introdução e Objetivos da Oficina

Esta oficina foi desenhada para capacitar profissionais de saúde coletiva no uso de sistemas algorítmicos e Inteligência Artificial (IA) generativa, com foco na organização de um congresso técnico-científico em vigilância em saúde. Ao longo de seis horas, os participantes irão compreender os fundamentos da IA, discutir seus aspectos éticos e aplicar ferramentas práticas, como o Microsoft Copilot, para automatizar tarefas complexas.

Os objetivos específicos incluem a compreensão dos tipos de IA, a criação de agentes automatizados para busca de especialistas, emissão de passagens, elaboração de programas, gestão de convites e emissão de certificados.

---

## Módulo 1: Fundamentos da Inteligência Artificial (1,5 horas)

### 1.1 O que são Sistemas Algorítmicos?

Sistemas algorítmicos são conjuntos de instruções matemáticas e estatísticas que trabalham de forma orquestrada para solucionar problemas. As Inteligências Artificiais são subtipos desses sistemas, baseadas em cálculos avançados e grandes bases de conhecimento, sem serem explicitamente programadas para cada ação específica [1].

Existem três macrotipos principais de IA que os participantes devem compreender:
*   **IA Restrita (Narrow AI):** Sistemas desenvolvidos para realizar uma tarefa específica, como reconhecimento facial, recomendação de produtos ou tradução de idiomas.
*   **IA Generativa:** Modelos capazes de criar novos conteúdos, como textos, imagens, áudios e códigos, a partir de padrões aprendidos em vastos conjuntos de dados de treinamento. O Microsoft Copilot é um exemplo clássico desta categoria.
*   **IA Geral (AGI):** Um conceito teórico de sistemas com capacidade cognitiva comparável à humana, ainda não alcançado na prática.

Para deslindar a imagem apresentada nos slides sobre os tipos de IA, podemos organizar as subáreas da seguinte forma:

| Categoria Principal | Subáreas e Aplicações | Exemplos Práticos |
| :--- | :--- | :--- |
| **Machine Learning (ML)** | Aprendizado Supervisionado, Não Supervisionado e por Reforço. | Previsão de surtos epidêmicos baseada em dados históricos. |
| **Deep Learning** | Redes Neurais (CNNs, RNNs), Transformers, Large Language Models (LLMs). | Análise de imagens médicas para diagnóstico. |
| **Processamento de Linguagem Natural (NLP)** | Chatbots, Análise de Sentimento, Extração de Informação. | Transcrição de áudios e análise de prontuários médicos. |
| **Visão Computacional** | Reconhecimento de Imagens, Segmentação, Rastreamento. | Monitoramento de aglomerações em eventos de saúde pública. |

### 1.2 Aplicações no Dia a Dia e na Saúde

A IA já está presente em diversas ferramentas cotidianas, desde aplicativos de transporte e educação (como o Duolingo) até sistemas de busca e wearables. Na saúde coletiva, a IA tem sido aplicada para triagem de pacientes, análise epidemiológica e otimização de fluxos de trabalho [1].

**Questões para Debate (20 minutos):**
*   Quais ferramentas com IA embarcada você já utiliza no seu trabalho ou na sua pesquisa?
*   De que forma essas ferramentas impactaram sua rotina? O impacto foi predominantemente positivo ou trouxe novos desafios?
*   Para aqueles que ainda não utilizam, quais são as principais barreiras ou receios?

### 1.3 Questões Éticas e de Governança

O uso de IA na saúde exige rigorosos mecanismos de governança. Os principais riscos incluem vieses algorítmicos, a opacidade dos modelos (o problema da "caixa preta"), discriminação, despersonalização do atendimento e questões de privacidade e apropriação indevida de dados [1]. A Organização Mundial da Saúde (OMS) e a UNESCO possuem diretrizes específicas para o uso ético da IA na pesquisa e educação em saúde.

---

## Módulo 2: O Microsoft Copilot e a Criação de Agentes (2 horas)

### 2.1 Introdução ao Microsoft Copilot Educacional

O Microsoft Copilot, acessível via web através da licença educacional do Teams, é um assistente de IA generativa integrado ao ecossistema Microsoft 365. Ele permite a interação em linguagem natural para gerar textos, analisar dados, criar resumos e automatizar fluxos de trabalho, mantendo a segurança e a privacidade dos dados institucionais [2].

### 2.2 Framework para Criação de Agentes de IA

Um agente de IA é uma entidade digital configurada para atuar com um propósito específico, seguindo regras e comportamentos predefinidos. Para criar um agente eficaz no Copilot, utilizamos a técnica de *prompt engineering* estruturado.

A estrutura ideal de um prompt para agente inclui:
1.  **Papel e Especialidade:** Quem o agente deve ser.
2.  **Objetivo Principal:** O que ele deve alcançar.
3.  **Diretrizes e Referências:** Base de conhecimento que ele deve seguir.
4.  **Comportamentos e Regras:** Como ele deve interagir e formatar as respostas.
5.  **Tom e Estilo:** A linguagem a ser adotada.

### 2.3 Exercício Prático: Criando o "Agente Organizador de Congressos"

**Passo a passo no Copilot:**
1.  Acesse o Microsoft Copilot no navegador com sua conta educacional.
2.  Inicie um novo chat.
3.  Insira o prompt estruturado abaixo para configurar o agente.

**Prompt para o Copilot:**
> "Assuma o papel de um 'Especialista em Gestão de Eventos Científicos', com foco em saúde coletiva e vigilância epidemiológica. Seu objetivo principal é me auxiliar em todas as etapas da organização de um congresso técnico-científico nacional.
> 
> **Comportamentos e regras:**
> 1. Sempre que eu solicitar ajuda com uma etapa (ex: busca de palestrantes, cronograma, convites), você deve fornecer um passo a passo estruturado, sugerindo ferramentas e métodos eficientes.
> 2. Utilize uma linguagem profissional, clara e objetiva, adequada para a comunicação com gestores de saúde e pesquisadores.
> 3. Ao propor cronogramas ou listas, utilize tabelas Markdown para facilitar a visualização.
> 4. Ao final de cada resposta, faça uma pergunta para refinar a próxima etapa do planejamento.
> 
> Confirme que entendeu seu papel e aguarde minha primeira solicitação."

---

## Módulo 3: Automação da Organização do Congresso (2,5 horas)

Neste módulo, os participantes usarão o agente criado para planejar as etapas cruciais do congresso de vigilância em saúde. A atividade será dividida em quatro grandes desafios práticos.

### 3.1 Busca por Especialistas e Curadoria Científica

O primeiro desafio é identificar palestrantes relevantes para o tema "Novas Tecnologias na Detecção de Surtos".

**Prompt para o Copilot:**
> "Preciso montar a mesa redonda principal do congresso sobre 'Inovações na Detecção Precoce de Surtos Epidemiológicos'. Atue como pesquisador acadêmico e sugira critérios para a seleção de 4 especialistas brasileiros nesta área. Em seguida, crie um modelo de e-mail formal para o convite, destacando a importância do evento para a saúde pública."

**Atividade:** Os participantes devem revisar o e-mail gerado, ajustando o tom e inserindo variáveis como `[Nome do Especialista]` e `[Data do Evento]`.

### 3.2 Criação do Programa e Cronograma

Um congresso exige uma grade de programação meticulosa.

**Prompt para o Copilot:**
> "Elabore uma proposta de programação de 2 dias para o congresso. O evento ocorrerá das 08h às 18h. Inclua: credenciamento, cerimônia de abertura, 3 mesas redondas temáticas sobre vigilância em saúde, apresentação de trabalhos (pôsteres), intervalos para coffee break e almoço, e uma plenária de encerramento. Apresente o resultado em uma tabela detalhada com horários, atividades e sugestões de temas para as mesas."

**Atividade:** Os participantes devem analisar a tabela gerada, sugerir modificações de horários ou temas e pedir para o Copilot refazer a tabela com os ajustes.

### 3.3 Gestão de Convites, Passagens e Hospedagem

A logística de palestrantes consome muito tempo. A IA pode estruturar esse fluxo.

**Prompt para o Copilot:**
> "Crie um fluxo de trabalho (workflow) passo a passo para a gestão logística dos palestrantes confirmados. O fluxo deve cobrir: recebimento do aceite, solicitação de dados para emissão de passagens aéreas, reserva de hotel e envio do itinerário final. Elabore também um formulário (lista de campos) que devo enviar aos palestrantes para coletar as informações necessárias para a compra das passagens."

**Atividade:** Os participantes criarão, a partir da lista de campos gerada, um formulário digital (ex: Microsoft Forms) simulando a coleta de dados.

### 3.4 Automação de Certificados e Comunicação Final

A emissão de certificados pode ser otimizada com ferramentas integradas.

**Prompt para o Copilot:**
> "Explique como posso estruturar uma base de dados no Microsoft Excel para automatizar a emissão de certificados de participação usando a funcionalidade de Mala Direta do Word. Além disso, escreva o texto padrão que deve constar no certificado do congresso, incluindo a carga horária de 20 horas e a menção à organização do evento."

**Atividade Final:** Cada participante deve redigir um "prompt livre" pedindo ao Copilot que elabore um post para redes sociais anunciando o encerramento do congresso e agradecendo aos participantes.

---

## Encerramento e Avaliação (15 minutos)

A oficina será concluída com uma rodada de compartilhamento das experiências com o uso do Copilot.

**Questões Finais para Debate:**
*   Como a IA generativa pode reduzir o tempo gasto na organização de eventos acadêmicos?
*   Quais são os riscos de confiar cegamente na automação de processos sem revisão humana?
*   Como os conceitos aprendidos hoje podem ser aplicados nos projetos de pesquisa e extensão de cada participante?

---

## Referências

[1] Normando, P. (2026). *IA para pesquisa em Saúde Coletiva*. Slides de apresentação. Universidade Federal da Bahia.
[2] Microsoft. (2026). *Microsoft Copilot in Education*. Recursos e documentação oficial.
