# Assistente de Voz Inteligente para Farmácia Hospitalar 🏥

Este projeto foi desenvolvido como parte do Bootcamp de IA da DIO. O objetivo é criar uma ferramenta que recebe comandos de voz, processa através de uma Inteligência Artificial e responde em áudio, focando na rotina de um Auxiliar de Farmácia Hospitalar.

## 🚀 Funcionalidades

- **Captura de Áudio:** Gravação direta pelo navegador via Google Colab.
- **Transcrição (Whisper):** Transformação da fala em texto utilizando o modelo Whisper da OpenAI.
- **Cérebro (Gemini 3.1 Flash):** Processamento da linguagem natural com contexto especializado em farmácia hospitalar (unitarização, termolábeis, carrinhos de emergência).
- **Voz (gTTS):** Conversão da resposta técnica da IA em áudio para o usuário.

## 🛠️ Desafios Técnicos Superados

Durante o desenvolvimento, foram realizadas adaptações importantes para garantir o funcionamento do projeto:
1. **Migração de API:** Substituição da API da OpenAI (devido a limites de cota) pela API do **Google Gemini (modelo 3.1 Flash Lite)**, garantindo uma resposta rápida e gratuita.
2. **Personalização de Contexto:** Ajuste do *System Prompt* para que a IA atue especificamente como um profissional do **Hospital São Lucas**, trazendo respostas técnicas e práticas para o dia a dia farmacêutico.
3. **Resolução de Dependências:** Ajuste de bibliotecas que apresentavam incompatibilidade de versão no ambiente do Colab.

## 📋 Como utilizar

1. Abra o arquivo `.ipynb` no Google Colab.
2. Insira sua `GOOGLE_API_KEY` na célula correspondente.
3. Execute as células de instalação de dependências.
4. Execute a célula de gravação, fale sua dúvida técnica e aguarde a resposta em áudio.

---
Desenvolvido para fins de estudo no Bootcamp de Engenharia de Prompt.
