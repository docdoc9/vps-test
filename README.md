```bash
cd /workspaces/vps-test/
mkdir /workspaces/vps-test/mnt
sudo mount /dev/sda1 /workspaces/vps-test/mnt
sudo chown -R codespace:codespace /workspaces/vps-test/mnt
docker compose -f win10.yml up -d
docker logs -f windows
```


cd /workspaces/vps-test/
mkdir /workspaces/vps-test/mnt
sudo mount /dev/sda1 /workspaces/vps-test/mnt
sudo chown -R codespace:codespace /workspaces/vps-test/mnt
docker compose -f win10.yml up -d
docker logs -f windows
