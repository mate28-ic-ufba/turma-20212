## Parte I - Descrição do projeto

1. Nome: SpotBugs
2. Links:
   1. Website: https://spotbugs.github.io/
   2. Repo: https://github.com/spotbugs/spotbugs
3. Descrição: SpotBugs é o sucessor do FindBugs (arquivado em 2015) - uma ferramenta que realiza a análise estática para identificar bugs em códigos Java.

## Parte II - Reconhecimento Inicial

4. Há quanto tempo o projeto existe? Descreva brevemente o histórico do projeto.
   1. Houve um processo de migração do projeto FindBugs 3.0.1 para o SpotBugs 3.1.0. A primeira versão do Spotbugs é a 1.3.9 (GitHub - Junho de 2014) e a última versão do FindBugs é a 3.0.1 (SourceForge - Março de 2015). Estou considerando esse intervalo de tempo para a caracterização do projeto. 
   2. FindBugs ([SourceForge](https://sourceforge.net/projects/findbugs/)):
   - Criação: Março de 2003 (179fd6c19366bd9739a5ac82dfc632a4e61512f2)
   - Arquivado: Março de 2015 (5fc13043eaf606570bc3723affc8e02e8df50410)
   - Última versão: 3.0.1 - Março de 2015 (5fc13043eaf606570bc3723affc8e02e8df50410) 
   3. SpotBugs ([GitHub](https://github.com/spotbugs/spotbugs)):
   - Início: Junho de 2014 (3c10c02844144f57a07fbe0392440fa7a877cbcb), projeto ativo.
   - Primeira versão: 1.3.9 - Junho de 2014 (3c10c02844144f57a07fbe0392440fa7a877cbcb)
   - Versão mais recente: 4.4.1 - Setembro de 2021 (fca34060e81294274a9c1796895d823069f2985d)
5. Qual a licença do projeto?
    1. FindBugs e SpotBugs utilizam a licença LGPL-2.1.
    2. Para outros artefatos (e.g., imagens), os projetos utilizam a licença CC BY 4.0.
6. Qual o tamanho do projeto (linhas de código, classes)?
   1. Qtde de linhas: 188576
   3. Qtde de classes: 4565
   5. Qtde de contribuidores: 116
   6. Qtde de forks: 405
   7. Qtde de estrelas: 2.5K

7. O tamanho do projeto tem crescido nas últimas versões? 
   1. Da versão 3.0.1 para a 3.1.0, o tamanho do projeto diminuiu. Durante a migração do FindBugs para o SpotBugs, o projeto deixou de dar suporte para o Java 7 e outras bibliotecas/plugins. 
   2. Da versão 3.1.0 em diante, o projeto volta a crescer, apresentando correções de diversos bugs e adições de features.

Versão | # Classes | # Linhas | # Métodos
:---:  | :---:     |:---:     | :---:
1.3.9  | 3713      | 148677   | 14642
2.0.0  | 4478      | 201910   | 19742
3.0.1  | 4842      | 224727   | 20512
3.1.0  | 4465      | 186344   | 17548
4.3.0  | 4548      | 187723   | 17793
4.4.1  | 4565      | 188576   | 17858

8. Existe atividade recente no projeto? Sim. Último commit foi feito em Setembro de 2021.
9. Existe colaboração de empresas no projeto? Não encontrei empresas colaboradoras.
10. Quais as tecnologias usadas? Java
