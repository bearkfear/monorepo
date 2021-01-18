Template para criar projetos com monorepo

Crie seus projetos dentro da pasta packages. 

Caso a pasta packages não exista ainda, crie-a. 

Os projetos precisam ter seus nomes definido com um padrão monoreposotorio. 

Eu sigo esse padrão: `@project/subproject-name`

Um exemplo disso seria: 

`@meusistema/frontend`
`@meusistema/backend`
`@meusistema/mobile`

yarn install para instalar todas as dependencias. 

yarn new-version para atualizar as versoes dos pacotes de forma independentes. 

