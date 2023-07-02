# Hospital-fundamental
Atividade de banco de dados que visa ensinar o banco de dados conceitual:

Analise a seguinte descrição e extraia dela os requisitos para o banco de dados: O hospital necessita de um sistema para sua área clínica que ajude a controlar as consultas realizadas. Os médicos podem ser generalistas, especialistas ou residentes e têm seus dados pessoais cadastrados em planilhas digitais. Cada médico pode ter uma ou mais especialidades, que podem ser pediatria, clínica geral, gastroenterologia e dermatologia. Alguns registros antigos ainda estão em formato de papel, mas serão necessários incluir esses dados no novo sistema.

Os pacientes também precisam de cadastro, contendo dados pessoais (nome, data de nascimento, endereço, telefone e e-mail), documentos (CPF e RG) e convênio. Para cada convênio, são registrados nome, CNPJ e tempo de carência.

As consultas também foram registradas em planilhas, com data e hora de realização, médico responsável, paciente, valor da consulta ou nome do convênio, com o número da carteira. Também é necessário indicar na consulta qual a especialidade buscada pelo paciente.

Deseja-se ainda informar a receita do médico, de maneira que, no encerramento da consulta, ele possa registrar os medicamentos receitados, a quantidade e as instruções de uso. A partir disso, espere-se que o sistema imprima um relatório da receita ao paciente ou permita sua visualização via internet.

imagem

Parte 2: Os Segredos do Hospital
Para cada internação, são anotados a dados de entrada, a dados previstos de alta e dados efetivos de alta, além da descrição textual dos procedimentos a serem realizados.

As internações precisam ser vinculadas a quartos, com a numeração e o tipo.

Cada tipo de quarto tem sua descrição e seu valor diário (a princípio, o hospital trabalha com apartamentos, quartos duplos e enfermaria).

Também é necessário controlar quais profissionais de enfermaria serão responsáveis ​​por acompanhar o paciente durante sua internação. Para cada enfermeiro(a), é necessário nome, CPF e registro no conselho de enfermagem (CRE).

A internação, obviamente, é vinculada a um paciente – que pode se internar mais de uma vez no hospital – e um único médico responsável.

imagem

Parte 3
Abastecer o banco com informações fictícias.

Carga
imagem

Consultas
imagem

convenção
imagem

Endereço
imagem

Enfermeiro
imagem

Especialidade
imagem

Internação
imagem

Médico
imagem

paciente
imagem

quarto
imagem

receita
imagem

Parte 4
A Ordem do Change. Hummm... Não... Não acabou... Um banco de dados pode sofrer alterações ao longo da sua concepção e do seu desenvolvimento. Nesse momento devemos nos preparar para atualizar nossas estratégias. Mãos a Obra. Pensando no banco que já foi criado para o Projeto do Hospital, realize algumas alterações nas tabelas e nos dados usando comandos de atualização e exclusão: Crie um script que adicione uma coluna “em_atividade” para os médicos, indicando se ele ainda está no hospital ou não. Crie um script para atualizar ao menos dois médicos como inativos e os demais em atividade.

imagem

Parte 5
Todos os dados e o valor médio das consultas do ano de 2020 e das que foram feitas sob convênio.
imagem

Todos os dados das internações que tiveram data de alta maior que a data prevista para a alta.
imagem

3.Receituário completo da primeira consulta marca registrada com destinatário associado.

imagem

Todos os dados da consulta de maior valor e também da de menor valor (ambas as consultas não foram realizadas sob convênio).
imagem

Dados e número de quartos de internações em quartos do tipo “apartamento”.
imagem

Nome do paciente, data da consulta e especialidade de todas as consultas em que os pacientes eram maiores de 18 anos na data da consulta.
