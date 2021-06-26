# controle-series
Parte 1 do projeto desenvolvido para estudo sobre a Linguagem Laravel.
A aplicação para controle de séries foi feita da seguinte maneira:

    - Preparando o ambiente:
    - instalação do php;
    - instalação do Composer:
        O que é Composer?
            - Composer é uma ferramenta da linha de comando do PHP que traz algumas facilidades, dentre elas gerenciar dependências ou seja,
            criar um projeto, baixar uma dependência para um projeto já existente, entre outras.
    
    - Rotas;
    - Artisan; 
        Que é uma ferramenta da linha de comando do Laravel que nos da algumas facilidades, algumas ferramentas, como por exemplo subir um servidor.
    - Model:
      A parte de modelo/domínio ("Model") da nossa aplicação envolve tudo que envolver regras, como serviços, classes que buscam dados em bancos ou repositórios, etc. Esses arquivos deverão ser organizados em pastas separadas, da maneira que definirmos (ainda que com base em alguns padrões). Por convenção, no Laravel, os arquivos que acessam o banco de dados ficam na raiz da pasta "app".
    - View:
        É a parte do código responsável por apresentar os dados aos usuários finais.
    - Controller:
        Nesse padrão, o navegador faz uma requisição para o servidor Web, e a aplicação faz com que um arquivo de rotas seja lido. A partir dele, verificamos qual URL foi chamada, e a requisição é enviada para um Controller. A partir das informações da requisição, o Controller acessa a lógica de negócios (que pode acessar um banco de dados, como o MySQL), e devolve ao Controller os dados necessários. O Controller chama um arquivo de visualização que é montado com base nesses dados, e devolve para o servidor Web, que o exibe para o navegador.
    - Blade: 
        O blade utiliza o conceito de seções. Sendo assim, se pode definir o que entrará em cada página.
    - Migrations:
        As migrations são uma forma de escrever código (php) e passar as informações para o banco.
    - Eloquent ORM: 
        O Eloquent é uma ferramenta de ORM (Object Relational Mapping), ou seja, de mapeamento de um modelo orientado a objetos para um modelo relacional do banco de dados.
    De forma mais simples: um ORM pega o que temos orientado a objetos e manda de volta ao banco de dados de forma relacional (em forma de querys), e busca no banco de dados (pelas queries) e nos traz em forma de objetos.
