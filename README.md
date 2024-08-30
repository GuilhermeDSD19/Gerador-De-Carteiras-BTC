# Gerador de Carteiras Bitcoin

Este projeto foi desenvolvido como parte de um desafio do bootcamp da [DIO](https://www.dio.me/) em parceria com a [Binance](https://www.binance.com/), focado em blockchain. O desafio foi proposto pelo instrutor Cassiano Peres e envolve a criação de um gerador de carteiras Bitcoin utilizando pares de chave pública e privada.

## Funcionalidades

- **Geração de Carteiras Bitcoin**: Criação de pares de chave pública e privada para gerar uma carteira Bitcoin.
- **Criação de Endereços de Depósito e Envio**: Geração de endereços específicos para depósito e envio de bitcoins a partir da carteira criada.
- **Integração com Electrum**: Importação da carteira gerada para o Electrum, um aplicativo desktop que permite enviar e receber transações em Bitcoin.
- **Envio de Criptomoedas**: Realização de transações utilizando a carteira gerada no Electrum.

## Requisitos

- Node.js 
- Bibliotecas necessárias: `bitcoinjs-lib`, `bip32`, `bip39`
- [Electrum](https://electrum.org/) instalado no desktop para importação e gerenciamento das carteiras.

## Como Usar

1. Clone o repositório:
    ```bash
    git clone https://github.com/GuilhermeDSD19/GeradorDeCarteirasBTC
    ```
   
2. Navegue até o diretório do projeto:
    ```bash
    cd GeradorDeCarteirasBTC
    ```
   
3. Instale as dependências:
    ```bash
    npm install
    ```

4. Execute o gerador de carteiras:
    ```bash
    node geradorCarteiras.js
    ```

5. Importe a carteira gerada no Electrum para gerenciar seus fundos e realizar transações.

## Objetivos do Desafio

- Entender o funcionamento das carteiras Bitcoin e o processo de criação de pares de chaves públicas e privadas.
- Aprender a criar endereços para depósito e envio de criptomoedas.
- Experiência prática na integração de carteiras geradas com o Electrum.
- Realização de transações reais de criptomoedas.

## Sobre o Bootcamp

Este projeto foi realizado no contexto do bootcamp da DIO em parceria com a Binance, que oferece uma série de desafios e conteúdos focados em tecnologias de blockchain. O desafio específico de criar um gerador de carteiras Bitcoin foi conduzido pelo instrutor Cassiano Peres.

## Licença

Este projeto é de código aberto e está licenciado sob a [MIT License](LICENSE).
