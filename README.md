# 🏡 Análise Imobiliária RJ

Este projeto foi desenvolvido como uma prática de Ciência de Dados em um cenário simulado, onde fomos contratados por uma empresa imobiliária do Rio de Janeiro para dar suporte aos times de Machine Learning e Desenvolvimento Web.

Nosso objetivo principal foi realizar a limpeza, análise exploratória e enriquecimento de uma base de dados com imóveis, facilitando tanto a criação de um modelo de precificação quanto a exibição das informações no site da empresa.

---

## 📊 Objetivos do Projeto

- Explorar as características gerais dos imóveis (EDA);
- Tratar dados nulos e inconsistentes;
- Aplicar filtros com base em requisitos do time de ML;
- Criar colunas numéricas e categóricas para o site da empresa.

---

## 🗂️ Fonte dos Dados

A base de dados contém informações sobre imóveis localizados no Rio de Janeiro, incluindo:

- Tipo do imóvel (casa, apartamento, comércio, etc.);
- Valores de aluguel, condomínio e IPTU;
- Características como número de quartos, suítes, vagas de garagem, e área útil.

---

## 🛠️ Etapas Realizadas

- 📥 Importação e inspeção da base de dados;
- 📌 Análise Exploratória (EDA);
- 🚫 Remoção de registros inconsistentes (aluguéis e condomínios com valor 0);
- 🧼 Tratamento de valores nulos;
- 🔍 Aplicação de filtros com base em critérios do time de ML;
- ➕ Criação das colunas:
  - `valor_por_mes`: aluguel + condomínio;
  - `valor_por_ano`: IPTU + 12 meses de aluguel e condomínio;
  - `descricao`: resumo do imóvel para o site (tipo, bairro, quartos e vagas);
  - `possui_suite`: coluna booleana (sim/não).

---

## 💾 Resultado Final

Após todas as etapas, o dataframe foi exportado em formato `.csv`, pronto para ser utilizado nos modelos de Machine Learning e na interface do site.

---

## 📌 Tecnologias Utilizadas

- Python
- Pandas
- Jupyter Notebook

---

## ✨ Autor(a)

Projeto desenvolvido por Heloisa durante prática de Ciência de Dados da ALURA.  
