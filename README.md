## BeEF step by step installation on Vagrant VM [Ubuntu 18.04]
### Note: This has been particularly written for the Vagrant VM provided for the Students of Cybersecurity Bootcamp, University of Toronto, Canada

```
sudo apt update
```

Now install Ruby and it Development suite

```
```

```
sudo apt install ruby ruby-dev -y
```

Change directory to `sysadmin` home

```
cd ~
```

Download the BeEF repository from GitHub using git clone

```
git clone https://github.com/beefproject/beef
```

Change directory to beef

```
cd beef
```

The initial screen will appear and ask for `'Y'` (Capital Y) to start the installation

![](Images/beef-initial-installation-screenshot.PNG)

Again you will be promped for

`Do you want to continue? [Y/n] Y`

type `'Y'` (Capital Y)

The update of `rubygems` may take much longer time than its expected and you might think your VM is hang or so. But its usual and be patient.

![](Images/long-update-time-for-ruby-gem.png)


