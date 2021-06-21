ssh -i "neila-key.pem" ubuntu@ec2-54-210-171-108.compute-1.amazonaws.com

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.37.2/install.sh | bash

exit

nvm install v14.15.4

pm2 start npm --name "notes-api" -- run "start-prod" 

pm2 restart notes-api

pm2 stop notes-api

pm2 start notes-api

172.31.88.60

http://54.210.171.108:5000/



npm install eslint --save-dev
npx eslint --init

http://notesapp-v1.dicodingacademy.com/


npm run migrate create "create table notes"

npm run migrate up

//v2---------------start

npm run migrate create "create table users"

npm run migrate up

npm install bcrypt

npm run migrate create "create table authentications"

npm run migrate up

npm install @hapi/jwt

require('crypto').randomBytes(64).toString('hex');