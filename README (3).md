# 🩺 Painel de Análise de INSS - Médicos

Este projeto é um dashboard interativo desenvolvido com **Streamlit** para análise de médicos cadastrados, com foco na identificação de quem deve contribuir com **INSS**, além de outras visualizações úteis.

## 📊 Funcionalidades

- Visualização dos dados filtrados por:
  - **Status** (ex: ATIVO, INATIVO, NOVO)
  - **Hospitais vinculados**
  - **Contribuição com INSS**
- Contagem de médicos por hospital
- Lista de médicos ativos por hospital
- Filtro de **novos cadastros**
- Exportação dos dados filtrados em **CSV**

## 📂 Estrutura do projeto

```
📁 painel-inss/
├── app.py
├── requirements.txt
├── saida_unificada.csv
└── README.md
```

## ▶️ Como executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/painel-inss.git
   cd painel-inss
   ```

2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

3. Rode a aplicação:
   ```bash
   streamlit run app.py
   ```

---

## ☁️ Publicando no Streamlit Cloud

1. Suba o projeto para o GitHub.
2. Acesse: [https://streamlit.io/cloud](https://streamlit.io/cloud)
3. Conecte sua conta GitHub e selecione o repositório.
4. Escolha o arquivo `app.py` como principal.
5. O deploy será feito automaticamente.

---

## 📌 Observação

O arquivo `saida_unificada.csv` é necessário e deve estar no mesmo diretório do `app.py`.

---

## 📧 Contato

Projeto desenvolvido por Hélder Correa.  
Para dúvidas ou sugestões, abra uma _issue_ ou entre em contato!
