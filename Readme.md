### next-postgre

```sh
# Update package index
sudo apt-get update

# ติดตั้ง Docker
sudo apt-get install -y docker.io

# เริ่มต้น Docker และตั้งค่าให้เริ่มต้นอัตโนมัติ
sudo systemctl start docker
sudo systemctl enable docker

# ตรวจสอบว่า Docker ทำงานอยู่
sudo docker --version

# ติดตั้ง Docker Compose
sudo apt-get install -y docker-compose

# ตรวจสอบว่า Docker Compose ทำงานอยู่
docker-compose --version
```