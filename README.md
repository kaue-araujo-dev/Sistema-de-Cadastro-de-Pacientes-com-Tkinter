# MedCadastro 🏥

O **MedCadastro** é uma aplicação desktop simplificada desenvolvida em Python para o gerenciamento e cadastro de pacientes. O projeto combina conceitos fundamentais de **Programação Orientada a Objetos (POO)** com a criação de interfaces gráficas (GUI) utilizando a biblioteca nativa **Tkinter**.

Este software serve como um Produto Mínimo Viável (MVP) para demonstrar a captura, estruturação e exibição de dados clínicos em um ambiente controlado e interativo.

---

## ✨ Funcionalidades

* 📝 **Formulário de Entrada:** Campos intuitivos para inserção de dados do paciente (Nome, Idade, CPF e Tipo Sanguíneo).
* ⚙️ **Processamento Orientado a Objetos:** Instanciação automática de um objeto da classe `Paciente` ao submeter o formulário.
* 🖥️ **Exibição Dinâmica:** Atualização em tempo real da interface para exibir as informações cadastradas de forma legível.

---

## 🚀 Tecnologias Utilizadas

* **[Python](https://python.org):** Linguagem de programação principal.
* **[Tkinter](https://python.org):** Biblioteca nativa do Python para o desenvolvimento de interfaces gráficas.

---

## 🛠️ Como Executar o Projeto

Certifique-se de ter o Python 3 instalado em sua máquina. Como o Tkinter já vem integrado com o Python, você não precisa instalar nenhuma dependência externa.

1. **Clone o repositório:**
   ```bash
   git clone https://github.com
   ```

2. **Navegue até a pasta do projeto:**
   ```bash
   cd medcadastro
   ```

3. **Execute o aplicativo:**
   ```bash
   python main.py
   ```

---

## 📂 Estrutura de Código em Destaque

O projeto foi construído separando a lógica da interface do modelo de dados reais do paciente:

* **Classe `Paciente`:** Estrutura em POO responsável por encapsular as propriedades do paciente através de seu método construtor `__init__`.
* **Função `cadastrar_paciente()`:** Resgata os dados dos inputs da janela gráfica (`.get()`), cria o objeto correspondente e renderiza os dados formatados na tela (`.config()`).

---

## 🧠 Aprendizados e Evolução

O desenvolvimento deste projeto permitiu consolidar conhecimentos práticos em:
1. Manipulação de estados de elementos visuais no Tkinter (`Entry`, `Label`, `Button`).
2. Uso do gerenciador de layout básico (`.pack()`).
3. Modelagem de dados com classes no paradigma de POO.
