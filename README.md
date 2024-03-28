A PPA repository for my packages

# Usage

```bash
sudo curl -SsL -o /etc/apt/keyrings/leo-schick-keyring.pgp https://leo-schick.github.io/ppa/debian/leo-schick-keyring.pgp
sudo curl -SsL -o /etc/apt/sources.list.d/leo-schick.list https://leo-schick.github.io/ppa/debian/leo-schick.list
sudo apt update
sudo apt install ...
```

# Sources

- https://assafmo.github.io/2019/05/02/ppa-repo-hosted-on-github.html
- https://makandracards.com/makandra/37763-gpg-extract-private-key-and-import-on-different-machine
- http://blog.jonliv.es/blog/2011/04/26/creating-your-own-signed-apt-repository-and-debian-packages/
- https://medium.com/sqooba/create-your-own-custom-and-authenticated-apt-repository-1e4a4cf0b864
- https://github.com/tagplus5/vscode-ppa
