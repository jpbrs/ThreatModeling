# Armazenamento de dados – o elemento de armazenamento

![](data-store.png)

Representado por linhas paralelas, esse elemento representa os dados armazenados de modo temporário ou permanente.

Exemplos Incluem: 

1. Usando o cache do navegador para armazenar dados relacionados à sessão do usuário
2. Como adicionar um evento de log de segurança a um banco de dados


## Quando usar o elemento de armazenamento de dados

1. Sempre que você estiver armazenando dados em algum lugar, como o BD do Azure ou o cache local
2. Se você estiver estabelecendo a comunicação entre dois armazenamentos de dados, não se esqueça de adicionar um processo entre eles
3. Armazenamentos de dados e entidades externas iniciam o fluxo de dados, por isso verifique se você tem algum deles ativo


## Incluir contexto

| Contexto | Perguntas |
| -------- | --------- |
| Tipo | O sistema usa o SQL do Azure, cookies, locais ou algum outro tipo de armazenamento? Em caso afirmativo, qual? |
| Função | Como o armazenamento é usado? Ele é usado para compartilhar dados, armazenar backups, logs de segurança, credenciais e segredos? |
| Nível de permissão | Como o controle de acesso é implementado? Quem tem permissões de leitura e gravação? |
| Controles adicionais | Os dados são criptografados? E quanto ao disco? São usadas assinaturas digitais? |