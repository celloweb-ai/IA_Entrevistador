# 🧭 TechCareer Pathfinder (Agente 1)

![Version](https://img.shields.io/badge/version-1.0.0-blue?style=flat-square)
![Status](https://img.shields.io/badge/status-stable-green?style=flat-square)
![System](https://img.shields.io/badge/system-Multi--Agent-orange?style=flat-square)

> **Sua primeira parada na transição para o mercado de tecnologia.**
> *Este agente atua como o estágio inicial de triagem e descoberta em um ecossistema multi-agentes de orientação de carreira.*

---

## 📖 Sobre o Projeto

O **TechCareer Pathfinder** não é apenas um chatbot; é um **agente baseado em prompt** projetado para conduzir entrevistas de carreira estruturadas. Sua missão é eliminar a "paralisia por análise" que muitos iniciantes em tecnologia enfrentam.

Ele atua como um recrutador experiente que:
1.  Mapeia o perfil do usuário (interesses, tempo, background).
2.  Analisa os dados com uma matriz de decisão lógica.
3.  Recomenda as 3 melhores trilhas de carreira.
4.  **Crucial:** Prepara os dados para o próximo agente especialista (Planejador de Estudos).

## ✨ Funcionalidades Principais

| Funcionalidade | Descrição |
| :--- | :--- |
| **Entrevista Linear** | Faz apenas uma pergunta por vez, garantindo foco e respostas completas. |
| **Validação Ativa** | Reconhece as respostas do usuário antes de passar para o próximo tópico, criando uma conversa natural. |
| **Matriz de Decisão** | Usa um sistema interno de pontuação (1-20) para classificar carreiras baseadas em 4 pilares: Aderência, Tempo, Mercado e Background. |
| **Tech Handoff** | Gera um output estruturado (JSON) invisível ao usuário final, mas legível por máquinas/outros agentes. |

## 🧠 Arquitetura de Operação

O agente opera em três fases rígidas para garantir consistência:

```mermaid
graph LR
    A[Fase 1: Coleta] -->|7 Perguntas| B(Fase 2: Análise)
    B -->|Matriz de Decisão| C{Fase 3: Handoff}
    C -->|Recomendação Humanizada| D[Usuário Final]
    C -->|JSON Estruturado| E[Agente 2: Planner]

1. 📝 Coleta (Entrevista): 7 perguntas sequenciais cobrindo motivação, nível atual, disponibilidade real, preferências de rotina e experiência prévia.

2. 📊 Processamento (Análise): Cruzamento dos dados coletados com as demandas atuais do mercado de TI.

3. 🔄 Entrega (Handoff): Apresentação do "Top 3 Carreiras" e geração do ticket de transferência.

🚀 Quick Start (Como Usar)
Este é um agente "no-code" que roda diretamente dentro de grandes modelos de linguagem (LLMs).

Pré-requisitos
Acesso a um LLM de nível avançado: GPT-4o (Recomendado), Claude 3.5 Sonnet ou Gemini 1.5 Pro.

Nota: Modelos menores podem não respeitar todas as diretrizes comportamentais.

Passo a Passo
Abra o arquivo principal: Agente_1_TechCareer_Pathfinder.md.

Copie todo o conteúdo do arquivo.

Cole no chat do seu LLM preferido e envie.

O agente iniciará a entrevista automaticamente.

🤖 Integração (O "Handoff")
O diferencial deste agente é sua capacidade de se conectar com outros sistemas. Ao final da conversa, ele gera um bloco oculto:
