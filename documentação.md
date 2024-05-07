  5  sudo ufw status
    6  sudo ufw enable
    7  sudo netstat -tulpn | grep LISTEN
    8  docker ps -a
   19  mkdir nginx-docker
   20  cd nginx-docker
  153  docker run -it --rm -d -p 80:80 --name web -v ~/html:/usr/share/nginx/html nginx
  154  docker ps -a]
  
  155  nano index.html
´´bash
  docker pull mysql/mysql-server
´´

  
