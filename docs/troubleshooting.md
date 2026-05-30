# Troubleshooting

## Check Container Status

docker ps

## Check Container Logs

docker logs storage_node_container

## Check Server Uptime

uptime

## Check Disk Usage

df -h

## Check Running Processes

top

## Check Listening Ports

ss -tulnp

## Update Ubuntu

sudo apt update && sudo apt full-upgrade

## Upgrade StorX Node

cd S*
git pull
sudo bash ./upgrade.sh
