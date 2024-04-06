# PREVISAO-DO-TEMPO



# Comandos úteis para Git e Linux

Aqui estão alguns comandos úteis para trabalhar com Git e para navegar no sistema operacional Linux.

## Comandos do Linux

### Navegação no diretório
- `ls`: Lista os arquivos e diretórios no diretório atual.
- `pwd`: Mostra o diretório atual.
- `cd DOWNLOADS`: Navega para o diretório DOWNLOADS.
- `clear`: Limpa a tela do terminal.

### Editor de código
- `code .`: Abre o VSCode no diretório atual.

### Instalação do Git
- `sudo apt-get install git-all`: Instala o Git em sistemas baseados em Debian/Ubuntu.
- `apt-get install git-all`: Instala o Git em sistemas baseados em Debian/Ubuntu.
- `apt- install git-all`: Instala o Git em sistemas baseados em Debian/Ubuntu.
- `apt get install git-all`: Instala o Git em sistemas baseados em Debian/Ubuntu.

## Configuração do Git

### Verificação e configuração de versão
- `git --version`: Verifica a versão do Git instalada.

### Configuração do usuário
- `git config --global user.name "kayov"`: Configura o nome de usuário do Git como "kayov".
- `git config --global user.email "leonardofernandes22.pb@gmail.com"`: Configura o email do usuário do Git.

### Geração e adição de chaves SSH
- `ssh-keygen -t ed25519 -C "leonardofernandes22.pb@gmail.com"`: Gera uma nova chave SSH.
- `eval "$(ssh-agent -s)"`: Inicializa o agente SSH.
- `ssh-add ~/.ssh/id_ed25519`: Adiciona a chave SSH ao agente.

## Comandos do Git

### Clonagem de repositório
- `git clone git@github.com:Leonardo25dev/html.git`: Clona o repositório HTML.
- `git clone git@github.com:Leonardo25dev/Java-script.git`: Clona o repositório JavaScript.
- `git clone https://github.com/Leonardo25dev/comandos-Linux`: Clona o repositório de comandos Linux.

### Status e commits
- `git status`: Verifica o status do repositório Git.
- `git commit -m "comandos linux"`: Realiza um commit com uma mensagem especificada.

### Push e pull
- `git push`: Faz o push das alterações para o repositório remoto.

## Limpeza e desinstalação
- `sudo apt-get remove openssh-client openssh-serve`: Remove o cliente e o servidor OpenSSH.

