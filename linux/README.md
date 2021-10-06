# Atajos de teclado

| Teclado | Acciones |
|---------|----------|
| `Ctrl + Super(tecla Win) + d` | Muestra escritorio |
|`fuser -k -n tcp 4001`| Mata el proceso del puerto 4001|


# Instalación

- **Node js**
    - sudo apt install nodejs
    - node -v

    _Instalará una version por defecto No sirve_

    - sudo curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash
    - source ~/.bashrc
    - nvm list-remote
    - sudo nvm install v14.17.5
    - node -v
- **npm**
    - sudo apt install npm
    - npm -v

- **git**
    [Pagina oficial](https://git-scm.com/download/linux)
    - sudo add-apt-repository ppa:git-core/ppa
    - sudo apt update
    - -apt upgrade-
    - sudo apt install git