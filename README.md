# Projeto Java Estoque

Este é um simples aplicativo de console em Java para gerenciar o estoque de produtos. O projeto demonstra conceitos básicos de programação orientada a objetos, como classes, métodos e encapsulamento.

## Funcionalidades

- Cadastrar um produto com nome, preço e quantidade
- Adicionar produtos ao estoque
- Remover produtos do estoque
- Exibir dados do produto e informações atualizadas do estoque

## Como Executar

1. **Compile o projeto:**
   Abra um terminal na raiz do projeto e execute:
   ```sh
   javac -d bin src/application/Program.java src/entities/Product.java
   ```
2. **Execute a aplicação:**
   ```sh
   java -cp bin application.Program
   ```

## Exemplo de Uso

```
Digite os dados do produto:
Nome:
TV
Preço:
900.00
Quantidade em estoque:
10

Dados do produto: TV, $900.00, 10 unidades, Total: $9000.00

Digite o número de produtos a serem adicionados no estoque:
5
Dados atualizados: TV, $900.00, 15 unidades, Total: $13500.00

Digite o número de produtos a serem removidos do estoque:
3

Dados atualizados: TV, $900.00, 12 unidades, Total: $10800.00
```

## Requisitos

- Java JDK 8 ou superior

---

_Este projeto é para fins educacionais._
