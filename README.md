# 🦺 EPI-Detector
# 🚀 Projeto: Detecção de Equipamentos de Proteção Individual com Visão Computacional

Sistema de **detecção automática de Equipamentos de Proteção Individual (EPIs)** utilizando **Visão Computacional e Inteligência Artificial**, com foco em ambientes industriais e de construção civil.

O projeto tem caráter **educacional e experimental**, sendo desenvolvido como parte de um portfólio em Ciência de Dados e IA aplicada.

---

## 📌 Objetivo

Desenvolver um sistema capaz de identificar, em imagens e vídeos, a presença ou ausência de EPIs como:

* Capacete
* Colete de segurança
* Máscara
* Luvas

A solução utiliza modelos de **Deep Learning** para detecção de objetos e gera dados estruturados que podem ser analisados posteriormente em ferramentas de **Business Intelligence**.

---

## 🧠 Tecnologias Utilizadas

* **Python**
* **OpenCV** – Captura e processamento de imagens e vídeos
* **YOLO (You Only Look Once)** – Modelo de detecção de objetos em tempo real
* **TensorFlow / PyTorch** – Frameworks de Deep Learning
* **Streamlit** – Interface web interativa
* **Power BI** – Análise e visualização dos dados gerados

---

## 🗂️ Estrutura do Projeto

```bash
epi-detector/
│
├── data/
│   ├── raw/            # Dados brutos (imagens e vídeos)
│   └── processed/      # Dados processados
│
├── models/
│   └── yolo_weights.pt # Pesos do modelo treinado
│
├── src/
│   ├── detector.py     # Lógica de detecção de EPIs
│   ├── utils.py        # Funções auxiliares
│
├── app.py              # Aplicação Streamlit
├── requirements.txt    # Dependências do projeto
├── dashboard.pbix      # Dashboard Power BI
└── README.md
```

---

## 📸 Dataset

O projeto pode utilizar datasets públicos, como:

* **PPE Detection Dataset (Kaggle)**
* **Construction Site Safety Dataset**

Todos os datasets utilizados respeitam as licenças de uso e têm finalidade exclusivamente educacional.

Também é possível utilizar um dataset customizado a partir de imagens públicas.

---

## ⚙️ Funcionamento do Sistema

1. Captura de imagem ou vídeo (arquivo ou webcam)
2. Processamento com OpenCV
3. Detecção dos EPIs utilizando YOLO
4. Geração de logs com:

   * Tipo de EPI
   * Data e hora
   * Status (detectado ou ausente)
5. Exportação dos dados para CSV
6. Análise e visualização no Power BI

---

## 📊 Análise de Dados (Power BI)

Os dados gerados pelo sistema podem ser analisados por meio de dashboards contendo, por exemplo:

* Percentual de conformidade de EPIs
* EPIs mais frequentemente ausentes
* Análise temporal de ocorrências
* Indicadores de segurança

---

## 🚀 Como Executar o Projeto

### 1️⃣ Clonar o repositório

```bash
git clone https://github.com/seu-usuario/epi-detector.git
cd epi-detector
```

### 2️⃣ Criar ambiente virtual e instalar dependências

```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\\Scripts\\activate
pip install -r requirements.txt
```

### 3️⃣ Executar a aplicação

```bash
streamlit run app.py
```

---

## 📌 Roadmap

* [x] Estrutura inicial do projeto
* [x] Integração com YOLO
* [ ] Interface completa com Streamlit
* [ ] Exportação automática de dados
* [ ] Dashboard Power BI
* [ ] Documentação técnica final

---

## ⚠️ Aviso Importante

Este projeto **não substitui sistemas oficiais de segurança do trabalho**. Seu objetivo é demonstrar a aplicação de técnicas de Inteligência Artificial e Ciência de Dados em um contexto prático.

---

## 👩‍💻 Autora

**Ingrid Dias**
Estudante de Ciência de Dados | IA aplicada | Análise de Dados

* GitHub: [https://github.com/seu-usuario](https://github.com/seu-usuario)
* LinkedIn: [https://www.linkedin.com](https://www.linkedin.com)

---

✨ *Projeto desenvolvido para fins educacionais e de portfólio.*
