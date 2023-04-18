# Load-balancing-Algorithm
# Commands
docker build -t 

docker run --name foo -d -p 8080:80

sudo lsof -i :8080|grep "python3"|cut -d " " -f2|xargs kill -9
