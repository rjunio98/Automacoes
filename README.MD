# 🧩 Projeto de Automação para Mesclar PDFs

Este projeto foi desenvolvido para **automatizar a mesclagem de arquivos PDF** usando Python.  
Ele percorre uma pasta com arquivos PDF, organiza-os em ordem alfabética e gera um único arquivo final contendo todos os PDFs unidos.

---

## 🚀 Funcionalidades

- Lista todos os arquivos dentro da pasta `arquivos`.
- Ordena os arquivos para garantir a sequência correta.
- Verifica se o arquivo é um PDF.
- Mescla todos os PDFs encontrados em um único arquivo chamado **`PDF Final.pdf`**.

---

## 🧠 Tecnologias Utilizadas

- **Python 3.x**
- **Biblioteca [PyPDF2](https://pypi.org/project/PyPDF2/)**

---


## 📜 Como Usar

Crie uma pasta chamada `arquivos` e coloque dentro dela os PDFs que deseja unir.

Execute o script `projeto1.py`:

```bash
python projeto1.py
```

## 📂 Estrutura do Projeto 

📂 projeto
 ┣ 📂 arquivos
 ┃ ┣ 01. PDF.pdf
 ┃ ┣ 02. Arquivo.pdf
 ┃ ┗ 03. Ultimo Arquivo.pdf
 ┣ 📜 projeto1.py
 ┗ 📜 README.md

## 📦 Instalação

Antes de executar o script, instale a biblioteca necessária:

```bash
pip install PyPDF2 
```
