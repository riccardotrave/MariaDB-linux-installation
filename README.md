# MariaDB-linux-installation

## Step 1: Install the MariaDB server & Client
### Update the server
```shell
sudo apt update -y
```

### As a recommended practice, we will add the official MariaDB apt repository using the following script.

```shell
curl -LsS https://r.mariadb.com/downloads/mariadb_repo_setup | sudo bash
```

### Now, install MariaDB server and client.

```shell
sudo apt-get install mariadb-server mariadb-client -y
```

