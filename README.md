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
