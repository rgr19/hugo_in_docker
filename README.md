# hugo_in_docker

To switch from local to githubpages and back, go to .env and change 

```sh
HUGO_BASEURL=ralf-it.pl
```

accordingly between domain and `localhost`

and append only when `localhost`, for domain do:

```sh
HUGO_APPEND_PORT=false
```

Put `config.toml` in dir `src/config/${HUGO_ENV}` so have to setup that variable. Default configs in `src/config/_default/config.toml`.

NOTE: you may set hugo theme and version too. This will require to change directories in `src`, as usually theme comes with specific to it `data, i18, layouts, etc...` located in `exampleSite` so we need to copy from there to `src`.


