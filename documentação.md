```bash
  sudo ufw status
  sudo ufw enable
  sudo netstat -tulpn | grep LISTEN
  docker ps -a
  mkdir nginx-docker
  cd nginx-docker
  docker run -it --rm -d -p 80:80 --name web -v ~/html:/usr/share/nginx/html nginx
  docker ps -a]
  nano index.html
  docker pull mysql/mysql-server
```

  
