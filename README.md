# Consumindo dados da API ViaCEP

Este projeto Java demonstra como consumir a API ViaCEP para buscar informações de endereços a partir de um CEP fornecido pelo usuário e gerar um arquivo JSON com os dados obtidos.

## Funcionalidades

*   **Consulta de CEP:** Permite ao usuário inserir um CEP e buscar os dados correspondentes na API ViaCEP.
*   **Exibição de Endereço:** Exibe os dados do endereço (logradouro, complemento, bairro, localidade, UF) no console.
*   **Geração de Arquivo JSON:** Cria um arquivo JSON com os dados do endereço, formatado de forma legível.
*   **Tratamento de Exceções:** Lida com erros de conexão e CEPs inválidos, exibindo mensagens informativas ao usuário.

## Tecnologias Utilizadas

*   **Java:** Linguagem de programação principal.
*   **HttpClient:** Para fazer requisições HTTP à API ViaCEP.
*   **Gson:** Para converter a resposta JSON da API em objetos Java e vice-versa.
*   **Scanner:** Para receber a entrada do usuário pelo console.

## Como Executar

1.  **Pré-requisitos:**
    *   Java Development Kit (JDK) instalado (versão 8 ou superior).
    *   Um ambiente de desenvolvimento Java (IDE) como IntelliJ IDEA ou Eclipse (opcional).

2.  **Clone o repositório:**

    ```bash
    git clone [URL do seu repositório]
    ```

3.  **Compile o código:**

    *   Se você estiver usando uma IDE, ela geralmente fará isso automaticamente.
    *   Caso contrário, você pode compilar o código usando o comando `javac`:

        ```bash
        javac Principal.java ConsultaCep.java Endereco.java GeradorDeArquivo.java
        ```

4.  **Execute o programa:**

    ```bash
    java Principal
    ```

5.  **Siga as instruções no console:** O programa solicitará que você digite um CEP.

## Estrutura do Projeto
