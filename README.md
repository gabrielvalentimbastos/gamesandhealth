# Previsão do Risco de Vício em Jogos

## 🎯 Título e Objetivo
* **Título do Projeto:** Previsão do Risco de Vício em Jogos Eletrônicos
* **Objetivo:** Desenvolver uma aplicação capaz de prever a propensão de uma pessoa a desenvolver vício em jogos, analisando seu comportamento de jogo, hábitos de sono, sintomas físicos e nível de isolamento social.

---

## 👥 Integrantes
* **Gabriel Rocha Valentim Bastos**
* **Luis Roberto Santana Santos**

---

## 🌐 Fonte dos Dados
* **Dataset:** Gaming and Mental Health Dataset
* **Origem:** [Kaggle - Gaming and Mental Health](https://www.kaggle.com/datasets/shaistashahid/gaming-and-mental-health?resource=download)

---

## 📌 Tipo da Tarefa
* **Tipo de Aprendizado:** Classificação
* **Atributo-Alvo (`y`):** `gaming_addiction_risk_level` (Categorias: `Low`, `Moderate`, `High`, `Severe`)
* **Atributos Preditivos (`X`):** `daily_gaming_hours`, `sleep_hours`, `sleep_quality`, `social_isolation_score`, `withdrawal_symptoms`, `loss_of_other_interests`, `age`, `exercise_hours_weekly`, entre outros.

---

## 📁 Organização dos Arquivos
```text
├── datasets/
│   └── Gaming and Mental Health.csv  # Dataset original em formato CSV
├── projetoIA.ipynb                   # Notebook principal do projeto (Seções 5.1 a 5.7)
└── README.md                         # Documentação completa do projeto
```
---

## 🚀 Instruções para Execução no Google Colab

Existem duas formas simples de rodar o projeto no Google Colab:

### **Opção 1: Abrir diretamente pelo GitHub (Recomendado)**
1. Clique no botão abaixo para abrir o notebook diretamente no Google Colab:

   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/gabrielvalentimbastos/gamesandhealth/blob/main/projetoIA.ipynb)

2. Caso prefira abrir manualmente no Colab:
   - Acesse [colab.research.google.com](https://colab.research.google.com/).
   - Na janela inicial, selecione a aba **GitHub**.
   - Digite a URL do repositório (`https://github.com/gabrielvalentimbastos/gamesandhealth`) e selecione o arquivo `projetoIA.ipynb`.

### **Opção 2: Baixar o arquivo `.ipynb` e fazer Upload no Colab**
1. Faça o download do arquivo `projetoIA.ipynb` deste repositório para o seu computador.
2. Acesse o [Google Colab](https://colab.research.google.com/).
3. Na janela inicial, clique na aba **Upload** e selecione o arquivo `projetoIA.ipynb` que você baixou.

---

### **Como Executar os Códigos:**
* Após abrir o notebook por qualquer uma das opções, vá até o menu superior do Colab e selecione **Ambiente de execução** > **Executar tudo** (ou pressione `Ctrl + F9`).
* O dataset é baixado automaticamente a partir de um link público no repositório do GitHub, garantindo que o código rode perfeitamente sem precisar fazer upload de arquivos adicionais.

---

## 🤝 Divisão das Contribuições do Grupo
- Luís Roberto Santana Santos:

Identificação e descrição do problema (Seção 5.1).

Compreensão e interpretação dos dados (Seção 5.2).

Análise exploratória e visualizações gráficas (Seção 5.3).

Gravação da apresentação em vídeo.

- Gabriel Rocha Valentim Bastos:

Tratamento de dados e pré-processamento (Seção 5.4).

Separação estratificada de treino e teste (Seção 5.5).

Treinamento dos modelos e validação cruzada (Seção 5.6).

Avaliação de métricas, matriz de confusão e discussão dos resultados (Seção 5.7).

Documentação do repositório e gravação da apresentação em vídeo.

---

## 🎥 Link do Vídeo de Apresentação
Vídeo Explicativo: [![Assistir Apresentação](https://img.shields.io/badge/YouTube-Assistir%20Apresentação-red?style=for-the-badge&logo=youtube)](https://youtu.be/0kp7kpT2W3g)

---

## 🤖 Declaração de Uso de Ferramentas de IA
Em conformidade com as diretrizes do projeto:

Ferramenta Utilizada: Gemini (Google).

Finalidade: Auxílio na criação, estruturação e refatoração do código em Python (Scikit-Learn, Pandas) para a realização do pré-processamento, validação cruzada, avaliação e geração do gráfico da matriz de confusão. Suporte na redação, revisão e padronização dos textos explicativos e análises técnicas das seções do notebook e na estruturação do `README.md`.

Verificação e Validação: Todo o código fornecido ou sugerido foi revisado, testado e validado tecnicamente pelos integrantes do grupo no Google Colab, garantindo a prevenção de vazamento de dados (data leakage) e a integridade das análises efetuadas.
