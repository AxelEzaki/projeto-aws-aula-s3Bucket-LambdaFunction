# projeto-aws-aula-s3Bucket-LambdaFunction
Projeto AWS com bucket S3 e LambdaFunction, que lê um arquivo CSV e registra usuários presentes no arquivo e armazena em um DynamoDB

# Etapa
Criação de diagrama básico para entender o fluxo
Criação do bucket S3
Criação do arquivo CSV contendo os usuários
Criação do DynamoDB que armazenará dados
Criação do LambdaFunction que lerá, processará e armazenará os dados presentes no arquivo CSV para uma tabela DynamoDB

Informar um arquivo CSV no bucket e testar o LambdaFunction
Verificar logs para ver se houve algum erro, principalmente de permissão
Corrigir erros de permissão
Foi inserido permissão para buckets S3 de leitura e escrita, permissão de escrita para DynamoDB também
Inserir novamente o arquivo CSV

Verificar tabela no DynamoDB para ver se foram inseridos corretamente os usuários
