# 🏢 Assistente de Voz para Produtividade Corporativa

Este repositório apresenta uma solução de **Interface de Voz (VUI)** desenvolvida em Python, focada em automação de rotinas de escritório. O projeto utiliza modelos de Inteligência Artificial de ponta para converter voz em comandos e responder vocalmente ao usuário.

---

## 🛠️ Stack Tecnológica

| Componente | Tecnologia | Função |
| :--- | :--- | :--- |
| **STT** | OpenAI Whisper (Small) | Transcrição de alta precisão em Português |
| **TTS** | Google Text-to-Speech (gTTS) | Síntese de voz natural para feedback |
| **Interface** | JavaScript + Colab | Captura de áudio diretamente do navegador |
| **Lógica** | Python 3 | Processamento de comandos e fluxos |

---

## 🚀 Como Funciona?

O fluxo do sistema foi desenhado para ser intuitivo:

1.  **Captura:** O usuário grava um comando (ex: "Tarefa concluída").
2.  **Processamento:** O Whisper processa o áudio forçando o idioma `pt-br` para evitar erros de interpretação.
3.  **Análise:** O script identifica palavras-chave de rotinas de escritório.
4.  **Feedback:** O gTTS gera uma resposta em áudio confirmando a ação.

### Exemplo de Comandos Suportados:
- *"Finalizei a tarefa do projeto"* -> Confirmação de conclusão.
- *"Anote os pontos da reunião"* -> Acionamento de ata.

---

## 🔧 Configuração e Uso

Para rodar este projeto no **Google Colab**:
1. Ative a GPU em `Ambiente de Execução` > `Alterar tipo de ambiente de execução`.
2. Execute as células de instalação.
3. Utilize o botão interativo para gravar sua voz.

> **Nota:** O uso do modelo `small` do Whisper garante uma taxa de acerto superior para termos técnicos em português quando comparado ao modelo `base`.

---
⭐ Desenvolvido por **João Souza** durante a jornada na DIO!n]
