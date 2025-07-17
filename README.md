MAPA – Modelagem de Software: Diagrama de Interação para Sistema de PIX Bancário

Autor: Michael Ewerton Oliveira Disciplina: Modelagem de Software Instituição: UniCesumar

Sobre o Projeto

Nesta atividade prática, foi solicitado o desenvolvimento de um Diagrama de Interação (Sequência) representando o fluxo de comunicação entre os objetos envolvidos em uma transferência via PIX entre instituições bancárias distintas, com base no processo definido pelo Banco Central do Brasil.

A modelagem apresenta uma visão clara e cronológica das mensagens trocadas entre os elementos do sistema — desde o cliente iniciando o processo no aplicativo até o envio dos dados ao BACEN e à instituição bancária de destino.

Objetos Modelados no Diagrama

Usuário/Cliente

Banco de Origem

Módulo PIX

BACEN (Banco Central do Brasil)

Banco de Destino

Principais Interações

Cliente acessa o aplicativo e realiza autenticação

Conexão com o módulo PIX e cadastro de chave

Escolha entre chave existente ou nova

Início do processo de pagamento

Envio de dados da transação ao BACEN

Aprovação da transação

Reserva do valor pelo banco de origem

Confirmação de envio do PIX

Diferenciação de Fluxo

Transações internas (entre contas do mesmo banco) são informadas ao BACEN em lote semanal

Transações externas (entre bancos diferentes) requerem validação individual imediata

Resultado da Avaliação

Nota máxima e elogio do professor pela clareza no diagrama e domínio dos elementos de modelagem. Orientação concluída com sucesso segundo os objetivos da disciplina.
