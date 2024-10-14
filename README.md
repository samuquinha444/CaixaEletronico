# Simulação de Caixa Eletrônico em C#

## Visão Geral
Este programa simula um sistema de caixa eletrônico onde os usuários podem gerenciar suas contas bancárias. Os usuários podem realizar várias transações, como depósitos, saques e transferências para contas correntes e de poupança.

## Funcionalidades
- **Tipos de Conta**: Os usuários podem escolher entre contas correntes e de poupança.
- **Transações**:
  - Depositar fundos
  - Sacar fundos
  - Transferir fundos para outra conta
- **Saldo da Conta**: Exibe o saldo atual da conta após as transações.
- **Registro de Transações**: Todas as transações são registradas em um arquivo de texto para consulta posterior.

## Começando

### Pré-requisitos
- SDK do .NET instalado em sua máquina.
- Um editor de código (por exemplo, Visual Studio, VSCode) para executar e modificar o código.

### Instalação
1. Clone o repositório ou baixe o código.
2. Abra o projeto em seu ambiente de desenvolvimento C# preferido.
3. Compile o projeto para garantir que todas as dependências sejam resolvidas.

### Executando o Programa
1. Execute a aplicação a partir de seu ambiente de desenvolvimento ou linha de comando.
2. Siga os prompts para inserir um cartão e escolher o tipo de conta.
3. Use as opções apresentadas para realizar transações:
   - Para contas correntes, você pode depositar, sacar ou transferir fundos.
   - Para contas de poupança, as opções são limitadas a investimentos ou retornar ao menu principal.
4. Saia do programa quando terminar.

## Estrutura do Código

- **Programa Principal**: O ponto de entrada da aplicação onde a interface do caixa eletrônico é inicializada.
- **Manipulação de Transações**: Funções para gerenciar depósitos, saques e transferências, garantindo a atualização correta do saldo e o registro.
- **Manipulação de Arquivos**: Todas as transações são registradas em um arquivo de texto nomeado com a data e hora atual.

### Componentes Principais
- **Variáveis**:
  - `saldo`: Armazena o saldo atual da conta.
  - `escrever`: StreamWriter para gerenciar a escrita no arquivo de registro de transações.
  
- **Prompts para o Usuário**: O programa solicita a entrada do usuário para navegar nas funções do caixa eletrônico.
  
- **Fluxo de Controle**: Utiliza `switch` para os tipos de transação e loops para operação contínua até que o usuário decida sair.

## Exemplo de Transações
- **Depósitos**: Insira o valor que deseja depositar, e ele atualizará o saldo.
- **Saques**: Insira o valor a ser sacado; o programa verifica se há fundos suficientes disponíveis.
- **Transferências**: Insira os detalhes da conta e o valor a ser transferido.

## Tratamento de Erros
- O programa inclui validação básica para a entrada do usuário para lidar com entradas inválidas, garantindo uma experiência de usuário mais suave.

## Conclusão
Esta simulação de caixa eletrônico oferece uma maneira simples, mas funcional, de entender operações bancárias básicas através do código. Pode ser aprimorada ainda mais com a adição de recursos como autenticação de usuário, cálculos de juros para contas de poupança ou uma interface gráfica do usuário (GUI).


