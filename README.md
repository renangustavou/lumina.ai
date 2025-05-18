# lumina.ai
🛡️ **Lumina: Detecção Inteligente de Golpes com Gemini AI** 👵➡️🧑‍💻

## 💡 Visão Geral

Lumina utiliza a IA do <img src="https://img.shields.io/badge/Google_AI-lightgrey?style=for-the-badge&logo=google-ai&logoColor=red" alt="Google AI"> para analisar mensagens e alertar sobre possíveis fraudes, protegendo especialmente idosos.

## ✨ Funcionalidades

* 🔍 **Análise Inteligente:** Identifica padrões de golpes.
* 🚨 **Alertas:** Notifica em tempo real sobre ameaças.
* 🎯 **Recomendações:** Oferece orientações claras.

## ⚙️ Tecnologias

* <img src="https://img.shields.io/badge/Google_Gemini-lightgrey?style=for-the-badge&logo=google-gemini&logoColor=red" alt="Google Gemini">
* <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
* <img src="https://img.shields.io/badge/Google_ADK-lightgrey?style=for-the-badge&logo=google-cloud&logoColor=blue" alt="Google ADK">

## 🚀 Usando no Google Colab

### 🛠️ Pré-requisitos no Colab

* Conta Google
* Acesso ao <img src="https://colab.research.google.com/img/colab_favicon.ico" alt="Google Colab" width="20"> Google Colab

### ⚙️ Configuração no Colab

1.  **Abra um novo notebook** no Google Colab.
2.  **Instale as bibliotecas:** Execute a seguinte célula:
    ```python
    !pip install google-genai google-adk
    ```
3.  **Configure a chave da API:**
    * Crie uma célula de código e defina a variável de ambiente:
        ```python
        import os
        os.environ['GOOGLE_API_KEY'] = 'SUA_CHAVE_DA_API' # Substitua pela sua chave
        ```
        * **Importante:** Mantenha sua chave de API segura.

### ▶️ Execução no Colab

1.  **Cole o código do seu sistema Lumina** em células de código no Colab.
2.  **Execute as células** sequencialmente.
3.  **Interaja com o sistema** seguindo as instruções nas células de saída.

## 🧑‍💻 Autor

[Renan Miranda]

## 🙏 Agradecimentos

* <img src="https://img.shields.io/badge/Google-EA4335?style=for-the-badge&logo=google&logoColor=white" alt="Google"> (IA Gemini)
* <img src="https://img.shields.io/badge/Community-lightgrey?style=for-the-badge&logo=github&logoColor=black" alt="Comunidade"> de desenvolvedores
* <img src="https://www.alura.com.br/assets/img/alura-share.1647533640.svg" alt="Alura" width="20"> Alura (Imersão IA)
