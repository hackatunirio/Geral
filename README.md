Henrique Andrade:
# Geral
Repositório utilizado pela organização para compartilhar informações com os participantes.


##API UNIRIO

Durante o evento participantes podem utilizar a interface da API UNIRIO para acessar uma réplica do banco de dados da UNIRIO utilizando:

[URL base]
http://sistemas.unirio.br/api_teste

[SERVER api client]
PRODUCTION_DEVELOPMENT

[KEY]
744b3341f5f629a9560992f42b086494d4cb0b7a1b56a77c08240b8be97c7cb7ff3342c7034f5172761239b2943253e3

[Views interessantes]
V_SERVIDORES_DADOS
V_EMW_DISCIPLINAS
V_EMW_CURSOS
V_EMW_DOCENTES
V_ALUNOS_ATIVOS


Quem desenvolver em Python poderá utilizar o cliente disponível em http://pypi.python.org/pypi/unirio-api/1.1.0 .


Exemplo de query que retorna dados de alunos: http://sistemas.unirio.br/api_teste/ALUNOS?API_KEY=744b3341f5f629a9560992f42b086494d4cb0b7a1b56a77c08240b8be97c7cb7ff3342c7034f5172761239b2943253e3&LMIN=100
