Devcontainers
Deze repository bevat een eenvoudige webserver in Express geschreven. De webserver maakt een connectie naar een Postgres databank via het Prisma ORM.

Meer informatie:

Postgres: https://www.postgresql.org/
Express: https://expressjs.com/
Prisma: https://www.prisma.io/
Installatie instructies
Ga naar de api folder

Maak een .env bestand aan. Inhoud:

DATABASE_URL=postgres://postgres:Newpassword@localhost:5432/postgres

Installeer dependencies
npm install

Maak tabellen aan
npx prisma db push

Seed de databank
npx prisma db seed

Run instructies
Start de webserver
npm run start

Open browser en ga naar http://localhost:3000 of http://localhost:3000/blog
Data beheer
Prisma komt met een data beheer dashboard. Om te raadplegen, open een terminal en voer volgend command uit:

npx prisma studio