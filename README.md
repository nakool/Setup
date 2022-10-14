# Setup

## INSTALL WSL2
  - https://learn.microsoft.com/fr-fr/windows/wsl/install

## CREATE & ADD SSH KEY
  - ssh-keygen -t ed25519 -C "your_email@example.com"
  - ssh-add .ssh/id_ed25519


## INSTALL PYTHON3.10 SHELL
  - sudo apt update && sudo apt upgrade -y
  - sudo apt install software-properties-common -y
  - sudo add-apt-repository ppa:deadsnakes/ppa
  - sudo apt install python3.10

## INSTALL POETRY SHELL
  - curl -sSL https://install.python-poetry.org | python3.10 -

## INSTALL POETRY
  - code ~/.bashrc
  - tout en bas 'entrer' puis ajouter 'export PATH="~/.local/bin:$PATH"' -

## INSTALL REQUIREMENTS.TXT
  - pip install -r requirements.txt
