# exampleDAO# Example DAO 🌐

Um dashboard de votação e governança descentralizada (DAO) - exemplo para Aula no Defiverso. 

## 📋 Funcionalidades

- **Conexão com Carteira**: Integração perfeita com MetaMask.
- **Leitura Nativa**: Identificação automática de rede, avisos caso não esteja na rede Sepolia e botão de "Mudar para Sepolia" em 1-clique.
- **Painel de Propostas**:
  - Geração de lista das propostas ativas e encerradas.
  - Estimativa de duração em Blocos e projeção de Tempo (em minutos/horas).
  - Visualização rica em detalhes do resultado das propostas (Barra de Progresso mostrando aprovação, rejeição ou empates).
- **Votação**: Lógica em painel limpo, onde cada usuário pode enviar seu voto on-chain (SIM/NÃO).
- **Cache Local de Votos**: Utiliza cache do browser (localStorage) para evitar refetching agressivo do RPC público na hora de checar se o usuário já votou, evitando problemas comuns de delay da rede Ethereum e melhorando a UX (botão não cintila/reaparece).

## 🛠️ Tecnologias Utilizadas

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Web3**: [Ethers.js (v6)](https://docs.ethers.org/)
- **Blockchain**: Rede Ethereum Sepolia Testnet

## 📝 Como Interagir
1. acesse https://thiegocarvalho.github.io/exampleDAO/
2. Conecte sua Carteira na **Sepolia Testnet**.
3. É necessário ter saldos residuais em **Sepolia ETH** para disparar propostas ou votar. Use o Faucet integrado no DApp caso não tenha!
4. Acesse e crie sua proposta no DApp, passando a quantidade de "blocos" para duração (Em média, 1 bloco = ~12 segundos).

## 📄 Licença

Este projeto é um portal genérico para demonstração e estudo de governança on-chain.
