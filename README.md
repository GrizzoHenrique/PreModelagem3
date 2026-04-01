# Projeto Credit Score Parte 1 - Processamento de dados

### Objetivo:
**Neste projeto iremos análisar visualmente os riscos de um cliente se tornar inadimplente para isso iremos passar por todas as etapas de pré-processamento de dados vistas em modulos anteriores e ao final iremos separar a nossa base em treino(que contem todas as variáveis menos a target) e teste(que contém somente a target)**

### O Dataset
**Os dados foram importados a partir de um csv que continha as seguintes colunas:**
* **Age**: A idade dos nossos clientes.
* **Income**: Salário Mensal
* **Gender**: Gênero(Masculino/Feminino)
* **Education**: Nível de escolaridade dos clientes
* **Marital**: Estado Civil
* **Number of children**: Quantidade de filhos
* **Home**: Tipo de residência, aluga ou propria
* **Credit Score**: Nossa variável preditora, o score de crédito dos clientes

### Etapas do projeto:
1. Realizar toda primeira parte de tratamento dos dados verificando a necessidade de transformação
2. Verificação e tratamento de outliers
3. Análise Univariada
4. Análise Bivariada
5. Matrix de Correlação
6. Balanceamento
7. Codificação de variáveis categóricas
8. Separação de bases em treino e teste

### Tecnologias Utilizidas:
| Tecnologia | Versão |
|-----------|--------|
| ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) | 3.7 +|
| ![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white) | Latest |
| ![Plotly Express](https://img.shields.io/badge/Plotly-Express-3F4F75?logo=plotly&logoColor=white) | Latest |
| ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logoColor=white) | Latest |
| ![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat&logoColor=white) | Latest |
| ![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?logo=scikit-learn&logoColor=white) | Latest |

##  Como Executar

### Pré-requisitos
- Python 3.7+
- pip ou conda

### Instalação

```bash
# Clone o repositório
git clone https://github.com/GrizzoHenrique/PreModelagem3.git
cd PreModelagem3

# Crie um ambiente virtual (recomendado)
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate

# Instale as dependências
pip install -r requirements.txt
