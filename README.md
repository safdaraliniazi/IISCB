#Steps to start the project

1. CLone the repo ` git clone repo https://github.com/safdaraliniazi/IISCB.git `
2. build backend docker container using `docker build -t backend-image .\backend\`
3. bulid frontend docker container using `docker build -t frontend-image .\frontend\`
4. Now run backend using `docker run -d -p 5000:5000 backend-image`
5. Now run frontend using `docker run -d -p 80:80 frontend-image`

