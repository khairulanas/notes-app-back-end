pm2 start npm --name "notes-api" -- run "start-prod" 

pm2 restart notes-api

pm2 stop notes-api

pm2 start notes-api

http://100.25.165.141:5000/



npm install eslint --save-dev
npx eslint --init

http://notesapp-v1.dicodingacademy.com/