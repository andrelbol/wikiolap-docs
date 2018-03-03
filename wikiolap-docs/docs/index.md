<center>
#Wikiolap Docs
</center>

---

## O que é?
Wikiolap é uma plataforma Web de análise, compartilhamento e visualização de dados.

## Tecnologias
As tecnologias usadas no desenvolvimento do aplicativo são:

* [Django Framework](https://docs.djangoproject.com/en/2.0/): framework que tem como base a linguagem [Python](https://docs.python.org/3/) para desenvolvimento de aplicações web.
* [MongoDB](https://www.mongodb.com/): Banco de dados NoSQL que utiliza a abordagem orientada a documentos para o armazenamento.
* [Cassandra](http://cassandra.apache.org/): Banco de dados NoSQL que utiliza uma abordagem de família de colunas no armazenamento dos dados.
* [Spark](https://spark.apache.org/): Aplicação de processamento de dados em larga escala, orientado ao processamento em Clusters.

## REST API
O *Representational State Transfer* (REST) é um estilo arquitetural de aplicação que regula como serão acessados os serviços dessa. Um dos focos dessa arquitetura por exemplo é tirar proveito dos métodos existentes nas requisições HTTP, onde uma mesma url pode tanto acessar um dado, quanto modificá-lo ou até removê-lo. Essa estrutura é utilizada no Wikiolap através dos frameworks [Django REST Framework](http://www.django-rest-framework.org/) e [Django REST Framework Mongoengine](http://umutbozkurt.github.io/django-rest-framework-mongoengine/) (adaptação para o banco de dados do Mongo).

Assim, grande parte da aplicação comunica-se através de [requisições](/rest-api/urls) que retornam os dados requisitados ou realizam alguma alteração.



## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
