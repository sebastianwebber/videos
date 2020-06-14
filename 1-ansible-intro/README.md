# 1-ansible-intro

URL do vídeo: https://youtu.be/Co5bqBAtAY4

# Como Utilizar

Requisitos:

1. Python 3 (3.8 no exemplo)
1. [pipenv](https://github.com/pypa/pipenv) (caso deseje usar o [virtualenv](https://virtualenv.pypa.io/en/latest/))

## Virtual env

Caso deseje, utilize o pipenv para executar esse ambiente:

```bash
PIPENV_SKIP_LOCK=1 \
PIPENV_VENV_IN_PROJECT=1 \
PIPENV_IGNORE_VIRTUALENVS=1 \
pipenv install --clear --skip-lock
```

## Maquinas virtuais

Antes de tudo, [instale o vagrant](https://www.vagrantup.com/docs/installation). Então execute os comandos abaixo para subir as VMs:

```bash
vagrant up
```
