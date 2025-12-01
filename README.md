# Concessionária

Projeto voltado para estudo, onde será implementado uma API para revenda de automotores.
Irei criar o projeto utilizando Nestjs, que utiliza TypeScript por padrão e adota uma arquitetura inspirada em padrões de design consolidado.

## Atividade 1 - VENDA DE VEÍCULOS:

Uma empresa de revenda de veículos automotores nos contratou para implantar uma plataforma.
Ficou sob sua responsabilidade criar a API, para que posteriormente o time de frontend integre a solução.

Para testar a solução deverá utilizar um banco de dados local (DynamoDB), para isso sugiro pesquisar sobre aws local stack. Ela simulará um banco de dados, como o de homologação, dessa forma você armazena os dados para poder atualizar em outras consultas.

O desenho da solução envolve as seguintes necessidades do negócio:
- Cadastrar um veículo para venda (Marca, modelo, ano, cor, preço)
- Editar os dados do veículo
- Efetuar a venda de um veículo (Vincular o CPF da pessoa que comprou e data da venda)
- Listagem de veículos à venda, ordenada por preço, do mais barato para o mais caro
- Listagem de veículos vendidos, ordenada por preço, do mais barato para o mais caro.

O time de qualidade de operação definiu que todas as mudanças da solução (implantação ou alteração) sejam feitas usando Pull Requests e devem ter testes unitários com todos os testes passando e com cobertura de testes de pelo menos 80%.

### Temas complementares
Rotas, Controladores, Repositórios e banco de dados. [LINK](https://codewithmatt.hashnode.dev/understanding-the-building-blocks-of-a-web-application-routes-controllers-services-repositories-and-databases)