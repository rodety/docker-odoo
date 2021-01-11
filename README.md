# docker-odoo
Launch Odoo on Linux Unbuntu or EC2 Amazon


# Instalando Docker
curl -sSL https://get.docker.com/ | sh
sudo usermod -aG docker ubuntu
# Instalando Docker Compose
sudo curl -L "https://github.com/docker/compose/releases/download/1.22.0/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
