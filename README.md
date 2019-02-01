# vrstorygram
startup for VRStoryGram

## Azure Container Service setup

Web App + MySQL : This creates an App Service plus a MySQL Database

## Running in Docker on Linux

docker run -d --env mysql_database=*MySQL_DB_Name* \
    --env mysql_host=*MySQL_host* \
    --env mysql_userid=*MySQL_Username* \
    --env mysql_password=*MySQL_Password* \
    -p 80:80 -p 2022:2222 tfournet/vrstorygram-docker


