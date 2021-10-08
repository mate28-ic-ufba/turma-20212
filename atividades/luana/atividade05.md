## Parte I - Documentação do projeto

1. Onde é encontrada a documentação do projeto?
   - Arquivos dentro de [docs](https://github.com/spotbugs/spotbugs/tree/master/docs) e [github](https://github.com/spotbugs/spotbugs/tree/master/.github).
   - Página [ReadTheDocs](https://spotbugs.readthedocs.io/en/stable/).
2. Que tipo de documentação existe?
   - Usuário (CC BY-NC-SA): https://spotbugs.readthedocs.io/en/stable/
   - Contribuidores: https://github.com/spotbugs/spotbugs/tree/master/.github
3. Como contribuir com a documentação do projeto?
   - Se necessário, contactar um desenvolvedor específico para configurar Read the Docs.
   - Para dar suporte a outras linguagens, é necessário criar um ReadTheDocs independente. 
   - Informar modificações no changelog e enviar um pull request. 
4. Quando ocorre atualizaçao na documentação?    
   - A cada versão do projeto
5. Quando uma mudança na funcionalidade do software, a documentação é atualizada ao mesmo tempo? 
   - Sim.
6. Existem pessoas no projeto mais dedicadas à atividade de documentação? 
   - Sim. O contribuidor KengoTODA.
7. A documentação parece ser relevante? Consistente? 
   - Sim.
8. São usadas ferramentas para apoiar o processo de documentação? Quais? 
   - Sim. As ferramentas [Sphinx](https://www.sphinx-doc.org/en/master/) e [readTheDocs](https://readthedocs.org/).

## Parte II - Contribuição 

9. Escolha uma forma/tipo de documentação.
   - Documentação do usuário - [Issue 540](https://github.com/spotbugs/spotbugs/issues/540).
10. Faça uma contribuição ao projeto e envie um patch.
    - Vou descrever como integrar as findsecbugs regras do findsecbugs no SpotBugs.
    - Estou aprendendo as tecnologias necessárias, mas solução consiste em descrever o trecho de código a ser adicionado no `pom.xml`:
    ```
    <plugin>
      <groupId>com.github.spotbugs</groupId>
      <artifactId>spotbugs-maven-plugin</artifactId>
      <version>4.2.0</version>
      <configuration>
        <effort>Max</effort>
        <threshold>Low</threshold>
        <xmlOutput>true</xmlOutput>
        <plugins>
          <plugin>
            <groupId>com.h3xstream.findsecbugs</groupId>
            <artifactId>findsecbugs-plugin</artifactId>
            <version>1.10.1</version>
          </plugin>
        </plugins>
      </configuration>
      <executions>
        <execution>
          <goals>
            <goal>check</goal>
          </goals>
        </execution>
      </executions>
    </plugin>
    ```
11. Qual foi o feedback que você recebeu dos desenvolvedores do projeto?
    - Ainda não submeti o pull request