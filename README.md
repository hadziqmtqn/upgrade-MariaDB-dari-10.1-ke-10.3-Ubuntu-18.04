# upgrade-MariaDB-dari-10.1-ke-10.3-Ubuntu-18.04
```bash
sudo apt-get install software-properties-common
```
```bash
sudo apt-key adv --recv-keys --keyserver hkp://keyserver.ubuntu.com:80 0xF1656F24C74CD1D8
```
```bash
sudo add-apt-repository 'deb [arch=amd64,arm64,ppc64el] http://www.ftp.saix.net/DB/mariadb/repo/10.3/ubuntu bionic main'
```
```bash
sudo apt update
```
```bash
sudo apt install mariadb-server
```

Sumber https://vander.host/knowledgebase/databases/how-to-upgrade-mariadb-from-101-to-103-ubuntu-bionic-1804-lts-server/
