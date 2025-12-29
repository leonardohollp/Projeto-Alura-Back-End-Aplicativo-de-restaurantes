# Projeto-Alura-Back-End-Aplicativo-de-restaurantes

## Descrição

Este projeto consiste em um aplicativo de restaurantes desenvolvido durante o curso de Back-End com Python da Alura. O principal objetivo da aplicação foi aprender e evoluir conhecimentos na linguagem de programação Python, abordando desde conceitos básicos e lógica simples até tópicos avançados como Orientação a Objetos, herança, polimorfismo, criação de ambientes virtuais, uso de APIs e manipulação de arquivos.

O sistema permite o gerenciamento de dados de restaurantes e seus cardápios.

## Funcionalidades

De acordo com a documentação disponível, as funcionalidades do projeto incluem:

*   **Cadastro de restaurantes**: Funcionalidade para registrar novos estabelecimentos.
*   **Cadastro de pratos**: Permite associar pratos aos restaurantes, incluindo valores e descrições.
*   **Consulta**: Funcionalidade para visualizar os restaurantes e pratos cadastrados.

## Tecnologias Utilizadas

As seguintes tecnologias e ferramentas foram identificadas no repositório:

*   **Linguagem**: Python (98.2%).
*   **Framework**: FastAPI.
*   **Ambiente Virtual**: `aluravenv`.
*   **Outros**: Cython (1.8%).

## Estrutura do Projeto

A estrutura de arquivos identificada no repositório é a seguinte:

*   `aluravenv/`: Diretório contendo o ambiente virtual configurado para o projeto.
*   `modelos/`: Pasta destinada às classes e modelos do sistema (contexto de Orientação a Objetos).
*   `app.py`, `app2.py`, `main.py`: Arquivos de código fonte Python (scripts principais de execução).
*   `requirements.txt`: Arquivo contendo as dependências do projeto.
*   `*.json`: Arquivos de dados (ex: `Burger King.json`, `McDonald’s.json`, `Pizza Hut.json`, etc.), indicando uso de arquivos para persistência ou exemplos de dados.

## Pré-requisitos

Para executar este projeto, é necessário ter instalado:

*   **Python**: Linguagem base do projeto.
*   **Dependências**: Listadas no arquivo `requirements.txt`.


## Como Executar o Projeto

*O passo a passo exato de execução não foi detalhado nas fontes fornecidas. Abaixo segue um guia padrão baseado nos arquivos encontrados:*

1.  **Instalação de Dependências**:
    Certifique-se de instalar os pacotes listados no arquivo de requisitos:
    ```bash
    pip install -r requirements.txt
    ```

2.  **Ambiente Virtual**:
    O projeto contém uma pasta `aluravenv`. Recomenda-se ativar o ambiente virtual antes da execução.

3.  **Execução**:
    O projeto possui múltiplos pontos de entrada potenciais (`app.py`, `app2.py`, `main.py`). A execução deve ser feita chamando o interpretador Python ou o servidor do framework (caso utilize Uvicorn com FastAPI):
    ```bash
    python main.py
    # ou
    python app.py
    ```

## Configurações

*   **Arquivos de Configuração**: As dependências do projeto estão listadas em `requirements.txt`.
*   **Variáveis de Ambiente**: Não informado nas fontes.

## Exemplos de Uso

O repositório contém arquivos `.json` que exemplificam a estrutura de dados ou registros de restaurantes já existentes no sistema:
*   Burger King.json
*   KFC.json
*   McDonald’s.json
*   Pizza Hut.json
*   Taco Bell.json
*   Wendy’s.json

Estes arquivos sugerem que o sistema manipula ou exporta dados neste formato.
