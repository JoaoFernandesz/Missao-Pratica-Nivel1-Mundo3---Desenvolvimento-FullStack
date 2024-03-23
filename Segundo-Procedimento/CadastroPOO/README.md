# Procedimento 2 - Criação do Cadastro em Modo Texto

Para a implementação desta parte do projeto, o seguinte arquivo foi alterado:

- `App.java`: Arquivo principal que inicia a aplicação.

## Execuções
<details closed>
<summary>Todas as Funcionalidades</summary>

```
@JoaoFernandesz ➜ /workspaces/Missao-Pratica-Nivel1-Mundo3---Desenvolvimento-FullStack/Segundo-Procedimento/CadastroPOO (main) $  /usr/bin/env /usr/local/sdkman/candidates/java/21.0.2-ms/bin/java --enable-preview -XX:+ShowCodeDetailsInExceptionMessages -cp /workspaces/Missao-Pratica-Nivel1-Mundo3---Desenvolvimento-FullStack/Segundo-Procedimento/CadastroPOO/bin App 
    ==================================
    1 - Incluir Pessoa
    2 - Alterar Pessoa
    3 - Excluir Pessoa
    4 - Buscar pelo Id
    5 - Exibir Todos
    6 - Persistir Dados
    7 - Recuperar Dados
    0 - Finalizar Programa
    ==================================
    Escolha uma opção: 1
    Incluir Pessoa: [F] - Física | [J] - Jurídica
    f
    Digite o id da pessoa: 01
    Digite o nome da pessoa: Joao Fernandes
    Digite o CPF da pessoa: 99999999999
    Digite a idade da pessoa: 20
    Pessoa Física incluída com sucesso.
    ==================================
    1 - Incluir Pessoa
    2 - Alterar Pessoa
    3 - Excluir Pessoa
    4 - Buscar pelo Id
    5 - Exibir Todos
    6 - Persistir Dados
    7 - Recuperar Dados
    0 - Finalizar Programa
    ==================================
    Escolha uma opção: 5
    Exibir Todos: [F] - Física | [J] - Jurídica
    f
    Pessoas Físicas:
    ID: 1, Nome: Joao Fernandes
    CPF: 99999999999, Idade: 20
    ==================================
    1 - Incluir Pessoa
    2 - Alterar Pessoa
    3 - Excluir Pessoa
    4 - Buscar pelo Id
    5 - Exibir Todos
    6 - Persistir Dados
    7 - Recuperar Dados
    0 - Finalizar Programa
    ==================================
    Escolha uma opção: 4
    Buscar Pessoa pelo ID: [F] - Física | [J] - Jurídica
    f
    Digite o id da pessoa: 01
    ID: 1, Nome: Joao Fernandes
    CPF: 99999999999, Idade: 20
    ==================================
    1 - Incluir Pessoa
    2 - Alterar Pessoa
    3 - Excluir Pessoa
    4 - Buscar pelo Id
    5 - Exibir Todos
    6 - Persistir Dados
    7 - Recuperar Dados
    0 - Finalizar Programa
    ==================================
    Escolha uma opção: 3
    Excluir Pessoa: [F] - Física | [J] - Jurídica
    f
    Digite o id da pessoa: 01
    Pessoa Física excluída.
    ==================================
    1 - Incluir Pessoa
    2 - Alterar Pessoa
    3 - Excluir Pessoa
    4 - Buscar pelo Id
    5 - Exibir Todos
    6 - Persistir Dados
    7 - Recuperar Dados
    0 - Finalizar Programa
    ==================================
    Escolha uma opção: 5
    Exibir Todos: [F] - Física | [J] - Jurídica
    f
    Pessoas Físicas:
    ==================================
    1 - Incluir Pessoa
    2 - Alterar Pessoa
    3 - Excluir Pessoa
    4 - Buscar pelo Id
    5 - Exibir Todos
    6 - Persistir Dados
    7 - Recuperar Dados
    0 - Finalizar Programa
    ==================================
    Escolha uma opção: 1
    Incluir Pessoa: [F] - Física | [J] - Jurídica
    j
    Digite o id da pessoa: 02
    Digite o nome da pessoa: Joao Pessoa Juridica
    Digite o CNPJ da pessoa: 00000000000000
    Pessoa Jurídica incluída com sucesso.
    ==================================
    1 - Incluir Pessoa
    2 - Alterar Pessoa
    3 - Excluir Pessoa
    4 - Buscar pelo Id
    5 - Exibir Todos
    6 - Persistir Dados
    7 - Recuperar Dados
    0 - Finalizar Programa
    ==================================
    Escolha uma opção: 6
    Digite o prefixo para os arquivos de persistência: joao
    Dados persistidos com sucesso.
    ==================================
    1 - Incluir Pessoa
    2 - Alterar Pessoa
    3 - Excluir Pessoa
    4 - Buscar pelo Id
    5 - Exibir Todos
    6 - Persistir Dados
    7 - Recuperar Dados
    0 - Finalizar Programa
    ==================================
    Escolha uma opção: 5
    Exibir Todos: [F] - Física | [J] - Jurídica
    j
    Pessoas Jurídicas:
    ID: 2, Nome: Joao Pessoa Juridica
    CNPJ: 00000000000000
    ==================================
    1 - Incluir Pessoa
    2 - Alterar Pessoa
    3 - Excluir Pessoa
    4 - Buscar pelo Id
    5 - Exibir Todos
    6 - Persistir Dados
    7 - Recuperar Dados
    0 - Finalizar Programa
    ==================================
    Escolha uma opção: 3
    Excluir Pessoa: [F] - Física | [J] - Jurídica
    j
    Digite o id da pessoa: 02
    Pessoa Jurídica excluída.
    ==================================
    1 - Incluir Pessoa
    2 - Alterar Pessoa
    3 - Excluir Pessoa
    4 - Buscar pelo Id
    5 - Exibir Todos
    6 - Persistir Dados
    7 - Recuperar Dados
    0 - Finalizar Programa
    ==================================
    Escolha uma opção: 5
    Exibir Todos: [F] - Física | [J] - Jurídica
    j
    Pessoas Jurídicas:
    ==================================
    1 - Incluir Pessoa
    2 - Alterar Pessoa
    3 - Excluir Pessoa
    4 - Buscar pelo Id
    5 - Exibir Todos
    6 - Persistir Dados
    7 - Recuperar Dados
    0 - Finalizar Programa
    ==================================
    Escolha uma opção: 7
    Digite o prefixo para os arquivos de recuperação: joao
    Dados recuperados com sucesso.
    ==================================
    1 - Incluir Pessoa
    2 - Alterar Pessoa
    3 - Excluir Pessoa
    4 - Buscar pelo Id
    5 - Exibir Todos
    6 - Persistir Dados
    7 - Recuperar Dados
    0 - Finalizar Programa
    ==================================
    Escolha uma opção: 5
    Exibir Todos: [F] - Física | [J] - Jurídica
    j
    Pessoas Jurídicas:
    ID: 2, Nome: Joao Pessoa Juridica
    CNPJ: 00000000000000
    ==================================
    1 - Incluir Pessoa
    2 - Alterar Pessoa
    3 - Excluir Pessoa
    4 - Buscar pelo Id
    5 - Exibir Todos
    6 - Persistir Dados
    7 - Recuperar Dados
    0 - Finalizar Programa
    ==================================
    Escolha uma opção: 0
    Finalizando programa...
    @JoaoFernandesz ➜ /workspaces/Missao-Pratica-Nivel1-Mundo3---Desenvolvimento-FullStack/Segundo-Procedimento/CadastroPOO (main) $ 
```
</details>


## Análise e Conclusões

### O que são elementos estáticos e qual o motivo para o método main adotar esse modificador?

Os elementos estáticos pertencem à classe e não a uma instância específica da classe. É por isso que ele pode ser acessado sem a necessidade de criar uma instância, por isso o método `main` é `static`.

### Para que serve a classe Scanner?

A classe `Scanner` serve para ler dados, independente da fonte (entrada do usuário, arquivos, strings).

### Como o uso de classes de repositório impactou na organização do código?

Isola a lógica de acesso aos dados da lógica de construção deles. Permite facilitar testes, testando de forma independente.


