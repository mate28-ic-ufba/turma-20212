## Parte I - Internacionalização do projeto

1. Há partes do projeto (interface de usuário, documentação, website) preparadas para tradução ("internationalization" - I18N)?
    - Sim. A documentação do usuário no ReadTheDocs.
    - Atualmente, a documentação está disponível em inglês e japonês
2. Quais as ferramentas usadas para apoiar o processo de tradução ("localization" - L10N)?
    - Configuração usando o [Sphinx](https://www.sphinx-doc.org/en/master/usage/advanced/intl.html)
    - Usamos o Sphinx para gerar um catálogo de mensagens em arquivos .pot no diretório `/docs/locale/LANGUAGE`. 
    - Para cada linguagem, é necessário criar um ReadTheDocs independente, configurar as opções de idioma e linkar ao repositório principal.
3. Qual o formato utilizado? 
    - N/A
4. Há uma equipe fazendo tradução para Português do Brasil (pt-br)?
    - Não.

## Parte II - Contribuição 

5. Faça uma contribuição de tradução ao projeto e envie um patch.
    - Estou fazendo a tradução da documentação em um [ReadTheDocs](https://spotbugslm.readthedocs.io/pt_BR/latest/) independente.
    - É necessário solicitar acesso de mantenedor ao contribuidor kengoToda para configurar o ambiente.
6. Qual foi o feedback que você recebeu dos desenvolvedores do projeto?
    - Enviei um email para KengoToda descrevendo minha contribuição e solicitando acesso de mantenedor.
    - Irei submeter o PR assim que ele me responder. Acredito que irão aceitar a contribuição, são bastante receptivos :) 
    - O KengoToda respondeu meu email, solicitando para abrir uma discussão no GitHub de modo a guiar pessoas que queiram fazer contribuições similares. Criei a discussão em [Translation of SpotBugs manual](https://github.com/spotbugs/spotbugs/discussions/1786).     
