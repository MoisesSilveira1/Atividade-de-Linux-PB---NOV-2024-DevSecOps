# Atividade-de-Linux-PB---NOV-2024-DevSecOps
Atividade de Linux PB - NOV 2024 | DevSecOps

# Projeto: Monitoramento do Nginx

## 1. Instalação do Linux
1. Baixe a imagem ISO de uma distribuição Linux (Ubuntu/Debian/CentOS).
2. Grave a imagem em um pen drive utilizando ferramentas como Rufus ou Etcher.
3. Configure a BIOS para iniciar pelo pen drive.
4. Siga as instruções do instalador para particionar o disco e configurar o sistema.

## 2. Configuração do Servidor Nginx
- Atualize os pacotes: `sudo apt update`.
- Instale o Nginx: `sudo apt install nginx -y`.
- Inicie e habilite o serviço: 
  ```bash
  sudo systemctl start nginx
  sudo systemctl enable nginx

