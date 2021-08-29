# Atajos de teclado

| Teclado | Acciones |
|---------|----------|
| `Ctrl + Super(tecla Win) + d` | Muestra escritorio |
|||


# Instalación

- **Node js**
    - sudo apt install nodejs
    - node -v

    _Instalará una version por defecto No sirve_

    - curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh
    - curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash

    _El ultimo comando es completo para saber si funcionara, puede omitir el penultimo_

    - source ~/.bashrc
    - nvm list-remote
    - sudo nvm install v14.17.5
    - node -v
- **npm**
    - sudo apt install npm
    - npm -v

- **git**
    [Pagina oficial](https://git-scm.com/download/linux)
    - add-apt-repository ppa:git-core/ppa
    - apt update
    - -apt upgrade-
    - sudo apt install git
    - sudo apt install git-all //no funciono