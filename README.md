<p align="center"><a href="#readme"><img src="https://gh.kaos.st/devcontainer.svg"/></a></p>

<br/>

Set of development containers for using with GitHub codespaces.

`devcontainer.json` example:

```json
{
  "name": "Bash",
  "build": {
    "dockerfile": "Dockerfile",
  },
  "settings": {
    "terminal.integrated.shell.linux": "/usr/bin/zsh"
  }
}
```

`Dockerfile` example:

```dockerfile
FROM ghcr.io/essentialkaos/devcontainer:bash

WORKDIR /root

ENTRYPOINT ["/usr/bin/zsh"]
```

### License

[Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0)

<p align="center"><a href="https://essentialkaos.com"><img src="https://gh.kaos.st/ekgh.svg"/></a></p>
