# Pipeline de dados: integrando Python com MongoDB e MySQL
**Instituição:** Alura  
**Status:** FINALIZADO ✅  

#  1. Configuração do Ambiente Virtual no WSL

```
python3 -m venv venv
source venv/bin/activate

```
## Instalação das bibliotecas necessárias
```
pip install requests==2.31.0
pip install pymongo==4.4.0
pip install pandas==2.0.3
pip install mysql-connector-python==8.0.33

```

#  2. Extração e Armazenamento dos Dados
## No notebook extract_and_save_data.ipynb:

- Extração dos dados a partir de uma API.

- Armazenamento dos dados no MongoDB Atlas.

- Geração de arquivos CSV para backup e análise.

# 3. Transformação dos Dados
## No notebook transform_data.ipynb:

- Limpeza e padronização dos dados.

- Ajuste de formatos e remoção de inconsistências.

- Preparação para carga no banco relacional

# 4. Carga no MySQL
## No notebook save_data_mysql.ipynb:

- Conexão do Python com o MySQL.

- Criação de banco de dados e tabelas.

- Inserção dos dados transformados no MySQL.

- Consulta e visualização das informações.

# O que aprendi com esse projeto:

- Construir um pipeline de dados com Python.

- Configurar o MongoDB Atlas.

- Utilizar a biblioteca Pymongo para integração com MongoDB.

- Aplicar transformações e limpeza de dados com Pandas.

- Instalar e configurar o MySQL no WSL.

- Conectar o MySQL ao Python com mysql-connector-python.

- Estruturar códigos Python em funções reutilizáveis.


```
## 📂 Estrutura do Repositório
PIPELINE_MONGO_SQL/
│
├── data/
│ ├── pasta onde será gerada os CSV
│
├── notebooks/
│ ├── extract_and_save_data.ipynb
│ ├── save_data_mysql.ipynb
│ ├── transform_data.ipynb
│
├── README.md/
```