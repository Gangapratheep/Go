LS
    2  ls
    3  sudo apt update
    4  git clone https://github.com/iam-veeramalla/go-web-app
    5  ls
    6  cd go-web-app
    7  ls
    8  cd go-web-app
    9  ls
   10  docker --version
   11  sudo apt install docker
   12  docker --version
   13  sudo apt install apt-transport-https ca-certificates curl software-properties-common
   14  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg
   15  echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
   16  sudo apt update
   17  sudo apt install docker-ce
   18  docker --version
   19  ls
   20  cd go-web-app
   21  ls
   22  cd go-web-app
   23  ls
   24  docker --version
   25  docker build -t gangapratheep/go-web-app:v1
   26  docker build -t gangapratheep/go-web-app:v1 .
   27  sudo groupadd docker      # Create the docker group if it doesn't already exist
   28  sudo usermod -aG docker $ubuntu  # Add the current user to the docker group
   29  sudo docker build -t gangapratheep/go-web-app:v1 .
   30  sudo chmod 666 /var/run/docker.sock
   31  sudo chown ubuntu:ubuntu /var/run/docker.sock
   32  sudo usermod -aG docker ubuntu
   33  sudo systemctl restart docker
   34  docker run hello-world
   35  sudo usermod -aG docker ubuntu
   36  sudo systemctl restart docker
   37  docker build -t gangapratheep/go-web-app:v1 .
   38  RUN ls /app/main && echo "Main binary exists" || echo "Main binary not found"
   39  RUN go build -o main .
   40  go build -o main .
   41  sudo apt update
   42  sudo apt install golang-go
   
