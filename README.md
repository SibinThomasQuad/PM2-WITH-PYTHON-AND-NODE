# PM2-WITH-PYTHON-AND-NODE

PM2 is a process manager for the JavaScript runtime Node.js. In 2016, PM2 was ranked as the 82nd most popular JavaScript project on GitHub
--------------------------------------------------  INSTALLATION ---------------------------------------------<br>
With yarn:

yarn global add pm2

With npm:

npm install pm2 -g

------------------------------------------------- RUNNING FILES ----------------------------------------------<br>
to start node in pm2

pm2 start index.js

with watch 

(PM2 can automatically restart your application when a file is modified in the current directory or its subdirectories:)

pm2 start start index.js --watch

to run python in pm2

pm2 start api.py --interpreter=python3 --watch

--------------------------------------------------------------------------------------------------------------<br>
![image](https://user-images.githubusercontent.com/54390036/193266451-682fb39f-8bea-4d5f-9ad5-9f5cac63bcd2.png)
