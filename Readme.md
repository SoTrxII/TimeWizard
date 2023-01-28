# Time wizard thingy

## Install

- Install Docker (https://docs.docker.com/desktop/install/windows-install/)
- Install Dapr -> Enter this in a Admin Terminal

```shell
powershell -Command "iwr -useb https://raw.githubusercontent.com/dapr/cli/master/install/install.ps1 | iex"
# Reopen a new terminal before doing the next command
dapr init
npm install
```

Final step, create a .env file with the following content 
```shell
BOT_TOKEN=<YOUR_BOT_TOKEN>
```

## Run the bot

```shell
# In a first terminal
npm run start:dapr
# In another terminal
npm run start:dev
```