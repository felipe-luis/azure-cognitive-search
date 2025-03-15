# Azure Cognitive Search: Utilizando AI Search para indexação e consulta de Dados

* Como configurar uma Pesquisa
    * Primero devemos criar o azure AI services
    * Devemos criar criar também o serviço AI Search
    * Por último criamos uma conta de Armazenamento (Storage Account)

1- No storage account, criamos um novo container e após isso, fazemos o upload dos arquivos que serão analisados, no caso, os arquivos de review do usuários.

2- Em seguida, vamos ao mecanismo de busca, selecionamos a opção de importar dados e selecionamos aonde estão os dados cognitivos, ou seja, meus arquivos de review.

3- Após fazer essa vinculação, podemos entrar no Search explorer, em AI Search, e fazer consultas.

4- Podemos passar alguns parametros para realizar a busca, como 'location'(localização), 'sentiment'(sentimento), 'names'(nomes)

## Resumo
* A estratégia nesse caso é, criar um serviço de IA, fazer um link com essa automação e a partir disso, direcionar isso para um repositório.
* Essas ferramentas podem trazer resultados de uma forma rápida e precisa, permitindo que façamos uma mineração de conhecimento em um grande volume de dados.
