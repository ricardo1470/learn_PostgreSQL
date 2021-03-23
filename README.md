> # learn_PostgreSQL
---

## Install PostgreSQL
* `sudo apt update`
* `sudo apt install postgresql postgresql-contrib`

## start postgres shell
* `sudo -u postgres psql`
* `pass= root`

## Basic postgres commands
* `\q`: Quit
* `\c` __database__: Connect to a database
* `\d` __table__: Show table definition including triggers
* `\dt` *.*: List tables from all schemas (if *.* is omitted will only show SEARCH_PATH ones)
* `\l`: List databases
* `\dn`: List schemas
* `\df`: List functions
* `\dv`: List views
* `\timing`: Show query timing stats

## postgres status

* `sudo service postgresql start`
* `sudo service postgresql stop`
* `sudo service postgresql status`
* `sudo service postgresql restart`
* `sudo service postgresql reload`

---
> ## contact 💬

| [twitter](https://twitter.com/RICARDO1470) | [linkedin](https://www.linkedin.com/in/ricardo-alfonso-camayo/) | [mail](1466@holbertonschool.com) | [github](https://github.com/ricardo1470/README/blob/master/README.md) |
|---|---|---|---|

---

## License
*`learn_PostgreSQL` is open source and therefore free to download and use without permission.*

<a href="url"><img src="https://www.holbertonschool.com/holberton-logo.png" align="middle" width="100" height="30"></a>

---