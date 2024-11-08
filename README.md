# Desafio Frontend - Autenticação e DataTable com Next.js

## Objetivo

Este desafio simula a criação de uma aplicação completa com autenticação, conexão a um banco de dados para gerenciamento de sessão juntamente com o **NextAuth** e exibição de dados obtidos de uma API pública. O desafio ajuda a desenvolver habilidades reais necessárias para um desenvolvedor frontend.

## Instruções

### Configuração do Projeto
- Utilize **Next.js** como framework (TypeScript é opcional, mas será um diferencial).
- Configure **NextAuth** para autenticação.
- Conecte o projeto a um banco de dados **MongoDB** para gerenciar os dados do usuário e sessão.

### Autenticação
- O sistema de login e logout deve ser simples e seguro.
- Permita que o usuário acesse uma página protegida apenas quando estiver autenticado, utilizando middleware nativo do Next.js.

### Página Protegida
- Ao fazer login, o usuário terá acesso a uma página onde os dados de uma API pública serão exibidos.
- Utilize uma API pública que forneça dados interessantes e de fácil uso para o desenvolvimento de um **DataTable** com busca e paginação.
- A API pode ser escolhida através da url: https://github.com/public-apis/public-apis

### Requisitos do DataTable
O DataTable deve:
- Exibir os dados paginados.
- Possuir um campo de busca que filtre os dados apresentados.
- Ter uma interface de fácil navegação e interação.

### Responsividade
- A interface deve ser **responsiva**, adaptando-se bem a diferentes tamanhos de tela (desktop, tablet e mobile).
- O layout deve ser fluido e funcional em telas pequenas, com botões e campos de busca visíveis e interativos em dispositivos móveis.
- Utilize media queries, se necessário, para garantir a experiência do usuário em todos os dispositivos.

### Estilização
- **Styled Components** deve ser, preferencialmente, utilizado para a estilização do projeto.
- As regras de CSS devem ser bem estruturadas, utilizando o conceito de componentes de estilo reutilizáveis.
- Não é permitido utilizar CSS global, exceto em casos essenciais como resets ou estilos globais necessários (root, *).

### Layout
- Para a criação do layout, pode-se utilizar qualquer **biblioteca de componentes** que o desenvolvedor preferir (ex: **Material-UI**, **Chakra UI**, entre outras), mas a escolha não é obrigatória. Fique à vontade para utilizar o que melhor se encaixar na solução, respeitando as boas práticas de design e regras estabelecidas neste arquivo.

### Escolha de API
- **Sugestão**: Utilize a **API REST Countries** para listar informações de países. Ela oferece dados como o nome do país, capital, região, população e área — ideal para exibir em um DataTable.
- Link com todas as API's: https://github.com/public-apis/public-apis

### Deploy
- Realize o deploy na versão gratuita da **Vercel**.
- Inclua no **README** o link da aplicação em produção, tal como as informações de como rodar o projeto local.

## Tecnologias Recomendadas
- **Next.js** (com ou sem TypeScript)
- **NextAuth** para autenticação
- **MongoDB** para o banco de dados
- **Mongoose** para abstrair o banco de dados
- **Axios** para requisições
- **Vercel** para deploy

## Critérios de Avaliação
- Implementação de autenticação e conexão com o MongoDB.
- Interface intuitiva, **responsiva** e funcional do DataTable com paginação e busca.
- Código bem estruturado e otimizado.
- Deploy funcional com link ativo.

## Entrega
Ao finalizar, suba o código em um repositório público no **GitHub** e envie o link da aplicação em produção.
