# Procedimento 1 - Criação das Entidades e Sistema de Persistência

Para a implementação deste projeto, os seguintes arquivos Java foram criados:

- `App.java`: Arquivo principal que inicia a aplicação.
- `Pessoa.java`: Classe abstrata base para pessoas.
- `PessoaFisica.java`: Classe que representa uma pessoa física, estendendo `Pessoa`.
- `PessoaJuridica.Java`: Classe que representa uma pessoa jurídica, estendendo `Pessoa`.
- `PessoaFisicaRepo.java`: Repositório para gerenciar pessoas físicas.
- `PessoaJuridicaRepo.java`: Repositório para gerenciar pessoas jurídicas.

## Execuções
```
@JoaoFernandesz ➜ /workspaces/Missao-Pratica-Nivel1-Mundo3---Desenvolvimento-FullStack/Primeiro-Procedimento/CadastroPOO (main) $  cd /workspaces/Missao-Pratica-Nivel1-Mundo3---Desenvolvimento-FullStack/Primeiro-Procedimento/CadastroPOO ; /usr/bin/env /usr/local/sdkman/candidates/java/21.0.2-ms/bin/java --enable-preview -XX:+ShowCodeDetailsInExceptionMessages -cp /workspaces/Missao-Pratica-Nivel1-Mundo3---Desenvolvimento-FullStack/Primeiro-Procedimento/CadastroPOO/bin App 
    Dados de Pessoa Fisica Armazenados.
    Dados de Pessoa Fisica Recuperados.
    ID: 1, Nome: Ana
    CPF: 11111111111, Idade: 25
    ID: 2, Nome: Carlos
    CPF: 22222222222, Idade: 52
    Dados de Pessoa Juridica Armazenados.
    Dados de Pessoa Juridica Recuperados.
    ID: 3, Nome: XPTO Sales
    CNPJ: 33333333333333
    ID: 4, Nome: XPTO Solutions
    CNPJ: 44444444444444
```


## Análise e Conclusões
**Quais as vantagens e desvantagens do uso de herança?**

*Vantagens:*
- Permite reutilizar código fazendo o reaproveitamento de métodos e variáveis em diversos contextos, reduzindo a duplicação do código.
- Facilita a organização e manutenção do código.
- Permite que objetos de classes diferentes sejam tratados como o mesmo objetivo de uma superclasse, o que facilita trabalhar com vários tipos de objetos ao mesmo tempo.

*Desvantagens:*
- Java não suporta herança múltipla, o que limita o uso de uma única superclasse por subclasse.
- Em sistemas mais complexos é difícil modificar a estrutura.

**Por que a interface Serializable é necessária ao efetuar persistência em arquivos binários?**

A serialização é uma forma de avisar a JVM que aquela informação pode ser salva em binário, convertendo o estado do objeto em um fluxo de bytes que podem ser armazenados em um arquivo. Essa prática é ideal por aumentar a performance de transferência de dados e definir um padrão de persistência que pode ser lido por diferentes plataformas, versões e arquiteturas. E todo arquivo serializado pode ser deserializado para leitura dinâmica das informações.

**Como o paradigma funcional é utilizado pela API stream no Java?**

Essa fuga do paradigma do POO em Java na API Stream é utilizada para declarar de forma mais prática toda manipulação de dados sequencial, como filter, reduce, map. Permitindo uma performance maior, sem complexidade e sem modificar os dados dos objetos originais, agindo em paralelo ao funcionamento padrão do programa. No entanto, ela ainda opera sobre objetos e classes, processando os dados de maneira funcional dentro da orientação por objetos de Java.

**Quando trabalhamos com Java, qual padrão de desenvolvimento é adotado na persistência de dados em arquivos?**

A persistência de dados em arquivos no desenvolvimento com Java é o DAO. Que separa a lógica de acesso aos dados da lógica de negócios da aplicação.

