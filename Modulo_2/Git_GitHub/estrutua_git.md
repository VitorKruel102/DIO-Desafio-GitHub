# Git

## SHA (Secure Hash Algorithn):
Encriptação do git para proteger os arquivos.

## Estrutura:

1. Blobs:
    - Sua função é conter meta-dados do git, ou seja, tipo do objeto, tamanho 
    do arquivo e outros dados. (SHA)
2. Tree:
    - Sua função é armazenar e apontar para diversos blobs diferentes e guarda
    o nome desse arquivo
3. Commit:
    - Sua função é juntar tudo para fazer as alteraçõe sdesejados. Ele aponta
    para uma árvore(tree), ele aponta para o último commit, para o autor e 
    para a mensagem.

# Instruções:

- git clone (Clonar repositório);
- git init (inicializar o controle de versões);
- git config --global user.email "" (Criar a configução global da máquina);
- git config --global user.name "" (Criar a configução global da máquina);
- git add * (Adicionar todos os arquivos para fazer o commit);
- git add 'file' (Adicionar um arquivo expecífico para commit);
- git commit -m "mensagem" (Realizar o commit);
- git status (Utilizado para ver os status dos arquivos);
- git push (Enviar a nova versão);
- git pull (Trazer a nova versão).