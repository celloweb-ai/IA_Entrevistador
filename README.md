# 🧭 TechCareer Pathfinder (Agente 1)

> **Primeiro estágio do sistema multi-agentes de orientação de carreira.**

Este repositório contém o prompt fonte para o **TechCareer Pathfinder**, um agente conversacional projetado para atuar como a primeira camada de interação em um sistema inteligente de aconselhamento de carreira para o mercado de tecnologia.

## 🎯 Objetivo do Agente

O **TechCareer Pathfinder** tem a missão crítica de realizar o "triunfo" inicial do usuário. Ele não apenas conversa, mas conduz uma entrevista estruturada para extrair dados vitais sobre as motivações, disponibilidade e background do usuário, finalizando com recomendações baseadas em lógica e preparando o terreno para o planejamento detalhado de estudos (Agente 2).

## 🧠 Arquitetura Comportamental

Este agente foi desenhado com diretrizes rígidas para garantir uma experiência de usuário fluida e profissional:

### Fases de Operação

1.  **📝 Fase 1: Entrevista Estruturada**
    * Conduz 7 perguntas sequenciais (uma por vez).
    * Mantém o foco e evita "alucinações" ou desvios de assunto.
    * Valida respostas naturalmente antes de avançar.

2.  **📊 Fase 2: Análise e Recomendação**
    * Aplica uma "Matriz de Decisão" interna (pontuação de 1-20).
    * Cruza perfil do usuário (Pessoas/Dados/Código) com demandas de mercado.
    * Gera um TOP 3 carreiras aderentes com justificativas personalizadas.

3.  **🔄 Fase 3: Transferência (Handoff)**
    * Após a escolha do usuário, gera um artefato técnico (`[AGENT_TRANSFER_TICKET]`).
    * Este ticket JSON contém todos os dados estruturados necessários para que o próximo agente (Planejador de Estudos) inicie seu trabalho sem precisar re-perguntar nada.

## 📂 Estrutura do Repositório

```bash
.
├── Agente_1_TechCareer_Pathfinder.md  # O PROMPT PRINCIPAL (Cérebro do agente)
└── README.md                          # Este arquivo

Conversa com o Gemini
criar um readme.md para o repositório contendo o desafio em anexo.

Aqui está uma proposta de README.md detalhado e profissional para o repositório deste desafio.

Markdown
# 🧭 TechCareer Pathfinder (Agente 1)

> **Primeiro estágio do sistema multi-agentes de orientação de carreira.**

Este repositório contém o prompt fonte para o **TechCareer Pathfinder**, um agente conversacional projetado para atuar como a primeira camada de interação em um sistema inteligente de aconselhamento de carreira para o mercado de tecnologia.

## 🎯 Objetivo do Agente

O **TechCareer Pathfinder** tem a missão crítica de realizar o "triunfo" inicial do usuário. Ele não apenas conversa, mas conduz uma entrevista estruturada para extrair dados vitais sobre as motivações, disponibilidade e background do usuário, finalizando com recomendações baseadas em lógica e preparando o terreno para o planejamento detalhado de estudos (Agente 2).

## 🧠 Arquitetura Comportamental

Este agente foi desenhado com diretrizes rígidas para garantir uma experiência de usuário fluida e profissional:

### Fases de Operação

1.  **📝 Fase 1: Entrevista Estruturada**
    * Conduz 7 perguntas sequenciais (uma por vez).
    * Mantém o foco e evita "alucinações" ou desvios de assunto.
    * Valida respostas naturalmente antes de avançar.

2.  **📊 Fase 2: Análise e Recomendação**
    * Aplica uma "Matriz de Decisão" interna (pontuação de 1-20).
    * Cruza perfil do usuário (Pessoas/Dados/Código) com demandas de mercado.
    * Gera um TOP 3 carreiras aderentes com justificativas personalizadas.

3.  **🔄 Fase 3: Transferência (Handoff)**
    * Após a escolha do usuário, gera um artefato técnico (`[AGENT_TRANSFER_TICKET]`).
    * Este ticket JSON contém todos os dados estruturados necessários para que o próximo agente (Planejador de Estudos) inicie seu trabalho sem precisar re-perguntar nada.

## 📂 Estrutura do Repositório

```bash
.
├── Agente_1_TechCareer_Pathfinder.md  # O PROMPT PRINCIPAL (Cérebro do agente)
└── README.md                          # Este arquivo
🚀 Como Usar
Para testar ou executar este agente, não é necessário instalação de código complexo, apenas um LLM competente:

Abra o arquivo Agente_1_TechCareer_Pathfinder.md.

Copie todo o seu conteúdo.

Cole em um LLM de sua preferência (ex: ChatGPT-4o, Claude 3.5 Sonnet, Gemini 1.5 Pro).

O agente iniciará imediatamente a entrevista com a primeira pergunta.

🤖 Exemplo de Output (Handoff)
No final da interação, o agente gerará um bloco JSON invisível para o usuário comum, mas vital para o sistema. Exemplo:

JSON
[AGENT_TRANSFER_TICKET]
{
  "target_agent": "Agent 2 - Study Planner",
  "user_profile": {
    "chosen_career": "Engenharia de Dados",
    "study_availability_hours": "15h/semana",
    "current_level": "Transição de carreira (vindo de Finanças)",
    "primary_goal": "Primeiro emprego tech em 12 meses",
    "work_preference": "Dados/Padrões",
    "key_interests": "Análise de dados, automação",
    "background_leverage": "Excel avançado, estatística básica"
  },
  "interviewer_notes": "Usuário muito analítico, preocupado com a barreira de entrada da matemática."
}
🛠️ Próximos Passos (Desafio)
O output deste agente serve de input direto para o Agente 2 (Study Planner). O desafio continua na construção deste segundo especialista, que deverá ler o JSON acima e criar um cronograma de estudos semana a semana.

Desenvolvido como parte do desafio de Sistemas Multi-Agentes.

gere um arquivo Readme.md completo para download

Aqui está o arquivo README.md pronto para ser baixado e usado no seu repositório.

Markdown
# 🧭 TechCareer Pathfinder (Agente 1)

> **Primeiro estágio do sistema multi-agentes de orientação de carreira.**

Este repositório contém o prompt fonte para o **TechCareer Pathfinder**, um agente conversacional projetado para atuar como a primeira camada de interação em um sistema inteligente de aconselhamento de carreira para o mercado de tecnologia.

## 🎯 Objetivo do Agente

O **TechCareer Pathfinder** tem a missão crítica de realizar o "triunfo" inicial do usuário. Ele não apenas conversa, mas conduz uma entrevista estruturada para extrair dados vitais sobre as motivações, disponibilidade e background do usuário, finalizando com recomendações baseadas em lógica e preparando o terreno para o planejamento detalhado de estudos (Agente 2).

## 🧠 Arquitetura Comportamental

Este agente foi desenhado com diretrizes rígidas para garantir uma experiência de usuário fluida e profissional:

### Fases de Operação

1.  **📝 Fase 1: Entrevista Estruturada**
    * Conduz 7 perguntas sequenciais (uma por vez).
    * Mantém o foco e evita "alucinações" ou desvios de assunto.
    * Valida respostas naturalmente antes de avançar.

2.  **📊 Fase 2: Análise e Recomendação**
    * Aplica uma "Matriz de Decisão" interna (pontuação de 1-20).
    * Cruza perfil do usuário (Pessoas/Dados/Código) com demandas de mercado.
    * Gera um TOP 3 carreiras aderentes com justificativas personalizadas.

3.  **🔄 Fase 3: Transferência (Handoff)**
    * Após a escolha do usuário, gera um artefato técnico (`[AGENT_TRANSFER_TICKET]`).
    * Este ticket JSON contém todos os dados estruturados necessários para que o próximo agente (Planejador de Estudos) inicie seu trabalho sem precisar re-perguntar nada.

## 📂 Estrutura do Repositório

```bash
.
├── Agente_1_TechCareer_Pathfinder.md  # O PROMPT PRINCIPAL (Cérebro do agente)
└── README.md                          # Este arquivo
🚀 Como Usar
Para testar ou executar este agente, não é necessário instalação de código complexo, apenas um LLM competente:

Abra o arquivo Agente_1_TechCareer_Pathfinder.md.

Copie todo o seu conteúdo.

Cole em um LLM de sua preferência (ex: ChatGPT-4o, Claude 3.5 Sonnet, Gemini 1.5 Pro).

O agente iniciará imediatamente a entrevista com a primeira pergunta.

🤖 Exemplo de Output (Handoff)
No final da interação, o agente gerará um bloco JSON invisível para o usuário comum, mas vital para o sistema. Exemplo:

JSON
[AGENT_TRANSFER_TICKET]
{
  "target_agent": "Agent 2 - Study Planner",
  "user_profile": {
    "chosen_career": "Engenharia de Dados",
    "study_availability_hours": "15h/semana",
    "current_level": "Transição de carreira (vindo de Finanças)",
    "primary_goal": "Primeiro emprego tech em 12 meses",
    "work_preference": "Dados/Padrões",
    "key_interests": "Análise de dados, automação",
    "background_leverage": "Excel avançado, estatística básica"
  },
  "interviewer_notes": "Usuário muito analítico, preocupado com a barreira de entrada da matemática."
}
🛠️ Próximos Passos (Desafio)
O output deste agente serve de input direto para o Agente 2 (Study Planner). O desafio continua na construção deste segundo especialista, que deverá ler o JSON acima e criar um cronograma de estudos semana a semana.

Desenvolvido como parte do desafio de Sistemas Multi-Agentes.

gere um arquivo para download

O arquivo solicitado não pode ser gerado diretamente para download. Posso fornecer o conteúdo completo para que você copie e salve com a extensão desejada, se isso ajudar.

sim

Aqui está o conteúdo completo do arquivo README.md. Você pode copiar o texto abaixo e colá-lo em um editor de texto (como Bloco de Notas, VS Code, etc.) e salvar o arquivo com o nome README.md.

Markdown
# 🧭 TechCareer Pathfinder (Agente 1)

> **Primeiro estágio do sistema multi-agentes de orientação de carreira.**

Este repositório contém o prompt fonte para o **TechCareer Pathfinder**, um agente conversacional projetado para atuar como a primeira camada de interação em um sistema inteligente de aconselhamento de carreira para o mercado de tecnologia.

## 🎯 Objetivo do Agente

O **TechCareer Pathfinder** tem a missão crítica de realizar o "triunfo" inicial do usuário. Ele não apenas conversa, mas conduz uma entrevista estruturada para extrair dados vitais sobre as motivações, disponibilidade e background do usuário, finalizando com recomendações baseadas em lógica e preparando o terreno para o planejamento detalhado de estudos (Agente 2).

## 🧠 Arquitetura Comportamental

Este agente foi desenhado com diretrizes rígidas para garantir uma experiência de usuário fluida e profissional:

### Fases de Operação

1.  **📝 Fase 1: Entrevista Estruturada**
    * Conduz 7 perguntas sequenciais (uma por vez).
    * Mantém o foco e evita "alucinações" ou desvios de assunto.
    * Valida respostas naturalmente antes de avançar.

2.  **📊 Fase 2: Análise e Recomendação**
    * Aplica uma "Matriz de Decisão" interna (pontuação de 1-20).
    * Cruza perfil do usuário (Pessoas/Dados/Código) com demandas de mercado.
    * Gera um TOP 3 carreiras aderentes com justificativas personalizadas.

3.  **🔄 Fase 3: Transferência (Handoff)**
    * Após a escolha do usuário, gera um artefato técnico (`[AGENT_TRANSFER_TICKET]`).
    * Este ticket JSON contém todos os dados estruturados necessários para que o próximo agente (Planejador de Estudos) inicie seu trabalho sem precisar re-perguntar nada.

## 📂 Estrutura do Repositório

```bash
.
├── Agente_1_TechCareer_Pathfinder.md  # O PROMPT PRINCIPAL (Cérebro do agente)
└── README.md                          # Este arquivo
🚀 Como Usar
Para testar ou executar este agente, não é necessário instalação de código complexo, apenas um LLM competente:

Abra o arquivo Agente_1_TechCareer_Pathfinder.md.

Copie todo o seu conteúdo.

Cole em um LLM de sua preferência (ex: ChatGPT-4o, Claude 3.5 Sonnet, Gemini 1.5 Pro).

O agente iniciará imediatamente a entrevista com a primeira pergunta.

🤖 Exemplo de Output (Handoff)
No final da interação, o agente gerará um bloco JSON invisível para o usuário comum, mas vital para o sistema. Exemplo:

JSON
[AGENT_TRANSFER_TICKET]
{
  "target_agent": "Agent 2 - Study Planner",
  "user_profile": {
    "chosen_career": "Engenharia de Dados",
    "study_availability_hours": "15h/semana",
    "current_level": "Transição de carreira (vindo de Finanças)",
    "primary_goal": "Primeiro emprego tech em 12 meses",
    "work_preference": "Dados/Padrões",
    "key_interests": "Análise de dados, automação",
    "background_leverage": "Excel avançado, estatística básica"
  },
  "interviewer_notes": "Usuário muito analítico, preocupado com a barreira de entrada da matemática."
}
🛠️ Próximos Passos (Desafio)
O output deste agente serve de input direto para o Agente 2 (Study Planner). O desafio continua na construção deste segundo especialista, que deverá ler o JSON acima e criar um cronograma de estudos semana a semana.

Desenvolvido como parte do desafio de Sistemas Multi-Agentes.
