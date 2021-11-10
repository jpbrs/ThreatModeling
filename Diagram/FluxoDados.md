# Fluxo de dados – o elemento de dados em trânsito

![](data-flow.png)

A movimentação de dados entre elementos é representada por setas direcionais para indicar a comunicação entre a fonte de dados e o destino.

Exemplos incluem : 

1. Credenciais enviadas por um usuário para acessar um serviço
2. Solicitação de um processo para adicionar uma entrada ao armazenamento de dados

## Incluir contexto

| Contexto | Perguntas |
| -------- | --------- |
| Descrição | O fluxo de dados está passando um token de sessão, uma cadeia de caracteres SQL ou credenciais de usuário? Se não, o que está passando? |
| Protocolo | O fluxo usa HTTPS ou SOAP? Se não, o que ele usa? |
| Sequência de fluxo | O fluxo de dados é enumerado para tornar mais fácil seguir a sequência de fluxo? |
| Tipo | Que tipo de dados está no fluxo de dados? Cookies? XML? Payload SOAP? Payload REST? Payload JSON? |
| Controles adicionais | O fluxo de dados tem proteção contra falsificação habilitada? Outros sinalizadores de segurança habilitados? |
| Autenticação | O processo depende do Azure Active Directory para autenticação? Se não, o que ele usa? |
| Autorização | Ele depende de ACLs (listas de controle de acesso) para autorização? Se não, o que ele usa? |