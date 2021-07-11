1. Get from url `sudo wget -o ../template/minecraft_server_X-XX-X.jar https://minecraft.net/path/to/newest/version/server.jar`

1. Overwrite old server `sudo cp ../template/minecraft_server_X-XX-X.jar minecraft_server.jar`

1. Update ownership `sudo chmod minecraft minecraft_server.jar`

1. Restart the server `sudo systemctl restart minecraft@main`
