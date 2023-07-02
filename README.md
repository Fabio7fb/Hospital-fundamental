# Hospital-fundamental
Atividade de banco de dados que visa ensinar o banco de dados conceitual:

Analise a seguinte descrição e extraia dela os requisitos para o banco de dados: O hospital necessita de um sistema para sua área clínica que ajude a controlar as consultas realizadas. Os médicos podem ser generalistas, especialistas ou residentes e têm seus dados pessoais cadastrados em planilhas digitais. Cada médico pode ter uma ou mais especialidades, que podem ser pediatria, clínica geral, gastroenterologia e dermatologia. Alguns registros antigos ainda estão em formato de papel, mas serão necessários incluir esses dados no novo sistema.

Os pacientes também precisam de cadastro, contendo dados pessoais (nome, data de nascimento, endereço, telefone e e-mail), documentos (CPF e RG) e convênio. Para cada convênio, são registrados nome, CNPJ e tempo de carência.

As consultas também foram registradas em planilhas, com data e hora de realização, médico responsável, paciente, valor da consulta ou nome do convênio, com o número da carteira. Também é necessário indicar na consulta qual a especialidade buscada pelo paciente.

Deseja-se ainda informar a receita do médico, de maneira que, no encerramento da consulta, ele possa registrar os medicamentos receitados, a quantidade e as instruções de uso. A partir disso, espere-se que o sistema imprima um relatório da receita ao paciente ou permita sua visualização via internet.

![Hospital 1](https://github.com/Fabio7fb/Hospital-fundamental/assets/125493191/1d3aa548-788b-4f85-8018-40f3139b206f)


Parte 2: Os Segredos do Hospital
Para cada internação, são anotados a dados de entrada, a dados previstos de alta e dados efetivos de alta, além da descrição textual dos procedimentos a serem realizados.

As internações precisam ser vinculadas a quartos, com a numeração e o tipo.

Cada tipo de quarto tem sua descrição e seu valor diário (a princípio, o hospital trabalha com apartamentos, quartos duplos e enfermaria).

Também é necessário controlar quais profissionais de enfermaria serão responsáveis ​​por acompanhar o paciente durante sua internação. Para cada enfermeiro(a), é necessário nome, CPF e registro no conselho de enfermagem (CRE).

A internação, obviamente, é vinculada a um paciente – que pode se internar mais de uma vez no hospital – e um único médico responsável.

![Hospital 2](https://github.com/Fabio7fb/Hospital-fundamental/assets/125493191/208cf514-f169-4d95-85b9-e64c5f78ece4)


Parte 3
Abastecer o banco com informações fictícias.

Carga
![Hospital 3](https://github.com/Fabio7fb/Hospital-fundamental/assets/125493191/09a23a0f-924a-4b0f-88a1-93336e289f96)


Consultas
![Consultas](https://github.com/Fabio7fb/Hospital-fundamental/assets/125493191/68e0b3d5-4a84-4e54-a71e-fafc4f1cbee3)


convenção
![Conveção](https://github.com/Fabio7fb/Hospital-fundamental/assets/125493191/f8c2963a-9330-4f6e-80fb-5a835b765f6a)


Endereço
![endereço](https://github.com/Fabio7fb/Hospital-fundamental/assets/125493191/0d6ebd12-f996-4359-9711-520d2bffcd9f)


Enfermeiro
![208771929-8f35a5e1-3ed9-41b2-9730-ad5fee78ccac](https://github.com/Fabio7fb/Hospital-fundamental/assets/125493191/89b371d4-83a0-41fd-b99b-cd047ab1a74c)


Especialidade
![208771945-9c749dd5-9e3f-4b5e-a693-12bd09673b85](https://github.com/Fabio7fb/Hospital-fundamental/assets/125493191/62186efc-5bce-4f90-b181-997cb24011e2)


Internação
![208771964-bd7e96a6-0b80-4609-9d06-2936aaa1eeb7](https://github.com/Fabio7fb/Hospital-fundamental/assets/125493191/bf6cd2e4-050d-47ba-aeed-0b096e4ca4fc)


Médico
![208771994-21cac6ff-78d8-4f59-8bed-f5568b3741af](https://github.com/Fabio7fb/Hospital-fundamental/assets/125493191/bc665bb4-7bc7-4036-9901-bf6a0da22b8e)


paciente
![208772023-456af260-7a16-4b80-8ac1-b5df31664a57](https://github.com/Fabio7fb/Hospital-fundamental/assets/125493191/2ce0ff60-9ef9-4853-ba02-d90fed7404a1)


quarto
![208772046-27a3374b-e3cd-4f8a-a7b1-f9560b030344](https://github.com/Fabio7fb/Hospital-fundamental/assets/125493191/4ceccd68-0505-402e-99a5-384460e70e48)


receita
![208772083-e4421b5f-9825-4ff7-bf10-177077039f97](https://github.com/Fabio7fb/Hospital-fundamental/assets/125493191/d5b878a1-e3fc-431a-84c0-5497e7b42e7d)


Parte 4
A Ordem do Change. Hummm... Não... Não acabou... Um banco de dados pode sofrer alterações ao longo da sua concepção e do seu desenvolvimento. Nesse momento devemos nos preparar para atualizar nossas estratégias. Mãos a Obra. Pensando no banco que já foi criado para o Projeto do Hospital, realize algumas alterações nas tabelas e nos dados usando comandos de atualização e exclusão: Crie um script que adicione uma coluna “em_atividade” para os médicos, indicando se ele ainda está no hospital ou não. Crie um script para atualizar ao menos dois médicos como inativos e os demais em atividade.

![209404044-5d67e376-b96d-4025-8c77-c78922e95557](https://github.com/Fabio7fb/Hospital-fundamental/assets/125493191/b30218fc-2b8b-40a2-88e6-88d10d0a5193)


Parte 5
Todos os dados e o valor médio das consultas do ano de 2020 e das que foram feitas sob convênio.
![209850099-12a6634f-5096-44de-b14a-608eabdb158d](https://github.com/Fabio7fb/Hospital-fundamental/assets/125493191/bfcaa956-620f-4fa4-91ad-313edd7f4dd8)


Todos os dados das internações que tiveram data de alta maior que a data prevista para a alta.
![209850147-91ca142c-3986-457b-b6d8-cecbec5e1ac2](https://github.com/Fabio7fb/Hospital-fundamental/assets/125493191/0b016509-2f93-4404-a251-51e300c51575)


3.Receituário completo da primeira consulta marca registrada com destinatário associado.

![209851130-412c44ca-1711-4eba-b909-1cbb4af5bdad](https://github.com/Fabio7fb/Hospital-fundamental/assets/125493191/925507b4-8ab5-428f-98c5-e8485a6d7e02)


4.Todos os dados da consulta de maior valor e também da de menor valor (ambas as consultas não foram realizadas sob convênio).
![209852728-150cabbb-e883-4a25-a7a8-ea568140b553](https://github.com/Fabio7fb/Hospital-fundamental/assets/125493191/da85acbd-7e04-4c90-b46a-a5330234f7d2)


Dados e número de quartos de internações em quartos do tipo “apartamento”.
![209861890-9450fd31-1662-4773-ac69-51709488179d](https://github.com/Fabio7fb/Hospital-fundamental/assets/125493191/09a57e97-4919-4a94-85ae-7202a027dbf6)


6.Nome do paciente, data da consulta e especialidade de todas as consultas em que os pacientes eram maiores de 18 anos na data da consulta.
