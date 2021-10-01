## Reconhecimento técnico

### Parte I - Descrição do projeto

1. *Nome:* Zulip Terminal
2. *Website:* https://zulip.com/
3. *Descrição:* É o cliente de terminal para o Zulip, um chat para times distribuídos.

![image](https://user-images.githubusercontent.com/43190457/135662629-cedb35ea-f1f8-4fbd-86c5-915c455476c7.png)


### Parte II - Reconhecimento Inicial

4. *Há quanto tempo o projeto existe? Descreva brevemente o histórico do projeto:* 
    Desde 22 de março de 2017, 199 versões foram lançadas. 9 releases foram lançados desde então

5. *Qual a licença do projeto?:*
    Apache-2.0 License

6. *Qual o tamanho do projeto (linhas de código, classes)?*

    | File Type | Files | Lines of Code | Total Lines |
    |-----------|-------|---------------|-------------|
    | Python    | 63    | 23043         | 26608       |
    | Text      | 10    | 0             | 1567        |
    
7. *O tamanho do projeto tem crescido nas últimas versões?*
    O projeto estava em plena atividade até julho deste ano, e nos meses seguintes sua atividade foi diminuindo bastante. 

8. *Existe atividade recente no projeto?*
    Razoavelmente. Como dito, o projeto recebeu modificações grandes em julho deste ano, e o último commit foi no dia 30 de agosto.

9. *Existe colaboração de empresas no projeto?*
    Não, apenas pessoas independentes.

10. *Quais as tecnologias usadas?*
    A linguagem de programação utilizada é Python. As seguintes bibliotecas são utilizadas em desenvolvimento:
    
    
    Dependências de teste
    testing_deps = [
      "pytest~=6.2.3",
      "pytest-cov~=2.11.1",
      "pytest-mock~=3.6.0",
    ]


    Verificadores automáticos de código
    linting_deps = [
        "isort~=5.7.0",
        "flake8~=3.9.0",
        "flake8-quotes~=3.2.0",
        "flake8-continuation~=1.0.5",
        "black>=21.5b1",
    ]


    Bibliotecas de digitação
    typing_deps = [
        "mypy==0.910",
        "types-python-dateutil",
        "types-tzlocal",
        "types-pytz",
        "types-requests",
    ]


    Bibliotecas de desenvolvimento
    dev_helper_deps = [
        "pudb==2017.1.4",
        "snakeviz==0.4.2",
        "gitlint>=0.10",
        "autopep8~=1.5.4",
        "autoflake~=1.3.1",
    ]
