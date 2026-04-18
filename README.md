# Assistente de Voz Inteligente: Especialista em Farmácia Hospitalar 🏥

Este projeto é uma solução personalizada desenvolvida para o desafio de IA da DIO. O foco foi criar um assistente funcional para a rotina de um **Auxiliar de Farmácia Hospitalar**, otimizando processos de consulta técnica e logística.

## 🚀 Diferenciais do Projeto (O que eu mudei)

Diferente do projeto base, esta versão implementa melhorias críticas para garantir que a ferramenta seja moderna e funcional:

* **Migração para Gemini 3.1 Flash:** Devido às limitações de cota e instabilidade da API da OpenAI, o "cérebro" do projeto foi migrado para o **Google Gemini 3.1 Flash Lite**. Isso resultou em uma resposta muito mais rápida e sem custos de API.
* **Mapeamento Dinâmico de Modelos:** Implementação de uma rotina para identificar os modelos mais recentes disponíveis no ambiente do Google Colab (2026), garantindo que o código não quebre por versões desatualizadas.
* **Prompt de Especialista:** A IA foi configurada com um *System Prompt* rigoroso para atuar na área hospitalar, focando em:
    * Unitarização de medicamentos termoláveis.
    * Conferência de carrinhos de emergência.
    * Gestão de validade e armazenamento de estoque.

## 🛠️ Tecnologias Utilizadas

* **Google Colab:** Ambiente de desenvolvimento.
* **Whisper (OpenAI):** Transcrição de áudio para texto (Speech-to-Text).
* **Google Generative AI (Gemini 3.1):** Processamento inteligente da solicitação.
* **gTTS (Google Text-to-Speech):** Conversão da resposta técnica em áudio.

## 📋 Como Executar

1.  Abra o arquivo `.ipynb` no Google Colab.
2.  Insira sua `GOOGLE_API_KEY` gerada no Google AI Studio.
3.  Execute as células em sequência.
4.  Grave sua dúvida (ex: "Como proceder na unitarização de termolábeis?") e ouça a orientação técnica imediata.

---
**Status:** 100% Funcional e Atualizado | **Foco:** Logística Hospitalar
