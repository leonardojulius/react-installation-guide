Source from [computingforgeeks.com](https://computingforgeeks.com/install-node-js-14-on-ubuntu-debian-linux/).

### Step 1: Update APT index

```
sudo apt update
```

### Step 2: Install Node.js 14 on Ubuntu 22.04|20.04|18.04

```
curl -sL https://deb.nodesource.com/setup_14.x | sudo bash -
```

The script above will create apt sources list file for the NodeSource Node.js 14.x repo:

```
# Ubuntu 20.04 example
$ cat /etc/apt/sources.list.d/nodesource.list
deb https://deb.nodesource.com/node_14.x focal main
deb-src https://deb.nodesource.com/node_14.x focal main
```

Once the repository is added, you can begin the installation of Node.js 14 on Ubuntu Linux:

```
sudo apt -y install nodejs
```

Verify the version of Node.js installed.

```
$ node  -v
v14.17.5
```

### Step 3: Installing NPM in Ubuntu

Source from [www.tecmint.com](https://www.tecmint.com/install-reactjs-on-ubuntu/)
```
$ sudo apt install npm
```

```
$ npm --version

6.14.4  [Output]

```

### Step 4: Installing create-react-app Utility

```
sudo npm -g install create-react-app
```

![](https://www.tecmint.com/wp-content/uploads/2021/02/Install-create-react-app.png)

Once installed, you can confirm the version of installed by running:

```
$ create-react-app --version

4.0.1  [Output]
```
### Step 5: Create & Launch Your First React Application













