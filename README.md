# 🐍 Projetos Educacionais em Python: Finanças e História

![Python Version](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![Tkinter](https://img.shields.io/badge/GUI-Tkinter-lightgrey?style=for-the-badge)
![Pillow](https://img.shields.io/badge/Pillow-Image_Processing-green?style=for-the-badge)
![Requests](https://img.shields.io/badge/Requests-HTTP-red?style=for-the-badge)
![Educação](https://img.shields.io/badge/Foco-Educa%C3%A7%C3%A3o-success?style=for-the-badge)

> **Uma coleção de aplicações gráficas desenvolvidas em Python utilizando Tkinter.**  
> Projetos elaborados com foco didático para alunos do programa **Jovem Aprendiz**, integrando conceitos de programação procedural, educação financeira e história do Brasil.

---

## 🎯 Objetivos Didáticos

Este repositório foi construído para facilitar o aprendizado prático de iniciantes na programação, focando em:

- **🧠 Lógica Procedural:** Estruturação de código sem o uso de Orientação a Objetos (POO), facilitando a assimilação inicial de funções, parâmetros e escopo global (`global`).
- **🖥️ Interface Gráfica (GUI):** Construção de telas interativas utilizando `tkinter` e seus componentes mais modernos (`ttk.Notebook`, `Listbox`, `Frame`, etc.).
- **🛡️ Tratamento de Exceções:** Implementação de blocos `try/except` para validação de entradas numéricas, prevenindo quebras no sistema.
- **🌐 Integração Web:** Consumo de requisições HTTP (com a biblioteca `requests`) e manipulação de imagens (com `Pillow`).

---

## 🚀 Projetos Incluídos

### 1. 📜 Linha do Tempo: Eufrásia Teixeira Leite
*(Arquivo: `historia_financas_with_eufrasia_seunome.py`)*

Uma interface interativa que conta a história de **Eufrásia Teixeira Leite (1850–1930)**, reconhecida como a primeira investidora global do Brasil.
* **Destaques:** 
  * Download e exibição de imagem via requisição HTTP (`requests` e `Pillow`).
  * Tratamento de falhas de conexão (mantém a aplicação funcional mesmo offline).
  * Botões interativos que revelam fatos históricos.
* 🖼️ *[Insira aqui uma captura de tela do projeto]*

### 2. 💵 Simulador de Aportes
*(Arquivo: `financas_aportes_bankb3_seunome.py`)*

Uma calculadora de fluxo de caixa simplificada, ideal para ensinar os conceitos básicos de operações de depósito e saque.
* **Destaques:**
  * Controle de saldo em tempo real.
  * Lógica de validação para impedir saques superiores ao saldo disponível.
  * Atualização dinâmica de rótulos e campos de texto na interface.
* 🖼️ *[Insira aqui uma captura de tela do projeto]*

### 3. 📊 Dashboard Financeiro - Padrão B3
*(Arquivo: `financas_dashboard_bankb3_seunome.py`)*

Um painel completo simulando o ambiente da Bolsa de Valores brasileira (B3).
* **Destaques:**
  * Navegação moderna utilizando abas interativas (`ttk.Notebook`) para as seções: Conta Corrente, Criptoativos e Extrato.
  * Simulação de compra de frações de Bitcoin (BTC).
  * Histórico de transações atualizado em tempo real utilizando `tk.Listbox`.
* 🖼️ *[Insira aqui uma captura de tela do projeto]*

---

## 🛠️ Pré-requisitos e Instalação

Para executar os projetos localmente, você precisará do **Python 3.10 ou superior** instalado em sua máquina.

### 1. Clonando o Repositório
```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```

### 2. Instalando Dependências
Abra o terminal (ou prompt de comando) e execute o comando abaixo para instalar as bibliotecas externas necessárias:

```bash
pip install requests pillow
```
*(Alternativamente: `python -m pip install requests pillow`)*

> ⚠️ **Nota sobre o Tkinter:** O Tkinter já vem instalado por padrão na maioria das distribuições do Python para Windows e macOS. Caso esteja utilizando Linux (Ubuntu/Debian) e encontre erros, instale-o via terminal com:
> ```bash
> sudo apt-get update
> sudo apt-get install python3-tk
> ```

---

## 💻 Como Executar as Aplicações

Com o terminal aberto na pasta do projeto, execute o arquivo correspondente ao projeto que deseja abrir:

**Para a Linha do Tempo de Eufrásia:**
```bash
python historia_financas_with_eufrasia_seunome.py
```

**Para o Simulador de Aportes:**
```bash
python financas_aportes_bankb3_seunome.py
```

**Para o Dashboard da B3:**
```bash
python financas_dashboard_bankb3_seunome.py
```

---

## 🗂️ Estrutura do Repositório

```text
📦 Projetos-Educacionais-Python
 ┣ 📜 historia_financas_with_eufrasia_seunome.py  # App sobre Eufrásia Teixeira Leite
 ┣ 📜 financas_aportes_bankb3_seunome.py          # Simulador simples de depósitos/saques
 ┣ 📜 financas_dashboard_bankb3_seunome.py        # Dashboard financeiro com abas (B3)
 ┗ 📜 README.md                                   # Documentação do projeto
```

---

<p align="center">
  💙 <i>Projeto desenvolvido para fins educacionais e de capacitação profissional.</i>
</p>
