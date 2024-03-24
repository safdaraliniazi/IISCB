#Steps to start the project

1. CLone the repo ` git clone https://github.com/safdaraliniazi/IISCB.git `
2. Go to the backend folder and paste this command on terminal `pip install -r requirements.txt`
3. Go to the frontend folder and paste this command on terminal `npm install`
4. build backend docker container using `docker build -t backend-image .\backend\`
5. bulid frontend docker container using `docker build -t frontend-image .\frontend\`
6. Now run backend using `docker run -d -p 5000:5000 backend-image`
7. Now run frontend using `docker run -d -p 80:80 frontend-image`

