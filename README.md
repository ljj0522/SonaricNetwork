install Sonaric Network script 

------------env---------------

sudo apt update && apt upgrade -y

sudo apt install curl make wget clang net-tools pkg-config libssl-dev build-essential jq gcc unzip snapd -y

----------start---------------

sh -c "$(curl -fsSL https://get.sonaric.xyz/scripts/install.sh)"

sonaric node-register discordCode

--------check-----------------

sonaric node-info

sonaric points


-------export-----------------

sonaric identity-export -o yourname.identity
