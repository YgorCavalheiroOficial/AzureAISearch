# AzureAISearch
Utilizando AI Search para indexação e consulta de Dados - Bootcamp DIO

## Laboratório AI Search

* Para realizar esse laboratório foi necessário realizar a criação de um recurso para o AI Search, Azure AI Services e um Storage Account.
* Após se fez necessário habilitar a permissão do acesso anônimo ao Blob nas configurações no Storage Account como podemos perceber na imagem abaixo, essa "quebra" de segurança do storage foi apenas um detalhe para que as chances de ocorrer algum erro sejam poucas, já que é apenas um laboratório para estudo, sendo assim não será prejudicial ao sistema.
    
  ![Screenshot_1](https://github.com/YgorCavalheiroOficial/AI_Vision_MA/assets/157850301/9ff26c1d-8540-4b43-9e85-42302488462d)

* Em seguida foi realizado a criação de um container dentro do Storage Account.

  ![Screenshot_2](https://github.com/YgorCavalheiroOficial/AI_Vision_MA/assets/157850301/47ca14fc-5091-476b-a2b6-2c980c82f219)

* Seguindo o processo, foi necessário baixar um arquivo .zip com as informações de base para realizar o upload no container.

  ![Screenshot_3](https://github.com/YgorCavalheiroOficial/AI_Vision_MA/assets/157850301/c9fad765-eb5c-4514-b969-2b0bdbaf4834)

  ![Screenshot_4](https://github.com/YgorCavalheiroOficial/AI_Vision_MA/assets/157850301/d93ff3df-11af-4262-baf9-bc9eb249f144)
  
  ![Screenshot_5](https://github.com/YgorCavalheiroOficial/AI_Vision_MA/assets/157850301/579a23c1-db97-4ab3-ad51-f6a5d26dd546)

* Após ter realizado a criação de mecanismo de busca, um recurso de IA e um Storage Account com conteúdo, me direcionei até o AI Search e importei os dados.

  ![Screenshot_6](https://github.com/YgorCavalheiroOficial/AI_Vision_MA/assets/157850301/318ed6e4-b541-4297-a55c-62b3bb826e8f)

* Em seguida realizei as seguintes configurações.
  
  ![Screenshot_7](https://github.com/YgorCavalheiroOficial/AI_Vision_MA/assets/157850301/f6459079-50e0-4fa7-82d4-35a47aa1c8bc)
  
  ![Screenshot_8](https://github.com/YgorCavalheiroOficial/AI_Vision_MA/assets/157850301/f7c83ad3-3367-4e43-90e9-2547d73615b2)

  ![Screenshot_9](https://github.com/YgorCavalheiroOficial/AI_Vision_MA/assets/157850301/0bd9319b-be18-402a-801f-af07bccd13f5)

  ![Screenshot_10](https://github.com/YgorCavalheiroOficial/AI_Vision_MA/assets/157850301/359a2b58-f6bb-4842-b3ca-2dc84cb8c1ef)

  ![Screenshot_11](https://github.com/YgorCavalheiroOficial/AI_Vision_MA/assets/157850301/b44f342b-78a7-470a-9b32-250205baa014)

* Retornei para a página principal do AI Search, acessei os indexadores e atualizei até ter êxito.
  
  ![Screenshot_12](https://github.com/YgorCavalheiroOficial/AI_Vision_MA/assets/157850301/379b1d1d-cd08-4475-a470-9acff23074f4)
  
  ![Screenshot_13](https://github.com/YgorCavalheiroOficial/AI_Vision_MA/assets/157850301/33582f82-99e9-44aa-8f3e-12d1fcad3a84)

* Em seguida fui no gerenciador de pesquisa do AI Search e realizei algumas buscas.

  ![Screenshot_14](https://github.com/YgorCavalheiroOficial/AI_Vision_MA/assets/157850301/e87db9c6-765f-4fe2-a193-924a71fac3d7)

  ![Screenshot_15](https://github.com/YgorCavalheiroOficial/AI_Vision_MA/assets/157850301/f79b1cba-d18d-40cc-a5ae-ccd43fd1c5d0)
  - Pesquisa retorna todos os documentos no índice de pesquisa.

  ![Screenshot_16](https://github.com/YgorCavalheiroOficial/AI_Vision_MA/assets/157850301/3bf4dcb5-3845-4396-82aa-228453a9ce3f)
  - A consulta pesquisa todos os documentos no índice e filtra revisões com localização em Chicago.

  ![Screenshot_17](https://github.com/YgorCavalheiroOficial/AI_Vision_MA/assets/157850301/158db1e4-c650-4a21-85ea-e7473481e720)
  - A consulta pesquisa todos os documentos no índice e filtra revisões com sentimento negativo.

