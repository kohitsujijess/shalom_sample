docker build -t shalom_sample .
docker run --env-file .env -p 3000:3000 -it shalom_sample
