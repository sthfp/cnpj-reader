# CNPJ Reader

O projeto tem por objetivo extrair e unificar informações de um determinado CNPJ, tais como endereço, telefone para contato, e-mail e situação cadastral. O objetivo é tornar possível extrair essas informações em massa.

## 🚀 Começando

Para utilizar o CNPJ reader, você deve utilizar um leitor de Jupyter Notebook. Pode ser um editor de código como Visual Studio Code (veja link para download em "Construído com"), ou utilizando [Jupyter Notebook](https://jupyter.org/install).

### 📋 Pré-requisitos

Instalação das bibliotecas abaixo. As seguintes versões foram utilizadas:

* **requests** 2.31.0
* **plyer** 2.1.0
* **pandas** 2.0.3

### 🔗 Fontes de Dados

As APIs utilizadas são do site [Brasil API](https://brasilapi.com.br/docs). A documentação de utilização de cada API está no site.

* [API CNPJ](https://brasilapi.com.br/docs#tag/CNPJ)
* [API CEP](https://brasilapi.com.br/docs#tag/CEP)
* [API Corretoras](https://brasilapi.com.br/docs#tag/Corretoras)

### 📄 Tabelas

**corretoras_database**

**cnpj_database**

**cep_database**

### 🧰 Principais Funções

As principais funções são as responsáveis pela extração de cada tabela definida acima.

    corretoras_database
    cnpj_database
    cep_database

### ↔️ Relacionamento entre as Tabelas


<img src="/relacionamento_tabelas.jpg">


## 🛠️ Construído com

Mencione as ferramentas que você usou para criar seu projeto

* [Visual Studio Code](https://code.visualstudio.com/download)

## 📄 Licença

Este projeto está sob licença.
