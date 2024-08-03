# CriandoCarteiraBTC
Projeto de criação de carteira BTC experimental na TestNet para receber e transacionar cryptos, realizado durante BootCamp Blockchain Developer with Solidity da Binance em parceiria com a DIO.

## Tecnologias Utilizadas

- Node.js: Ferramenta capaz de interpretar códigos JavaScript em ambiente externo ao navegador.
- JavaScript: Linguagem de programação interpretada estruturada, de script em alto nível com tipagem dinâmica fraca e multiparadigma.
- Electrum: Carteira de Bitcoin
- BlockCypher: Explorador de Blocos, Endereços e Transações em redes crypto.
- Bitcoin Faucet: Provedor de liquides experimental.

## Como Usar

1. Instale o Node.js:

https://nodejs.org/pt


2. Instale o Electrum:

```bash
https://electrum.org/
```

3. Clone este repositório:

```bash
git clone https://github.com/6uilhermeTeixeira/CriandoCarteiraBTC.git
```

4. Rode o gerador de Carteiras:

- Abra o terminal do Node.js
- Caminhe até o repositório na pasta ..\src no caminho ..\CriandoCarteiraBTC\src
- Dentro da pasta ..\src rode o comando
  ```bash
    node createWallet.js
  ```

5. Sincronizar carteira Electrum
- Abrir o Electrum
- Criar nova carteira
- Nomear e selecionar a opção importar carteira existente
- Importar carteira utilizando Chave Privada

6. Solicitar recebimento de bitcoin na testnet
- Acessar
  ```bash
  https://bitcoinfaucet.uo1.net/
  ```
- Inserir endereço da carteira e clicar em 'Enviar testnet Bitcoins'

7. Consultar explorador de blocos

Consultar explorador de blocos de testnet no link abaixo
```bash
https://live.blockcypher.com/btc-testnet/
```

## Carteiras criadas

A seguir informações para consulta das 2 carteiras criadas e utilizadas para transacionar bitcoin durante o curso.

### Carteira 1
-Endereço:  n2uBcaL9JaTYmwYUJLpiALBwBXx4NRhAgY
-Chave privada: cRkp8PhzJz8jR5VbeACGSqjFKaNqdQtN7Qfo844SnkZGniGMdgZQ
-Seed: coffee wife squeeze transfer hen vital hub away school hip rally soda

### Carteira 2
Endereço:  myNvJSB2HNiR8u6N46TivgicoPEVYFQsZ1
Chave privada: cVLneGYr8avaaXu711wuuSku69yue2itB7s6ePRz61PUzybao5Bm
Seed: sun sure normal idea onion cluster submit segment adjust raccoon regret inform   
