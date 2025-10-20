# Projeto: Análise dos Dados dos Impactos da Pandemia nas Escolas e Ambiente Laboral no Brasil (2019-2023)

Este projeto analisa os efeitos da pandemia na educação e no mercado de trabalho brasileiro, utilizando dados públicos e bibliotecas de análise de dados em Python.

---

## Como usar os datasets no Google Colab

### 1. Baixar os dados

- Faça o download do arquivo `.zip` contendo os datasets do projeto.

### 2. Extrair os arquivos

- Extraia o conteúdo do `.zip` no seu computador usando o gerenciador de arquivos de sua preferência.

---

### 3. Subir os arquivos para o Google Colab

#### Passo a passo:

1. Acesse o [Google Colab](https://colab.research.google.com) e abra o **notebook principal do projeto**.

2. No menu à esquerda, clique no ícone de **arquivos** (ícone de pasta).

3. Dentro da pasta `/content`, clique com o **botão direito do mouse** e selecione **"Nova Pasta"** para criar as seguintes pastas:

   - `Indic_BR`
   - `Indic_Geo`
   - `Rend_Escolar`

4. Agora, **arraste os arquivos extraídos no seu computador** para dentro das respectivas pastas criadas:

   - Os arquivos `Indic_BRxxxx.csv` vão para a pasta `Indic_BR`
   - Os arquivos `Indic_Geoxxxx.csv` vão para a pasta `Indic_Geo`
   - Os arquivos `Rend_Escolarxxxx.csv` vão para a pasta `Rend_Escolar`

---

### Estrutura esperada no Colab

```
/content/
├── Indic_BR/
│ ├── Indic_BR2019.csv
│ ├── Indic_BR2020.csv
│ └── ...
├── Indic_Geo/
│ ├── Indic_Geo2019.csv
│ ├── Indic_Geo2020.csv
│ └── ...
├── Rend_Escolar/
│ ├── Rend_Escolar2019.csv
│ ├── Rend_Escolar2020.csv
│ └── ...

```


> Com essa estrutura, o código do projeto conseguirá carregar os arquivos corretamente sem precisar alterar os caminhos.

---

## 🧪 Tecnologias utilizadas

- Python 3.10+
- `pandas`
- `plotly`
- `requests`
- Google Colab

---

