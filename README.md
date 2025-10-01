A guardyia é uma bilbioteca com o intuito de facilitar a criação de autenticação e registro registro nome, email e senha E login email e senha

A seguir o tutorial de uso Passo 1 Para baixar a bilbioteca npm i guardiya

Passo 2 Para configurar o prisma com o nextjs 15 npx guardiya prisma

remova a linha output = "../app/generated/prisma"

Passo 2 Para gerar a tabela de usuarios > npx guardiya add-user-model

Passo 3 Para gerar o jwt_secret > npx guardiya add-jwt-secret

Passo 4 Para gerar todo o fluxo login e registro e logout junto com o exemplo da rota dashboard protegida

npx guardiya init

Utilidades: Caso use o docker compose a guardiya tem um comando para gerar uma imagem do postgres chamado: > npx guardiya postgres-docker-compose

Para reverter o BoilerPlate criado pelo guardiya > npx guardiya revert
