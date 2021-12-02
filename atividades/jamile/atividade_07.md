## Utilização de Issue Tracker



**Qual a ferramenta de issue tracker usada em seu projeto? Há ferramentas externas?**

Duas ferramentas concentram o processo de report de bugs e issue tracker do projeto: [GitHub](https://github.com/musescore/MuseScore) e [Website](musescore.org), nas seções Fórum e Issue Tracker.

Processo:
- O primeiro passo para relatar um susposto problema ou funcionalidade ausente é postá-lo no [Fórum](https://musescore.org/pt-br/forum) para obter uma segunda opinião e esclarecer questões junto à equipe.
- Quando confirmada a existência da issue, deve-se cadastradá-la no site, desta vez, na seção [issue tracker](https://musescore.org/en/project/issues/musescore). 
- Em seguida, membros da equipe fazem o devido acompanhamento, checando a issue e averiguando se o report está completo. Na sequência, elas são priorizadas e os status mantidos atualizados, podendo ser "active", "needs info" ou "PR (pull request) created", conforme encaminhamento por parte da equipe. 
- Issues são então criadas no GitHub e identificadas em uma das 24 (vinte e quatro) opções de labels, tais como, sugestões para iniciantes, classificações por prioridade e reservadas para equipe interna.


**Desde o início do projeto, qual o número total de issues? Qual a média por ano de issues no projeto? Qual a média de issues resolvidas?**

Desde a existência do projeto até a data atual (05/nov/21) foram criadas 9639 issues. Destas, 443 ainda estão em aberto e 9196 foram fechadas.

A média é 963,9 issues por ano, entretanto, como pode-se observar no quadro abaixo, o crescimento do projeto intensificou-se a partir de 2018, desta forma, tal média não é representativa se for considerado os primeiros anos do projeto.


| Ano / Issues | Criadas | Em aberto | Fechadas | Média resolvidas
| :------------- | :------------- | :------------- | :------------- |:------------- |
| 2021 | 2461 | 421 | 2040 | - |
| 2020 | 1624 |  17 | 1607 | 98,95% |
| 2019 | 1040 |   5 | 1035 | 99,52% |
| 2018 | 1049 |   0 | 1149 | 100% | 
| 2017 |  430 |   0 |  430 | 100% | 
| 2016 |  609 |   0 |  609 | 100% | 
| 2015 |  733 |   0 |  733 | 100% | 
| 2014 |  974 |   0 |  974 | 100% | 
| 2013 |  461 |   0 |  461 | 100% | 
| 2012 |  158 |   0 |  158 | 100% | 
| TOTAL|  9639| 443 |  9196 |



**Em 2021, quantas issues foram abertas e quantas foram resolvidas?**

De 01/jan/21 até a presente data, 05/nov/21, foram abertas 2461 issues, sendo que destas, 2040 foram resolvidas e 421 seguem abertas. 


**Escolha ao menos 3 issues de seu projeto, sendo ao menos aberta (“open”), e uma fechada (“closed”), cada uma com ao menos 3 comentários, e conte a estória resumida da issue, incluindo labels/tags usados, referência(s) a outras issues, pedido de explicação da solução, resolução de conflitos, se houve indicação de duplicação de issue, se há integração contínua (com uso de testes automatizados? com análise estática de código? outros?).**

***Issue 1** - [Inspector] Bracket / Parenthesis options for accidentals using incorrect UI [#9442](https://github.com/musescore/MuseScore/issues/9278)*

![](https://user-images.githubusercontent.com/21022311/136990688-8cb64ce8-c363-4258-8497-4aababf99d40.png)

| | | 
| :------------- | :------------- | 
| Criada em: | 10/out/21 |
| Status: | Fechada |
| Label: | P2 - Priority: Medium |
| Participantes:| 06 |
| Comentários: | 09 |

Descrição: Trata-se de uma sugestão de remoção da possibilidade de usar parêntesis para indicar acidente em uma nota. Além de ser uma notação incorreta, o espaço reservado para o texto do botões é restrito e isso causaria problemas com idiomas que possuem termos com muitos caracteres, como alemão ou polonês.

Solução: Após algumas discussões, acatou-se a sugestão de remover os parêntesis como opção, e trocar palavras por ícones, o que resolveria  possíveis problemas com traduções. 
Houve ainda uma certa dúvida em levar adiante a remoção de um elemento UI, mas concluiu-se que não haveria problemas pois estes seriam removidos apenas da interface, ou seja, usuários que já usaram o recurso não teriam problemas em suas partituras.
Issue foi encerrada.


***Issue 2** - Metronome Sound Needs to be implemented [#9182](https://github.com/musescore/MuseScore/issues/9182)*

![](https://user-images.githubusercontent.com/21022311/133816939-7c03043b-01df-478c-bf9c-d43f8ec1824f.png)

| | | 
| :------------- | :------------- | 
| Criada em: | 17/set/21 |
| Status: | Aberta |
| Label: | P0 - Priority: Critical |
| Participantes:| 04 |
| Comentários: | 06 |


Descrição: Trata-se da implementação do metrônomo no MuseScore v. 4. 
Quatro membros discutem qual melhor som para esta função. A primeira sugestão é usar som de blocos de madeira, a segunda, manter o som já usado no MU3, mas é alertado que esta versão usa um som sintetizado simples, não um canal soundfont. Por fim, outro membro sugere que não sejam usados sons parecidos com instrumentos que possam ser inseridos nas partituras, para evitar confusão sonora. Lembrou ainda a necessidade de dois sons para alternar as batidas, o que se encaixa nos blocos de madeira. 

Solução: A issue foi incluída há 20 dias na lista de To Do. 
Aguardando algum pull-request.

***Issue 3** - [MU4 Issue] Two Musescore 4's open while trying to create a new score [#9631](https://github.com/musescore/MuseScore/issues/9631)*

| | | 
| :------------- | :------------- | 
| Criada em: | 01/nov/21 |
| Status: | Aberta |
| Label: | P0 - Priority: Critical |
| Participantes:| 04 |
| Comentários: | 04 |


Descrição: Em alguns momentos, uma segunda janela do MuseScore 4 é aberta quando tenta-se criar uma nova partitura. Erro fatal detectado no Windows e Mac. Issue possui lavel de prioridade máxima.

Solução: Encaminhada para a adequada pasta To Do. Aguardando algum pull-request.

