# backend-challenge

A proposta desse é desafio é que o candidato demonstre as suas técnicas preferidas.

# o que deve ser feito

- Criar uma api para conversão de moedas.
- Esse serviço deve recuperar as cotações reais de algum provedor disponível na internet.
- Para aumentar a resiliência esse serviço deve implementar um sistema de fallback para os provedores de cotação. Caso o provedor principal esteja indisponível por algum problema técnico o serviço deve conseguir requisitar a cotação de um segundo provedor, se o segundo provedor estiver indisponível, então o serviço deve falhar.
- Esse serviço ainda deve guardar o cache da cotação por 30 segundos.
- O serviço deve suportar BTC, ETH, USD, BRL e EUR.

# o que iremos avaliar

- Testes automatizados.
- Utilização de padrões como Injeção de Dependência e Design Pattern (Strategy, Chain of Responsability, etc...).
- Organização e legibilidade do código.
