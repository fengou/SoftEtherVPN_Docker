# SoftEtherVPN_Docker

sudo docker build -t breakwaller/softethervpn:latest .

# 构建多平台的image
sudo docker buildx build -t breakwaller/softethervpn.latest --platform=linux/arm,linux/arm64,linux/amd64 . --push
