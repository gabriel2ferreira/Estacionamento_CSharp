# Sistema de Estacionamento com C#

Este projeto consiste na implementação de um sistema simples de estacionamento em C# para gerenciar veículos estacionados, realizar operações como adicionar veículos, remover veículos (calculando o valor cobrado durante o período) e listar os veículos.

## Funcionalidades Implementadas

### Classe `Estacionamento`

- **Variáveis:**
  - `precoInicial` (Tipo: decimal) - Representa o preço cobrado para deixar um veículo estacionado.
  - `precoPorHora` (Tipo: decimal) - Representa o preço por hora que um veículo permanece estacionado.
  - `veiculos` (Tipo: List<string>) - Representa a coleção de veículos estacionados, contendo apenas a placa do veículo.

- **Métodos:**
  1. `AdicionarVeiculo()`: Adiciona um veículo à lista, solicitando ao usuário a entrada da placa.
  2. `RemoverVeiculo()`: Remove um veículo da lista, calculando e exibindo o valor total cobrado com base no tempo estacionado.
  3. `ListarVeiculos()`: Exibe a lista de veículos estacionados ou uma mensagem informando que não há veículos.

### Menu Interativo

O programa oferece um menu interativo com as seguintes opções:
1. Cadastrar veículo
2. Remover veículo
3. Listar veículos
4. Encerrar

O usuário pode escolher uma das opções, e o programa executa a operação correspondente.

## Como Usar

1. Ao iniciar o programa, o usuário é solicitado a inserir o preço inicial e o preço por hora.
2. Um menu é exibido, permitindo ao usuário escolher entre as operações disponíveis.
3. Cada operação realiza as ações conforme descrito anteriormente.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para propor melhorias ou correções.

## Autor

Gabriel de Lima Ferreira

---

**Observação:** Este projeto faz parte do Desafio de Fundamentos da DIO

