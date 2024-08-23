Projeto: Criação de Carteira Bitcoin na Rede de Teste
Este projeto foi desenvolvido com o objetivo de aprender a criar uma carteira Bitcoin na rede de teste (testnet) utilizando Node.js. O código implementado gera uma nova carteira, exibindo o endereço público e a chave privada. A rede de teste permite realizar transações sem risco de perda de dinheiro real, sendo ideal para fins de aprendizado e testes.

Pré-requisitos
Para rodar este projeto, você precisa ter o Node.js instalado em sua máquina. Além disso, você precisará das seguintes dependências:

bitcoinjs-lib: Biblioteca para trabalhar com Bitcoin no Node.js.
bitcoinjs-message: Para assinar e verificar mensagens Bitcoin.
axios: Para fazer requisições HTTP, caso você deseje integrar com um serviço de API.
Instalando as Dependências
Para instalar as dependências necessárias, execute:

bash
Copiar código
npm install bitcoinjs-lib bitcoinjs-message axios
Como Executar
O código abaixo gera uma nova carteira Bitcoin na rede de teste (testnet):

Explicação do Código
bitcoinjs-lib: Usado para criar pares de chaves e endereços Bitcoin.
testnet: Indica que estamos usando a rede de teste do Bitcoin.
makeRandom(): Gera uma chave privada aleatória.
p2pkh(): Cria um endereço Pay-to-PubKey-Hash (P2PKH) a partir da chave pública.
toWIF(): Converte a chave privada para o formato WIF (Wallet Import Format), que pode ser usado em outras carteiras.
você verá o endereço Bitcoin e a chave privada no terminal. Esses dados podem ser usados para enviar e receber Bitcoin na rede de teste.

Contribuição
Sinta-se à vontade para contribuir com melhorias ou sugestões para este projeto. Você pode fazer isso através de pull requests ou abrindo issues.

Licença
Este projeto é licenciado sob a licença MIT - veja o arquivo LICENSE para mais detalhes.
