pip freeze > requuirements.txt
chmod +x ./entrypoint.sh
docker-compose up -d --build
http://0.0.0.0:8000/
docker exec -it django /bin/sh