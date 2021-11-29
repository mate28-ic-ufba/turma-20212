## Atividade 7: Como seu projeto utiliza “issue tracker”?

1. Qual a ferramenta de ***issue tracker*** usada em seu projeto? Há ferramentas externas?
    - Não consegui localizar ferramentas externas. E é difícil de gerenciar as *issues*. 
  
2. Desde o início do projeto, qual o número total de issues?
    - Como o projeto que escolhi possui múltiplos repositórios, vou abordar o Java. Atualmente, existem 56 issues abertas e 498 fechadas.
 
3. Qual a média por ano de *issues* no projeto? 
    - Considerando a primeira *issue* em 2017, tem-se 4 anos. Logo, tem-se uma média de 138 *issues* por ano.

4. Qual a média de *issues* resolvidas?  
      - Como posso diferenciar uma *issue* fechada de uma resolvida?
  
  
5. Em 2021, quantas *issues* foram abertas e quantas foram resolvidas?  
    - Eu busquei por: is:issue  created:>2021-01-01 
    - Como resultado, temos 56 issues abertas e 194 fechadas.
  
6. Escolha ao menos 3 issues de seu projeto, sendo ao menos aberta (“open”), e uma fechada (“closed”), cada uma com ao menos 3 comentários, e conte a estória resumida da issue, incluindo labels/tags usados, referência(s) a outras issues, pedido de explicação da solução, resolução de conflitos, se houve indicação de duplicação de issue, se há integração contínua (com uso de testes automatizados? com análise estática de código? outros?).  
    - No projeto que escolhi as issues são abertas para adição de algoritmos.
	    - A issue aberta:  Reverse a stack [JAVA]  #2364
		    - Ela contém a descrição do algoritmo a adicionar e uma breve discussão entre usuários sobre alocação de memória e recursão. 
		    - Vários contribuidores se propõem a participar na solução.
		    - A única label usada é ***Verified***.

	  - Outra issue aberta (iniciada em 5 de Outubro) é Binary Tree Maximum Path Sum  #2497
		  - Após uma breve discussão sobre caminhos, a issue foi aberta e atribuída a um usuário.
  
    -  Outra issue aberta é: Efficient Fibonacci Implementation: O(logN)  #2600 que foi proposta como parte do Hacktoberfest 2021.
	    - A proposta foi aceita, implementada, mas ainda consta como issue aberta. Há uma requisição de revisão pelo autor que está pendente.
  
    - Uma issue fechada é: Fix package declarations  #2575
	    - O autor da issue aponta uma falha na nomenclatura do pacote.
	    - Ele também aponta que há outras falhas de nomenclatura de pacotes e se é necessário uma issue para cada correção. O adm o orienta a colocar todas as propostas de correção num único PR.
	    - Não há tags.
