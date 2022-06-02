Logo
ig.News - Next.js
Aplicação para inscrição de newsletter com pagamento via stripe

Sobre o Projeto • Tecnologias • Configurações necessárias • Licença • Autor

Sobre o projeto
O projeto tem como objetivo o estudo e desenvolvimento de uma aplicação em ReactJS com NextJS para listagem de posts e sistema de inscrição(subscription).

A aplicação foi desenvolvida utilizando o framework NextJS aplicando conceitos como consumo de API externas, API Root, Server Side Rendering (SSR), Static Site Generation (SSG), STRIPE para pagamentos das subscriptions, NextAuth para autenticação com Github, FaunaDB para armazenar as informações do usuário em um banco de dados e Prismic CMS para adição e gerenciamento do conteúdo dos posts.

O projeto foi desenvolvido como pratica das aulas do modulo 03 do Ignite da Rocketseat

Tecnologias
Abaixo as tecnologias utilizadas para construção da aplicação

ReactJS
NextJS
TypeScript
SASS
Next-Auth
Stripe
FaunaDB
Prismic CMS
Configurações necessárias
Requisitos
Necessário realizar as instalações:

Git
Yarn
Stripe CLI
Criar conta e configurar os serviços externos:

Stripe
FaunaDB
Prismic CMS
Configurações dos serviços estão localizadas no arquivo servicesConfig.md na raiz do projeto.

Clone do projeto
# Execute o comando git clone para realizar o clone do repositório
$ git clone https://github.com/nelsonsantosaraujo/ignews.git
# Entre na pasta do repositório clonado
$ cd ignews
Iniciando o projeto
# Execute yarn para instalar as dependências
$ yarn

# Na raiz do projeto crie uma copia do arquivo .env.local.example
# Altere o nome da copia para .env.local
# Preencha as variáveis ambiente de acordo com as instruções
$ cp .env.local.example .env.local

# Execute stripe listen para ouvir eventos do webhook
$ stripe listen --forward-to localhost:3000/api/webhooks 

# Para iniciar a aplicação
$ yarn dev
Licença
Distribuído sob a licença MIT. Veja LICENSE para mais informações.

Autor
Feito por Nelson Araújo 👋🏽 Entre em contato!

Linkedin Badge Gmail Badge
