# ppa-pmact
PPA for pmact repository

From [assafmo](https://assafmo.github.io/2019/05/02/ppa-repo-hosted-on-github.html)

```bash
$ curl -s --compressed "https://tommoulard.github.io/ppa-pmact/KEY.gpg" | sudo apt-key add -
$ sudo curl -s --compressed -o /etc/apt/sources.list.d/my_list_file.list "https://tommoulard.github.io/ppa-pmact/my_list_file.list"
$ sudo apt update
````
