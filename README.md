<h1 align="center">Service Provider</h1>
<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/gsoaresdz/service-provider?color=56BEB8">
  <img alt="Github language count" src="https://img.shields.io/github/languages/count/gsoaresdz/service-provider?color=56BEB8">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/gsoaresdz/service-provider?color=56BEB8">
</p>
<p align="center">
  <a href="#dart-about">About</a> &#xa0; | &#xa0; 
  <a href="#sparkles-analyses-performed">Analyses Performed</a> &#xa0; | &#xa0;
  <a href="#rocket-technologies">Technologies</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requirements">Requirements</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-running">Running</a> &#xa0; | &#xa0;
  <a href="#memo-data-structure">Data Structure</a> &#xa0; | &#xa0;
  <a href="#memo-license">License</a> &#xa0; | &#xa0;
  <a href="https://github.com/gsoaresdz" target="_blank">Author</a>
</p>
<br>

## **:dart: About**

This repository contains a project that analyzes data from a service provider. The goal is to explore and visualize information about services rendered, clients, and employees, providing a comprehensive overview of the business.

## **:sparkles: Analyses Performed**

:heavy_check_mark: **Analysis 1**: Distribution of services rendered by category

:heavy_check_mark: **Analysis 2**: Total revenue by month and year

:heavy_check_mark: **Analysis 3**: Employee performance based on services rendered

:heavy_check_mark: **Analysis 4**: Demographic analysis of clients

## **:rocket: Technologies**

The following tools were used in this project:

- [Python](https://www.python.org/)
- [Jupyter Notebook](https://jupyter.org/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- Seaborn

## **:white_check_mark: Requirements**

Before starting :checkered_flag:, you need to have [Python 3](https://www.python.org/downloads/) installed.

## **:checkered_flag: Running**

### Cloning the Repository

First, clone the project repository to your local machine.

```bash
$ git clone https://github.com/gsoaresdz/service-provider.git
```

### Installing Dependencies

To install the project dependencies, run the following command in the terminal:

```bash
$ pip install pandas matplotlib seaborn jupyter
```

### Using Jupyter Notebook

1. Make sure Python 3 is installed on your system.
2. Install Jupyter Notebook:
    
    ```bash
    pip install jupyter
    ```
    
3. Navigate to the project directory and start Jupyter Notebook:
    
    ```bash
    jupyter notebook
    ```
    
4. Open the **`main.ipynb`** file and run the code cells to see the analyses and charts.

## **:memo: Data Structure**

The data is structured in the following columns:

### **BaseServiçosPrestados.xlsx**

- Service
- Category
- Date
- Value
- Client_ID
- Employee_ID

### **CadastroClientes.csv**

- Client_ID
- Name
- Age
- Gender
- City

### **CadastroFuncionarios.csv**

- Employee_ID
- Name
- Position
- Hiring_Date

## **:memo: License**

This project is licensed under the MIT License. For more details, see the [LICENSE](LICENSE) file.

Made with :heart: by <a href="https://github.com/gsoaresdz" target="_blank">gsoaresdz</a>
