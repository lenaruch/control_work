## Task №1-2
```
mkdir control_work
cd control_work
cat > pets
cat > pack_animals
cat pets pack_animals > home_animals
mv home_animals > human_friends

mkdir new_dir
mv human_friends new_dir
```
## Task №3
```
sudo wget https://dev.mysql.com/get/mysql-apt-config_0.8.23-1_all.deb
sudo dpkg -i mysql-apt-config_0.8.23-1_all.deb
sudo apt-get update
sudo apt-get install mysql-server
```
## Task №4
```
sudo wget https://download.docker.com/linux/ubuntu/dists/jammy/pool/stable/amd64/docker-ce-cli_20.10.13~3-0~ubuntu-jammy_amd64.deb
sudo dpkg -i docker-ce-cli_20.10.133-0ubuntu-jammy_amd64.deb
sudo dpkg -r docker-ce-cli
```