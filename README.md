# steps to do this project 
    1  mkdir ~/docker
    2  cd docker
    3  sudo apt update
    4  sudo apt install docker.io -y
    5  sudo usermod -aG docker ubuntu
    6  sudo systemctl status docker
    7  docker run hello-world
    8  git clone https://github.com/07prince/docker_image
    9  cd docker
   10  git clone https://github.com/07prince/docker_image
   11  ls
   12  cd docker_image
   13  ls
   14  docker login
   15  docker build -t princeshahi007/my-first-image:latest .
   16  docker images
   17  docker push princeshahi007/my-first-image
