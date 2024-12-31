docker login
docker build -t vigilance-auth .
docker tag vigilance-auth edaral3/vigilance-auth:latest
docker push johndoe/my-app:latest