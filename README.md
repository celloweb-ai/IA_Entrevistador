<h1 align="center">
  🚀 TechCareer Pathfinder
</h1>

<h3 align="center">
  IA Mentor de Carreira: Descubra Seu Futuro em Tech
</h3>

<p align="center">
  Um agente inteligente projetado para realizar entrevistas estruturadas e direcionar talentos para as carreiras tecnológicas mais aderentes aos seus perfis.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-em%20desenvolvimento-yellow?style=flat-square" alt="Status">
  <img src="https://img.shields.io/badge/license-MIT-blue?style=flat-square" alt="License">
  <img src="https://img.shields.io/badge/feito%20por-Marcus%20Vasconcellos-brightgreen?style=flat-square" alt="Author">
</p>

---

## 📖 Sobre o Projeto

O **TechCareer Pathfinder** nasceu da necessidade de orientar novos talentos em meio ao vasto universo da tecnologia. Este projeto conceitual foi desenvolvido como parte do desafio "IA Mentor de Carreira" do Bootcamp **DIO CAIXA – Inteligência Artificial na Prática**.

O objetivo é criar um agente conversacional capaz de atuar como um mentor de carreira inicial, validando interesses, avaliando disponibilidade e recomendando caminhos personalizados com base em uma lógica de decisão robusta.

---

## ✨ Funcionalidades Principais

- 🎯 **Entrevista Estruturada:** 7 perguntas estratégicas para mapear o perfil do usuário.
- 🧠 **Validação Natural:** Compreensão contextual das respostas (não apenas palavras-chave).
- 📊 **Matriz de Decisão:** Sistema de pontuação para avaliar aderência, viabilidade e demanda de mercado.
- 📋 **Recomendação Personalizada:** Sugestão das TOP 3 carreiras com prós e contras.
- 🔄 **Integração de Agentes:** Geração de "ticket" JSON para handover técnico a agentes de planejamento de estudos.

---

## 🗂️ Fluxo do Agente

O agente opera em um pipeline de três fases distintas para garantir precisão na recomendação:

### 📍 Fase 1: A Entrevista (Coleta de Dados)
O agente conduz uma conversa amigável para entender:
1.  **Motivação Central** (O "porquê" do usuário)
2.  **Nível Atual** (Iniciante, transição, avançado)
3.  **Disponibilidade Real** (Tempo para dedicação aos estudos)
4.  **Rotina Preferida** (Foco em código, pessoas, dados ou design?)
5.  **Objetivo Imediato** (Emprego rápido vs. especialização longa)
6.  **Interesses Tech** (Áreas que já chamam a atenção)
7.  **Background Transferível** (Experiências prévias úteis)

### 📊 Fase 2: O Processamento (Análise)
> *Engine de Decisão*
> Aplicação de pesos e pontuações (máx. 20 pts) cruzando os dados coletados com perfis de carreiras pré-mapeados.

### 🔄 Fase 3: O Resultado (Entrega & Handover)
Apresentação das recomendações e geração do output estruturado para os próximos passos da jornada do usuário.

---

## 🧪 Cenários de Uso (Personas)

Exemplos de como o **TechCareer Pathfinder** se adapta a diferentes perfis:

| Perfil | Cenário & Necessidade | Solução do Agente |
| :--- | :--- | :--- |
| **👩‍💻 A Iniciante** | João está começando do zero e perdido com tantas opções. | Identifica perfil criativo e lógico. Recomenda: **Front-End** ou **UX Design**. |
| **🎯 Em Transição** | Maria vem do Marketing e quer migrar para Tech. | Valoriza o background dela. Recomenda: **Analista de BI** ou **Cientista de Dados**. |
| **⏳ Sem Tempo** | Carlos só tem 5h semanais para estudar. | Avalia viabilidade realista. Recomenda foco inicial em **QA Testing**. |
| **🧭 O Indeciso** | Ana gosta de tecnologia, mas não sabe o quê exatamente. | Detecta interesse em resolução de problemas críticos. Recomenda: **Cibersegurança**. |

---

## 🛠️ Tecnologias & Conceitos

Este projeto utiliza uma abordagem agnóstica de plataforma, focando na lógica conversacional e estruturação de dados.

* **Core:** Lógica de Decisão Estruturada
* **Interface:** Markdown (Documentação) & Conversational Design
* **Integração:** JSON (para troca de dados entre agentes)

---

## 🚀 Como Executar

Este é um projeto de **design de agente**. Ele pode ser implementado em diversas plataformas:
* *Low-code:* Power Virtual Agents, Dialogflow.
* *Pro-code:* Python (usando LangChain ou frameworks similares), APIs da OpenAI/Anthropic.

Para testar o fluxo, utilize o roteiro de entrevista definido na documentação e aplique manualmente a matriz de decisão.

---

## 🤝 Contribuições

Sugestões são sempre bem-vindas! Sinta-se à vontade para abrir uma *issue* com ideias de novas perguntas para a entrevista, novos perfis de carreira para a matriz, ou melhorias na lógica de pontuação.

---

## 📬 Autor

<img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/69893591?v=4" width="100px;" alt="Foto do Autor"/>
<br />

**Marcus Augusto da S. Vasconcellos**
<div>
<a href="https://www.linkedin.com/in/marcusvasconcellos" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
<a href="mailto:[SEU-EMAIL]"><img src="https://img.shields.io/badge/-Email-%23D14836?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
</div>

---

## 📝 Licença

Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](./LICENSE) para mais informações.
