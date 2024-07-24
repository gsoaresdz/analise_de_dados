<h1 align="center">Prestadora de Serviços</h1>
<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/gsoaresdz/prestadora-de-servicos?color=56BEB8">
  <img alt="Github language count" src="https://img.shields.io/github/languages/count/gsoaresdz/prestadora-de-servicos?color=56BEB8">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/gsoaresdz/prestadora-de-servicos?color=56BEB8">
</p>
<p align="center">
  <a href="#dart-sobre">Sobre</a> &#xa0; | &#xa0; 
  <a href="#sparkles-análises-realizadas">Análises Realizadas</a> &#xa0; | &#xa0;
  <a href="#rocket-tecnologias">Tecnologias</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requerimentos">Requerimentos</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-execução">Execução</a> &#xa0; | &#xa0;
  <a href="#memo-estrutura-dos-dados">Estrutura dos Dados</a> &#xa0; | &#xa0;
  <a href="#memo-licença">Licença</a> &#xa0; | &#xa0;
  <a href="https://github.com/gsoaresdz" target="_blank">Autor</a>
</p>
<br>

## **:dart: Sobre**

Este repositório contém um projeto que analisa dados de uma prestadora de serviços. O objetivo é explorar e visualizar informações sobre serviços prestados, clientes e funcionários, proporcionando uma visão abrangente do negócio.

## **:sparkles: Análises Realizadas**

:heavy_check_mark: **Análise 1**: Distribuição dos serviços prestados por categoria

:heavy_check_mark: **Análise 2**: Receita total por mês e ano

:heavy_check_mark: **Análise 3**: Desempenho dos funcionários com base nos serviços prestados

:heavy_check_mark: **Análise 4**: Análise demográfica dos clientes

## **:rocket: Tecnologias**

As seguintes ferramentas foram usadas neste projeto:

- [Python](https://www.python.org/)
- [Jupyter Notebook](https://jupyter.org/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- Seaborn

## **:white_check_mark: Requerimentos**

Antes de iniciar :checkered_flag:, você precisa ter [Python 3](https://www.python.org/downloads/) instalado.

## **:checkered_flag: Execução**

### Clonando o Repositório

Primeiramente, clone o repositório do projeto para sua máquina local.

```bash
$ git clone https://github.com/gsoaresdz/prestadora-de-servicos.git
```

### Instalação das Dependências

Para instalar as dependências do projeto, execute o seguinte comando no terminal:

```bash
$ pip install pandas matplotlib seaborn jupyter
```

### Usando Jupyter Notebook

1. Certifique-se de ter o Python 3 instalado no seu sistema.
2. Instale o Jupyter Notebook:
    
    ```bash
    pip install jupyter
    ```
    
3. Navegue até o diretório do projeto e inicie o Jupyter Notebook:
    
    ```bash
    jupyter notebook
    ```
    
4. Abra o arquivo **`main.ipynb`** e execute as células de código para ver as análises e gráficos.

## **:memo: Estrutura dos Dados**

Os dados estão estruturados nas seguintes colunas:

### **BaseServiçosPrestados.xlsx**

- Serviço
- Categoria
- Data
- Valor
- Cliente_ID
- Funcionario_ID

### **CadastroClientes.csv**

- Cliente_ID
- Nome
- Idade
- Gênero
- Cidade

### **CadastroFuncionarios.csv**

- Funcionario_ID
- Nome
- Cargo
- Data_Admissão

## **:memo: Licença**

Este projeto está sob licença do MIT. Para obter mais detalhes, consulte o arquivo [LICENSE](LICENSE).

Feito com :heart: by <a href="https://github.com/gsoaresdz" target="_blank">gsoaresdz</a>

&#xa0;

<a href="#top">De volta ao topo</a>
