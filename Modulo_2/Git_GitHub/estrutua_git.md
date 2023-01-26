# Git
=====

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
