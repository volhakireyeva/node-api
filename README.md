## Step 1: Install NodeJS and NPM using nvm

```bash
sudo su -
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash
```

```bash
. ~/.nvm/nvm.sh
```

```bash
nvm install node
```

```bash
node -v
npm -v
```

## Step 2: Install Git and clone repository from GitHub

```bash
sudo apt-get update -y
sudo apt-get install git -y
```

```bash
git — version
```
```bash
git clone https://github.com/volhakireyeva/node-api.git```


```bash
cd node-api
npm install
```
Start the application
To start the application, run the below command in the terminal:

```bash
npm start
```

