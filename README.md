<strong>Steps to get your local development environment:</strong>

* `git clone https://github.com/nabin5s/dev-local.git`
* `cd dev-local/`
* `docker-compose up -d`
* Visit `localhost` to run code from `/code/` directory.

Adding local domains:

* Changes for `localhost.test` are included in repo and will serve `/code/localhost` directory.
* You need to add `127.0.0.0 localhost.test` to `C:\Windows\system32\drivers\etc` in Windows OS.
