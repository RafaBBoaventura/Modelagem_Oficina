# Modelagem_Oficina
Desafio de criação de uma modelagem do zero a partir da narrativa disponibilizada na formação SQL Database Specialist da DIO

*Objetivo:*
Criar o esquema conceitual do zero para o contexto de oficina com base na narrativa fornecida

*Narrativa:*
* Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica
* Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões periódicas
* Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.
* A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra
* O valor de cada peça também irá compor a OS
* O cliente autoriza a execução dos serviços
* A mesma equipe avalia e executa os serviços
* Os mecânicos possuem código, nome, endereço e especialidade
* Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.

Com base na narrativa acima, criei a seguinte modelagem utilizando a ferramenta MySQL Workbench

![Modelo Oficina](https://github.com/RafaBBoaventura/Modelagem_Oficina/assets/131798428/236206b0-41fd-45e7-a979-cc5a99cf20b0)
