# Pata Mansa Store

Este é um **sistema de loja de tênis** desenvolvido como trabalho final da disciplina **Programação de Soluções Computacionais**.

## 📚 Descrição

O Pata Mansa Store é um protótipo de um e-commerce destinado à **venda de tênis**.  
Com ele, é possível:

- Cadastrar usuários
- Realizar o login
- Visualizar uma lista de produtos
- Adicionar produtos ao carrinho
- Selecionar o tamanho
- Quantidade
- Realizar o pagamento (Boleto, Pix ou Cartão)
- Ver o histórico de compras já realizadas

## ⚙ Tecnologias Utilizadas

- **Java**
- **BufferedReader** e **BufferedWriter** para persistir os dados em `.txt`.
- **Scanner** para entrada de dados pelo console.
- Implementação de tratamento de exceções
- Aplicação de programação orientada a objetos

## 🏹 Estrutura do Projeto

- **Vendedor.java** — classe que representa um vendedor
- **Produto.java** — classe que representa um tênis
- **Cliente.java** — classe que representa um comprador
- **ItemCarrinho.java** — classe que relaciona um item a um carrinho
- **Carrinho.java** — classe que faz a mesma função que um carrinho de compras
- **ProdutoArquivo.java** — grava e lê os produtos de um arquivo
- **ClienteArquivo.java** — grava e lê os clientes de um arquivo
- **LojaDeTenisApp.java** — classe principal que faz a interação com o usuário pelo console

## 🔹 Como usar 🔹

1. Compile o aplicativo:
```bash
javac *.java
