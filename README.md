# MariaDB-linux-installation

## Step 1: Install the MariaDB server & Client
### Update the server
`sudo apt update -y`

### As a recommended practice, we will add the official MariaDB apt repository using the following script.

`curl -LsS https://r.mariadb.com/downloads/mariadb_repo_setup | sudo bash`

### Now, install MariaDB server and client.

`sudo apt-get install mariadb-server mariadb-client -y`
