git init

npx create-next-app@latest

npm i prisma --save-dev

npx prisma init

in your env. put in the connection string

mongodb+srv://vincentlaucs:<password>@clusternextblog.zju25jy.mongodb.net/?retryWrites=true&w=majority

completely replace <password> with the password and add testDb right after mongodb.net/ and before ?retryWrites=true

after you set up your models in prisma, do: npx prisma generate

now we can push the schema into the database so it would allow us to sync our schema with the database using: npx prisma db push

npm i @prisma/client

if you want the site to create an alert whenever you do something, you can use the toast import 

npm i react-hot-toast
