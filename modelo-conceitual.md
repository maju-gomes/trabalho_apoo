# Classes de Análise

- O diagrama apresenta as classes essenciais para o sistema de gerenciamento de materiais recicláveis.

## Empresa
Representa as organizações responsáveis pelo transporte dos materiais recicláveis, sendo identificada por atributos como:
- **CNPJ**
- **Nome**
- **Endereço**
- **ID**

## MaterialReciclavel
Armazena informações relativas aos materiais, incluindo:
- **Identificador**
- **Tipo**
- **Quantidade disponível**

## PontoColeta
Define os locais e horários destinados à coleta dos materiais, contendo:
- **ID**
- **Endereço**
- **Data/Hora da coleta**

## Usuario
Representa os participantes do processo, que podem atuar como:
- **Coletor**
- **Recebedor**  
Conforme definido pelo atributo **tipo**.

## TransicaoReciclavel
Registra as movimentações dos materiais, detalhando:
- **ID**
- **Data/Hora**
- **Tipo de finalização da transação**  
Estabelecendo a conexão entre o **usuário** e o **ponto de coleta**.

---

- Dessa forma, as empresas assumem papel fundamental no transporte dos materiais entre os pontos de coleta e os usuários.
