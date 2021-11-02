# Grupo 8 - StrongBerry
Vídeo propaganda:

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/j-bdUnaeUbI/0.jpg)](https://www.youtube.com/watch?v=j-bdUnaeUbI)

## O Projeto

O projeto trata-se de um veículo pulverizador para agricultores familiares e lavouras comunitárias.

Agricultura de precisão diz respeito à aplicação de tecnologias de agricultura digital (imagens, sensores, hardwares, softwares, etc ) para melhorar o manejo de culturas, aperfeiçoar o uso de insumos, reduzir custos e aumentar a produtividade da lavoura. No entanto, devido ao alto custo financeiro, esse tipo de maquinário e tecnologia se restringem a grandes lavouras, não sendo utilizados por produtores de pequeno porte que desejam expandir e otimizar a produção em suas lavouras. Sendo assim, este projeto tem por objetivo construir um veículo pulverizador de fertilizantes e pesticidas líquidos para lavouras de hortaliças.

O pequeno veículo elétrico será guiado por entre as fileiras de lavoura, identificando, por meio de sensores, a existência de uma planta e pulverizando quantidades exatas de insumo agrícola. Contará com um sistema de software que contabilizará e armazenará informações relacionadas ao produto utilizado, quantidades de pulverizações e datas de utilização; o sistema poderá enviar essas informações ao agrônomo responsável pela seleção de insumos/ dosagens, bem como permitirá ao produtor uma fácil interface de dados para planejar reposição de estoques e comparar resultados na produtividade da lavoura.


## Repositórios

O projeto utiliza de diversos repositórios nessa organização. Sendo eles:

- [Frontend](https://github.com/PI2-Grupo-8/frontend) - Frontend web da aplicação, desenvolvido em React JS.
- [Sensors Data API](https://github.com/PI2-Grupo-8/sensors-data-api) - Microsserviço de dados dos sensores e alertas do veículo, desenvolvido em Node JS.
- [Vehicle API](https://github.com/PI2-Grupo-8/vehicle-api) - Microsserviço de veículos, desenvolvido em Node JS.
- [User API](https://github.com/PI2-Grupo-8/user-api) - Microsserviço de usuário e autenticação do sistema, desenvolvido em Node JS.
- [Sistema Embarcado](https://github.com/PI2-Grupo-8/sistema-embarcado) - Sistema embarcado no veículo, desenvolvido em C.

## Divisão das atividades do projeto

**Estrutura:**
- Projeto da estrutura e movimentação do veículo;
- Seleção de materiais adequados;
- Alocação/acomodação física entre os sistemas eletrônicos e de energia.

**Eletrônica:**
- Levantamento dos sensores e projeto do circuito do pulverizador;
- Seleção e dimensionamento de dispositivos para movimentação do veículo por entre as fileiras;
- Integração entre os sistemas de software e de energia.

**Energia:**
- Projeto da alimentação do veículo;
- Dimensionamento de bateria (desacoplável para carga ou carregada via painel fotovoltaico);
- Integração com sistema eletrônico.

**Software:**
- Projeto do sistema de coleta, armazenamento e envio de dados referentes ao produto e sua aplicação;
- Criação da interface acessível para agrônomo e produtor;
- Integração com o sistema eletrônico.
