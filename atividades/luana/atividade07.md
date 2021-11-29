## Parte I - Como seu projeto utiliza "issue tracker"?

1. Qual a ferramenta de issue tracker usada em seu projeto? Há ferramentas externas?
    - As issues ficam no repositório do [SpotBugs](https://github.com/spotbugs/spotbugs/issues) no GitHub.
    - Não há ferramentas externas.
    
2. Desde o início do projeto, qual o número total de issues? Qual a média por ano de issues no projeto? Qual a média de issues resolvidas?
    - Ao todo são 810 issues; 393 abertas e 417 resolvidas.
    
3. Em 2021, quantas issues foram abertas e quantas foram resolvidas?
    - Em 2021 foram reportadas 24 issues; 14 ainda estão abertas e 10 foram resolvidas.

4. Escolha ao menos 3 issues de seu projeto, sendo ao menos aberta (“open”), e uma fechada (“closed”), cada uma com ao menos 3 comentários, 
e conte a estória resumida da issue, incluindo labels/tags usados, referência(s) a outras issues, pedido de explicação da solução, 
resolução de conflitos, se houve indicação de duplicação de issue, se há integração contínua (com uso de testes automatizados? 
com análise estática de código? outros?).

  - [Issue 1067](https://github.com/spotbugs/spotbugs/issues/1602) 
    -  Status: fechada.
    -  Número de comentários: 9.
    -  Aberta em: 05 de julho de 2021.
    -  Fechada em: 23 de agosto de 2021.
    -  Labels: Nenhuma (mas deveria ser Duplicate).
    -  Descrição: O usuário `coinzz` não estava conseguindo visualizar a GUI de forma completa. 
    Ele estava pensando ser alguma incompatibilidade com seu workspace, já que os seus colegas de trabalho obtém uma GUI funcional. O `coinzz` reportou a issue 
    utilizando imagens, mas não indexou o log de erro necessário para o contribuidor `iloveeclipse` ajudá-lo. O `iloveeclipse` ajudou `coinzz` a identificar a 
    localização do log de erro. Na sequência, podemos ver o `coinzz` fazendo diversas tentativas e apresentando o log de erro para 'iloveeclipse'.
    Outro contribuidor, o `msternermxy`, indicou que essa issue é uma duplicata da [Issue 1477](https://github.com/spotbugs/spotbugs/issues/1477).
    Essa segunda issue foi reportada e resolvida por `msternermxy`, cuja correção está disponível na Release 4.4.0 do SpotBugs. 
    Como essa solução resolveu o problema do `coinzz`, ele fechou a issue. 
    
  - [Issue 1515](https://github.com/spotbugs/spotbugs/issues/1515)
    - Status: aberta.
    - Número de comentários: 13.
    - Aberta em: 16 de abril de 2021. 
    - Fechada em: --
    - Labels: Nenhuma.
    - Descrição: A issue reporta a discussão entre dois usuários, `jglick` e `pfirmstone` sobre a desativação de um detector do SpotBugs por padrão. 
    O usuário `jglick` relata que a organização em que trabalha utiliza o SpotBugs em centenas de projetos. Dado que o detector DoInsideDoPrivileged 
    utiliza um método de uma API marcado como deprecated com Java 17, ele acredita que o detector DoInsideDoPrivileged deva ser removido 
    ou desabilitado por padrão no SpotBugs. O usuário `pfirmstone` discute que muitos outros projetos podem utilizar de outras versões Java e o detector se faz
    necessário por tratar de quesões de segurança de autenticação. Como o SpotBugs suporta a configuração dos detectores a serem executados, ele sugere que o 
    `jglick` apenas configure isso. Essa discussão é bem longa e outros usuários tem se juntado a ela e, inclusive, foram criadas duplicatas dessa issue. 
    Uma das sugestões para resolver o problema é disparar um aviso sobre deprecated-for-removal API, mas eles ainda não chegaram a uma conclusão sobre o que fazer.
    
  - [Issue 540](https://github.com/spotbugs/spotbugs/issues/540)
    - Status: fechada.
    - Número de comentários: 8.
    - Aberta em: 19 de janeiro de 2018.
    - Fechada em: 11 de novembro de 2021.
    - Labels: good-first-issue, documentation
    - Descrição: O usuário `jacek99` reporta que a página da ferramenta afirma que é possível integrar o SpotBugs com outros plugins usando maven e gradle, mas não tem documentação sobre isso.
    O contribuidor `iloveeclipse` disse que a integração é meio que trivial, mas concorda que a documentação precisa ser melhorada e adiciona a label documentation.
    O contribuidor `h3xstream` aparece com uma solução próxima ao que pode ser seguido para documentar o que `jacek99` solititou.
    O contribuidor `KengoTODA` apontou que parte da solução, integração usando gradle, já estava disponível na documentação. Como não tinha documentação para a parte maven, ele adicionou a label good-first-issue.
    E foi essa issue que eu, `luana-martins`, trabalhei na minha primeira atividade no SpotBugs. Interagi com o pessoal para saber se poderia trabalhar na issue. Submeti meu PR, mas não sabia como fechar a issue.
    Então o `KengoTODA` fechou a issue após fazer o merge do meu PR.
