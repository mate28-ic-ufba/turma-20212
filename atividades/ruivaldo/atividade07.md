1. Qual a ferramenta de issue tracker usada em seu projeto? Há ferramentas externas?

Github issues. Não há ferramentas externas.

2. Desde o início do projeto, qual o número total de issues? Qual a média por ano de issues no projeto? Qual a média de issues resolvidas?

350 desde o início. Média de 87 issues por ano. Taxa de resolução de 95%.

3. Em 2021, quantas issues foram abertas e quantas foram resolvidas?

125 foram abertas, sendo 100 resolvidas.

4. Escolha ao menos 3 issues de seu projeto, sendo ao menos aberta (“open”), e uma fechada (“closed”), 
cada uma com ao menos 3 comentários, e conte a estória resumida da issue, incluindo labels/tags usados, 
referência(s) a outras issues, pedido de explicação da solução, resolução de conflitos, 
se houve indicação de duplicação de issue, se há integração contínua (com uso de testes automatizados? com análise estática de código? outros?).

# https://github.com/zostera/django-bootstrap4/issues/276 (open)

labels: please discuss

Usuário migrou do pacote django-bootstrap3 para o django-bootstrap4, e em um dos formulários da aplicação dele um campo de filtro começou a ter a classe "is-valid" 
adicionada ao ser renderizado. Esta classe traz tons verses e um ícone de "validado" para dentro do campo.

O comportamento é, de fato, indesejado mas até o momento sem uma solução clara, pois o bootstrap (framework CSS) mudou a orientação, passando a priorizar a validação client-side 
dos componentes.

Um "workaround" é apresentado usando um parâmetro existente, mas não documentado, do pacote django-bootstrap4.

A issue encontra-se em aberto até uma solução mais definitiva.

Não houve interação com CI/CD, duplicação de issues ou referência a outras issues.

# https://github.com/zostera/django-bootstrap4/issues/340 (closed)


labels: nenhum

Ao utilizar o template de autenticação sugerido no framework Django juntamente como pacote django-bootstrap4 os campos login e senha aparecem como válidos apesar da autenticação 
falhar. Isso ocorre pois o Django indica o erro de autenticação mas não associa a nenhum campo.

A solução, similar a issue anterior, usa o parâmetro "bound_css_class" para impedir tal comportamento.

Não houve interação com CI/CD, duplicação de issues ou referência a outras issues.


# https://github.com/zostera/django-bootstrap4/issues/222 (closed)

labels: nenhum

Ao instalar o pacote django-bootstrap4, as dependências de desenvolvimento estavam sendo instaladas também.

O erro foi causado por um typo no arquivo de configuração do pacote e deploy "pyproject.toml".

Não houve interação com CI/CD, duplicação de issues ou referência a outras issues.
