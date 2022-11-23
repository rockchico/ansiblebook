
## Instala venv python
apt install python3.10-venv

## cria o ambiente virtual chamado ansiblebool
python3 -m venv ansiblebook

## ativa o ambiente virtual
source ansiblebook/bin/activate

## faz o upgrade do pip
python3 -m pip install --upgrade pip

## faz instalação dos pacotes a partir do requirements.txt
python3 -m pip install -r requirements.txt 

```
ansible>=4.0.0
```