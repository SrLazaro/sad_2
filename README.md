2 Atividade SAD - Data Warehouse

Executando o Script convertido em MySql dos dados da atividade:
![image](https://github.com/SrLazaro/sad_2/assets/78516759/2dfe7c77-0807-4370-9f22-ae98d8aeff6c)

Podemos visualizar pelo próprio MySql o relacionamento das tabelas.
![image](https://github.com/SrLazaro/sad_2/assets/78516759/c1bcb34b-cd38-41cb-8309-51dc63d42f17)

É notório que os nomes das colunas e o próprio nome das tabelas deixam o analista confuso. Além disso, muitas tabelas estão sobrecarregadas com dados que não pertence a mesma, devendo ser criada outra no lugar. Dessa forma, precisaremos efetuar o processo de ETL para deixar esse banco mais coeso.

Ao analisar os dados, consegui a chegar nesse digrama. 
![image](https://github.com/SrLazaro/sad_2/assets/78516759/9d0b270e-5efc-402a-a67b-fe31f6bafb6f)
![image](https://github.com/SrLazaro/sad_2/assets/78516759/394ed1ca-435c-400a-90f1-7af343b32857)

Agora, será necesário efetuar o processo de tratamento e inserção dos dados nas tabelas.
![image](https://github.com/SrLazaro/sad_2/assets/78516759/7cce355f-6322-4f2a-9288-2c45aa6a95be)
![image](https://github.com/SrLazaro/sad_2/assets/78516759/e8942ccd-0fe5-4c97-90e2-ad7b3d670332)

