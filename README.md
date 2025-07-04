# 💼 Gerenciador de Clientes - Documentação para Iniciantes

Bem-vindo ao **Gerenciador de Clientes**, uma aplicação simples em **Python** 🐍 para gerenciar informações de clientes (nome, sobrenome, e-mail e CPF) com um banco de dados **SQLite** 💾 e interface gráfica feita com **Tkinter** 🖼️.  
Ideal para iniciantes em **Python**, **SQL** e **aplicações com interface gráfica**!

---

## 🛠️ O que esta aplicação faz?

A aplicação permite:

- ➕ **Adicionar** novos clientes ao banco de dados  
- 👀 **Visualizar** todos os clientes em uma tabela  
- 🔍 **Buscar** clientes por nome, sobrenome, e-mail ou CPF  
- ✏️ **Atualizar** dados de clientes existentes  
- ❌ **Deletar** clientes do banco  

A interface é amigável, com campos de entrada, botões intuitivos e uma tabela para visualizar os dados. Tudo é armazenado no arquivo `clientes.db`.

---

## 🧱 Estrutura do Projeto

O projeto é dividido em **3 arquivos** principais:

### 📁 `Gui.py`
- Cria a interface gráfica com **Tkinter**
- Campos de entrada, botões e tabela (Treeview)
- Conecta-se ao backend para executar ações no banco de dados

### 🧠 `Backend.py`
- Lida com todas as operações do banco de dados **SQLite**
- Métodos para **criar tabela**, **inserir**, **listar**, **buscar**, **atualizar** e **deletar** clientes
- Utiliza comandos **SQL seguros**

### ▶️ `application.py`
- Arquivo principal que **inicializa o banco de dados** e **executa a aplicação**
- Abre a interface gráfica

---

## 📦 Pré-requisitos

Você precisa ter instalado:

- ✅ **Python 3.x** (recomendado: 3.8+)  
  [Clique aqui para baixar](https://www.python.org/downloads/)
- ✅ **Tkinter** (já incluído com o Python)
- ✅ **SQLite** (já incluído no Python via `sqlite3`)
- ⚙️ **PyInstaller** (opcional, para criar um executável)

---

## 🚀 Como Executar o Projeto

### 1️⃣ Baixe os arquivos
Crie uma pasta (ex: `gerenciador_clientes`) e adicione os arquivos: `Gui.py`, `Backend.py` e `application.py`.

### 2️⃣ Verifique o Python
No terminal, digite:

```bash
python --version```

---

### ✍️ Autor: Nathan Lemos
