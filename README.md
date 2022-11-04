# linux-interface
´´´
docker run -d \
  --name=webtop \
  -e PUID=1000 \
  -e PGID=1000 \
  -e TZ=Europe/London \
  -p 3000:3000 \
  -v /path/to/data:/config \
  --shm-size="1gb" \
  --restart unless-stopped \
  ghcr.io/linuxserver/webtop
  
  ´´´
