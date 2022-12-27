# Projeto 26/12/2022 Redes de Computadores

## Questão:
29.45.32.0/24 para endereçar três departamentos com VLSM, conforme a seguir:

- Departamento Financeiro com 55 hosts
- Departamento Comercial com 62 hosts
- Departamento Contábil com 20 hosts

Etapa 1: Responda
a) Quantos bits serão necessários para fazer a divisão
e obter pelo menos 3 subredes?

b) Quantos endereços de hosts válidos estarão
disponíveis em cada subrede?

c) Quais as novas máscaras de subrede de cada subrede?

d) Listar a faixa de endereços de cada subrede.

Etapa 2: Simule
a) Utilizando o Cisco Packet Tracer, configure o cenário encontrado na etapa 1.
b) Para cada departamento configure dois clientes: o primeiro host e o último host
c) Realize os testes de comunicação: i) entre as máquinas do mesmo departamento (mesma subrede) e ii) entre máquinas de departamentos diferentes (subredes diferentes). O que aconteceu?

### Resumo sobre VLSM:

Atividade para praticar o VLSM(Variable Length Subnet Mask):
    O VLSM é basicamente alocação de hots dinamicamente envés de estaticamente, exemplo:
Para dividir uma rede de 3 sub-redes com 30 hots cada, usariámos um SALTO de 32 para cada sub-rede, já pelo VLSM não seria necessário o SALTO de 32 para cada, e sim de acordo com a demanda de hots para cada sub-rede.

### Desenvolvimento lógico do projeto:
Seguindo a lógica do seguinte site:
https://www.geeksforgeeks.org/introduction-of-variable-length-subnet-mask-vlsm/