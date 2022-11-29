# Banco on-line
![Sem título](https://user-images.githubusercontent.com/85747490/204543733-6367fc9f-c0a4-4a67-a1ce-10faa4d3a059.png)



# Contexto
Este projeto trata-se de uma aplicação onde é possível ver e enviar o seu saldo á algum outro usuário, filtrar suas transações por enviadas, recebidas ou por um período de data específico.

## Técnologias usadas

Front-end:
> Desenvolvido usando: React, TypeScript, Tailwind CSS, Radix, HeadlessUI, Phosphor icons, Material icons, axios, React Router Dom e Vite

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![MUI](https://img.shields.io/badge/MUI-%230081CB.svg?style=for-the-badge&logo=mui&logoColor=white)

Back-end:
> Desenvolvido usando: NodeJS, ExpressJS, PostgreSQL, Prisma, TypeScript, jsonwebtoken

![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)

## Como rodar o projeto na sua máquina

- É necessario ter o [Docker](https://www.docker.com/) instalado.

> Clone o repo
```bash
git clone git@github.com:Vitosoaresp/banking-online.git
cd banking-online
``` 

> Suba o docker-compose
```bash
docker-compose up -d
```

> Inicialize os container de backend e frontend
```bash
docker start ng_frontend ng_backend
```

> Rode esse comando para inicializar o banco
```bash
docker exec -it ng_backend sh
npm run db:push
```

## Porta das aplicações
 -  Backend: 3001
 -  Frontend: 3000
 -  Banco de dados: 5432

<hr />
![2](https://user-images.githubusercontent.com/85747490/204544476-b4efb15f-930a-4bbc-8428-673bac8af38e.png)




