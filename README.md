# Modelagem de software utilizando UML
#### Trabalho proposto pela UTFPR  - pos graduacao - Java

* Diagrama de caso de uso
* Diagrama de sequencia
* Diagrama de classes

#### SOFTWARE COM 3 CAMADAS 

#####
O Dr. Brow é proprietário de uma clínica médica que atende pacientes na área cardiovascular.
Atualmente, a referida clínica conta com o trabalho permanente de 5 médicos.
É importante salientar que existem vagas para mais 2 profissionais.
Brow contratou os alunos de pós-graduação para projetar a arquitetura do software de gestão de clínica médica.
Durante a atividade de levantamento de requisitos o médico enumerou as seguintes situações


######
* É necessário armazenar os dados pessoais dos pacientes que são atendidos na clínica. 

* No software de gestão de clínica médica será projetado um relatório de pacientes agrupados por cidades.

* Pressão arterial, peso, altura de um paciente caracterizam-se como dados importantes e devem ser armazenados no banco.

* As informações geradas em uma consulta também devem ser armazenadas. Data da consulta, hora, o paciente a ser consultado,
 o médico que consultou o paciente, se o paciente possui convênio médico, os exames solicitados pelo médico durante a consulta 
 e a medicação prescrita são informações importantes que devem ser armazenadas.
 
* O software de gestão de clínica médica irá emitir um relatório para o paciente com as informações geradas na consulta. Esse relatório possui os seguintes campos: Nome do paciente, nome do médico, especialidade do médico, data da consulta, hora, o convênio do paciente, exames solicitados, os laboratórios habilitados a realizar os exames (é importante armazenar os dados dos laboratórios), as restrições alimentares/físicas para a realização do exame.

* A Clínica de Brow é conveniada com várias cooperativas médicas, é importante saber quais os médicos conveniados no momento do agendamento de uma consulta.

* Por fim, é importante salientar que a clínica situa-se em uma cidade de 150.000 habitantes e é referência em atendimentos cardiovascular. Pessoas das cidades periféricas usufruem da qualidade da referida clínica. Essa prerrogativa deve ser contemplada na arquitetura.
