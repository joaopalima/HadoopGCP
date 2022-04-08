# HadoopGCP
Criando um Ecossistema Hadoop com Google Cloud Dataproc Bootcamp Cognizant Cloud Data Engineer #2

____________________________________________________________________

Desafio GCP Dataproc
O desafio faz parte do curso na plataforma da Digital Innovation One:

Criando um ecossistema Hadoop totalmente gerenciado com Google Cloud Platform

O desafio consiste em efetuar um processamento de dados utilizando o produto Dataproc do GCP. Esse processamento irá efetuar a contagem das palavras de um livro e informar quantas vezes cada palavra aparece no mesmo.

____________________________________________________________________

Etapas do Desafio
1- Criar um bucket no Cloud Storage

2- Atualizar o arquivo contador.py com o nome do Bucket criado nas linhas que contém {SEU_BUCKET}.

3- Fazer o upload dos arquivos contador.py e livro.txt para o bucket criado (instruções abaixo)

  https://cloud.google.com/storage/docs/uploading-objects
  
4- Utilizar o código em um cluster Dataproc, executando um Job do tipo PySpark chamando gs://{SEU_BUCKET}/contador.py

5- O Job irá gerar uma pasta no bucket chamada resultado. Dentro dessa pasta o arquivo part-00000 irá conter a lista de palavras e quantas vezes ela é repetida em todo o livro.

____________________________________________________________________

Entrega do Resultado
1- Criar um repositório no GitHub.

2- Criar um arquivo chamado resultado.txt. Dentro desse arquivo, colocar as 10 palavras que mais são usadas no livro, de acordo com o resultado do Job.

3- Inserir os arquivo resultado.txt e part-00000 no repositório e informar na plataforma da Digital Innovation One.
