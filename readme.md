<!-- frontend -->
 npm i @mui/x-data-grid @mui/material @emotion/react @emotion/styled lucide-react numeral recharts uuid axios
 npm i -D tw-colors
 npm i redux-persist

<!-- Backend -->
 npm i prisma @prisma/client
 npm i express body-parser cors dotenv helmet morgan concurrently
 npm run seed
 npx prisma migrate dev --name init  
 npx prisma generate                    
 npx prisma migrate     
 npm i -D ts-node typescript @types/node                
 npm i rimraf 

 <!-- start nodemon server -->
 npm run dev