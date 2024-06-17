Projeto de como usar o Git

git init --global init.defaultBranch master

git init

git status

git add Readme.md

git commit - m "primeiro commit"

git status

git -M "main"

git status

git add Readme.md

git commit -m "adicionado mais comandos e mudamos o nome da branch de master para main"

git status

Comandos para fazer conexao com GitHub

Agora vamos logar no GitHub e criar um repositorio com o nome do seu projeto net caso git_basico

agora vamos gerar a chave ssh pra poder conectar ao github pois não se conecta mais com password apenas

ssh-keygen

ssh-add /home/USUÁRIO/.ssh/id_ed25519.pub

export SSH_AUTH_SOCK=$XDG_RUNTIME_DIR/ssh-agent.socket

systemctl enable --user ssh-agent.service

ssh -T git@github.com

fazer o login com linha de comando seguindo as dicas

gh auth login

escolha o metodo de login

clone seu repositorio pela linha de comando usando o gh clone