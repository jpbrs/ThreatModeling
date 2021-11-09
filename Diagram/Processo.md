# Processo - o elemento de tarefa

![](process.png)

Representado por um círculo, esse elemento representa as atividades que podem modificar ou redirecionar a entrada recebida para as saídas apropriadas.

Exemplos Incluem:
1. Um microsserviço que recebe uma solicitação de chamada à API e a encaminha para um serviço de manipulação de API
2. Código que valida a entrada de dados antes de gravá-la em um armazenamento de dados


## Incluir contexto

| Contexto | Perguntas |
| -------- | --------- |
| Código | Esse processo está sendo executado em C#, C++, Objective C, Java ou em uma linguagem de script? |
| Nível de permissão	 | Esse processo precisa de permissões no nível de kernel, local ou administração para ser executado? |
| Isolamento de serviço	 | O processo está sendo executado em uma área restrita? |
| Entrada | Esse processo pode aceitar entrada de todos, de contas locais ou apenas de administradores? |
| Validação | Como o processo analisa, trata e aceita a entrada? |
| Autenticação | O processo depende do Azure Active Directory para autenticação? Se não, o que ele usa? |
| Autorização | Ele depende de ACLs (listas de controle de acesso) para autorização? Se não, o que ele usa? |
