# DASHBOARD DE VENDAS

Projeto feito com base no curso "Streamlit: construindo um dashboard interativo" da ALURA, que faz parte da formação "Avaçando em Python para Data Science"

---

## 🚀 Como Rodar o Projeto Localmente

Siga estas instruções para configurar e executar o projeto em sua máquina local.

### 📋 Pré-requisitos

Certifique-se de ter o **Python** instalado em sua máquina (versão 3.8 ou superior é recomendada). Você pode baixá-lo em [python.org](https://www.python.org/).

### 🛠️ Instalação

1.  **Clone o repositório:**
    Abra seu terminal ou prompt de comando e execute:
    ```bash
    git clone [https://github.com/SeuUsuario/NomeDoSeuProjeto.git](https://github.com/SeuUsuario/NomeDoSeuProjeto.git)
    cd NomeDoSeuProjeto
    ```
    *(Lembre-se de substituir `SeuUsuario/NomeDoSeuProjeto` pelo caminho real do seu repositório.)*

2.  **Crie e ative o ambiente virtual (venv):**
    É uma boa prática usar um ambiente virtual para isolar as dependências do projeto.
    ```bash
    python -m venv venv
    ```
    * **No Windows:**
        ```bash
        .\venv\Scripts\activate
        ```
    * **No macOS/Linux:**
        ```bash
        source venv/bin/activate
        ```

3.  **Instale as dependências:**
    Com o ambiente virtual ativado, instale todas as bibliotecas necessárias. Certifique-se de ter um arquivo `requirements.txt` no seu projeto com todas as dependências.
    ```bash
    pip install -r requirements.txt
    ```

### ⚡ Executando o Aplicativo Streamlit

Após a instalação das dependências, você pode iniciar o aplicativo Streamlit:

```bash
streamlit run seu_app.py