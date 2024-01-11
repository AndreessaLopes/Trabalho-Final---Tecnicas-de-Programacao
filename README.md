# Trabalho-Final---Tecnicas-de-Programacao
TP - 4 Periodo

# Árvore B em Disco
Este projeto implementa uma Árvore B em disco em C++, conforme as especificações de um trabalho acadêmico. A estrutura da árvore é persistida em registros de arquivo, proporcionando eficiência em operações de leitura e gravação em massa.

## Funcionalidades

- Inserção eficiente de valores na árvore.
- Remoção de valores da árvore mantendo a consistência.
- Impressão completa da árvore.
- Busca de valores na árvore.
- Execução de um conjunto padronizado de testes.

## Pré-requisitos

- Linguagem de programação: C++
- Ambiente de Desenvolvimento: Code::Blocks
- Compilação e teste realizados em ambiente Linux
  
## Contribuindo
Contribuições são bem-vindas! Se você encontrar algum problema ou tiver sugestões para melhorar este projeto, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Como Usar

[Inserir instruções sobre como usar a biblioteca. Exemplos de código são úteis.]

```python
# Exemplo de código em Python
from arvore_b_em_disco import ArvoreBEmDisco

# Criar uma instância da árvore
arvore = ArvoreBEmDisco(grau=4)

# Inserir elementos
arvore.inserir(10)
arvore.inserir(20)
arvore.inserir(5)

# Buscar elementos
resultado = arvore.buscar(20)
print(resultado)  # Deve imprimir True

# Remover elementos
arvore.remover(10)

# Imprimir árvore
arvore.imprimir()



