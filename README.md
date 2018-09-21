
# Geral
Repositório utilizado pela organização para compartilhar informações com os participantes.


## API UNIRIO

Durante o evento participantes podem utilizar a interface da API UNIRIO para acessar uma réplica do banco de dados da UNIRIO utilizando:

[URL base]
http://sistemas.unirio.br/api

[SERVER api client]
PRODUCTION

[KEY]
94ebdcee824a8fc9876c4c0b22580540a8d2330da2ec089d2e396afce2ee20332383a2df43936763358021ef9d163a21

[Views interessantes]

* V_ALUNOS_ATIVOS
* V_EMW_DOCENTES
* V_EMW_CURSOS
* V_EMW_DISCIPLINAS
* V_PROJETOS_EXTENSAO
* V_PROJETOS_PESQUISA


Quem desenvolver em Python poderá utilizar o cliente disponível em http://pypi.python.org/pypi/unirio-api/1.1.1 .


Exemplo de query: http://sistemas.unirio.br/api/V_EMW_DOCENTES?API_KEY=94ebdcee824a8fc9876c4c0b22580540a8d2330da2ec089d2e396afce2ee20332383a2df43936763358021ef9d163a21&LMIN=100

## LDAP 

A UNIRIO possui um serviço de diretório de usuários LDAP que pode ser acessado com as seguintes credenciais:

mode = uid  #cpf do usuário

base_dn = ou=people,dc=unirio,dc=br

server = ldap.unirio.br
