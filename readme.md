ssh -i "neila-key.pem" ubuntu@ec2-54-210-171-108.compute-1.amazonaws.com


pm2 start npm --name "notes-api" -- run "start-prod" 

pm2 restart notes-api

pm2 stop notes-api

pm2 start notes-api

172.31.88.60

http://54.210.171.108:5000/



npm install eslint --save-dev
npx eslint --init

http://notesapp-v1.dicodingacademy.com/