# Previsão de Vendas de Sorvete com Azure Machine Learning

## Visão Geral

Este projeto tem como objetivo prever a quantidade de vendas de sorvete com base na temperatura e dados históricos. Foi gerada uma tabela simulada com 10 registros de vendas por dia, ao longo de 2 anos, contendo:

- **Data**
- **Temperatura**
- **Quantidade Vendida**

Esses dados foram utilizados em um experimento no ambiente do **Azure Machine Learning**, com foco no uso do recurso **Automated ML** para a construção de um modelo de regressão.

## Ambiente de Desenvolvimento

O experimento foi realizado na ferramenta **Azure Machine Learning Studio**, utilizando a interface visual do **Designer**, que permite a criação de fluxos de trabalho de machine learning sem necessidade de escrever código.

Embora a análise pudesse ser feita utilizando notebooks e scripts Python, este laboratório priorizou o uso da ferramenta Designer, destacando a facilidade e acessibilidade da abordagem de baixo código.

## Etapas do Desenvolvimento

### Criando o Resource Group e o Azure Machine Learning

![image](https://github.com/user-attachments/assets/2fcd92d3-3007-4af3-94fc-032c760d89a5)

---

### Acessando os notebooks

![image](https://github.com/user-attachments/assets/a7e1f44c-234c-4058-9bce-87745813ecb1)

---

### Base de dados importada

![image](https://github.com/user-attachments/assets/0dc6615c-55e5-4f27-86be-2cae8e98b61e)

---

### Criação da instância e do cluster

![image](https://github.com/user-attachments/assets/5f307988-4e01-4df9-b130-554601b36ca9)  
![image](https://github.com/user-attachments/assets/5ea1d82b-3319-471c-8d97-0be23a174815)

---

### Criando e executando o Automated ML

![image](https://github.com/user-attachments/assets/34f757c7-327e-421f-ba59-a61ec2a1068b)

---

### Configurando o Designer

![image](https://github.com/user-attachments/assets/1d675ff8-5f5a-4218-8b01-a458f088dcbe)

---

### Resultado após o pipeline ser executado

![image](https://github.com/user-attachments/assets/04571859-e042-4fbd-a93f-09ade7c800d8)  
![image](https://github.com/user-attachments/assets/bdece277-6517-417c-b4b5-bc0738bfb34b)

---

## Pipeline do Experimento

1. **Importação dos Dados**: A base de dados foi carregada no Azure Machine Learning.
2. **Configuração do Automated ML**: Foi criado um experimento para prever a variável "quantidade vendida" com base na temperatura.
3. **Execução via Designer**: O fluxo foi construído visualmente com os módulos disponíveis na ferramenta.
4. **Treinamento Automático**: O Automated ML testou diferentes algoritmos de regressão, avaliando automaticamente o desempenho


---

## Principais recursos utilizados

### `Resource Group`
Grupo lógico que agrupa todos os recursos utilizados no projeto, facilitando a gestão e controle de custos no Azure.

### `Azure Machine Learning`
Serviço em nuvem da Microsoft para criação, treinamento e implantação de modelos de machine learning. Suporta tanto codificação quanto interfaces visuais.

### `Compute Instances`
Máquinas virtuais usadas para desenvolvimento, testes e execução de notebooks Jupyter.

### `Compute Clusters`
Clusters escaláveis de máquinas virtuais utilizados para treinar modelos de machine learning em larga escala.

### `Automated ML`
Ferramenta que automatiza o processo de machine learning, realizando tarefas como:
- Seleção de algoritmos
- Pré-processamento de dados
- Ajuste de hiperparâmetros
- Avaliação de modelos

### `Designer`
Interface de arrastar-e-soltar para criação de pipelines de machine learning. Permite montar experimentos completos sem escrever código, sendo ideal para prototipagem e ensino.

---

**Autor:** Marco Aurélio Alencastro  

**LinkedIn:** [Marco Alencastro](https://linkedin.com/in/marco-alencastro)  

**Data:** Abril/2025
