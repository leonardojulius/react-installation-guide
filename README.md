Source from [computingforgeeks.com](https://computingforgeeks.com/install-node-js-14-on-ubuntu-debian-linux/).

Layout Guide [Github-Formatting](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

--Arrange By Julius Leonardo

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

```
$ create-react-app tecmint-app
```
This takes roughly 5 minutes to install all the packages, libraries, and tools needed by the application. Some patience will come in handy.

![](https://www.tecmint.com/wp-content/uploads/2021/02/create-react-app.png)

If the creation of the application was successful, you will get the notification below giving the basic commands that you can run to start managing the application.

![](https://www.tecmint.com/wp-content/uploads/2021/02/Summary-of-react-app.png)


### To run the application, navigate into the app directory

```
$ cd tecmint-app
```

### Then run the command:

```
$ npm start
```











































