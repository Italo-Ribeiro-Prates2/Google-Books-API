# Google Books API

Este projeto é um exemplo simples de como usar a Google Books API para buscar informações sobre livros a partir de um nome fornecido pelo usuário.

# Explicação do Código
O aplicativo usa HttpClient para enviar uma solicitação HTTP GET para a API do Google Books.
O usuário é solicitado a inserir o nome do livro.
O aplicativo constrói a URL da solicitação da API usando o nome do livro inserido e uma chave de API predefinida.
A resposta da API é impressa no console.

# Uso
Quando solicitado, insira o nome do livro que deseja buscar.
O aplicativo enviará uma solicitação para a API do Google Books e exibirá a resposta.

## Exemplo de Uso

```sh
Digite o nome do livro: Harry Potter

## Pré-requisitos

- Java JDK 23
- Internet ativa

## Como executar

1. Clone o repositório para sua máquina local:
    ```sh
    git clone <URL_DO_REPOSITORIO>
    ```

2. Navegue até o diretório do projeto:
    ```sh
    cd GoogleBooksAPI
    ```

3. Compile o código:
    ```sh
    javac src/Main.java -d out
    ```

4. Execute o programa:
    ```sh
    java -cp out Main
    ```

5. Digite o nome do livro quando solicitado e pressione Enter.

## Estrutura do Projeto

- `src/Main.java`: Contém o código principal que faz a requisição à Google Books API e exibe o resultado.

