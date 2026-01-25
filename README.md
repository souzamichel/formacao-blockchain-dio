# Formação Blockchain DIO
Repositório contendo os desafios de projeto da formação

# Módulo 1 - Criando e Utilizando a Sua Carteira de Criptomoedas

## Arquivo(s)
- formacao-blockchain-dio/Modulo 01 Fundamentos da Blockchain/Curso 01 Introducao a Blockchain/Criando e utilizando a sua carteira de criptomoedas/src

## Passos

- 1 - Instalar Node JS - Link Windows : https://nodejs.org/en/download
- 2 - Criar pasta para o projeto - Use o vscode para facilitar
- 3 - Abrir o terminal - No Windows, pode ser o Prompt de Comando(cmd.exe, exemplo: c:\btcwallet)
- 4 - Verifique a versão no Node - Comando: node -v
- 5 - Verifique a versao do NPM - Comando: npmv -v
- 6 - Na pasta criada, execute "npm init -y"
- 7 - Instale os pacotes com o seguinte comando: "npm install bip39 bip32@2.0.6 bitcoinjs --save"
- 8 - Criar/Editar o arquivo createWallet.js - Pode usar qualquer editor de texto
- 9 - Executar o script: "node createWallet.js"
- 10 - Guarde as informações apresentadas para importação no Electrum.
- 11 - Faça o download e instalação do Electrum: https://electrum.org/#download
- 12 - Siga os passos para instalação, criando uma wallet nova, do tipo padrão.
- 13 - Faça uma verificação da sua carteira em Blockchain.com ou blockexplorer.one - Lembre-se se que estamos usando uma testnet
- 14 - Pesquise no Google: bitcoin faucet testnet
- 15 - Encontre e clique no site: bitcoinfaucet.u01.net ou coinfaucet.eu/btc-testnet
- 16 - Envie faucets para a sua carteira
- 17 - Ative a testnet no Electrum ( você pode executar o electrum no modo TestNet nas versões mais atuais , é criado um atalho para TestNet após a instalação )
- 18 - Execute o Electrum no modo TestNet
- 19 - Crie nova carteira, e importe a chave privada da TestNet
- 20 - Já poderá ser vista a operação com bitcoin faucet
- 21 - Agora, crie uma outra carteira na TestNEt com o script nodejs
- 22 - Pelo Electrum, use essa nova carteira criada para enviar bitcoins e analise a operação pelos sites ou então pelo Electrum
- 23 - Feita a primeira operação com bitcoin!

- # Módulo 3 - Criando a Sua Primeira Criptomoeda da Rede Ethereum

## Passos

- 1 - conectar-se ao remix - conectei através da minha conta github
- 2 - instalar metamask no navegador
- 3 - criar uma conta metamask
- 4 - instalar o ganache
- 5 - abrir e criar um workspace no ganache
- 6 - no metamask, adicionar a rede do ganache
- 7 - adicionar uma ou duas contas do ganache no metamask (add wallet -> importar)
- 8 - (opcional) testar o envio de DIO entre as duas contas para testar o funcionamento da metamask
- 9 - adicionar as carteiras do metamask no remix(improved provider - metamast, aba Deploy & run transactions)
- 10 - codificar o contrato conforme padrão ERC20
- 11 - compile o código (mude a configuração de opcode=200 nas configurações avançadas do compilador do remix)
- 12 - faça o deploy do contrato, aceite no metamask, e observe o log de transações do ganache 
- 13 - usar a seção Deployed Contracts da aba Deploy & run transactions para interagir com o contrato novo
- 14 - faça transações entre as contas do ganache que serão usadas
- 15 - operações permitidas: totalSupply, symbol, name, decimals, balanceOf, allowance, transferFrom, transfer e approve.
